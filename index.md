---
layout: default
title: Trusted Programming
---

We are leading the smooth transition towards more trustworthy software engineering
through innovative R&D in **programming theory**, e.g., lambda calculus-based functional
programming, deep code learning-based intelligent software engineering; **programming
technology and methods**, e.g., model-driven software development (MDSD), domain-specific
languages (DSL), and **programming tools**, e.g., code transpiler, deep code learner, bug
localizer, etc.

<h2>Blog posts <a href="{{ site.baseurl }}/feed.xml"><img class="feed" src="{{ site.baseurl }}/images/feed.svg"></a></h2>

<div class="posts">
{% for post in site.posts %}
  {% unless post.url contains "_cn" %}
    <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
  {% endunless %}
{% endfor %}
</div>

## Huawei and opensource

<div class="posts">
  <a href="{{ site.baseurl }}/articles/opensource-contributions.html">Huawei's opensource contributions</a>
  <a href="{{ site.baseurl }}/articles/work-in-progress/index.html">Huawei's opensource work in progress</a>
</div>

## Conferences 
<div class="posts">
  <a href="https://rustconf.com/">Rust Conference 2022</a>
  <a href="https://www.bagevent.com/event/8252295?bag_track=bagevent">The 2nd Rust China Conf 2021-2022, Shanghai, China</a>
  <a href="https://rustconf.com/">Rust Conference 2021</a>
  <a href="https://foundation.rust-lang.org">Huawei is one of the founding contributors to the Rust Foundation</a>
  <a href="https://2020conf.rustcc.cn">The 1st Rust China Conf 2020, Shenzhen, China</a>
</div>

## Jobs
<div class="posts">
  <a href="https://smu.recruiterpal.com/career/jobs/kdzg2">Full-time Research Scientist/post-doc position on Deep Code Learning -- Joint Research Project between Huawei and Singapore Management University - Open from 4 Nov 2022 to 18 Nov 2022</a>
  <a href="https://apply.workable.com/huawei-ireland/j/823CFEB55B/">Join Huawei R&D for Trusted Programming -- Job Opportunities</a>
  <a href="https://www.open.ac.uk/stem/computing-and-communications/node/230">Full-time PhD on Machine Learning for Software Engineering -- Joint Research Project between Huawei and The Open University (Closing date: 31 March, 2022 - 17:00)</a>
  <a href="https://www.linkedin.com/jobs/view/2703556146/">Full-time Postdoc position on Empirical Data-Driven Bug Localisation -- Joint Research Project between Huawei and The Open University (Closed)</a>
</div>
