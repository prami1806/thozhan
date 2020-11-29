---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "header_team.jpg"
widget1:
  title: "Our Mission"
  text: 'To make people socially aware, provide opportunities for each to bring about equal social justice to an integrated, balanced and progressive society.'
  image: 'mission.jpg'
  url: '/about-us'
widget2:
  title: "Our Vision"
  text: 'To bring multifaceted awareness, ability to analyze, comprehensive knowledge, provide opportunities, make a man socially aware, and dissolve the differences to hold hands and to prosper by sharing.'
  image: 'vision2.png'
  url: '/activities'
widget3:
  title: "Our Progress"
  url: '/contact-us'
  image: progress.jpg
  text: '<ul><li><strong>643</strong>  campaigns per year</li><li><strong>51400</strong>   volunteering hours per year</li><li><strong>400620</strong>   public people benefitted</li></ul>'
  
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

callforaction:
  url: https://forms.gle/9n5TKAfcby4JceYN9
  text: Subscribe to our newsletter >
  style: info

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
