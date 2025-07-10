---
layout: post
title: a post with bibliography
date: 2023-07-12 09:56:00-0400
description: an example of a blog post with bibliography
tags: formatting bib
categories: sample-posts
giscus_comments: true
related_posts: false
related_publications: true
---

This post shows how to add bibliography to simple blog posts.

> **Note:**  
> On GitHub Pages, custom tags like `{% cite %}` are **not supported**.  
> You can manually add references as shown below.

You can add simple citations using Markdown footnotes like this [^1], multiple citations like this [^1][^2], or long references with a blockquote:

> **Einstein (1905) On the Movement of Small Particles Suspended in Stationary Liquids Required by the Molecular-Kinetic Theory of Heat**  
> _Annalen der Physik, 17:549–560, 1905._

Here is a sample quote from Einstein (1905):

> Lorem ipsum dolor sit amet, consectetur adipisicing elit,  
> sed do eiusmod tempor.
>
> Lorem ipsum dolor sit amet, consectetur adipisicing.

If you would like something more academic, check the [distill style post]({% post_url 2018-12-22-distill %}).

---

## References

[^1]: Einstein, A. (1950). _The Meaning of Relativity_. Princeton University Press.
[^2]: Einstein, A. (1905). _On the Movement of Small Particles Suspended in Stationary Liquids Required by the Molecular-Kinetic Theory of Heat_. Annalen der Physik, 17:549–560.
