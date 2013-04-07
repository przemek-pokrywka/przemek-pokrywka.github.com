---
layout: post
title: "Blogging with Octopress"
date: 2013-04-07 01:21
comments: true
categories: unix
---

After long time of hesitation and exploring the options I've decided to use Octopress as my new platform for blogging. I was fed up with Blogger mainly because the process of editing and configuring of layout wasn't transparent for me. Octopress is based on a totally different concepts. Like Unix, it's built from small independent parts, that work well with each other. Rake, Jekyll, Git are some of them. For a developer with Java background setup is pretty easy on standard Ubuntu box. I've encountered only one problem not mentioned in the official documentation, yet only because I haven't followed the steps exactly. The problem was in the Ruby package. The default Ubuntu package was not enough, I needed to install the dev version (StackOverflow had the answer).
What I like about the new environment is that all content is just plain text files, everything versioned in git. Even configuration of my blog is versioned so I can freely experiment with it and do rollbacks when I don't like the result. I've chosen my personal Github pages as the deployment target. That way I'm taking one aspect of my life out of Google, on which I already depend more than I'd want to. But Octopress lets me publish to any host I prefer, so I got maximum independence on hosting.

I'm pretty happy with that setup. Let's see how will it work.

