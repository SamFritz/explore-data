---
layout: page
title: Customization + Publishing
permalink: /jekyll-customization/
parent: Adventures with Jekyll
navigation_weight: 3
---

### 5. Customize and Create

This is the fun step, where you get to alter the site to meet you needs, organize the information structure, and select visual display preferences.

The file for making changes to the visual aspects of this Jekyll site: `just-the-docs-default.css` because  the `index.html` defines the stylesheet as

 `<link rel="stylesheet" href="/assets/css/just-the-docs-default.css">`

**Changes**

I was interested in changing the **color** of the site (or for us Canadians, colour <-- I can't tell you how many issues I've created for my self because I've used CND spelling when coding). Majority of my work uses [Adobe Color](https://color.adobe.com/create/color-wheel) to help create palettes. 

Searched for #7253ed (there were 11 instances), attempted to change to `f77e7e`

`background-color` options

|  Color Code |   |
|-------------|---|
| #D9896C     |   |

### 6. Publish

Up until now, the site has been maintained and view locally. This means that even if you gave someone the `http://localhost:4000`, they will not see the content you've created.  So now it's time to make the Jekyll site viewable publically (if that's what you choose). This is also where I hit a snag. 

Resources to try out:

* 