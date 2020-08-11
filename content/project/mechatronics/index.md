---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Mechatronics"
summary: ""
authors: []
tags: []
categories: []
date: 2020-07-13T12:59:58+01:00
Weight: 3

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
### Project Overview

{{< figure src="8.png" title="One of the starting images" lightbox="true" >}}

The project involved a task initially conducted with physical access to the Loughborough university mechatronics lab and the second half conducted remotely. The physical lab work covered designing a control system to execute a ‘goal’ on a table football rig. This was broken into a vision, manipulator and kicker engineer role. By using an overhead camera, X & Y axis motor and a motor axis the system needed to manoeuvre the ‘kicker’ to the ‘puck’ and kick the puck into the goal. However due to the impact of Covid-19 the second half of the project was conducted remotely. This resulted in changed aims and deliverable to cope with the lack of lab access. Thus a simulated system was identified as a requirement using NI’s LabVIEW software.

For the manipulator task a displayed simulated movement to the kicking site and an overlain image with potential shots on goal and the selection of a ‘best’ shot. This involved calculating velocity traces for the X and Y axis and displaying the kicker movement. The shot prediction was conducted by evaluating shot obstacles, evaluating collisions and identifying valid shots on goal. The output from this project is a LabView program capable of displaying the manoeuvring of a kicker to the kicking site. To identify possible shots both directly on goal or rebound shots off the edges of the playing surface, to the goal avoiding the four obstacles and suggesting the best shot option. This system simulation meets the requirements as defined in the briefing document.

The output from the project is shown below as a straight shot and a bounce shot, avoiding the blockers. The movement from the 'Home' position in the bottom right of the image is shown in three colours, green as acceleration blue as steady velocity and red as a deceleration stage. The shot prediction is shown with possible shots in blue and the 'best' shot in green.

{{< figure src="capture 2.png" title="Direct shot option" lightbox="true" >}}

{{< figure src="capture.png" title="Bounce shot option" lightbox="true" >}}
