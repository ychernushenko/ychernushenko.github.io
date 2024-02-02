---
layout: post
title:  "Autonomous cars competition"
date:   2015-12-15 14:19:20 +0200
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

There was an <a href="http://russianaicup.ru/">AI competition</a> this December. The task was to program autonomous racing cars in the simulator, so your car would come first in racing. I went through the first round but stuck later. My solution was developed on Python and was a bit slow, my people were much more efficient in C++, but I assume they also had a better strategy. While doing this task I skimmed through pretty advanced <a href="https://www.udacity.com/course/artificial-intelligence-for-robotics--cs373">course on Udacity</a> about autonomous cars and applied A* algorithm in my solution.  

Here you can see my algorithm in action (my nickname is Rumbo):
<p align="center"><iframe width="700" height="525" src="https://www.youtube.com/embed/rXnBztmnWl8" frameborder="0" allowfullscreen></iframe></p>
