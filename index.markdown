
<html>
<head>
<title>Page Title</title>
</head>
<body>

<div class="posts">
     <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>

<h1>Bienvenido a blog de unir</h1>
<p>Es un espacio de pruebas.</p>

</body>
</html>
