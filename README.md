# Archethought Blog

Experimenting with jekyll-based website creation & blogging:  
We decided to go with the SoSimple layout for now. See below for branches with other layouts we considered. We can change layouts at any time fairly easily.

## How to add information
We have a spot for both articles and blogs: \_posts/blog and \_posts/articles

To add a blog entry, you simply write the blog with [Kramdown](http://kramdown.gettalong.org/syntax.html) styled markdown and check it into the \_posts/blog directory, similarly with articles.  Any referenced images go in the images/posts directory.  Each blog entry requires a header as per this sample:
```
---
layout: post
title: "<document title>"
categories: blog howTo practices
tags:	[virtual machine, vm]
date:   2016-10-07T12:00:00
modified:
---
```

## Findings
[Jekyll themes](https://github.com/jekyll/jekyll/wiki/Themes) really aren't *themes* at all, but simply layouts which are pre-developed site pages you can add to the github.io repository and then expand upon. No magic.
With Jekyll, you can verify your post looks acceptable before making it public. Clone the repository, modify your site; i.e., add a blog, and then serve it locally before committing with `bundle exec jekyll serve`. See more detail below.


## Branched Samples

We have branches prototyping several layouts.  To see the Archethought prototype of any one of these, do
```
git fetch
git checkout <branch name>
bundle update
bundle exec jekyll serve
```
Then view http://localhost:4000 in a browser.  Of course, you need to have jekyll and bundler installed, and the repository checked out. You might need to run ```bundle install``` as well.

Listed in order of promise. Kim liked iHavee over Flex.

* iHavee
<br/> Might need some work for a more professional appearance, but all is customizable. It lists by category and tag out of the box.  I've already modified the default colors and font size.
  * source: https://github.com/iHavee/iHavee.github.io
  * demo: http://ihavee.github.io/
* neo-hpstr
<br/> Has some deprecation warnings to resolve if we use this. Lists by category and tag. Has "share with" buttons so user can tell the world about our blog.
  * source: https://github.com/aron-bordin/neo-hpstr-jekyll-theme
  * demo: http://aronbordin.com/neo-hpstr-jekyll-theme/
* sosimple
<br/> This one looks professional out of the box, and could be extended for our entire website. The designer has several layouts and good explanation of how to use them. It does not list by category/tag out of the box.  Has a nice footer for contact links.
  * source: https://github.com/mmistakes/so-simple-theme
  * demo: https://mmistakes.github.io/so-simple-theme/
* hpstr
<br/> Just a blog. Interesting modern layout. Lists by tags. Has "share with" buttons so user can tell the world about our blog.
  * source: https://github.com/mmistakes/hpstr-jekyll-theme
  * demo: https://mmistakes.github.io/hpstr-jekyll-theme/
* flex
<br/> A very basic blog with two column layout.  Each blog entry has/can have a banner image. It does not list by category/tag out of the box.
  * source: https://github.com/the-development/flex
  * demo: http://the-development.github.io/flex/
* yummy 
<br/> I could not get this one to work, and wasn't worth debugging someone else's code. Unfortunately I'd already created the branch. I do like the demo, as it has a nice list of categories. 
``` 
jekyll 3.3.0 | Error:  undefined method 'sort' for false:FalseClass 
```
  * source: https://github.com/DONGChuan/Yummy-Jekyll
  * demo: http://dongchuan.github.io/
