---
layout: page
title: Getting Started
permalink: /getting-started/
parent: Adventures with Jekyll
navigation_weight: 2
---

## Introduction

My interest in working with a Jekyll site came after attending a few workshops, where instructions had been set up through an insitutional repository and displays through the just-the-docs theme. 

I wanted to launch a Jekyll site that:
- brought together materials walking through my data analysis exploration (of which there are a variety of techniques)
- it's a humbling experience to do something difficult and out of your comfort zone, when there's an easier option

## Steps

### 1. Gather the Ingredients
**Tools**:

* GitHub user account
* Text Editor
* Basic understanding of Command Line ([Intro to Bash](https://programminghistorian.org/en/lessons/intro-to-bash) tutorial from Programming Historian)
* Basic understanding of Markdown ([Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) provides a great overview)

**Dependencies**: (in coding terms, this means when a piece of software relies on another one)
* Homebrew
* Ruby
* Ruby Gems
* Jekyll

### 2. Dependency Checks / Jekyll Install

Mike Dane, a developer and teacher, has created a series of [Jekyll Tutorials](https://www.youtube.com/watch?v=1na-IWfv08M&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=8), and these were invaluable for understanding how Jekyll works, how to create a Jekyll site and information around configuring content.

* Check ruby version: `ruby -v` ([2.5.0 or higher](https://jekyllrb.com/docs/), as of September 2021 )
* Check gem version: `gem -v`
* Install the jekyll and bundler gems: `gem install jekyll bundler`
* Check Jekyll version: `jekyll -v`

### 3. Create a New Jekyll Site

Followed instructions from Mike Dane's [Tutorial: Creating a Site](https://www.youtube.com/watch?v=pxua_1vyFck&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=4)

* Create a new Jekyll site: `jekyll new myblog`
* Change into your new directory: `cd myblog`
* Build the site and make it available on a local server: `bundle exec jekyll serve`
* Open browser to view local version of you Jekyll site: `http://localhost:4000`

### 4. Jekyll Themes

There are a variety of themes available for Jekyll. This means that a theme can be applied to the site you've just created to change the way the information is visually structured and displayed. 

The Jykell site offers a variety of resources to search for themes: https://jekyllrb.com/docs/themes/. 

I found this was a bit of a tricky step, especially when apply themes that hadn't had a lot of recent development. I decided to go with the [just-the-docs theme](https://github.com/pmarsceill/just-the-docs), which is prevelant in many academic institutions for sharing tutorial based workshops.

Opening myblog folder using a text editor, navigate to the **Gemfile** (not the Gemfile.lock): 

`gem "just-the-docs"`

Navigate to the **_config.yml** folder and add:

`theme: just-the-docs`

And then execute:

`bundle`

If you run into any issue, I also found you could install it via:

`gem install just-the-docs`

### 5. Customize and Create

This is the fun step, where you get to alter the site to meet you needs, organize the information structure, and select visual display preferences. 

### 6. Publish

Up until now, the site has been maintained and view locally. This means that even if you gave someone the `http://localhost:4000`, they will not see the content you've created.  So now it's time to make the Jekyll site viewable publically (if that's what you choose). This is also where I hit a snag. 

Resources to try out:

*  