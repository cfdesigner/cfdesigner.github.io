---
layout: default
title: Home
---
Craig Atallah Frost has a background in digital design, engineering, and product. He's currently helping to improve the state of consumer research as Head of Design at [Attest](https://www.askattest.com/). He cares about people, products, and process—in that order. You can reach him on [Twitter](https://twitter.com/_ctfd_uk), [LinkedIn](https://www.linkedin.com/in/craigtfrost/), or [Dribbble](https://dribbble.com/_ctf).

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}), on {{ post.date | date: "%b %d, %Y" }}
{% endfor %}