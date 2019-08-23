layout: false

.left-column[
## Demo
]
.right-column[
<br>
<br>
<br>

### GOTO .green[Eclipse]

]

???
- (Marketplace Eintrag zeigen)
- USUS Perspektive vorstellen
  - "Projects covered" als Einstieg
  - "Usus Cockpit" listet Analyseergebnisse
  - Pareto-Prinzip: Hotspots von oben nach unten abarbeiten
  - Bsp: `UsusInfoBuilder` "Extract Method" -> Trend nach oben 
  - Einige Metriken erläutern
- "Yellow Count"
  - je mehr Warnungen desto kräftiger gefärbt
- Paketzyklus zeigen (`org.projectusus.ui`)
  - Layout "Tree Horizontal"
  - Checkbox "Cyclic Dependencies"
  - umordnen, ausblenden
  - "Highlight" erläutern und Beispiel von Release 0.7.8 zeigen: https://github.com/usus/usus-plugins/releases/tag/v0.7.8
- "Show in Class Graph"
  - Filter "Source folder" zeigen
  - Zyklus auflösen: `UsusUIPlugin` verschieben  

---

layout: false
.left-column[
## Demo
]
.right-column[
### Read the docs

Überblick im GitHub Wiki
- https://github.com/usus/usus-plugins/wiki
<p/>

Viel Hintergrundwissen im andrena Wiki
- https://mail.andrena.de/wiki/Andrena/UsusWarumDieseMetriken
<p/>

Verschiedene Artikel aus Fachmagazinen im Repo
- https://github.com/usus/usus-plugins/tree/master/org.projectusus.documentation
]
