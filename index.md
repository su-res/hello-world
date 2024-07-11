---
layout: home
---

# Welcome to My Awesome Blog

This is the home page of your new Jekyll blog. You can edit this content in the `index.md` file. 

## Latest Posts

{% for post in site.posts %}
  * {{ post.date | date: "%B %d, %Y" }} &raquo; [ {{ post.title }} ]({{ post.url }})
{% endfor %}
