# HelloWorld

- just for learning things
- want to try out github pages

# Collection List

{% for fruit in site.fruits %}
  <h2>{{fruit.title}}</h2>
  {{fruit.content | markdownify}}
{% endfor %}

## add a section

[GitHub](http://github.com)


{% include_relative list.md %}

{% include_relative Products/prod1.md %}
{% include_relative Other/addon.md %}




