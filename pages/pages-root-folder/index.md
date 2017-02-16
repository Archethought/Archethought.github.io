---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
#header:
#  image_fullwidth: "fr-images/header_unsplash_5.jpg"
#image_fullwidth: gear-wallpaper-1600x507.jpg

widget1:
  title: "Big Data Handling"
#  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'We work with and collect big data sets, then combine your data with tools that bring you insight'

widget2:
  title: "Sensors & Beacons"
#  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'Using Beacons and Sensors, we gather data and seek to create learning and actionable observations'

widget3:
  title: "Code Development"
#  url: 'https://github.com/Phlow/feeling-responsive'
  image: widget-github-303x182.jpg
  text: 'We excel in front-end and backend development, creating Apps, APIs, and Service'
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
#callforaction:
#  url: https://tinyletter.com/feeling-responsive
#  text: Inform me about new updates and features ›
#  style: alert

permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
