---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  title: Mahamaya Paints & Chemicals
  image_fullwidth: banner1.jpg
widget1:
  title: "Pesticides"
  url: "/pesticides/"
  image: pesticides.jpeg
widget2:
  title: "Industrial Chemicals"
  url: "/chemicals/"
  image: chemical.jpg
widget3:
  title: "Mineral Powder"
  url: "/minerals/"
  image: powder.jpg

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
  url: "/products"
  text: See All Products ››
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
