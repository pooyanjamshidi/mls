---
layout: page
title: Projects
permalink: /projects/
---

## Coursework Template

Please use this [template](https://github.com/pooyanjamshidi/mls/blob/master/resources/coursework-template.zip) for submitting your written assignments.


## Topics

The course project is an opportunity to apply what you have learned in class to a problem of your interest. Potential projects must have these two components:

- `Machine Learning` algorithm: Any ML model class including neural networks or any good old-fashioned ML/AI.

- `Computer Systems`: The project should have at least one computer systems component: (i) Platform: Embedded, Realtime, Cloud, IoT, Edge; (ii) Systems issues such as scalability, performance, reliability; (iii) On-device ML: e.g., TinyML, AI on Edge; (iv) Trustworthy AI: Bias, Fairness, Robustness, Privacy, Security, Explainability, Interpretability, Interoperability; (v) Robot Learning, any project that makes robots more intelligent! 

The following categories also fit within the scope, and I highly encourage students to consider such projects: 

* There are lots of resources that you can read, review, and study to find a specific project idea with a clear scope. For example, you can use `blog posts` from engineering teams at high-tech companies: [Uber Engineering](https://eng.uber.com/), [The Netflix Tech Blog](https://medium.com/netflix-techblog), [Spotify Labs](https://labs.spotify.com/), [Meta](https://engineering.fb.com/), and many more.


* Topics related to `AI in Robotics` or `Autonomy in Robotics` are great for this course. You can use simulators such as [Gazebo](https://gazebosim.org/home) or [Bullet](https://pybullet.org/wordpress/) or use cloud services such as [Amazon RoboMaker](https://aws.amazon.com/robomaker/) for your project and do not need to have it on a physical robot, but if you want to do a project with physical robots, you can do it in our robotics lab, come and talk with me. I have several project ideas related to Autonomy and Robotics. We have also a robotics team, called [Gamecock Robotics](http://gamecockrobotics.github.io/). You can define your project to make the robot autonomous. You can also read [blog posts](https://aws.amazon.com/blogs/machine-learning/introducing-amazon-sagemaker-reinforcement-learning-components-for-open-source-kubeflow-pipelines/) to formulate a well-scoped project. 

* Building on top of an `open source ML system` that you can find on GitHub, e.g., you can develop a tracking algorithm and develop a plugin for [DeepStream](https://developer.nvidia.com/deepstream-sdk)

* `AI competitions` are great project ideas for non-CS students, e.g., [EvalAI](https://eval.ai/) hosts many interesting competitions with prizes suitable for students from all backgrounds, e.g., (i) [Open Catalyst Challenge](https://opencatalystproject.org/) for Chemical Engineering students; (ii) [Neural Latents Benchmark](https://neurallatents.github.io/) for Neuroscience students; (iii) [The Robotic Vision Challenges](https://nikosuenderhauf.github.io/roboticvisionchallenges/) for students interested in robotics. 

* `Hackathons`, e.g., [PyTorch Annual Hackathon 2021](https://pytorch2021.devpost.com/), [AWS BugBust](https://aws.amazon.com/bugbust/), [Kaggle](https://www.kaggle.com/competitions)

* `Systematic study of open source ML Systems` via (i) interview study (please make sure you design the interview study correctly before conducting the interviews) and/or (ii) Formulating interesting research questions about building ML systems, for example, contrasting testing practices for ML systems vs. traditional software systems, collecting data from software repositories, and systematically extracting info from these repositories that answers your research questions.

* `TinyML` projects, you can find many ideas on [GitHub](https://github.com/gigwegbe/tinyml-papers-and-projects) and [TinyML community forum](https://discuss.tinymlx.org/c/projects/5)

* And, in general, for any interesting ML systems project ideas, try [GitHub](https://github.com/NirantK/awesome-project-ideas), [Reddit](https://www.reddit.com/r/MachineLearning/search/?q=systems&restrict_sr=1)

If you are unsure whether the project you have defined fits within the scope, please talk with me after class. If you believe that might be helpful for other students, please ask your question on Piazza or during class hours.

## Project Proposal [1 page]

* What is the **problem** that you will be investigating? Why is it interesting? 
* What **reading** will you examine to provide context and background? 
* What **data** will you use? For example, if you are collecting new data, how will you do it? 
* What **method** or algorithm are you proposing? If there are existing implementations, will you use them, and how? How do you plan to improve or modify such implementations? You don't have to have an exact answer at this point, but you should have a general sense of how you will approach the problem you are working on. 
* How will you **evaluate** your results? Qualitatively, what kind of results do you expect (e.g., plots or figures)? Quantitatively, what kind of analysis will you use to evaluate and/or compare your results (e.g., what performance metrics or statistical tests)?

**Submission**: Please submit your proposal as a PDF on the college [dropbox](https://dropbox.cse.sc.edu/). **Only one person on your team should submit**. Please have this person add the rest of your team to the author list.

## Project Milestone [2-3 pages]

Your project milestone report should be between 2-3 pages using the provided template. The following is a suggested structure for your report:

- `Title, Author(s)`
- `Introduction`: This section introduces your problem and the overall plan for approaching your problem
- `Problem statement`: Describe your problem precisely specifying the dataset to be used, expected results, and evaluation
- `Technical Approach`: Describe the methods you intend to apply to solve the given problem
- `Intermediate/Preliminary Results`: State and evaluate your results up to the milestone

**Submission**: Please submit your milestone as a PDF on Gradescope. **Only one person on your team should submit**. Please have this person add the rest of your team to the author list.

## Final Report [6-8 pages]

Each group needs to write a project report (in addition to the IPython notebook, their content could overlap) of at least four pages, not including references. 

The project report should be formatted similarly to a workshop paper and should use the [ICML 2018 style](https://icml.cc/Conferences/2018/StyleAuthorInstructions).
I will post all the final reports online to read about each others' work. If you do not want your write-up to be posted online, please let me know at least a week before the final write-up submission deadline.

The suggested structure:

- `Title, Author(s)`
- `Abstract`: Briefly describe your problem, approach, and key results. 
- `Introduction (10%)`: Describe the problem you are working on, why it's important, and an overview of your results.
- `Related Work (10%)`: Discuss published work related to your project. How is your approach similar or different from others?
- `Data (10%)`: Describe the data you are working with for your project. What type of data is it? Where did it come from? How much data are you working with? Did you have to preprocess, filter, or other special treatments to use this data in your project?
- `Methods (25%)`: Discuss your approach to solving the problems you set up in the introduction. Why is your approach the right thing to do? Did you consider alternative approaches? You should include figures, diagrams, or tables to describe your method.
- `Experiments (40%)`: The exact experiments will vary depending on the project, but you might compare with previously published methods, use visualization techniques to gain insight into how your model works, and discuss the standard failure modes of your choices. You should include graphs, tables, or other figures to illustrate your experimental results.
- `Conclusion (5%)`: Summarize your key results - what have you learned? Suggest ideas for future extensions or new applications of your thoughts.
- `Supplementary Materials` are not counted toward your 6-8 page limit and are submitted as a separate file. 

Your supplementary material might include:
- `Source code`
- `IPython notebook, videos, interactive visualizations, demos, etc...`

Some examples of good project reports:
- [`Sample 1`](http://cs231n.stanford.edu/reports/2017/pdfs/130.pdf)
- [`Sample 2`](http://cs231n.stanford.edu/reports/2017/pdfs/121.pdf)
- [`Sample 3`](http://cs231n.stanford.edu/reports/2017/pdfs/610.pdf)
- [`Sample 4`](http://cs231n.stanford.edu/reports/2017/pdfs/116.pdf)

Project reports - CSCE 790 - Fall 2018:
- [`Project1: Hassan Alamri, Yang Ren, Rui Xin`](https://github.com/pooyanjamshidi/mls/blob/master/reports/2018/pdfs/project1.pdf)
- [`Project3: Joshi Bharat, Harrison Howell, Jianhai Su`](https://github.com/pooyanjamshidi/mls/blob/master/reports/2018/pdfs/project3.pdf)

## Project Presentation (videorecording)
We will use video recording for groups to present and share their project. Each group must submit a 5-minute presentation video for their final project. Students can be as creative as they like for their video presentations. The easiest option is to create a slide deck together as a team and record yourselves presenting the slide deck as a group using zoom. Each student member should speak during the presentation. Also, we prefer if students use a webcam to see you in the video recordings.

The following is a suggested structure for the video presentation. You don't necessarily have to organize your presentation using these sections in this order, but that would likely be a good starting point for most projects.

* **Problem Statement**: Briefly describe the problem your group is tackling. Describe the overall motivation and the input/output of the problem.
* **Technical Challenges**: Briefly describe why the problem is technically challenging.
* **Related Works**: Briefly in what ways previous works have tackled the technical challenges.
* **Your Approach and Results**: Describe your detailed technical approach and innovations. Describe evaluation results (dataset and metric). Emphasize important, interesting, or unexpected results and explain the expected results compared with previously reported results.
* **Broader Impact**: How do you expect the impact of your work to be? What can others learn from it, or how can they apply it to solve their problems? What are the limitations of your work? What are areas for future improvements?


## What and How to Submit Final Materials:
1. **Project Report:** in PDF format using the template above. This PDF file is the only file you need to submit, all other items should be hosted somewhere as described below, and you only put the links into your report.
2. **Code:** put the GitHub or GitLab link in your report. Please make sure the repository is public, and you put all materials, including all code, scripts, tutorials, and everything that one requires to replicate the results in your report.
3. **Data:** Including training dataset, testing dataset, metadata, and more importantly, all experimental data, logs that you have collected during your experiments, and everything that one requires to replicate the results.
4. **Project Presentation:** you can use Keynote or PowerPoint to prepare the slides and convert them to PDF. You can publish your presentation on SlideShare/SpeakerDeck and put the link in your report. If you prefer, you can push the PDF into your git repository.
5. **Video Recording:** You are encouraged to use YouTube to publish your presentation; you then put the link to the video recording in the report.


---------------------------------------

## Topics [2020]

All details about the course project can be found at [Project Athena](https://github.com/csce585-mlsystems/project-athena)


## Topics [2018 and 2019]

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
