---
layout: page
title: Lectures
permalink: /lectures/
---

<!-- <ul id="archive">


{% for gallery in site.data.lectures %}
  {% if lectures.id == page.galleryid %}
    <h1>{{ lectures.description }}</h1>
    {% for image in sortedimages %}
      <li class="archiveposturl">
        <span><a href="{{ site.url }}/graphs/{{ image.file }}">{{image.title }}</a></span><br>
<span class = "postlower">{{ image.caption }}<br />
<strong>Tags:</strong> {{ image.tags }}</span>
      </li>
    {% endfor %}
  {% endif %}
{% endfor %}

</ul> -->


<ul id="archive">
{% for lectures in site.data.lectures %}
      <li class="archiveposturl">
        <span><a href="{{ site.url }}/{{ lectures.dirname }}/{{ lectures.filename }}.pdf">{{ lectures.title }}</a></span><br>
<span class = "postlower">
<strong>tl;dr:</strong> {{ lectures.tldr }}</span>
<strong style="font-size:100%; font-family: 'Titillium Web', sans-serif; float:right">
	<a href="{{ site.githublink}}/tree/master/{{ lectures.dirname }}"><i class="fab fa-github"></i></a>&nbsp;&nbsp;
<a href="{{ site.githublink}}/blob/master/{{ lectures.dirname }}/{{ lectures.filename }}.pdf"><i class="fas fa-file-pdf"></i></a>
</strong> 
      </li>
{% endfor %}
</ul>

<!-- 2018 details -->
<!-- There will be **no classes** on the following days (I will announce assignments and homeworks in the blackboard system): 
- Oct 18 (Fall break)
- Nov. 6 (Election day)
- Nov. 8 (I will be at [ESEC/FSE'18](https://2018.fseconference.org/home))
- Nov. 22 (Thanksgiving)
- Nov. 29 (I will be at Machine Learning for DevOps [Summit](https://www.re-work.co/events/machine-learning-for-devops-summit-2018)) -->

**Timeline** for your course projects:
- Project Proposal: September 12
- Project Milestone: October 17
- Posters: November 28 
- Final Report: December 3