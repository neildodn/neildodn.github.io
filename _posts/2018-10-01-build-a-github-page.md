---
layout: post
title: "Build a Github Page"
date: 2018-10-01
---

**_This is a tutorial for building an Github page with Jekyll style (without installing Jekyll) in an online fashion._**

## Comments
### Advantages:
- This website is hosted on Github
- Using both html and Markdown languages.
- It can support LaTex.
- The theme is clear and looks modern.
- Posts are composed using Markdown, and they can written offline using some
Editors such as Atom. After finishing writing, just upload the `.md` file
to the repo on GitHub

### Disadvantage
- The website is generated only if its source code is hosted on Github.
For instance, if we download the source code and open the `index.html` file
locally, the `css` is not effected, the `.md` files are not rendered to `html`

## Step 1: Create a GitHub page
We can create a simple Github page with Jekyll (which is not needed to be
  installed) by following the tutorial: Creating and Hosting a Personal Site on GitHub](http://jmcglone.com/guides/github-pages/)

## Step 2: Connect GitHub Desktop with the source code
In order to easily edit `.html` and mostly `.md` files, we should clone the
repository to GitHub Desktop and edit these files using Atom
- Open GitHub
- Login into the account
- File > Clone Repositories
- Go to History > open file that needed to be edited using Atom > edit files >
save
- Go to Changes > write a brief summary > Commit to master
- Push origin

## Step 3: Compose posts

For Markdown used to edit `.md` files, please refer to [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

For integrating LaTex into the GitHub page, please refer to [How to use LaTex in Markdown](http://flennerhag.com/2017-01-14-latex/)


## References
- [Setting up your GitHub Pages site locally with Jekyll](https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/)
- [Creating and Hosting a Personal Site on GitHub](http://jmcglone.com/guides/github-pages/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [How to use LaTex in Markdown](http://flennerhag.com/2017-01-14-latex/)
- [How to Automatically Convert Markdown to HTML](https://zapier.com/blog/markdown-html-export/)
- [Online Markdown Editor: Dillinger](https://dillinger.io/)
