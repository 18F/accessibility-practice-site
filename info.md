---
layout: page
title: Newsletter
permalink: /newsletter/
---

<img src="{{ "/images/newspaper.gif" | prepend: site.baseurl | prepend: site.url }}" style="height: 200px"/> 

Sign up for the news letter to get more information about accessibility every month!

<form>
  <div>
    <label>
      First Name
      <input type='text' />
    </label>
  </div>
  <div>
    <label for='lname'>
      Last Name
      <input type='text' id='lname'/>
    </label>
  </div>
  <div>
    Email Address
    <input type='text' aria-label="email" />
  </div>
  <button type="submit">Sign up</button>
</form>
