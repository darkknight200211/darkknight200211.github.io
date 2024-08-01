---
layout: page
title: Contact
description: Feel free to leave a message and get in touch
permalink: /contact/
nav: true
nav_order: 7
---

<form accept-charset="UTF-8" action="https://formkeep.com/panjwal1111@gmail.com" method="POST">
  <!-- <input type="email" name="email" placeholder="Your Email">
  <input type="text" name="name" placeholder="Your Name">
  <input type="hidden" name="utf8" value="✓">
  <button type="submit">Submit</button> -->
</form>

<div id="formkeep-embed" data-formkeep-url="https://formkeep.com/p/6e4c137f2c1d8d5afe29f5b2f4262daa?embedded=1"></div>

<script type="text/javascript" src="https://pym.nprapps.org/pym.v1.min.js"></script>
<script type="text/javascript" src="https://formkeep-production-herokuapp-com.global.ssl.fastly.net/formkeep-embed.js"></script>

<!-- Get notified when the form is submitted, add your own code below: -->


<script>
const formkeepEmbed = document.querySelector('#formkeep-embed')

formkeepEmbed.addEventListener('formkeep-embed:submitting', _event => {
  console.log('Submitting form...')
})

formkeepEmbed.addEventListener('formkeep-embed:submitted', _event => {
  console.log('Submitted form...')
})
</script>
