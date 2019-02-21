---
layout: project
title: progress.stream
description: Progress Bars as a service!
repo_url: https://github.com/aduane/progress
live_url: http://progress.stream
preview_picture_path: /img/projects/progress-stream-preview.png
technologies: ruby, rails, websockets, redis
---

I had a really long-running test suite and wanted to keep tabs on it
remotely. I built this and paired it with a custom rspec test runner so I
could follow along with the progress on my phone.

It supports updating the progress absolutely ("we are now 43% done") and 
incrementally ("another unit of work is completed"). The second option there 
allowed me to use it even when running my tests across multiple processes. The
individual test processes did not need any knowledge of the others, they just
report on the work they do.
