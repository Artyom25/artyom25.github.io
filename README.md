---
title: My bloh
---
<!DOCTYPE HTML>
<html>
  <head>
    <title>{{ page.title }}</title>
  </head>
  <body>
    <ul>
      {% for post in site.posts %}
        <li>
          <a href="{{ post.url }}">{{ post.title }}</a>
          {{ post.excerpt }}
        </li>
      {% endfor %}
    </ul>
  </body>
</html>
	
