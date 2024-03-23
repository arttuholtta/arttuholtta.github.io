---
title: About me
layout: landing
description: ''
image: 
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<p>My name is Arttu Hölttä and I'm <span id="age"></span> years old.</p>
		<p>I'm currently studying Automation and Computer Sciences at the University of Vaasa.</p>
	</div>
</section>

<script>
  // Get the birth date
  var birthDate = new Date("2000-04-17");

  // Calculate the age
  var ageDifMs = Date.now() - birthDate.getTime();
  var ageDate = new Date(ageDifMs); // miliseconds from epoch
  var age = Math.abs(ageDate.getUTCFullYear() - 1970);

  // Display the age
  document.getElementById("age").innerHTML = age;
</script>