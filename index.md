---
title: Home
---

# Microbial Genomics in Liverpool

This website gives you an overview of the team of Microbial Genomics in Liverpool, which was born in 2019 when Eva joined LSTM in her first independent position after 10 years of post-doccing and travelling the planet. 

We are very grateful to the [greene lab](https://www.greenelab.com/) for providing this easy-to-use template [Lab Website Template](https://github.com/greenelab/lab-website-template), which forms the basis for our website and made our lives a lot easier!

{%
  include link.html
  type="github"
  icon=""
  text="See the template on GitHub"
  link="greenelab/lab-website-template"
  style="button"
%}
{%
  include link.html
  type="docs"
  icon=""
  text="See the documentation"
  link="https://github.com/greenelab/lab-website-template/wiki"
  style="button"
%}
{:.center}

{% include section.html full=true %}

{% include banner.html image="images/Malawi_hike.jpg" %}

{% include section.html %}

# Highlights

{% capture text %}
Our research focuses on bacterial interactions with their hosts, considering both pathogens and symbionts across a range of projects anchored in clinical microbiology and in vector biology.

{%
  include link.html
  link="research"
  text="See what we've published"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/canvas.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}
As we are a computational lab, we try to make any tools we produce publicly available and easy-to-use. Please take a look and let us know what experiences you have!

{%
  include link.html
  link="tools"
  text="Browse our tools"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/resource.png"
  link="resources"
  title="Our Resources"
  flip=true
  text=text
%}

{% capture text %}
We are a friendly and enthusiastic group of people, if you want to know a bit more about who is currently part of our team, this is us!

{%
  include link.html
  link="team"
  text="Meet our team"
  icon="fas fa-arrow-right"
  flip=true
%}
{:.center}
{% endcapture %}

{%
  include feature.html
  image="images/Dik-Dik.jpeg"
  link="team"
  title="Our Team"
  text=text
%}


