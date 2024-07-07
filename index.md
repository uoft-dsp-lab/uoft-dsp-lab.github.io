---
---

# University of Toronto Multimedia Laboratory

The Multimedia Laboratory at the University of Toronto, is part of the Communications Group at the Edward S. Rogers Sr. Department of Electrical and Computer Engineering. Our Laboratory has been at the forefront of the signal and image processing field. Specifically, research has been focused in the areas of artificial intelligence, efficient deep learning, biometric systems, secure and privacy enhancing multimedia solutions, nonlinear signal and image processing, multichannel image processing, morphological filters, neural networks and image and video coding.


<!-- {%
  include button.html
  type="docs"
  link="https://greene-lab.gitbook.io/lab-website-template-docs"
%} -->
{%
  include button.html
  type="link"
  text="Professor Konstantinos N. Plataniotis"
  link="https://www.plataniotis.com"
%}

{%
  include button.html
  type="github"
  text="On GitHub"
  link="uoft-dsp-lab"
%}

{%
  include button.html
  type="huggingface"
  text="On HuggingFace"
  link="uoft-dsp-lab"
%}

{% include section.html %}

## Highlights

{% capture text %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. -->

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

<!-- {% capture text %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

{%
  include button.html
  link="projects"
  text="Browse our projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%} -->

{% capture text %}

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. -->

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/cover_photos/LabHomePage.png"
  link="team"
  title="Our Team"
  text=text
%}
