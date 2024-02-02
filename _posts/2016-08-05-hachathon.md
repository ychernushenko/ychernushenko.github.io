---
layout: post
title:  "First try with Neural Networks"
date:   2016-08-05 14:19:20 +0200
categories: software
---

There was a hackathon this weekend about <a href="http://kubernetes.io/">Kubernetes</a> and <a href="https://crate.io/">Crate</a>. The idea was using these technologies create something cool. We decided with my friend <a href="https://www.facebook.com/silnov">Sergey</a> to try something from deep learning and ended up transferring style from the <a href="https://en.wikipedia.org/wiki/Sunflowers_(Van_Gogh_series)">Van Gogh Sunflowers</a> to a video.  

The idea was to have next steps:  
1. Split video into several frames with some rate, because processing of all frames would take too long.  
2. Process each frame on separate Kubernetes container  
3. Gather result and create gif  

Step one was done based on <a href="https://gist.github.com/baraldilorenzo/07d7802847aaad0a35d3">this</a> pretrained model. We downloaded weights and trained it on each frame. Processing of one frame took for 10 iterations on my local machine about 10-15 min and looked like this:  

<img src="/assets/2016-08-05-one-frame.png">  

Step two was not that easy to implement while the hackathon. There was some free balance for the google cloud platform, but is was not that easy to configure Kubernetes in several hours we had and this cloud is actually not that efficient for this kind of tasks(no GPU options available out of the box).  

Final gif looked like this:  
<img src="/assets/2016-08-05-final-video.gif">
