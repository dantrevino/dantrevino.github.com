--- 
wordpress_id: "124"
layout: blog_post
title: handbrake fix for ubuntu hardy heron
wordpress_url: http://wrevolution.org/?p=124
---
The handbrake gui no longer works due to changes in how mono was packaged in ubuntu.  I've made a simple dummy package that satisfies the dependency in the existing debs.  This only applies to hardy.  Linuxcrypt has a writeup <a href="http://linuxcrypt.net/?p=119" target="_blank">here</a>, along with the deb.
