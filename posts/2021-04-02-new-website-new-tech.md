---
title: New website, new tech
description: My path to make a new website
date: 2021-04-02
tags:
  - web
layout: layouts/post.njk
---

Welcome! 👋👋👋

This is my new website, built after trying a bunch of different static site generators (SSG). I ended up using [Eleventy](https://www.11ty.dev/), a very slim SSG that runs in Javascript.

Originally I was considering [GatsbyJS](https://www.gatsbyjs.com/) since I am pretty familiar with it on one of my projects. It has some great optimizations for websites, like image placeholders and great plugins, but the larger company's pivot into web hosting and its lack of detailed, fleshed out documentation (despite being around for a few years now) led me to look for other options.

I tried [NextJS](https://nextjs.org/) which is the most powerful and versatile React-based framework I have seen. It's most recent major version (10) seems very competitive with Gatsby in terms of building static sites, and on top of that can run server rendered sites as well. I think my next projects will use Next, given its power and versatility.

But this is my blog, not an e-commerence website. I don't need to connect to a CMS so a customer can make updates to the site on their own. I don't need complex app interactivity or shopping carts. I just want to show off my latest work and write Markdown from time to time, and after bouncing around between SSG technologies, I realized <mark>I want something fast and simple.</mark> Years ago I was using Jekyll and having a fine time with that, so why not use something similar, just a little more modern?

## Eleventy

It's simple, light, and builds standard HTML/CSS/JS websites, with none of the JS-loading-HTML trickery of React. It has a great community, and lots of different options in its [starter library](https://www.11ty.dev/docs/starter/) to check out.

If you so desire, you can port an old Jekyll site straight over to it with little fuss. But of course, doing what I do best, I found some fun ways to complicate my new site.

Although simple to start using by itself, Eleventy allows for a lot of complexity, so if you want a template with all the bells and whistles, you can find it. I ended up using [eleventy-high-performance-blog](https://github.com/google/eleventy-high-performance-blog), developed by a Google engineer with a lot of web best-practices baked into it. There's also a bunch of Google Analytics stuff in there that I pruned away, because I don't care about tracking people. After some more pruning and styling, I ended up with the website you see before you! It scores 100s on Lighthouse audits at its Netlify host, thanks to its pre-fetching and image handling. And it's a loose enough framework that I know I can extend and play with it over the next few years as web technology continues to change.
