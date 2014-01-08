---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

Hello guys! 

    What if I do this, oh that's cool 


    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username



Here is what I link looks like: [Jekyll Bootstrap](http://jekyllbootstrap.com)

Recent posts:

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Here's another heading

Why hello there again

```python
 s = "Python syntax highlighting"
 print s
 ```



