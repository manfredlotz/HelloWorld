# HelloWorld

- just for learning things
- want to try out github pages

# Collection List

{% for ele in site.list %}
  <h2>{{ele.title}}</h2>
  {{ele.content | markdownify}}
  <p>bla</p>
{% endfor %}

## add a section

[GitHub](http://github.com)


{% include_relative list.md %}

{% include_relative Products/prod1.md %}
{% include_relative Other/addon.md %}




