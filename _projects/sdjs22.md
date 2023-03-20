---
layout: page
title: The State of Data Journalism 2022 Survey
description: a project for the European Journalism Centre
img: assets/img/skill_shorter.gif
---

For the second year in a row, I have been in charge of a global survey aimed at the data journalism industry, designed and delivered for the <a href="https://ejc.net/">European Journalism Centre</a>’s <a href="https://datajournalism.com/">DataJournalism.com</a>. The project constitutes the largest survey of data journalists worldwide, and this year the survey's second edition saw over 1800 people participating. 

&nbsp; 

<h2>In the media</h2>
-   <a href="https://ejc.net/news/explore-the-results-of-our-2022-state-of-data-journalism-survey">European Journalism Centre's announcement</a>
-   <a href="https://www.journalism.co.uk/news/pandemic-and-russia-ukraine-war-have-demonstrated-the-value-of-data-journalism/s2/a1011357/">Journalism.co.uk article</a>
-   <a href="https://twitter.com/smfrogers/status/1634253611277639680">Twitter thread by Simon Rogers</a>
-   <a href="https://www.journalismfestival.com/programme/2023/data-journalism-skills-tools-and-trends">Dedicated panel at the International Journalism Festival 2023</a>


&nbsp; 
<h2>Tasks</h2>

In the project, tasks included:
-   create the survey and spread it
-   analyse the results
-   visualise the results
-   create <a href="https://datajournalism.com/survey/2022/">a website</a> where to present the visual results
-   write textual content to accompany the visuals
-   <a href= "https://github.com/ejcnet/stateofdatajournalism2022">release an open version of the dataset</a>

&nbsp; 

<h2>Presenting the results</h2>
<br>
The results are contained in a nested website, where visualisations are grouped by survey topic (e.g., demographics, employment, challenges) and stored in separate pages. This choice was made to allow the visualisations to load quickly, and to prevent users from feeling as if they were drowning in a huge amount of material (the survey was quite long as it had 63 questions, and there are hundreds of resulting visualisations). 

<br>

From the homepage, one can get a sense of which topic exists and visit the results specific to that. If they scroll down, instead, they can read our selection of the key takeaways, read a methodology and survey metadata, or a mission statement.

&nbsp; 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/homepage.gif" title="homepage" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The homepage.
</div>

&nbsp; 

Each of the results pages presents its sub-topics (oftentimes they match a survey question) through a series of buttons. The buttons can be clicked to head straight to the sub-topic of interest, or else one can scroll down the page to see the results in full. 

&nbsp; 

<div class="row">
    <div class="col-sm mt-3 mt-md-4">
        {% include figure.html path="assets/img/result_page.gif" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The result page relating to questions about the Covid-19 pandemic and data journalism.
</div>

&nbsp; 

As this was the second time I worked on the project, I strived to improve last year's work by making a few small but impactful tweaks. Among the changes, I repositioned the axes, made the color palette lighter, introduced automated textual popups, increased the interactivity of the charts, introduced new visualisations.

&nbsp; 

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2022_skill.gif" title="2022 visualisation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/2021_skill.gif" title="2021 visualisation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A comparison of some changes implemented between 2022 (left) and 2021 (right).
</div>

&nbsp; 

<h3>Color palette</h3>
<br>
I felt the purple was too intense, and changed it to a colder and lighter shade (see below). I think it overall makes everything much lighter on the eye and takes away weight from the page. I also introduced a new sequential and a new discrete color palette

<br>
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/colorpalette.jpg" title="color palette" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
    </div>
</div>



&nbsp; 

<h3>Automated custom popups</h3>
<br>
This year most visualisations feature a “textual” popup. I felt it better explained the data points. I am really happy with this feature, I had to “code” it in a custom way for each graph.

<br>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-4">
        {% include figure.html path="assets/img/popups.jpg" title="custom popups" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
    </div>
</div>

&nbsp; 

<h3>Higher interactivity</h3>
<br>
I have added new control features to make the plots more interactive. Last year I restrained from doing this as I did not want to overload the user, but this time I felt I wanted to simplify the visuals, and make them more dynamic. After all, I want users to be able to play with the data, and avoiding confusing them.
<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/interactivity.gif" title="custom popups" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

&nbsp; 

<h3>New visualisations</h3>
<br>
Last year I relied heavily on barchart. They felt, often, like an appropriate choice of chart for the data. I though felt the pages became a bit boring, that there was little visual variation. This year, being faster at processing the data, I had a little time over to a) explore new intersections between variables, b) explore new visuals. I introduced scatterplots, quadrant plots, areacharts, that overall vary our outputs and better suit the data. 

<br>
<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
         {% include figure.html path="assets/img/new_visuals.gif" title="new visuals" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
         {% include figure.html path="assets/img/access_local.gif" title="new visuals 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    A comparison of some changes implemented between 2022 (left) and 2021 (right).
</div>

<br>
<h3>Grids and aspect ratio</h3>
<br>
It was nearly the last thing on my mind, but potentially the one that had the highest impact in terms of improvements: aspect ratio and gridlines. I reduced the number of grids, and squished the graphs a bit.

<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/comparison.jpg" title="new visuals 2" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
