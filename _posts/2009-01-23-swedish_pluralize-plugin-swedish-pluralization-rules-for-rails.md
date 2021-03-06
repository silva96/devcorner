---
title: 'swedish_pluralize plugin: Swedish pluralization rules for Rails'
author: Richard
layout: post
categories:
  - Ruby on Rails
tags:
  - plugin
  - pluralization
  - Ruby on Rails
  - swedish
  - swedish_pluralize
---
For those of you looking for Swedish pluralization for Rails, I just refactored this module of ours into a plugin. You can find it on GitHub: [https://github.com/mynewsdesk/swedish_pluralize](https://github.com/mynewsdesk/swedish_pluralize)

It’s extracted from the old swe_rails plugin by Ola Bini, which did a bit more than just pluralize in Swedish. So if pluralize is all you want to do, check out the plugin.

It adds an string inflector like so:

{% highlight2 ruby %}
>> "bok".swedish_pluralize
=> "böcker"
{% endhighlight2 %}
Happy pluralizing!