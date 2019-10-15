---
layout: post
title: presentations
description: and posters
img: /img/budapest1.jpg
---

Every project has a beautiful feature shocase page. It's easy to include images, in a flexible 3-column grid format. Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so: 

	---
	layout: post
	title: Project
	description: a project with a background image
	img: /img/12.jpg
	---


<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/friends.jpg" alt="" title="example image"/>
	<img class="col two" src="{{ site.baseurl }}/img/family.jpg" alt="" title="example image"/>
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

You can also put regular text between your rows of images. Say you wanted to write a little bit about your project before you posted the rest of the images. You describe how you toiled, sweated, *bled* for your project, and then.... you reveal it's glory in the next row of images.


<div class="img_row">
	<img class="col two" src="{{ site.baseurl }}/img/nyc_bruun_tes.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/nyc_bridge.jpg" alt="" title="example image"/>
</div>

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/italy1.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/italy2.jpg" alt="" title="example image"/>
	<img class="col one" src="{{ site.baseurl }}/img/italy3.jpg" alt="" title="example image"/>
</div>

<div class="img_row">
	<img class="col one" src="{{ site.baseurl }}/img/dutch_sea.jpg" alt="" title="example image"/>
	<img class="col two" src="{{ site.baseurl }}/img/camping.jpg" alt="" title="example image"/>
</div>



<br/><br/><br/>


The code is simple. Just add a col class to your image, and another class specifying the width: one, two, or three columns wide. Here's the code for the last row of images above: 

	<div class="img_row">
	  <img class="col two" src="/img/6.jpg"/>
	  <img class="col one" src="/img/11.jpg"/>
	</div>
