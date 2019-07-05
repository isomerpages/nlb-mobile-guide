---
layout: simple-page
title: Buddha Tooth Temple
permalink: /buddha-tooth-temple/
breadcrumb: Buddha Tooth Temple
---

<style>
.zoomwall {
	font-size: 0;
	overflow: hidden;	
	float: left;
	width: 25%;
	padding: 10px;
}

.zoomwall img {
	height: 15vw;
	opacity: 1;
	vertical-align: top;
	
	transform-origin: 0% 0%;
	transition-property: transform, opacity;
	transition-duration: 0.3s;
	transition-timing-function: ease-out;

	-webkit-transform-origin: 0% 0%;
	-webkit-transition-property: transform, opacity;
	-webkit-transition-duration: 0.3s;
	-webkit-transition-timing-function: ease-out;
}

.zoomwall.lightbox img {
	transition-timing-function: ease-in;
	-webkit-transition-timing-function: ease-in;
}

.zoomwall.lightbox img {
	opacity: 0.3;
}

.zoomwall.lightbox img.active {
	opacity: 1;
}
</style>

<script type="text/javascript" src="/zoomwall/zoomwall.js"></script>

<div id="gallery" class="zoomwall">
	<img src="/images/merlion/merlion-01.jpg" data-highres="/images/merlion/merlion-01.jpg" style="width:100%" />
    <img src="/images/merlion/merlion-02.jpg" data-highres="/images/merlion/merlion-02.jpg" style="width:100%" />
</div>

<script>
	window.onload = function() {
		zoomwall.create(document.getElementById('gallery'));
	};
</script>