---
layout: post
title:  "Pagemarks - text summarization"
date:   2017-08-01 14:19:20 +0200
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
    <p>This project is focused on producing extractive summarization for the web pages. This work is inspired by Fast Forward Labs <a target="_blank" href="http://blog.fastforwardlabs.com/2016/04/11/new-tools-to-summarize-text.html">article</a> and one of the <a target="_blank" href="http://micha.codes/2017-qcon-deeplearning/#1">workshops</a> they gave.</p>
    <p>Summarization is a hard problem, but use cases could be very helpful in everyday life.</p>
    <p align="center"><iframe width="700" height="525" src="https://www.youtube.com/embed/-GHniIbwOvw" frameborder="0" allowfullscreen></iframe></p>
</div>

<br>

<div class="text-col text-col-1">
  <div style="text-align:left;"><img src="/assets/2017-08-01-1.png"></div>
  <div style="text-align:left;"><img src="/assets/2017-08-01-2.png"></div>
  <div style="text-align:left;"><img src="/assets/2017-08-01-3.png"></div>
</div>

<div class="text-col text-col-2">
  <b>Approach</b>:

  <ol>
    <li> Train the model on curated dataset of summaries (I used <a target="_blank" href="http://thebrowser.com">The Browser</a>) </li>
    <li> Scrape the page </li>
    <li> Encode sentences with <a target="_blank" href="https://github.com/ryankiros/skip-thoughts">Skip-Thought Vectors</a> </li>
    <li> Pick the most important sentences in the article (based on the trained model) </li>
  </ol>
</div>
