---
title: Slate, Window Management Tool for OS X
layout: post
tags: window management tool slate
---

The window management experience in OS X is awesome — except for programmers who rely hightly on their keyboards. I believe most programmers, like myself, feel a little painful when trying to resize an app, or switch between apps, in OS X. Alfred solves part of the pazzle, like quickly jumping to an app by typing its name. But that's not enough. Fortunately I have Slate now. I've used it for about a week and **it completely changed my way of using my computer**.

![](/res/slate.jpg)

Slate is an open sourced window management tool for OS X. It's extremely configurable and once you configured it in your favor, the benefit is huge, just like the author promoted. I'm only gonna talk about how I used Slate in this blog. But you can read always Slate's GitHub [homepage](https://github.com/jigish/slate) and this [post](http://thume.ca/howto/2012/11/19/using-slate/) to get a more thorough understaning of what Slate can do and how to configure it.

First and most important, I use Slack to focus my favorite apps. I set shortcuts for each of my most used apps, like my browser, my text editor, Xcode, Mailbox, and Gitbox. It's blazing fast. Trust me, you will never want to type in the name of an app in Alfred once you tried using shortcuts. There may be other ways to do it, but since Slate provides a very easy way to achieve this, why bother.

Next big thing, resizing windows and moving windows, potentially across monitors. I have configured shortcuts to set window to full screen, left half screen, right half screen, top half screen, bottom half screen and four corners of screen. Previouly I have to reach to my trackpad or mouse to finish this sort of task, now I can stay on my keyboards. Perfect.

Last but not least, I sometimes use direction keys to focus apps laid on top of the screen. It's fundamentally the same as with using shortcuts to focus a specific app, just more intuitive. Plus, you can do this on apps without a preconfigured shortcut.

For all of these shortcuts, I use `ctrl + cmd + [key]`. In case you might want to follow my approach, I created a gist with my configuration file. 

{% gist zichuanwang/48f92678616d3d58badc %}