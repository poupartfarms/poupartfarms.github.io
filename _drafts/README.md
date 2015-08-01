---
layout: post
title: "Readme"
quote: "Is this thing on?"
video: false
comments: true
tags: [ veganism, philosophy, speciesism ]
author: Chris
fbimage: /media/2015-07-29-cecil_the_lion/cecil.jpg
image: /media/2015-07-29-cecil_the_lion/cecil.jpg
---

This file is kept here so that git will continue to track this directory even
when there are no blog drafts for Jekyll.

# Working with drafts

Drafts are posts without a date. They’re posts you’re still working on and 
don’t want to publish yet. To get up and running with drafts, create a 
`_drafts` folder in your site’s root (as described in the site structure 
section) and create your first draft:

```
 |-- _drafts/
 |   |-- a-draft-post.md
```

To preview your site with drafts, simply run `jekyll serve` or `jekyll build` 
with the `--drafts` switch. Each will be assigned the value modification time 
of the draft file for its date, and thus you will see currently edited drafts 
as the latest posts.
