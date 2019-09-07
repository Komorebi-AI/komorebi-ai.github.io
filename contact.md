---
layout: page
title: Contact
# subtitle: Data Scientist and PhD Student
---



<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdi62jROrimTz7VHFQvCn8LQkxtLCFDrWrhidy4zE0YzhQwIA/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
  Name:<br>
  <input type="text" name="entry.1774498490" id="entry.1774498490"><br>
  Email:<br>
  <input type="text" name="entry.90651633" id="entry.90651633"><br>
  Message:<br>
  <input type="text" name="entry.169648525" id="entry.169648525">
  <input type="submit" value="Submit">
</form>

<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>

<script src="js/jquery-3.2.1.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed. We will get in touch soon!');
  });
</script>