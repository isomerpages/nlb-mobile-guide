---
layout: simple-page
permalink: /reader/
breadcrumb: Fuel My Reading Habit
title: Fuel My Reading Habit
---

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
<p>If you love reading, you are in the right place! Here are some tips:</p>
<p> 
</p>

<p>For more information on how to use the Libby app, click <span style="background-color: #00ffff;">here</span>.</p>
<p>For more information on how to use the NLB Mobile app, click <span style="background-color: #00ffff;">here</span>.</p>
<p>To find out how to access eNewspapers and eMagazines on PressReader, click <span style="background-color: #00ffff;">here</span>.</p>
<p><h2>More Tips</h2></p>
<button class="accordion">Any recommendations on what to read next?</button>

<div class="panel">
    <div class="libby">
        <p>Tap on 'Library' in the Libby app, located at the bottom left corner of your screen,  and scroll down to browse book lists by category,  e.g. thrillers or what’s trending. Just tap on the theme you’re in the mood for and let Libby lead you to your next great read!</p></div>
</div>

<button class="accordion">I love reading but I’m too busy!</button>

<div class="panel">
  <div class="libby">
      <p>How about eAudiobooks? You can listen to them while doing chores, driving –even right before bed as part of your wind-down routine. Some of these books are read by famous authors themselves, especially autobiographies such as Becoming by Michelle Obama. To check if the book you want has an audiobook version, simply search for the title. The word “audiobook” will appear underneath your search term if available.</p>
  <p>
      <img src="/images/Reader_eAudiobook_screenshot.jpg" alt="A screenshot showing how to filter search results by eAudiobooks.">
  </p>
<p>If you just want to explore what is available, tap on 'Library' in the Libby app and select 'Available Audiobooks'. If you listen before bedtime, Libby can automatically pause the narration after a specific amount of time set by you. Open the audiobook and tap, hold and drag down the moon icon to set the sleep timer.</p>
<p>Short stories are also a great way to squeeze in some reading. To find them, go to Library -> Explore -> Subjects -> Short Stories. Some of these are also available as eAudiobooks! </p>

</div>
</div>

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
