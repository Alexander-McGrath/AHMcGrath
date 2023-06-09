---
---

# Alexander-McGrath's Website

Marine experimental ecologist with an interest in host-microbe systems.

{% include section.html %}

## Highlights

{% capture text %}

Leveraging ecological theory wtihin holobiont systems to determine cause-effect relationships within a changing environment

{%
  include button.html
  link="Research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/HB.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

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
%}

{% capture text %}



{%
  include button.html
  link="team"
  text="About"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/Headshot.jpg"
  link="team"
  title="About me"
  text=text
%}
