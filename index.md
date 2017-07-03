---
layout: default
title: About me
permalink: /
---

## About me

My name is Pierre Le Gall, some friends of mine call me Pieru.

I'm a music lover close to Techno and Psy Trance culture. I like dansing, sleeping and boardgames. I just hate when things are unnecessarily complicated.

I currently work for [Zenika at Nantes](https://nantes.zenika.com/) (France) as developer. I use to work on the JS/Node.js stack with our clients, however I'm more inspired by the Erlang/Elixir ecosystem at the moment. More globally, I'm interested in back-end development, “lowtech” solutions and knowledge sharing.

You can find me on the Internet on [Twitter](https://twitter.com/{{ site.twitter_username }}), [Github](https://github.com/{{ site.github_username }}), or on this website where you can find some blog posts about random stuff.

## Blog posts

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
    <small class="hidden-xs">{{ post.date | date: "%B %-d, %Y" }}</small>
  </li>
  {% endfor %}
</ul>

<p class="rss-subscribe">RSS/Atom feed available <a href="{{ '/feed.xml' | relative_url }}">here</a>.</p>
