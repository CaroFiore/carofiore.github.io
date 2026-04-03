---
title: Entry3-BlogStruggle
date: 2026-04-02
toc: false
layout: post
---

# Dear Diary..
If you are reading this, then CaroFiore (bless his soul) has managed to set up the blog.
Now, going from the previous entry to this is quite a jump, so let me update on what happened.

### The Bus Stop(ped)
Yesterday, fittingly on April 1st, I was giga-pranked by the local bus company running our "OV".
Now, it doubled my traveling time to and from my education-location, and I spent a **lot** of that time figuring out the blogging stuff.

For the first time in a long time, I came home and could not stop working on it. I'm not used to this level of motivation, but it was pleasant :]

What was not pleasant however, was the **gods be damned bleeding mess that was jekyll and github pages.**

![relevant](https://imgs.xkcd.com/comics/average_familiarity.png)

> This xkcd resonates with me to no end. I've been turned off and away from IT and coding a ton due to what I consider to be the horrible way information is documented and communicated.
>
> Attempting to work with jekyll and github pages has reinvigorated my blazing hatred for any resource that lacks beginner-friendly options. Thanks xkcd for providing us with such a beautiful piece of art.

### The Couch
At home, having eaten dinner and continuing my work on the blog, I started looking for accessible tutorials for GitHub Pages.
My first serious attempt started with [this tutorial by sfarrens](https://github.com/sfarrens/jekyll_tutorial).

The result of following this tutorial was a mess of failed repo's and general confusion as to what in the world I was actually doing. 
I don't actually fault sfarrens for this, but I may or may not have had to mercilessly purge several repo's into the graveyard.

I suppose it did not help that this resource was from 6 years ago, which may explain the fuckton of deprecation errors I got trying to build the site. *Hmmm..*

**An utter failure, if I may say so myself.**

Deep breaths. Let's learn from our previous mistakes. Time to consult **the oficial documentation for GitHub Pages.**
As was with jekyll, now hopefully is with GitHub.

[yeah.. no](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll)

GitHub's documentation did two things:
1. Not explain their step-by-step process and
2. Make way too many steps

So that was a bust. (I did attempt it, I swear. I just got majorly stuck when it came to having multiple repo's besides just the github.io repo! I'm still not sure what the idea was, I must have misunderstood one of the steps..)

> My second quoteblock I will devote to my complaint regarding step-by-step tutorials. Listen well:
> 
> **IF YOUR STEP BY STEP TUTORIAL NEEDS MORE THAN 10 STEPS TO COMPLETE, YOU NEED TO RETHINK WHETHER A STEP TUTORIAL WAS THE RIGHT CHOICE.**
>
> Disagree if you wish, but just like Minecraft Redstone, if your tutorial requires more than 10 steps, perhaps it's time to actually explain what you are doing. If a user messes up one of the steps, then the more steps you have, the harder it is to debug where it came from.. 
> 
> Subdivision into sections with validation whether you did it right is huge!

### The Following Day
The clock didn't just strike, but utterly hammered 10 o'clock. It was time to relax.
I told myself that I failed today, but of course, failure is part of the process.
The day after, I was going to do it right.

And I did (I think?). I learned from my mistake and instead devoted my attention to a Youtube tutorial.
I made sure the date on it was recent, which paid off. [Ahmed Tremo, if you are ever reading this, cheers dude.](https://www.youtube.com/watch?v=m1RYsmOMPLs)

**The blog was working**, my site showed up on my github.io page, and all was well in the world. I celebrated with a peanut butter sandwich.

### But It's Not Over
Now, I used Chirp as my template for the jekyll site, which is great. 
It works just fine, but I got stubborn, and decided to mess around with files myself.

Since I am now working with WSL, my assumption was that I would not be able to access any Linux files on my system in my windows file explorer. After all, **I had devoted myself to living inside the command line**.

I am still *sort of* committed to using command line as much as possible, but it kind of broke my workflow realizing I had no bloody way to open, edit and move .png files. 
That's when I found out I **CAN** actually access all my stuff in my linux directories via explorer. Neat!

I spent about half an hour trying to replace the favicon on the site. Tediously I manually resized my profile picture multiple times to match the favicons that were provided by the Chirp template.

My mistake? My failure? Editing all that in the fucking _site directory. All my carefully handcrafted images were obliterated in the blink of an eye when I called the site to rebuild.
**Turns out that's not how you do it, you baboon.**

> Working with Linux and command line related stuff has made me quite alert with the state of my files. It's common knowledge that there is no way back once you call rm -r, 
> but I must say it's almost quite fascinating how little guardrail there is in place sometimes.
> 
> Just now I put my files in the wrong spot and saw them deleted in an instant, no way back. I obviously did it right the second time, and learned from my mistakes, but what if I had put the wrong files in there?
> **Yay to backups!!**

### Now We Rest
I managed to use [favicon generator](https://realfavicongenerator.net/your-favicon-is-ready) to create my icons, and that was that. The next step will likely be to actually customize things a bit further, but **the only .css file I've found so far is literally 1 line. *ONE LINE. WITH LIKE A GAJILLION CHARACTERS. WHY?***

This was pretty fun. See you in the next entry.
