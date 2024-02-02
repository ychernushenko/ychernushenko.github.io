---
layout: post
title:  "Chat bot for municipality"
date:   2016-04-01 14:19:20 +0200
categories: software
---

Bots are really cool for some things. This case was for the small city municipality in Russia, bot was working for Telegram and had these features:  
- Schedule of the bus (most used feature)  
- Announcements from the municipality (it was before channels in Telegram)  
- Facilities open hours and contact details
- Contact with an concierge (integration with Zendesk ticketing)  

<div class="text-col text-col-1" style="text-align:left;">
    Telegram user's interface:
    <img src="/assets/2016-04-01-interface.jpg">  

    <p>Back end was done on Python (Flask) and information was stored at Facebook Parse. Interface was buttons based.</p>
</div>

<div class="text-col text-col-2" style="text-align:left;">
    Operator's web interface:

    <img src="/assets/2016-04-01-operator.jpg">    

    <p>Also operator on in the back of this concierge service had and interface to change standard replies and broadcast messages to subscribers.</p>
</div>

<div class="text-full-width">
  Users also might use text commands like "/bus". And ask questions in free form.

  Interesting extension would be integration with geolocation for tracking buses and payments integration.  

  One of the biggest benefit that came out of these project where reduction of concierge service with standard questions that users where easily able to find by themselves now.  
</div>
