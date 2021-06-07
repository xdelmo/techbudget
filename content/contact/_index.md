---
title: "Contact"
bg_image: "images/2020-landscape-2.png"
# meta description
description: "This is meta description"
# save as draft
draft: false
---

This is a page with some basic contact information, such as an address and phone number. You might also try a plugin to add a contact form.

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>

 
  <p>
    <label>Your Role: <select name="role[]" multiple>
      <option value="leader">Leader</option>
      <option value="follower">Follower</option>
    </select></label>
  </p>

  <p>
 
  
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
