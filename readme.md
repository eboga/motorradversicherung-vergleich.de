Now to see partner card you need to do this:

cards:
- partner: "adac"
secondary: true


Created file that contains all partners data (title, text, svg-path, url) – https://bitbucket.org/eboga/motorradversicherung-vergleich.de/src/ref-vergleich/_data/partners.yml.

url strokes are set to false, it means that all product will lead to /vergleich/ page, if you want to change it set desired url:

url: "/partner-page/"


or

url: "https://parterter-website.com"


You can override all data, doing so:

cards:
- partner: "adac"
title: "Pizza"
text: "Call me Ishmael. Some years ago--never mind how long precisely..."
url: "https://www.google.com/"
secondary: true
