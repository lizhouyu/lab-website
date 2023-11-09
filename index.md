---
---

# Yu Lab


Welcome to Yu lab at NC State University, where innovation knows no bounds! We are a dynamic team delving into the realms of optimization, application, and security of morden network systems. Nestled at the forefront of technology, our expertise extends seamlessly into the realms of Edge Computing, Distributed Graph Learning, Wireless Network and Security, Quantum Network and Computing, and the fascinating world of AI Computing Systems and Applications such as Autonomous Driving. 

{% include section.html %}

# News
<ul>
   {% for news_item in site.posts limit:5 %}
       <li>[{{news_item.time}}] {{ news_item.title }}</li>
   {% endfor %}
</ul>
{%
  include button.html
  link="news"
  text="More news"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

## Highlights

{% capture text %}

We leverage traditional and learning-based optimization methods to crafting high-performance, robust, and user-friendly systems. From the intricacies of smart homes to the vast landscapes of intelligent cities, and from trending Internet of Things to emerging Quantum and Satellite Networks, our focus extends beyond the conventional, exploring the uncharted territories that lie between and beyond.

{%
  include button.html
  link="publications"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/centennial_building.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Our projects cover multiple areas including Internet-of-Things, Edge Computing, Microservices, Distributed Machine Learning, Quantum Networks, and Blockchain.

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
  image="images/ncsu_banner.jpg"
  link="projects"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Our team is a melting pot of intellect, with members ranging from PhD and Master's students to enthusiastic undergraduates and bright high school students.

{%
  include button.html
  link="people"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/team.jpg"
  link="team"
  title="Our Team"
  text=text
%}
