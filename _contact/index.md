---
layout: page
title: Contact

permalink: /contact/
---



<style>
@import url(https://fonts.googleapis.com/css?family=Lato);
input[type='text'] { font-size: 18px; font-family: "Lato"; }
input[type='email'] { font-size: 18px; font-family: "Lato"; }
textarea[name='message'] { font-size: 14px; font-family: "Lato"; }
input[type='submit'] { font-size: 14px; font-family: "Lato"; }
</style>

<form action="//formspree.io/{{ site.email }}"
      method="POST">
    <input type="text" placeholder="Name" name="name" size="30%"><br>
    <input type="email" placeholder="Email" name="_replyto" size="30%"><br>
    <div>&nbsp;</div>
    <textarea rows="8" cols="63" name="message" placeholder="Message"></textarea><br>
    <input type="hidden" name="_subject" value="New submission!" />
    <input type="hidden" name="_next" value="/contact/thanks" />
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" value="Send">
</form>

<h5 align="right">Powered by <a href="http://formspree.io">Formspree</a>.</h5>
