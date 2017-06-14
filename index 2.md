---
layout: base
title: Anand Doshi
//background: "#EAF9FF"
---

<!-- background: "#EAF9FF" -->

<h3 class="hi">
	Hi.
	I am Anand Doshi.
</h3>

I am an upcoming interaction designer and a graduate student at the [University of Michigan](https://www.si.umich.edu/academics/msi/human-computer-interaction-hci). Previously, I worked at [Frappé](https://frappe.io/about) and we made [ERPNext](https://github.com/frappe/erpnext), one of the best open source ERPs that exists today. Here, I wore many hats: that of system administrator, developer, designer, debugger, mentor and trainer. Over the years, I became passionate about user experience and interaction design; So, I decided to go back to school and learn more about it. 

Just a few months into the program, I have worked on interactions using acoustic, inertial and visual motion tracking, interviewed clients and performed user research based on the principles of contextual inquiry, formally learned the fundamentals of graphic design, and have a general understanding of how human behavior affects user experience. Recently, I have been accepted into the Integrated Product Development  program (IPD), and will be working with a diverse team to produce and market a wearable device. Life is taking an exciting turn!


#### Design

{% assign posts = site.categories['portfolio'] %}
<ul class="list-unstyled">
	{% for i in (0..3) %}
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

#### Blog

{% assign posts = site.categories['blog'] %}
<ul class="list-unstyled">
	{% for i in (0..3) %}
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

#### Links

<ul class="list-unstyled">
	<li>
		<a href="https://github.com/anandpdoshi" target="_blank">Github</a>
	</li>
	<li>
		<a href="https://in.linkedin.com/in/anandpdoshi" target="_blank">LinkedIn</a>
	</li>
	<li>
		<a href="/photography">Photography</a>
	</li>
	<li>
		<a href="/assets/others/toughspirit-blog-files/resume.pdf" target="_blank">Resumé</a>
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

.hi {
	text-align: left;
}


</style>
