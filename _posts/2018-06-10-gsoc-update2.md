---
layout: post
title: GSOC Update Week 3 and Week 4
excerpt: Coding up the basic functionality.
tags: GSoC
comments: true
---

So, two more weeks have passed and I can officially say that I have started with the core of the codebase.
Although these were two slow weeks, I still have gotten some work done.

1. Config values are being used wherever possible. This allows for the code functionality to be tweaked more easily.
1. Video upload works. One can now upload videos the synced GDrive.
1. Searching. Users can search for videos by their name or their tags.
1. Tagging works. Users can now tag their videos with various tags. This can help in searching.
1. Users can also bulk-tag videos by also using the search feature.

In addition to these I have squashed a few implementation level bugs across various modules involved.

On the other hand there is some more work regarding these that needs to be done.
1. There is no set of 'allowed' tags. Anyone can upload anything. There is also no control on 
the values or the count of the tags. This will be rectified in the future.
1. Tagging only works on already uploaded videos. 
1. Semantics on search is pretty limited to the simplest AND/OR operations. Fixing this will probably be a 
very stretch goal.

All in all, as I said, a bit of a slow week but we are still on schedule.
