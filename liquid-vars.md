## liquid / Jekyll vars 

### what needs "publishing," and what works with a straight push?
<ul>
  {% for post in site.posts %}
    <li>
      <a href=".{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

<p>
* Time 
{{ site.time }}
</p>