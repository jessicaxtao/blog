---
layout: page
title: 2020 Goals
permalink: /goals/
customjs:
 - http://code.jquery.com/jquery-1.4.2.min.js
 - http://yourdomain.com/yourscript.js
---

Tracker

<div id="container" style="margin:20px, width: 100%, height:20px"></div>
<div id="container1" style = "margin: 30px auto, width: 20%, height: 100px"></div>

<script>

var tuluzz = new ProgressBar.Line(container, {
  strokeWidth: 2,
  easing: 'easeInOut',
  duration: 5000,
  color: '#FFEA82',
  trailColor: '#eee',
  trailWidth: 1,
  svgStyle: {width: '100%', height: '100%'},
  from: {color: '#FFEA82'},
  to: {color: '#ED6A5A'},
  step: (state, bar) => {
    bar.path.setAttribute('stroke', state.color);
  }
});

tuluzz.animate(1.0);  // Number from 0.0 to 1.0

tuluzz.animate(0.6);  // Number from 0.0 to 1.0
</script>
