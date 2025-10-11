+++
author="Xavier Travers"
title = "Creating this dev-blog"
description = "The beginnings of the dev-blog. And a little about how I work (or don't)."
date=2025-10-11
draft=false
[taxonomies]
categories=["dev-blog"]
tags=["dev-blog"]
+++

I have, for some time now, been contemplating a need to create a website to host my thoughts and project overviews. This is a standard practice among software engineers. Some start on [Medium](https://medium.com/), some create a [Susbtack](https://substack.com/home), and some create their own websites. 

## How is this built?

- Compiled with [Zola](https://www.getzola.org/).
- Currently themed using [serene](https://github.com/isunjn/serene).
- Hosted on [GitHub Pages](https://docs.github.com/en/pages).
- Written with `markdown`.

### Why Zola?

My (now outdated) portfolio website [\<code\>digital](https://codedigital.me/), is currently compiled with [React](https://react.dev/) using [NEXT.js](https://nextjs.org/). This was a fun learning experience, and I may like to revisit modern web stacks as a whole, but my current goal is to produce as much output as I am taking in input. That means adopting a fast/simple static-site generator that can support some `markdown` and maybe other neat features on an as-needed basis. So when I started looking into creating this site, I focused in on simplicity.

My next stop of investigation was to briefly consider [Hugo](https://gohugo.io/). `Go` is on my wishlist of programming languages to learn, and Hugo is a well-recognized library.
So I started a tutorial, installed Hugo with `wget`, and got to creating the website you're reading right now...

Actually, I didn't do that. Instead, I did some research.
It turns out that Hugo uses the `Go` template engine, which is noticeably dissimilar to `Jinja`.[^1] So much so, that a developer built his own templating system [Tera](https://keats.github.io/tera/) and static site generator (Zola). This was enough for me to make the jump. 

[^1]: [According to an interview](https://rustacean-station.org/episode/007-zola/) with [Vicent Prouillet](https://www.vincentprouillet.com/).


## Why make this?

Provides me with:
- A place to store my thoughts for me.
- A place to store/share project ideas.
- A public way to force myself to complete projects.

I find that I often have ideas and thoughts that I would love to share with others which I often lose to the moment. I could have a conversation with an interesting conclusion, or a one-liner thought that I want to expand on. Unless I write these things down, I am likely to forget them and move on. This goes against one of my intrinsic motivations: "contributing to the expansion of knowledge / possibility". 

Speaking of motivation, I struggle with perfectionism. When I start a project, I must complete it **perfectly**. If I cannot achieve this, I will move onto something else.
This influences my ability to work on personal projects in a way that I do not appreciate.
I have started to work on many projects, few of which have seen the light of day. This dev-blog presents a great way to provide an explicit extrinsic motivator for working on things: prying eyes. Hopefully, the prospect of readers such as yourself viewing my work in an in-progress and completed state will motivate me to action.