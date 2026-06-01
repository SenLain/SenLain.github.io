---
title: Building This Blog
published: 2026-03-08
description: 'In this post I will describe my journey of building this blog site'
image: ''
tags: [Blog]
category: 'Blog'
draft: false 
---

# How I Built This Blog

This is the first post on my new blog, written as my university assignment. I want to share how I built this site from scratch, what technologies I used, and why I made certain choices along the way.

## Why Not Traditional Hosting?

I looked at Combell's web hosting options first. They offer WordPress hosting and Linux-based web hosting. However, I don't have much experience with WordPress, and managing a Linux server with all its setup requirements felt like too much work for just a simple project. I wanted something else.

## Finding the Right Technology

I needed to build a static site, I wanted something modern, fast and not too complicated. That is when I discovered Astro.

Astro is a static site generator that builds websites with very little JavaScript. Most of the work happens at build time, not when someone visits the page. This means my blog loads extremely fast.

After deciding on Astro, I started looking for templates. I wanted something that looked professional but also felt personal. I came across Fuwari and immediately liked it.

The design is clean with dark mode support. The layout puts the content first, which is exactly what a blog needs. I also appreciated how Fuwari organizes posts using simple Markdown files. No complex editors. Just write in plain text and save.

## Choosing GitHub Pages

Instead of traditional hosting, I decided to use GitHub Pages. It is completely free and perfect for static websites like blogs. There is no server to configure, no database to manage, and nothing to update. I had this website running locally on my computer long before putting it on GitHub Pages because I wanted to have a foundation first where I could write and post my blog posts without worrying about hosting. After I was done with my local setup and it was time to publish my blog. I pushed everything to my GitHub repository and the site went live with minimal changes and configuration required.


## The Technology Stack

Here is everything that powers this blog:

- **Astro**: The static site generator that builds all the pages
- **Fuwari**: The template that provides the design and layout
- **GitHub Pages**: The free hosting service that serves the files
- **GitHub Actions**: The automation tool that builds and deploys my site whenever I push changes
- **Markdown**: The simple format I use to write every post

## What I Learned

Building this blog took some initial research, but the result is a site I fully understand. I know exactly how it works from top to bottom. That feels much better than clicking buttons on a managed platform and hoping for the best.
