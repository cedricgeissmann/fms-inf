---
title: "Tabellenverarbeitung"
---

Beim Arbeiten mit Tabellen, geht es oft darum das Sie Listen in tabellarischer
Form darstellen. Oftmals werden in den Tabellen auch automatische Berechnungen
durchgeführt. Ein einfaches Beispiel wo oft eine Tabellenkalkulation verwendet
wird, ist ein Monatsbudget. Wir werden nun Schritt für Schritt eine
Budgettabelle erstellen und dabei die Grundlagen der Tabellenkalkulation
entdecken.

Am Ende könnte ein Budgetplan in etwa so aussehen: [Budgetplan.pdf](res/01-Budgetplan.pdf)

## Neue Tabelle erstellen

Damit es für alle gleich aussieht, und wir keine Probleme mit verschiedenen
Betriebssystemen oder Programmversionen haben, arbeiten wir im Browser. Dazu
loggen Sie sich auf [portal.office.com](https://portal.office.com) ein.

Auf der linken Seite finden Sie eine Schaltfläche `Erstellen`. Klicken Sie
diese an, und wählen Sie eine neue Arbeitsmappe. Diese sollte sich dann gleich
öffnen.

## Dokumente organisieren und benennen

Das erste was Sie mit einer neuen Datei machen sollen, ist diese mit einem
vernünftigen Namen an einem Ort zu speichern wo Sie das ganze wieder finden.
Dazu sehen Sie in dem grünen Band ganz oben den Namen der Datei. Klicken Sie da
drauf und speichern die Datei mit einem sinnvollen Namen.

::: {.example}
### Hinweis

Wenn Sie möchten das Ihre Dateien geordnet sind, können Sie einfach Zahlen vor
die Datei hängen. Damit sind diese immer alphabetisch sortiert, und für jetzt
auch nach Kapitel eingeteilt.
:::

::: {.example}
### Hinweis

Sie sollten keine Leerzeichen in Dateinamen verwenden. Brauchen Sie stattdessen
das `-` Zeichen.
:::

## Gestaltung von Zellen

Bei der Gestaltung der Zellen hat man sehr viele Möglichkeiten. Man kann Zellen
verbinden, die Farbe ändern und die Schriftform verändern. Bei der Gestaltung
sollte folgende Regel aber immer gelten, weniger ist mehr. In erster Linie geht
es um die Verarbeitung und Eingabe der Daten, die Präsentation der Daten sollte
separat davon gemacht werden. Da wir aber noch ganz am Anfang sind, und nur
sehr einfache Daten verarbeiten, legen wir schon Wert auf eine vernünftige
Darstellung.

Wir werden nun zusammen einige Beispiele für Formate durchgehen. Dabei werden
Sie die folgenden Dinge lernen:

- Zellen verbinden
- Schriftform verändern
- Hintergrundfarbe verändern
- Schriftfarbe verändern
- Zellenumrandung anpassen

::: {.example}
### Hinweis

Wenn Sie einen Rechtsklick auf eine Zelle machen, dann sehen Sie ein Menü wo
Sie all die Optionen angezeigt bekommen.
:::

::: {.example}
### Hinweis

Die Schaltfläche mit dem Pinsel lässt Sie Formate auf andere Zellen übertragen.
Das kann Dinge sehr vereinfachen, kann aber auch zu Problemen führen wenn Sie
nicht alle Formatierungen übernehmen möchten.
:::

## Formatierung des Zelleninhalts

Da man in der Tabellenkalkulation oft Berechnungen anstellen möchte, aber die
Daten auch lesbar angezeigt bekommen, gibt es die Möglichkeit Formatierungen
für Zellen zu verwenden. Dabei kann man einstellen welches Format ein Datum
haben sollte, oder wie eine Zahl angezeigt werden soll.

::: {.example}
### ACHTUNG

Hier sollten Sie unbedingt aufpassen, denn in der Ansicht können so Daten
verloren gehen, wenn sie beispielsweise gerundet werden. Dadurch wird das
Kopieren aus einer Tabelle gefährlich, und sollte immer hinterfragt werden.
:::

::: {.example}
### Hinweis

Wenn Sie mit einem Datum arbeiten, kann es auch passieren das Fehler
auftreten. Je nach Format das verwendet wird, können beispielsweise Tag und
Monat vertauscht werden. Dies passiert oft wenn der Computer versucht zu
erkennen ob es sich um ein Datum handelt oder nicht, und wenn die gleiche Datei
dann auf verschiedenen Computern oder mit verschiedenen Versionen eines
Programms geöffnet wird.
:::

## Bedingte Formatierung

Sie können Formate auch *bedingt* verwenden, also wenn eine Zahl grösser als 0
ist, oder auch ganz andere Dinge. Wählen Sie dazu eine Zelle an, und geben Sie
oben im Suchfenster **Regeln verwalten** ein. Dann öffnet sich auf der rechten
Seite ein neues Menü, welches alle Regeln für diese Zelle enthält.

Wir erstellen nun gemeinsam eine Regel, welche uns das Saldo `rot` einfärbt,
wenn es negativ ist.

## Tabellen erstellen

Sie können Tabellen innerhalb einer Tabellenkalkulation erstellen. Die Idee
dahinter, ist das Sie einen Bereich haben, der einer Tabelle entspricht.
Innerhalb einer Tabelle können Sie dann Spalten sortieren, oder filtern. Das
kann sehr praktisch sein, wenn Sie schnell etwas suchen müssen.

Wählen Sie den Bereich an den Sie zu einer Tabelle zusammenfügen möchten, geben
Sie oben im Suchfeld Tabelle ein, und erstellen Sie eine neue Tabelle.

## Berechnungen automatisieren

Sie können mit einer Tabellenkalkulation auch Berechnungen erstellen lassen.
Dazu müssen Sie am Anfang der Zelle einfach ein `=` eingeben, dann können Sie
verschiedene Formeln auf alle möglichen Zelle anwenden lassen.

Wir werden dies gleich zusammen machen, um das Saldo zu berechnen.

::: {.example}
### ACHTUNG

Es gilt vorsichtig zu sein bei automatischen Berechnungen. Es kann sein das
eine Summe über einen Bereich nicht alles abdeckt, so können sehr einfach
Fehler passieren die erst sehr spät oder auch gar nicht entdeckt werden. Prüfen
Sie also immer nach ob die Bereiche Ihrer Formeln auch stimmen.
:::
