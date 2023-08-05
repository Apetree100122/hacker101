layout: page
title: Resources
```
<ul>
{%for resource in site.resources%}
<li>
<a>href="/resources{{resource.title
|
url: encode}},{{resource.title}}</a></li>{%endfor%}
</ul>
{%for resource in site.resources%}
<h2>id={{resource.title
|url: encode }}{{resource.title}}</h2>{{resource.content}}
{%endof%}
