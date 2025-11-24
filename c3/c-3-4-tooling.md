---
  title: "Capstone Übung C.3.3: Tooling-Hinweise"
---
Für das Styling von `@media print` muss immer der Druck-Dialog des Browsers aufgerufen, um die Druckvorschau zu sehen. Änderungen am CSS werden erst nach dem Neuladen der Druckvorschau sichtbar.

Das ist so nicht optimal, aber auch hier gibt es Abhilfe: Im Chrome-Browser kann man in den Entwicklertools (F12) im Tab "Rendering" (ggf. über das Drei-Punkte-Menü rechts oben einblendbar) die Option "Emulate CSS media type" auf "print" setzen. Dann wird die Seite so dargestellt, als ob sie gedruckt werden soll, ohne dass der Druck-Dialog geöffnet werden muss.

![Tab Rendering](4.png)


![Im Tab Rendering den media type auf print setzen](5.png)

