---
layout: simple-page
title: Buddha Tooth Temple
permalink: /buddha-tooth-temple/
breadcrumb: Buddha Tooth Temple
---
<script  type="text/javascript" src="https://unpkg.com/nanogallery2@2.4.2/dist/jquery.nanogallery2.min.js"></script>

<!-- nanogallery2 -->
<style>
	@import url("https://unpkg.com/nanogallery2@2.4.2/dist/css/nanogallery2.min.css");
</style>

<div id="nanogallery2">Buddha Tooth Temple</div>

<script>
    jQuery(document).ready(function () {
		jQuery("#nanogallery2").nanogallery2( {
        // ### gallery settings ### 
        thumbnailHeight:  150,
        thumbnailWidth:   150,
        itemsBaseURL:     'https://staging-nlb-mobile-guide.netlify.com/images/merlion/',
                        
        // ### gallery content ### 
        items: [
			{ src: 'merlion-01.jpg', srct: 'merlion-01.jpg', title: 'Merlion 1' },
            { src: 'merlion-02.jpg', srct: 'merlion-02.jpg', title: 'Merlion 2' },
            { src: 'merlion-03.jpg', srct: 'merlion-03.jpg', title: 'Merlion 3' }
			]
        });
    });
</script>