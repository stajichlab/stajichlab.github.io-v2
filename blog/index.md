---
title: Blog
---

# <i class="fas fa-feather-alt"></i>Blog

## News

<!-- Twitter embeds from https://publish.twitter.com/ -->

<a class="twitter-timeline" data-width="400" data-height="400" href="https://twitter.com/stajichlab?lang=en">Tweets by StajichLab</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{:.center}

<a href="https://twitter.com/stajichlab?lang=en" class="twitter-follow-button" data-show-count="false">Follow @stajichlab</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
<a href="https://twitter.com/intent/tweet?screen_name=stajichlab" class="twitter-mention-button" data-show-count="false">Tweet to @stajichlab</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
{:.center}

## Videos

{% capture html %}
<!-- YouTube embed. Go to a video, click share, then embed. -->
<iframe width="600" height="400" src="https://youtu.be/okdpZFn-C5I" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{% endcapture %}

{% include centerer.html html=html %}

## Blog List

A _blog list_ component, to list and summarize all blog posts on your site.
Can be used on any page, but assumes its content from `/_posts`.

{% include blog-list.html %}

