---
layout: page
title: Projects
permalink: /projects/
---



<ul id="archive">
{% for projects in site.data.projects %}
      <li class="archiveposturl">
        <span><a href="{{ site.url }}/{{ projects.dirname }}/{{ projects.filename }}.pdf">{{ projects.title }}</a></span><br>
<span class = "postlower">
<strong>tl;dr:</strong> {{ projects.tldr }}</span>
<strong style="font-size:100%; font-family: 'Titillium Web', sans-serif; float:right">
	<a href="{{ site.githublink}}/tree/master/{{ projects.dirname }}"><i class="fab fa-github"></i></a>&nbsp;&nbsp;
<a href="{{ site.githublink}}/blob/master/{{ projects.dirname }}/{{ projects.filename }}.pdf"><i class="fas fa-file-pdf"></i></a>
</strong> 
      </li>
{% endfor %}
</ul>