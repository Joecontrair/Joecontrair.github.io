---
layout: page
---

# Welcome
Welcome to the Blog Page. Here I will hopefully have an index of Blogs or something? Definitely going to upload things I've been learning in FOM such as proofs and other interesting 
puzzles we've been working on. <br/>

[back](./)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
