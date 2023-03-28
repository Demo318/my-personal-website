---
layout: post
title:  "Post Reference Material"
date:   2023-03-27 18:34:18 -0500
date_updated: false
categories: jekyll update
tags: 
comments: true
related_posts: post-1 post-2 post-3
other_posts: post-4 post-5 post-6
---

## Filename conventions

Should always follow the format `year-month-date-title-information.md`. For example: `2023-02-28-my-first-blog-post.md`.
File-name dates should remain the date the post was initially published.

## Title & Headings

The 'title' taken from the front matter will be placed into the page with an h1 tag. Any headings occuring within the body of the post should begin with h2 tags, indicated with `##`.

## Front Matter

### Layout

Blog posts should always use layout `post`.

### Title

A string encapsulated in quotation marks in capitalized as desired, i.e. `"This New Blog Post"`.

Prefer titles that meet [APA Guidelines](https://capitalizemytitle.com/style/APA/).

### Categories

Categories are kept limited to fit with the website's overall flow. The only cateogires in use so far include:

#### Faith

Information related to Christianity or religion in general. This should include lessons take from Scripture, the Church Fathers, or other spiritually-focused insights.

#### Family

Marriage, fatherhood, and other family relationships. Even if using Christian principles and Scripture as a foundation, the overall emphasis of the post is "family," it should fall into this category.

#### Fitness

Health-related subjects. Primarily excercise but also some diet information.

#### Code

Learnings, examples, and updates on projects. Here include code snippets, summaries of things learned, and other such details.

### Tags

More information to come.

### Comments

By default, set to `true`, but option to set to `false` if no comments desired. (This front-matter can be set on both blog posts and webpages, driven by [Disqus](https://disqus.com/home/).)

### Related Posts

Three or four other posts from within the same cateogory. Shold be filenames without extensions separated by spaces, ex. `2023-03-27-welcome-to-jekyll 2023-04-01-jekyll-is-awesome`.

### Other Posts

Three or four posts from outside of the current category. Same logic as `Related Posts`.