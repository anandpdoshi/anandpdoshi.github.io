---
layout: post
title: Relationships between DocTypes in ERPNext
excerpt: The visualization shows relationship between 50 DocTypes selected based on the frequency of occurrence of its link
xpost: '<a href="https://frappe.io/blog/development/relationships-between-doctypes-in-erpnext" target="_blank">Frappé Blog</a>'
src: /assets/images/201X/relationships-between-doctypes.png
---


ERPNext is a highly complex product having more than 200 inter-connected tables (DocTypes). The visualization below shows relationship between 50 DocTypes selected based on the frequency of occurrence of its link. Click on the image below to interact with the visualization. If you hover the mouse on a particular DocType's arc (box on circle's rim), you will be able to view its relationships in isolation.

<a href="https://bl.ocks.org/anandpdoshi/raw/5124686/" target="_blank" class="no-underline">
	<img src="/assets/images/201X/relationships-between-doctypes.png" alt="Click on this image to interact">
</a>

Curious on how this was created? <a href="https://gist.github.com/anandpdoshi/5124686#file-erpnext_links-js" target="_blank">Check out its source</a>. The code has instructive comments.

This chord diagram was created using <a href="http://d3js.org" target="_blank">d3.js</a>

