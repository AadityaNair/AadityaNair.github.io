---
layout: post
title: GSOC Update Weeks 9, 10 and 11
excerpt: Additional features also done
tags: GSoC
comments: true
---

Oh man, we are at the final mile. A lot of stuff happend.
Biggest of all, my university started in full swing which is why this update was delayed.
Also, I wasn't able to do much these weeks.

1. The upload pipeline now also deletes stuff. No more filled disks!!
1. The pipeline now creates folders for each channels and uploads content there.
This brings much needed organisation to the recorded streams.
1. All logs now go to a file. This allows logs to be reviewed later.
1. Use simple `Popen` to convert files. This makes it easier to capture output.
1. I added an FTP backend to upload stuff to an FTP server. Obviously permissions don't work for FTP.
1. So as to simplify adding new backends later, I added a common storage backend which all fucntions call.
This new backend handles all interactions with individual backends.
1. You can specify in the config which all backends you want. This way you may configure many backends
but choose to upload to only a few.
1. Added support to store channel schedules. For each channel, you can now store when which program is 
going to air. You can also store some metadata related to that program as well.
1. This enables us to implement one nice feature for jobs. We can specify jobs by the schedule item metadata.
So during job specification, one can, for example, specify to download all programs with metadata `type:news`
to download all news airings. Currently, schedule is populated by directly adding elements to the DB.
1. Lot more test stubs. I wanted to bring the coverage value closer to the actual one
1. LOTS of bug fixes and consistency issues. A large part of database problems have been sorted out.

A little more than a week is left for this to end. For the final push, I think this is enough for code. I will be
focusing on the documentation and testing code. These have seen the least attention the last months.
