---
layout:     post
title:      "How to Quickly Start Jekyll on Github Page"
author:     Sirius Dely
date:       2017-04-03 16:00:00 +0700
tags:       [jekyll, github, meta]
---

So I have decided to try [Jekyll](https://jekyllrb.com) on [my Github Page](https://siriusdely.github.io), after wanting to try it since a long time before already. But It still took some-time for me to really understand what Jekyll is. Why was it?

The first reason, and also the main one, is because I have used [Git](https://git-scm.com) & [Github](https://github.com/siriusdely) for a while already. And I thought that Github will never modify whatever it is that has been pushed to my repo automagically for me. And now, knowing this Jekyll, things are different.

It took me a while reading through the [Jekyll docs][jekyll-docs] to find out what I need to do to generate the static files to push to Github. Meanwhile, what really needed is just a simple `git commit` & `git push`, and then Github itself will process whatever it is that I have pushed. Looking at [my siriusdely.github.com repo](https://github.com/siriusdely/siriusdely.github.com), still there are no static HTML, JS, or CSS files there. Amazing!

The second reason, I think is because I just barely knew how Github Page show which `branch` of the repo to show. I thought it only cared about things inside the `gh-pages` branch, but I was wrong. I just know that `master` branch is actually being used for User and/or Organization page. `gh-pages` branch is for Project page. And even for Project, Github Page can be done by providing things inside `docs` folder on the `master` branch. Those knowledge are new to me.

[jekyll-docs]: https://jekyllrb.com/docs/home
