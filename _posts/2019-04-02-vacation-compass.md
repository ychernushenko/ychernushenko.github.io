---
layout: post
title:  "Vacation compass"
date:   2019-02-04 19:19:20 +0200
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

<div class="text-full-width">
    <p>Idea is to show possible vacation destinations based on the temperature data from previous years. Maps were generated based on the <a href="http://www.worldclim.org/">WorldClim</a> dataset using <a href="https://code.earthengine.google.com/">EarthEngine</a>. </p>
</div>


<div class="text-col text-col-1" style="text-align:left;">
Vacation compass interface:
<img src="/assets/2019-04-02-1.jpg">  

