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



## faqs
faq:
  - title: "Rollerversicherung: Welche Ergänzung ist sinnvoll?"
    anchor: 
    content: >-
        Viele Versicherer bieten für den Roller nicht nur eine Haftpflichtversicherung an. Sie ergänzen die Absicherung um eine Teilkaskoversicherung. Dadurch ist das Zweirad unter anderem gegen Diebstahl und gegen Schäden aus dem Zusammenstoß mit Tieren versichert.
        Gerade bei einem neuen Roller lohnt sich häufig der Abschluss einer [Teilkaskoversicherung](/teilkaskoversicherung/). Müssen Sie nämlich einen neuen Roller aufgrund eines Diebstahls oder durch Vandalismus ersetzen, sind die Kosten deutlich höher als der Versicherungsbeitrag für eine Teilkaskoversicherung. Nach einigen Jahren können Sie die Teilkasko kündigen und Ihren Roller nur noch über die Haftpflicht versichern. So senken Sie den Beitrag für Ihren Versicherungsschutz und sind trotzdem sinnvoll abgesichert.

{% comment %}
faq:
  - title: ""
    anchor: 
    content: >-
        
{% endcomment %}
