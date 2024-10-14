---
title: Contact
---
<link rel="stylesheet" href="style.css">

You can contact me through [my LinkedIn profile](https://www.linkedin.com/in/streats) or by using the contact form below. 

You can also [open an issue on my GitHub](https://github.com/streats/streats.github.io/issues/new) with feedback or bug reports for this website. 

<form action="https://api.staticforms.xyz/submit" method="post">
<input type="hidden" name="accessKey" value="d6e38e6b-4733-477d-bd58-50d7551925fa">

Name:<br>
<input type="text" name="name"><br><br>
Email: <br>
<input type="text" name="email"><br><br>
Message: <br>
<textarea name="message"></textarea><br><br>

<!-- Redirect to specific url after submission -->
<input type="hidden" name="redirectTo" value="https://streats.github.io">

<!-- Set subject line of received emails -->
<input type="hidden" name="subject" value="Contact form submission from streats.github.io">

<!-- Set sender name as submitted name -->
<input type="hidden" name="replyTo" value="{{name}}">
  
<!-- Specify replyto address as submitted email -->
<input type="hidden" name="replyTo" value="@">

<!-- Spam protection - If data is submitted in this field submission will be ignored -->
<input type="text" name="honeypot" style="display: none;">

<input type="submit" value="Submit" class="button">
</form>
    

