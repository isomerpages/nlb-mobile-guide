---
layout: simple-page
permalink: /reader/
breadcrumb: Fuel My Reading Habit
title: Fuel My Reading Habit
---
<a href="/images/Reader_highres.png">![An infographic with tips on how to fuel your reading habit without spending a cent.](/images/Reader.png)</a>
<a href="/images/Reader_highres.png">Click to enlarge</a>

body {
  font-family: "Open Sans", sans-serif;
  line-height: 1.25;
}

table {
  border: 1px solid #ccc;
  border-collapse: collapse;
  margin: 0;
  padding: 0;
  width: 100%;
  table-layout: fixed;
}

table caption {
  font-size: 1.5em;
  margin: .5em 0 .75em;
}

table tr {
  background-color: #f8f8f8;
  border: 1px solid #ddd;
  padding: .35em;
}

table th,
table td {
  padding: .625em;
  text-align: center;
}

table th {
  font-size: .85em;
  letter-spacing: .1em;
  text-transform: uppercase;
}

@media screen and (max-width: 600px) {
  table {
    border: 0;
  }

  table caption {
    font-size: 1.3em;
  }

  table thead {
    border: none;
    clip: rect(0 0 0 0);
    height: 1px;
    margin: -1px;
    overflow: hidden;
    padding: 0;
    position: absolute;
    width: 1px;
  }

  table tr {
    border-bottom: 3px solid #ddd;
    display: block;
    margin-bottom: .625em;
  }

  table td {
    border-bottom: 1px solid #ddd;
    display: block;
    font-size: .8em;
    text-align: right;
  }

  table td::before {
    /*
    * aria-label has no advantage, it won't be read inside a table
    content: attr(aria-label);
    */
    content: attr(data-label);
    float: left;
    font-weight: bold;
    text-transform: uppercase;
  }

  table td:last-child {
    border-bottom: 0;
  }
}

<p>Find out more about the <a href="/get-started-with/nlb-mobile/">NLB Mobile app</a>.</p>
<p>Find out more about the <a href="/get-started-with/Libby/">Libby app</a>.</p>
<p>Find out more about <a href="/get-started-with/PressReader/">how to access eNewspapers and eMagazines on PressReader</a>.</p>
<p><h2>More Tips</h2></p>
<div class="acc-kontainer">          
	<div>
		<input type="radio" name="acc" id="acc1" checked>
		<label for="acc1"><i></i> Any recommendations on what to read next?</label>
		<div class="acc-body">
			<p>Tap on 'Library' in the Libby app, located at the bottom left corner of your screen,  and scroll down to browse book lists by category,  e.g. thrillers or what’s trending. Just tap on the theme you’re in the mood for and let Libby lead you to your next great read!</p>
		</div>
	</div>
    <div>
        <input type="radio" name="acc" id="acc2">
        <label for="acc2"><i></i> I love reading but I’m too busy!</label>
        <div class="acc-body">
			<p>How about eAudiobooks? You can listen to them while doing chores, driving –even right before bed as part of your wind-down routine. Some of these books are read by famous authors themselves, especially autobiographies such as Becoming by Michelle Obama. To check if the book you want has an audiobook version, simply search for the title. The word “audiobook” will appear underneath your search term if available.</p>
			<br>
			<img src="/images/Reader_screenshot_audiobook_search_Becoming.jpg" alt="A screenshot showing how to filter search results by eAudiobooks.">
			<p>If you just want to explore what is available, tap on 'Library' in the Libby app and select 'Available Audiobooks'. If you listen before bedtime, Libby can automatically pause the narration after a specific amount of time set by you. Open the audiobook and tap, hold and drag down the moon icon to set the sleep timer.</p>
			<p>Short stories are also a great way to squeeze in some reading. To find them, go to Library -> Explore -> Subjects -> Short Stories. Some of these are also available as eAudiobooks!</p>
		</div>
	</div>
</div>

