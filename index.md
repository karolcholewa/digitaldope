<header>
      <h1>{{ site.title | default: site.github.digitaldope }}</h1>
      <h2>{{ site.description | default: site.github.project_tagline }}</h2>
    </header>
{% for post in site.posts %}   
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <p><small><strong>{{ post.date | date: "%B %e, %Y" }}</strong> . {{ post.category }} . <a href="http://karolcholewa.github.com{{ post.url }}#disqus_thread"></a></small></p>            
{% endfor %}
