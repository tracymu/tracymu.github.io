---
layout: post
title: "Creating an Octopress Blog"
date: 2014-05-28 16:19:30 +1000
comments: true
categories:
author: "TracyMu"
---

Catherine Jones and I (Tracy Mu Sung) are getting geared
up to participate in the Rails Girls Summer of Code (or down
here, the Winter of Code), and have prepared this blog as
the repository for our daily logs and learnings.

The first lesson was actually in how to set up this blog!
It is using Octopress, which is a free blogging framework for
'hackers'. To run the blog you don't use a special CMS UI,
instead you create the blog posts in your text editor, manage
the blog via the terminal and in this case we're hosting on
GitHub. After you write new posts in your editor you update
your blog using the rake tasks they've provided.


## Using Octopress - for Beginners

* You need to have Git installed on your computer,
and then you can follow these simple install
[instructions](http://octopress.org/docs/setup/) to clone the
Octopress repository onto your computer.

* Deploy on the hosting site of your choosing. We're using
[GitHub](http://octopress.org/docs/deploying/github/)
but they also have [instructions](http://octopress.org/docs/deploying/)
for Heroku and Rsync.

* You can open up your new Octopress folder and browse around the files.
There are some instructions [here](http://octopress.org/docs/blogging/)
on how to create new blog posts and pages. Basically they are a set of
rake tasks which are pretty straight forward. The only thing I didn't
realise was that to make your blog posts and pages actually live not only
do you need to do `$ git push origin source`, you also need to do `$ rake deploy`

* Before you make any pages live though, you probably want to check them
with `$ rake preview`. Then you can view them at `http://localhost:4000`

* Another thing we've learnt is that if you want new pages to be in your top nav,
e.g. an about page, you can edit the nav in source/_includes/custom/navigation.html

* To enable multiple users to write for your blog, you add them as a contributor to
your repo, and then we followed the steps on [this blog](http://blog.zerosharp.com/clone-your-octopress-to-blog-from-two-places/)

We'll be sure to add to this list of Octopress tips as we get more experience using the platform
