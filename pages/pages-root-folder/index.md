---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-main.jpg

widget1:
  title: "Cypress.io"
  url: 'https://www.cypress.io/'
  image: cypress-logo.png
  text: 'Cypress is a next generation front end testing tool built for the modern web'

widget2:
  title: "Cypress documentation"
  url: 'https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell'
  image: gallery-example-4.jpg
  text: 'Explore all possibilities and libraries in cypress documentation '

widget3:
  title: "Cypress on github"
  url: 'https://github.com/cypress-io/cypress'
  image: widget-github-303x182.jpg
  text: 'Git repo'
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
