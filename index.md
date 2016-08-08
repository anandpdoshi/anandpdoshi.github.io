---
layout: base
title: Anand Doshi
background: "#EAF9FF"
---

<h3 class="hi">Hi. I am Anand Doshi.</h3>

I am an upcoming UX designer and a graduate student at the [University of Michigan](https://www.si.umich.edu/academics/msi/human-computer-interaction-hci). While working at [Frappé](https://frappe.io/about), I got hooked to design, typography and open source. I would start my day reading [Hacker News](https://news.ycombinator.com) and [Designer News](https://www.designernews.co/), and discuss anything interesting with my awesome colleagues. This culture of openness at Frappé shaped my work ethic and aesthetic tastes, and made me aware of my shortcomings. I believe I have something unique to offer to the world, and hope to realize my potential in the days to come.

#### Latest Articles

{% assign posts = site.categories['blog'] %}
<ul class="list-unstyled">
	{% for i in (0..1) %}
	{% assign post = posts[i] %}
	<li>
		<a href="{{ post.url }}">{{ post.title }}</a>
	</li>
	{% endfor %}
	<li>
		<small>
			<a href="/blog">more</a>
		</small>
	</li>
</ul>

#### Design

{% assign posts = site.categories['portfolio'] %}
<ul class="list-unstyled">
	{% for i in (0..1) %}
	{% assign post = posts[i] %}
	<li>
		<a href="{{ post.url }}">{{ post.title }}</a>
		<small>{{ post.excerpt }}</small>
	</li>
	{% endfor %}
	<li>
		<small>
			<a href="/portfolio">more</a>
		</small>
	</li>
</ul>


<h4><a href="https://github.com/anandpdoshi" target="_blank">Code</a></h4>

<ul class="list-unstyled">
	<li>
		<a href="https://github.com/frappe/erpnext" target="_blank">ERPNext</a> <small>ERP made simple</small>
	</li>
	<li>
		<a href="https://github.com/frappe/frappe" target="_blank">Frappé</a> <small>Web application framework in Python, Javascript & MariaDB</small>
	</li>
	<li>
		<a href="https://github.com/frappe/bench" target="_blank">Bench</a> <small>Scaffolding and deployment utilities for Frappé framework</small>
	</li>
	<li>
		<a href="https://frappe.io/blog/development/deployment-for-everyone" target="_blank">Central</a>
		<small>One click deployment for the Frappé team</small>
	</li>
	<li>
		<a href="http://bl.ocks.org/anandpdoshi/raw/5124686/" target="_blank">Relationships between ERPNext DocTypes</a>
		<small>Chord diagram using d3.js</small>
	</li>
	<li>
		<a href="http://bl.ocks.org/anandpdoshi/raw/5260254/#/worldmap" target="_blank">ERPNext World Presence in 2013</a>
		<small>Using d3.js and GeoJSON data from GADM.org</small>
	</li>
	<li>
		<a href="https://github.com/anandpdoshi/chart-builder" target="_blank">Chart Builder</a>
		<small>Using ChartJS and SlickGrid</small>
	</li>
	<li>
		<a href="http://bl.ocks.org/anandpdoshi/raw/9f1ad2503f9da99b13090eb6502ace45/" target="_blank">Interactive Sine Wave</a>
		<small>Using Paper.js</small>
	</li>
</ul>

#### Links

<ul class="list-unstyled">
	<li>
		<a href="https://github.com/anandpdoshi" target="_blank">Github</a>
	</li>
	<li>
		<a href="https://in.linkedin.com/in/anandpdoshi" target="_blank">LinkedIn</a>
	</li>
	<li>
		<a href="/photography" target="_blank">Photography</a>
	</li>
	<li>
		<a href="https://dl.dropboxusercontent.com/u/29814148/toughspirit-blog-files/resume.pdf" target="_blank">Resumé</a>
	</li>
</ul>

#### Get in touch

<ul class="list-unstyled">
	<li>
		<a href="mailto:hello@apd.is">hello@apd.is</a>
	</li>
	<li>
		<a href="https://twitter.com/anandpdoshi" target="_blank">@anandpdoshi</a>
	</li>
</ul>

<!-- style and script -->
<style>
.content {
	min-height: 85vh;
}

h4 {
	margin-top: 3.4rem;
}

@media(max-width: 767px) {
	.hi {
		font-size: 1.2rem;
	}
}

</style>

<script>
// var colors = [
// 	{ background: '#fff', color: '#444'},
// 	{ background: '#EAF9FF', color: '#444'},
// 	// { background: '#d9d1ba', color: '#1a3657'},
// 	// { background: '#1a3657', color: '#EAF9FF' },
// 	// { background: '#111', color: '#f9f9f9' },
// ];
// var selected = colors[Math.floor(Math.random() * colors.length)];
// document.body.style.background = selected.background;
// document.body.style.color = selected.color;
// document.body.style.fontWeight = selected.fontWeight || 300;

</script>
