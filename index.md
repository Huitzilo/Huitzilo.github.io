---
layout: page
title: BioMachineLearning
tagline: Neuromorphic computing, Odour Space exploration, and other things
---
{% include JB/setup %}

There's no content here and I have currently no plans to add any. Just wanted to play around with jekyll-bootstrap, and test the <username>.github.io web service, that's all. Everything you see on this page is boilerplate content from jekyll-bootstrap (except this note of course).

So, please walk on, nothing to see here folks. Have a nice day!
    
## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



