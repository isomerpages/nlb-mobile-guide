---
layout: leftnav-page-content
title: Libby
permalink: /get-started-with/Libby/
breadcrumb: Libby
collection_name: get-started-with
---
![A flowchart describing how to download eBooks and audiobooks with the Libby app.](/images/Libby_Flowchart.png)

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
  font-size: 15px;
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

<h2>Getting Started</h2>
<p></p>
<button class="accordion">What is the difference between NLB Mobile, OverDrive app and Libby?</button>
<div class="panel">
  <p>NLB Mobile, OverDrive and Libby are apps that let you borrow and read NLB’s eBooks/audiobooks. NLB’s eBooks/audiobooks are hosted on third-party platforms such as OverDrive. NLB Mobile is an NLB app designed for access and transactions. It lets you borrow and read eBooks online, but does not have an in-built eBook reader to read a downloaded eBook. Additionally, it lets you access eMagazines / eNewspapers, eLearning courses, and check your library account.

OverDrive lets you borrow and download eBooks/audiobooks from the library. You can use the in-app features to read downloaded eBooks and listen to downloaded audiobooks.

Libby is a new app by OverDrive. It also lets you borrow and download eBooks/ audiobooks, but with a simpler user interface.</p>
</div>

<button class="accordion">Section 2</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">Section 3</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
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

