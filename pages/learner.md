---
layout: simple-page
permalink: /learner/
breadcrumb: Learn
title: Learn
---

![An infographic describing four ways to learn anytime, anywhere.](/images/Learner.png)
<a href="/images/Learner.png">Click to enlarge</a>

<html>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 20px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #ccc;
}

.accordion:after {
  content: '\002B';
  color: #777;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2212";
}

.panel {
  padding: 0 18px;
  background-color: white;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
}
</style>
</head>

<body>

<p>We offer different ways for you to learn in your own time, whether you want to develop skills, get that promotion, and/or pursue your passions. The infographic below is your starter kit:</p>
<p>For more information on how to use the NLB Mobile app, click <span style="background-color: #00ffff;">here</span>.</p>
<p>To find out how to access eNewspapers and eMagazines on PressReader, click <span style="background-color: #00ffff;">here</span>.</p>
<p>For more information on how to use the Libby app, click <span style="background-color: #00ffff;">here</span>.</p>
<h3>I want to learn but I can't seem to find the time to do it! Do you have tips for me?</h3>
       <p>We recommend eAudiobooks as they allow you to multitask. You can learn something just by listening to eAudiobooks anytime, anywhere, whether you're stuck in traffic or doing chores. Just search for a subject you wish to explore and tap on 'audiobooks' underneath the search term to see what is available.</p>
        <p><img src="/images/Libby_screenshot_audiobooksearch.jpg" alt="A screenshot showing how to filter search results by eAudiobooks.">        
        </p>

<script>
var acc = document.getElementsByClassName("accordion");
var i;
for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.maxHeight){
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
  });
}
</script>
