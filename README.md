# Oral History Project

This is a Jekyll template for quickly creating and deploying oral history archives. It makes it (relatively) easy to get your archive up and running by letting you focus on collecting and transcribing oral history interviews. Once you have it working and configured, all you need to do is post content in Markdown format in an appropriate file.

Here is a broad overview of the types of pages Oryll Hystory lets you use and their file names.

## Home (index.md)

A home page for your website. It will pull the information you add in config.yml (e.g., the name of the project, the name of the researchers, or a header image) and post it onto the page automatically. You can edit the body text of the page yourself in the index.md file using Markdown.

## Project (project.md)

A page to describe your project/archive in detail. Like the home page, it will pull the information you add in config.yml and post it onto the page automatically. You can edit the body text of the page yourself in the project.md file using Markdown.

##Interview pages (all files in in the \_posts\ folder)

These pages will be the only ones you need to make yourself, unless you want to customize the template. Think of them as similar to blog posts (in the Jekyll framework, they technically are), but unlike blog posts they ask for front matter specifically geared toward oral history interviews. You need to include the following front matter:

```
---
title: interview title
header-img: link to header image
interviewee: interviewee
interviewee-photo: image source
interviewer: interviewer
blurb: blurb
layout: interview
tags: media some other stuff here
---
```

With the exception of "layout: interview", you will need to update the front matter of each interview with the correct information after the semi colon of each item.

## Interviews

This page will automatically pull every interview page and display it on a grid. There is nothing to edit here :)

## Tags

This page will automatically pull every tag and display it in a list. Nothing to edit here either.

## Categories

This page will automatically pull every tag and display it in a list. Again, this is all automatic.




---------------

A Jekyll-based framework for presenting oral history content. In development.

## To-Do:
- Style interview page
- ~~Change allposts.html -> interviews.html~~
- ~~Add tag functionality~~
- ~~Create all tags page~~
- Change samplelist.yml to nav.yml (duh)
- ~~Add category functionality~~
- ~~Create all categories Page~~
- ~~Create all interviewees Page~~
- add search functionality
- Icons
- Typography
- Add 404 page
- sitemap generator
- add config material
- Fix interview.html aside from breaking
- Create project page

-------------------------
Rick Wysocki

[website](rickwysocki.com)

[twitter](twitter.com/rickwysocki)
