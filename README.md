# HelloWorld

- just for learning things
- want to try out github pages

# Collection List

{% for fruit in site.fruits %}
  <h2>{{fruit.title}}</h2>
  <a href="{{ fruit.url }}">{{ fruit.title }}</a>
{% endfor %}




## add a section

[GitHub](http://github.com)


{% include_relative Products/prod1.md %}

{% include_relative fruits.md %}

{% include_relative Other/addon.md %}




