---
layout: post
title: GSOC Update Week 7 and Week 8
excerpt: More or less, finished.
tags: GSoC
comments: true
---

It's the beginning of the end. The project works as it is expected but with a few kinks ofcourse.
So, to clarify, I have completed the functionality part of the project. all functionalities are there
to be polished.

1. Implemented the permissions feature. Now, we can share data with other people.
1. Added database interfaces. We now store channels, jobs and permissions.
1. Recorder feature has been added. We can now record streams.
1. Added and tested the upload pipeline. Nephos can record, process, upload, tag and share recordings.
1. Due to python version of the test machine. I had to backport my code to python3.4.
1. Rest of the stuff is me trying to make sure that code works.

In addition to that, I have opened up a lot of [issues]. Here you can look up what problems the current Nephos faces,
and help out if you can. I am currently working on writing tests and making nephos more reliable.

[issues]: https://github.com/AadityaNair/ProjectNephos/issues
