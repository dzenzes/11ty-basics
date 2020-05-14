# Mein Blog

Erst haben wir so navigiert...

- [erster Eintrag](/posts/first-post/)
- [zweiter Eintrag](/posts/second-post/)

Jetzt sind wir schlauter und nutzen eine Collection:

<ul>
{%- for post in collections.blog -%}
  <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
{%- endfor -%}
</ul>
