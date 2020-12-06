---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-parents.png
widget1:
  title: "¿Qué somos, qué hacemos?"
  url: 'https://ampa.marcosfrechin.es/blog/'
  image: widget-1-302x182.jpg
  text: '¿Quieres saber lo que hace la A.M.P.A. del colegio? ¿Te gustaría participar? ¿Quieres conocer las actividades e iniciativas que se promueven desde la asociación?'
widget2:
  title: "Noticias"
  url: 'https://ampa.marcosfrechin.es/blog/'
  image: widget-github-303x182.jpg
  text: 'Os mantenemos al tanto de la actividad de la A.M.P.A. desde nuestro apartado de noticias. Estad atentos al mismo, en él publicaremos todo lo que sea de actualidad...'
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
  url: https://forms.gle/6anLZPQDZFwW7hfi9
  text: ¿Quieres ser socio? Inscríbete
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
