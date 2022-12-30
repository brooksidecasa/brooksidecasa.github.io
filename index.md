---
title: brookside.casa
---

- [about](/about.html)
- [projects](/projects.html)

## blog

<ul>
	{% for post in site.posts %}
		<li>
			<a href="{{ post.url }}">{{ post.title }}</a>
		</li>
	{% endfor %}
</ul>

---

this site was inspired by maya's <https://faust.land>, which was itself inspired by <https://fireflysanctuary.today>.