### My Projects
<ul>
<li>A private gamedev project</li>
</ul>

### My Interests
At the moment, I'm interested in making games.

### My Blog
<ul>
{% for post in site.posts %}
reached 
<li>
<a href="{{ post.url }}">{{ post.title }}</a>
</li>
{% endfor %}
</ul>

### Get in Touch
<ul>
<li><a href="https://twitter.com/{{ site.x_username }}">X/Twitter</a></li>
<li><a href="https://github.com/{{ site.github_username }}">GitHub</a></li>
</ul>
