---
layout: post
title:  "TIL: How to set up a Blog in 30 minutes"
tags: blogging
author: Jessica Keener
---

# TIL How to set up a Blog in 30 minutes

It really was ridiculously easy. Even though yes, I am a frontend engineer, I did not want to spent hours creating a nice custom blog, I just wanted to get to typing! Austin was suspicious I could accomplish a full-on blog as quickly as I thought, so I was out to prove a point more than anything else. Here's how it goes:

## Creating the Blog

This was easiest. There is literally a tutorial on github with an ELI5 setup, so I just chose "project setup" and followed the directions- done in 5 min!  [Here's the github pages article I followed](https://pages.github.com/)

**Note:** Because I wanted a _blog_, I actually found it much more useful to google "Jekyll blog themes", and use a free one, as most of the Github-included themes were not for _blogging_. I landed on [Contrast Jekyll Theme](https://jekyllthemes.io/theme/contrast)

This was nice, because It went ahead and had some of the other stuff installed and ready that I will cover below. But, if you're a purist, read on.

## Making the Blog have useful content

Ok, this was a little bit more work, because I had to learn what Jekyll did and why, but here is the short version:

1. Go ahead and clone the repo you made, assuming you haven't already. 
2. In your repo, create a `_posts` folder at the top level.
3. I added folders to contain the major categories I knew we would be blogging about, just to get started. Something like this:
```md
_posts
    - front-end
        - accessibility
    - today-i-learned
    - discord
    - debugging
```

4. I learned the basic format for making a file, and added my first file (this one!) `YYYY-MM-DD-BLOG-TITLE.md`, for example, I titled this bad boy `2021-08-27-gh-pages-blog.md`
5. At the top of all the files, Jekyll wants some markup, so I added it:
```md
---
layout: post
title:  "TIL: How to set up a Blog in 30 minutes"
tags: blogging
author: Jessica
---
```
Note, `author: Jessica` is a custom tag I am gonna try, as Austin and I plan to share this blog.

6. Start writing my markdown file that will turn into a blog!

And That's really all there was to it!

## Adding Assets

I figured I should go ahead and get the assets set up so we don't have to figure out out later, and it looks like Jekyll has also made that ridiculously easy.

It recommends creating a `assets/` folder at the top level, and linking as usual. Let's try it!

![All Might Thumbs Up!](/assets/images/allmight-thumbsup.png)

## More

I definitely gave a short version, but really, I just read through this [Jekyll Posts Blog](https://jekyllrb.com/docs/posts/) and grabbed the bits I cared about.


**Gl;HF!, Jessica**