---
layout: post
title:  "Mesh Networks mobile app"
date:   2015-04-15 14:19:20 +0200
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

Two month of this spring I dedicated to work at Yandex Tolstoy Camp for a bluetooth messaging mobile application. The main feature was that it can work without 3G or WiFi, using bluetooth only (mesh-networking). My main focus was on the backend merging bluetooth islands trough the backend in Java (Netty).

I like to draw architecture of my projects thinking about three aspects: Functional requirements, quality attributes (scalability, performance, security, etc.) and constraints (business and technical), check out presentation for more details:

<p align="center">
<iframe src="//www.slideshare.net/slideshow/embed_code/key/HURrrFEjMEkzW7" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/chernushenko/solidarity-server-architecture" title="Solidarity - server architecture" target="_blank">Solidarity - server architecture</a> </strong> from <strong><a href="//www.slideshare.net/chernushenko" target="_blank">Yury Chernushenko</a></strong> </div>
</p>
