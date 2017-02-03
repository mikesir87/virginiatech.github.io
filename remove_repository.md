---
layout: content
permalink: /remove_repository
---

## Looking to remove a repository?
{:style="text-align: center;"}
Some blurd about what happens when you remove a repository... blah blah blah


---
<b>Name</b> <font size="2.5rem"> (required) </font><br>
<input class="rounded" type="text" name="name" placeholder="" required><br><br>
<b>Email</b> <font size="2.5rem"> (required) </font><br>
<input class="rounded" type="email" name="_replyto" placeholder="" required><br><br>
<b>Subject</b> <font size="2.5rem"> (required) </font><br>
<input class="rounded" tpye="subject" name="subject" placeholder="" required><br><br>
<b>Message</b> <br>
<textarea class="rounded" rows="4" cols="40" name="message" placeholder=""></textarea><br>
<input type="submit" value="Send">
<input type="hidden" name="_next" value="{{ site.baseurl }}{% link submit_success.md %}" />
