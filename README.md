# HelloWorld

- just for learning things
- want to try out github pages

# Collection List

{% for fruit in site.fruits %}
  <a href="{{ fruit.url }}/index.html">{{ fruit.title }}</a>
{% endfor %}




## add a section

[GitHub](http://github.com)


{% include_relative Products/prod1.md %}

{% include_relative fruits.md %}

{% include_relative Other/addon.md %}




