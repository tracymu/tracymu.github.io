---
layout: post
title: "Creating an Octopress Blog"
date: 2014-05-28 16:19:30 +1000
comments: true
categories:
author: "TracyMu"
---

<p>Catherine Jones and I (Tracy Mu Sung) are getting geared up to participate in the Rails Girls Summer of Code (or down here, the Winter of Code), and have prepared this blog as the repository for our daily logs and learnings.</p>
<p>The first lesson was actually in how to set up this blog! It is using Octopress, which is a free blogging framework for 'hackers'. To run the blog you don't use a special CMS UI, instead you create the blog posts in your text editor, manage the blog via the terminal and in this case we're hosting on GitHub. After you write new posts in your editor you update your blog using the rake tasks they've provided. </p>
<h2>Using Octopress - for Beginners</h2>
<ul class="list-style">
	<li>You need to have Git installed on your computer, and then you can follow these simple install <a href="http://octopress.org/docs/setup/">instructions</a> to clone the Octopress repository onto your computer.</li>
	<li>Deploy on the hosting site of your choosing. We're using <a href="http://octopress.org/docs/deploying/github/">GitHub</a> but they also have <a href="http://octopress.org/docs/deploying/">instructions</a> for Heroku and Rsync</a>.</li>
	<li>You can open up your new Octopress folder and browse around the files. There are some instructions <a href="http://octopress.org/docs/blogging/">here</a> on how to create new blog posts and pages. Basically they are a set of rake tasks which are pretty straight forward. The only thing I didn't realise was that to make your blog posts and pages actually live not only do you need to </br>
		<code> $ git push origin source</code></br>
		You also need to</br>
			<code> $ rake deploy</code></li>
	<li>Before you make any pages live though, you probably want to check them with </br>
		<code>$ rake preview</code></br>
		Then you can view them at localhost:4000</li>
	<li>Another thing we've learnt is that if you want new pages to be in your top nav, e.g. an about page, you can edit the nav in source/_includes/custom/navigation.html</li>
	<li>To enable multiple users to write for your blog, you add them as a contributor to your repo, and then we followed the steps on <a href="http://blog.zerosharp.com/clone-your-octopress-to-blog-from-two-places/">this blog</a>.
</ul>
<p>We'll be sure to add to this list of Octopress tips as we get more experience using the platform</p>
