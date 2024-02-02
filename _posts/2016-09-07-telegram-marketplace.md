---
layout: post
title:  "Telegram marketplace bot in GoLang"
date:   2016-09-07 14:19:20 +0200
categories: software
---

<!-- Yandex.Metrika counter -->
<script type="text/javascript">
    (function (d, w, c) {
        (w[c] = w[c] || []).push(function() {
            try {
                w.yaCounter39542345 = new Ya.Metrika({
                    id:39542345,
                    clickmap:true,
                    trackLinks:true,
                    accurateTrackBounce:true
                });
            } catch(e) { }
        });

        var n = d.getElementsByTagName("script")[0],
            s = d.createElement("script"),
            f = function () { n.parentNode.insertBefore(s, n); };
        s.type = "text/javascript";
        s.async = true;
        s.src = "https://mc.yandex.ru/metrika/watch.js";

        if (w.opera == "[object Opera]") {
            d.addEventListener("DOMContentLoaded", f, false);
        } else { f(); }
    })(document, window, "yandex_metrika_callbacks");
</script>
<noscript><div><img src="https://mc.yandex.ru/watch/39542345" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
<!-- /Yandex.Metrika counter -->

This is a demo for the chat bot that allow to sell and buy things in messenger. Chatbot is written in golang with decoupling between admin, payment and client facing modules.  

<br>

<div class="text-col text-col-1">
  <div style="text-align:left;"><img src="/assets/2016-09-07-demo.gif"></div>
</div>

<div class="text-col text-col-2">
  <b>Features</b>:

  <ul>
    <li> Easy content publishing for sellers </li>
    <li> Automation of intent extraction (wit.ai, api.ai) </li>
    <li> Payments processing </li>
    <li> Recurrent orders </li>
    <li> Location based search </li>
    <li> Integration with customer support and analytics backend </li>
  </ul>

  Check out the video <a href="https://youtu.be/DSVH7_8Dewc">here</a>.  
</div>
