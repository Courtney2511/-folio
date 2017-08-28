---
layout: page
title: Sample Portflio
description:
img:
---

**Assignment**:

Build a portfolio website with HTML and CSS from the provided mockup. Website must be responsive and include images, description and links to projects.

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/1.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/2.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/3.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="img_row">
	<img class="col three" src="{{ site.baseurl }}/img/5.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	This image can also have a caption. It's like magic.
</div>

**Project Details**:

MultiBlog is a basic multi-user blogging site that allows users to create accounts and then share blog posts.  Cookies are used for user authentication.  As an extra in the assignment, I added the ability for users to 'like' each others posts.

**Technologies**:

* HTML
* CSS

View the code on <a href="https://github.com/Courtney2511/portfolio_assignment">Github</a>.

<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/img/6.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/11.jpg" alt="" title="example image"/>
</div>
<div class="col three caption">
	You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


<br/><br/><br/>


The code is simple. Just add a col class to your image, and another class specifying the width: one, two, or three columns wide. Here's the code for the last row of images above:

	<div class="img_row">
	  <img class="col two" src="/img/6.jpg"/>
	  <img class="col one" src="/img/11.jpg"/>
	</div>
