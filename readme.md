# Kanban bei arcus(x)

## Regeln
* jede Story < 5 Tage
* jede Story am Board bekommen jeden Tag einen Strich
* hängt eine Story länger als 5 Tage entscheidet das Team, wie es damit weiter geht: Abbruch, Split, Fortsetzung wie es ist
  => dieser Alarmmechanismus zeigt auf, dass Handlngsbedarf besteht, weil eine Story nicht genug Progress hat oder die Story den geplanten Rahmen von 5 Tagen sprengen wird
* die DOD einer begonnenen Story kann nicht mehr einseitig verändert werden (in Absprache mit den bearbeitenden Devs schon; sie selbst dürfen auch Ergänzungen oder Änderungen nach Rücksprache mit PO vornehmen)
  * im Laufe einer Story ergeben sich Erkenntnisse, die es falls möglich zu berücksichtigen gilt
  * den Umfang einer Story zu reduzieren ist eine mögliche Vorgehensweise auf die Erkenntnis, dass die Story nicht innerhalb von 5 Tagen fertig werden kann
* die Tasks einer Story werden zu Beginn der Story geplant und wandern beim Abarbeiten über das Board
* die Tasks einer Story können jederzeit ergänzt, geändert oder komplett verworfen und neu geplant werden (innerhalb der 5 Tage)
* die Stationen einer Story sind "in work", "dev test/qa", "production"
* Lanes bestimmen die Anzahl offener Stories (Personen * 3/4, wir pairen)
* gezogen werden können neue Stories nur, wenn eine Lane frei ist

## Werte

### Auslastung
vereinfacht Anzahl der Tickets gleichzeitig in Bearbeitung: zu viele = Switching/ Eff.Verlust; zu wenige = zu wenig Output.

### WIP bzw. Work in Progress Limit
Wird die Auslastung eines Systems zu hoch entstehen weitere Zeitverluste durch Wartezeiten; das WIP-Limit stellt sicher, dass ein System nicht überlastet wird.

### Lebendigkeit
Lebendigkeit ist die Fähigkeit neue Stories anzunehmen. Diese Fähigkeit ist Bedingung dafür, aus Sicht eines Außenstehenden mehrere Prioriäten "parallel" zu berücksichtigen. Dies wird dadurch erreicht, dass im Mittel alle 2-3 Tage (in maximal 5 Tagen) eine neue Story eines anderen Themas berücksichtig werden kann. Wenn eine Story länger benötigt als 5 Tage, beeinträchtigt sie die Fähigkeit eine andere Prio zu berücksichtigen. Darum sind hier Abbruch und Split einer Story angemessene Strategien, um die Lebendigkeit des Kanbans sicherzustellen.

### Output
Der Output pendelt sich mit einer Durchlaufzeit der Stories zwischen 3-3,5 Tagen ein und das Team stabilisiert seinen Output.

### Ständige Verbesserung
* Die 3-wöchige Retro stellt sicher, dass Erkenntnisse gesammelt und ausgewertet werden und zu Verbesserungsmaßnahmen umgewandelt werden.

## License
[WTFPL-2](./license.txt)
