---
layout: post
title:  "First post in demo category"
date:   2021-04-16 08:00:09 +0300
categories: demo
---

_Some italics here_ was pending because timestmp... now live!

Link to [second post](2021-04-18-Second-post.md)

test 1

{% post_url 2021-04-18-Second-post.md %}
{{ site.baseurl }}{% post_url 2021-04-18-Second-post.md %}
{{ site.baseurl }}{% post_url /demo/2021-04-18-Second-post.md %}

test 2

[Link title 2]({% post_url 2021-04-18-Second-post %})
[Link title 3]({{ site.baseurl }}{% post_url 2021-04-18-Second-post %})
