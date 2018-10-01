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


## Final Report

Each group needs to write a project report (in addition to the IPython notebook, their content could overlap) of at least four-pages, not including references. A one-page abstract for the report is due on the date you will present the progress, **October 23**. The final project report is due on **December 11**.


## Guideline

The project report should be formatted similarly to a workshop paper, and should use the [ICML 2018 style](https://icml.cc/Conferences/2018/StyleAuthorInstructions).
I will post all the final reports online so that you can read about each others' work. If you do not want your writeup to be posted online, then please let me know at least a week in advance of the final writeup submission deadline.

The suggested structure:

- `Title, Author(s)`
- `Abstract`: Briefly describe your problem, approach, and key results. 
- `Introduction (10%)`: Describe the problem you are working on, why it's important, and an overview of your results.
- `Related Work (10%)`: Discuss published work that relates to your project. How is your approach similar or different from others?
- `Data (10%)`: Describe the data you are working with for your project. What type of data is it? Where did it come from? How much data are you working with? Did you have to do any preprocessing, filtering, or other special treatment to use this data in your project?
- `Methods (25%)`: Discuss your approach for solving the problems that you set up in the introduction. Why is your approach the right thing to do? Did you consider alternative approaches? You should include figures, diagrams, or tables to describe your method.
- `Experiments (40%)`: The exact experiments will vary depending on the project, but you might compare with previously published methods, use visualization techniques to gain insight into how your model works, discuss common failure modes of your choices. You should include graphs, tables, or other figures to illustrate your experimental results.
- `Conclusion (5%)`: Summarize your key results - what have you learned? Suggest ideas for future extensions or new applications of your ideas.
- `Supplementary Material`, not counted toward your 6-8 page limit and submitted as a separate file. 

Your supplementary material might include:
- `Source code`
- `IPython notebook, videos, interactive visualizations, demos, etc`.

Some examples of good project reports:
- [`Sample 1`](http://cs231n.stanford.edu/reports/2017/pdfs/130.pdf)
- [`Sample 2`](http://cs231n.stanford.edu/reports/2017/pdfs/121.pdf)
- [`Sample 3`](http://cs231n.stanford.edu/reports/2017/pdfs/610.pdf)
- [`Sample 4`](http://cs231n.stanford.edu/reports/2017/pdfs/116.pdf)