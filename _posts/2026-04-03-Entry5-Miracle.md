---
title: Entry5-Miracle
date: 2026-04-03
layout: post
---

# Why did that work?

Okay, I've "kutted" with the css for a while now.

I had a massive problem with GitHub pages not displaying the same css as was on my localhost. This was firstly annoying to fix since localhost was **always fine**, and I had to commit + push to main every single time I wanted to try any change.

Well, I spent a lot of time looking through references in the html that GitHub could assume to be "wrong". I read that relative links break regularly, so that must be the solution..?

I'm still not used to the environment though. It's still a bit confusing where I need to be at what time, and where to look. There are a ton of hrefs in my css, do I need to fix them all? Which piece of html is using what parent? Are any of them adopted? Orphaned?

The more I tried, the less seemed to work **(GENIUS!)**, so I decided to do a full restart. Let's go back to where we were at the start...

**...and then it just.. *worked***

### What went wrong (or right)

There is a good chance that my pages worked since the beginning. The thing with github pages is that it loves to nestle your page into your cache. It can take over 10 minutes (sources claim) for your page to actually show your updated code.

I'm using a workaround, which is just clearing the cache for github.io, but it wasn't perfect. There is a chance that 2 hours ago, when I started bugfixing, *the page was already fine*, it just *wasn't showing up*.

> So, did I waste my time? I'm not sure. On one end I do feel like I've studied further on things that *could* go wrong, but this was not exactly productive. I haven't furthered my understanding about how this abusive relationship between github pages and jekyll works.
>
> If I say it bluntly, I believe my loud ex-neighbours had better communicative skills than these lads. Bless 'em, they're amazing.

### CSS

So now, my page has custom css. I did a lot of tweaking that may not be obvious behind the scenes, but at least I can now say that it looks something more like *"me"*.

The margins and formatting are all still just minima, don't get me wrong, but at least I am discerning myself from my fellow 12-year olds who have no clue how to css. Godspeed my friends, we will make it someday.

Also, bless html for being so nice with images and gifs, I really appreciate the simplicity <3

**With this, I think I can consider my first asignment a success!**
