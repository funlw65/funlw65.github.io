[-=Back to Home=-](https://funlw65.github.io/)

<hr />

#  :sparkles: News  :sparkles:
Here you can read all the news of this site

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>
        <strong><a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </strong>
      </li>
    {% endfor %}
  </ul>


```markdown
Done.
```
[-=Back to Home=-](https://funlw65.github.io/)
