# HelloWorld

- just for learning things
- want to try out github pages

# Collection List

{% for comet in site.comets %}
  <h2>{{comet.title}}</h2>
  {{comet.content | markdownify}}
{% endfor %}

## add a section

[GitHub](http://github.com)



{% include_relative Products/prod1.md %}
{% include_relative Other/addon.md %}




