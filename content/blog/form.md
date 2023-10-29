---
title: My Form.
description: This is a form made in HTML.
date: 2023-10-14
tags:
  - number 2
---
<style>
  message {
    width: 200px;
    height: 60px;
  }
  label {
  font-family:Helvetica;
  color: primary;
  }
</style>
<form action='#'>
    <label for="firstname">First Name *</label>
    <input type="text" id="firstname" name="firstname" required> <br>
    <label for='surname'>Surname *</label> 
    <input type='text' id='surname' name='surname' required> <br>
    <label for="email">Email Address *</label>
    <input type="email" id="email" name="email" required> <br>
    <label for='message'>Please type your message here *</label>
    <input type='text' id='message' name='message' required> <br>
    <input type='submit' value='Submit'>
</form>