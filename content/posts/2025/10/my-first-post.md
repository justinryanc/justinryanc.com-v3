---
date: "2025-10-13T12:30:51-04:00"
draft: false
title: My First Post
slug: my-first-post
description: "I've been a WordPress guy for what seems like an eternity and currently support over a dozen sites professionally at work (we use the WordPress VIP platform).  I even ran a very small website design and hosting business for over a decade.  The downside with WordPress?  It requires more effort than I wanted to maintain it and is prone to security issues.  I was tired of running what was essentially a static site anyway, just my Photography portfolio on WordPress."
categories:
- General
tags:
- Hugo
- Website
---

**New site is live!**

I've been a [WordPress](https://wordpress.org) guy for what seems like an eternity and currently support over a dozen sites professionally at work (we use the [WordPress VIP platform](https://wpvip.com)).  I even ran a very small website design and hosting business for over a decade.  The downside with WordPress?  It requires more effort than I wanted to maintain it and is prone to security issues.  I was tired of running what was essentially a static site anyway, just my Photography portfolio on WordPress.

So why a static site?  Since you aren't running an actual application it's just static files which makes it painless to maintain and more secure.  That's where [Hugo](https://gohugo.io) comes in, it's a static site generator that essentially builds your site from plain text [Markdown](https://en.wikipedia.org/wiki/Markdown) files.  There's a bit of initial setup, and you need to be somewhat comfortable with [HTML](https://www.w3schools.com/html), [CSS](https://www.w3schools.com/css/) and preferably [GitHub](https://github.com).  You'll need to find a Hugo [theme](https://themes.gohugo.io) (lots of free ones) and it will require some manual effort to tweak it to your liking.

If you do decide to go this route, I'd recommend storing the code in a GitHub repository and using a service like GitHub, [Cloudflare](https://www.cloudflare.com), etc. to host it.  You'll essentially setup a pipeline to build the site from the code in the repository.  Alternatively you can also use Hugo to upload the code without using a repository.  Also don't let the word static fool you, you can still setup comments on your site, add a contact form, etc.  For instance comments can be added using [giscus](https://giscus.app), or a contact form by using an [Azure Logic App](https://learn.microsoft.com/en-us/azure/logic-apps).

Either way I'm proud to go live today with my new site!