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
        itemsBaseURL:     'https://nanogallery2.nanostudio.org/samples/',
                        
        // ### gallery content ### 
        items: [
			{ src: 'berlin1.jpg', srct: 'berlin1_t.jpg', title: 'Berlin 1' },
            { src: 'berlin2.jpg', srct: 'berlin2_t.jpg', title: 'Berlin 2' },
            { src: 'berlin3.jpg', srct: 'berlin3_t.jpg', title: 'Berlin 3' }
			]
        });
    });
</script>