---
layout: simple-page
permalink: /parent/
breadcrumb: Bond through Reading and Learning
title: Bond through Reading and Learning
---
<html>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion1 {
  background-color: #f8cac6;
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
.accordion {
  background-color: #E9E1F5;
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

.active, .accordion1:hover {
  background-color: #ccc;
}

.accordion1:after {
  content: '\002B';
  color: #777;
  font-weight: bold;
  float: right;
  margin-left: 5px;
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

<p>There are many ways to bond with your loved ones through reading and learning! The infographic below is a great place to start.</p>
<p>For more information on how to use the NLB Mobile app, click <span style="background-color: #00ffff;">here</span>.</p>
<p>For more information on how to use the Libby app, click <span style="background-color: #00ffff;">here</span>.</p>
<h2>More Tips</h2>
<button class="accordion">It’s great that I can sign my child up to be an NLB member online! How do I do that?</button>

<div class="panel">
  <div class="libby">
    <p>You can sign your child up <a href="https://account.nlb.gov.sg">online</a> using your SingPass if:</p>
<ul>
<li>Your child is a Singaporean or Permanent Resident, and</li>
<li>Your child is born in Singapore</li>
</ul>
<p>Do note that:</p>
<ul>
<li>If your child is a PR and a student at a MOE school, he/she is eligible for a waiver on the one-time registration fee. To receive the waiver, sign up for library membership at the libraries instead of online.
<ul>
<li>If you have more than one child, you can choose to register just one child or all your children at the same time.</li>
</ul>
</li>
</ul></div>

</div>

<button class="accordion1">What do I need to sign up for library membership online?</button>

<div class="panel">
    <div class="libby">
  <p>You will need a:</p>
<ul>
<li>SingPass login ID and password</li>
<li>[For PRs] Debit/credit card to pay the one-time registration fee of $10.50</li>
      </ul></div>
</div>

<button class="accordion">eBooks with narration sounds interesting. How do I search for these books?</button>

<div class="panel">
  <div class="libby">
  <p>In the Libby app, tap on Library -> Explore -> Guide: Kids and scroll down until you see 'I Can Read! Series Read-Alongs' and 'Read-Alongs'.</p></div>
</div>

<button class="accordion1">I noticed that you offer a few types of interactive eBooks. What is the difference between the eBooks with narration in Libby (“Read-alongs”) and the animated picture books in Tumblebook Library?</button>

<div class="panel">
  <div class="libby">
      <p>Both types of interactive eBooks feature professionally-recorded narration that play along while you read. The animated picture books in Tumblebook Library are fully-animated videos whilst the 'Read-alongs' in Libby are more like eBooks with the words highlighted as they are read.</p>
      <p>Find out more about Tumblebook Library <a href="https://www.tumblebooklibrary.com/Help.aspx">here</a>.</p>
<p>Find out more about Libby&rsquo;s 'Read-alongs' <a href="https://help.overdrive.com/en-us/1152.htm#thundercontent">here</a>.</p>
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

var acc = document.getElementsByClassName("accordion1");
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




