---
layout: post
title:  "resources"
date: 2021-02-07
---

# [Processing](https://processing.org/)

  * [The Coding Train](https://www.youtube.com/user/shiffman)
  * [Learning Processing](http://learningprocessing.com/)
  
# git
  * [Guides](https://guides.github.com/)
  * [Learning Lab](https://lab.github.com/)
  * [hello world](https://guides.github.com/activities/hello-world/)
  * [open source guides](https://github.com/github/opensource.guide)
  * [Complete Markdown Emoji List](https://gist.github.com/rxaviers/7360908)
  * [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
  * [Creating and highlighting code blocks](https://docs.github.com/en/github/writing-on-github/creating-and-highlighting-code-blocks)

# Python

# Ruby

# C

# html/css
  * [Build a simple Meme Generator](https://projects.raspberrypi.org/en/projects/cat-meme-generator)

<details>
 <summary>  finished Code</summary>

 <html><head>
<meta http-equiv="content-type" content="text/html; charset=windows-1252">
<title>Meme Generator</title>
<style type="text/css">
	#message {
		background-color: transparent;
		font-size: 40px;
		font-family: "Impact";
		color: white;
		text-shadow: black 0px 0px 10px;
		width: 600px;
		position: absolute;
		left: 15px;
		top: 480px;
	}

	#image {
		width: 600px;
		border: 3px solid #000000;
	}

</style>

</head>
<body>

<form>
Select a picture <input type="file" id="picture" onchange="update_image()">
<p>
Meme text: <input type="text" id="meme_text" oninput="update_text()" maxlength="70">
</p><p>
</p></form>

<p>

</p><div id="message">&nbsp;</div>
<div id="image"><img src="" width="600" height="500"></div>


<script type="text/javascript">

// Update image onto the screen
function update_image(){
	var img = document.querySelector('img'); // Returns the first img element
	var file = document.querySelector('input[type=file]').files[0]; // Returns the first file element found
	img.src =  window.URL.createObjectURL(file);

}

// Write the text onto the meme
function update_text(){
	document.getElementById("message").innerHTML = document.getElementById("meme_text").value;
}

</script>



</body></html>
</details>

# Markdown
  * [Daring Fireball](https://daringfireball.net/projects/markdown/)
  * [Markdown Reference](https://commonmark.org/help/)

# Jekyll
  [homepage](https://jekyllrb.com/)
  
# CLI / Bash
  * [The Linux Command Line *by William Shotts*](http://linuxcommand.org/tlcl.php)
  
# Linux
  * [Linux Journey](https://linuxjourney.com/)
  * [Linux Handbook](https://linuxhandbook.com/)
  * [Linux Mint Developer's Guide](https://linuxmint-developer-guide.readthedocs.io/en/latest/index.html)
