---
layout: content
permalink: /about_us
---

# Who are we?


# What's the purpose of the VT GitHub Organization?


# How can I contact the GitHub Coordinators?

Some general text, for reference.

# **Contact us!**
{:style="text-align: center;"}
---

<form action="https://formspree.io/ttodorov@vt.edu"
    method="POST">
    <input type="hidden" name="_cc" value="mrp26@vt.edu" />
    <b>Name</b> <font size="2.5rem"> (required) </font><br>
    <input class="rounded" type="text" name="name" placeholder="" required><br><br>
    <b>Email</b> <font size="2.5rem"> (required) </font><br>
    <input class="rounded" type="email" name="_replyto" placeholder="" required><br><br>
    <b>Subject</b> <font size="2.5rem"> (required) </font><br>
    <input class="rounded" tpye="subject" name="subject" placeholder="" required><br><br>
    <b>Message</b> <font size="2.5rem"> (required) </font><br>
    <textarea class="rounded" rows="4" cols="40" name="message" placeholder="" required></textarea><br><br>
    <input type="submit" value="Send">
    <input type="hidden" name="_next" value="{{ site.baseurl }}{% link submit_success.md %}" />
</form>
