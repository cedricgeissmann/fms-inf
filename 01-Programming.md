---
title: "Einstieg ins Programmieren"
---

Beim Programmieren geht es darum das man Abläufe automatisieren kann, damit
grosse Datenmengen schnell und einfach verarbeitet werden können. Dazu braucht
man eine Programmiersprache um mit dem Computer zu sprechen. Wir werden hier
Javascript verwenden, weil man es einfach im Webbrowser benutzen kann und somit
schon Zugriff auf komplexere Dinge wie Benutzerinterfaces (z.b. Webseiten) hat.

Damit alle direkt arbeiten können, braucht es einen Account bei
[Replit](https://replit.com/). Wenn Sie einen Account erstellt haben, können
Sie das folgende [Repl](https://replit.com/@CedricGeissmann/easycoding) öffnen.
In dem folgenden Video gibt es eine kurze Einführung in das Repl.

::: {.video}
<iframe width="560" height="315"
src="https://www.youtube.com/embed/FPCdwpl4O0M"
frameborder="0" allow="accelerometer; autoplay; clipboard-write;
encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

## Lokal Arbeiten

Wenn Replit nicht funktioniert, können Sie auch lokal arbeiten. Dazu laden Sie
das folgende
[Archiv](https://github.com/cedricgeissmann/easycode/archive/refs/heads/master.zip)
herunter und öffnen danach im Browser die folgende URL:
[vscode](https://vscode.dev). Das folgende Video erklärt wie Sie damit arbeiten
können.

::: {.video}
<iframe width="560" height="315"
src="https://www.youtube.com/embed/D6_07NrkKLI"
frameborder="0" allow="accelerometer; autoplay; clipboard-write;
encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

## Variablen

Beim Programmieren sind Sie oft darauf angewiesen dass Sie ein Resultat
speichern können. Dafür gibt es Variablen.

::: {.example}
```javascript
let school = "FMS Muttenz"
let year = 2022
```
:::

In dem Video erfahren Sie noch ein wenig mehr über Variablen.

::: {.video}
<iframe width="560" height="315"
src="https://www.youtube.com/embed/PsMjrXimQp4"
frameborder="0" allow="accelerometer; autoplay; clipboard-write;
encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

## Textausgabe

Das wichtigste das Sie beim Programmieren haben, ist die Ausgabe in Text. Sie
brauchen das immer wieder, entweder um dem Anwender eine Nachricht zu geben,
oder um zu überprüfen was das eigene Programm gerade macht. Dafür ist es
wichtig den Wert von Variablen anzuzeigen. Am einfachsten geht das mit
sogenannten **Template Literals**.

::: {.example}
```javascript
let name = "Justus Jonas"
let greeting = `Hi! My name is ${name}.`
```
:::

In dem Video finden Sie noch mehr Informationen zu **Template Literals**.

::: {.video}
<iframe width="560" height="315"
src="https://www.youtube.com/embed/NKpQiltgNrs"
frameborder="0" allow="accelerometer; autoplay; clipboard-write;
encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

## Arbeiten mit Text als Liste

In dem folgenden Video wird einiges über das arbeiten mit Text als Liste von
Zeichen erklärt. Schauen Sie das Video sorgfältig an und lösen Sie die
nachfolgenden Aufgaben.

::: {.video}
<iframe width="560" height="315"
src="https://www.youtube.com/embed/obm6Po3-aCk"
frameborder="0" allow="accelerometer; autoplay; clipboard-write;
encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
:::

## Aufgaben

::: {.exercise}
### Aufgabe 1

Schreiben Sie ein Programm das Sie mit dem Namen begrüsst den Sie in das
Eingabefeld eintippen.
:::

::: {.exercise}
### Aufgabe 2

Schreiben Sie ein Programm das Ihren Namen als Liste von Zeichen ausgibt.
:::

::: {.exercise}
### Aufgabe 3

Schreiben Sie ein Programm das überprüft ob in einer Eingabe das Zeichen `'x'`
vorkommt.
:::

::: {.exercise}
### Aufgabe 4

Schreiben Sie ein Programm welches überprüft ob die Eingabe kürzer wie 12
Zeichen ist, und länger wie 0.
:::

::: {.exercise}
### Aufgabe 5

Schreiben Sie ein Programm das jedes Zeichen in der Eingabe verdoppelt.
:::

::: {.exercise}
### Aufgabe 6

Schreiben Sie ein Programm das zählt wie viele Leerzeichen in Ihrer Eingabe
vorkommen.
:::

::: {.exercise}
### Aufgabe 7

Schreiben Sie ein Programm das alle Leerzeichen in der Eingabe mit dem Zeichen
`_` ersetzt.
:::

::: {.exercise}
### Aufgabe 8

Schreiben Sie ein Programm welches überprüft ob nach jedem `.` in der Eingabe
ein Leerzeichen kommt.
:::

::: {.exercise}
### Aufgabe 9

Schreiben Sie ein Programm welches die Eingabe umkehrt.
:::

::: {.exercise}
### Aufgabe 10

Schreiben Sie ein Programm das die Eingabe auf ein *Palindrom* überprüft.

**Hinweis**: Ein *Palindrom* ist eine Zeichenkette die vorwärts und rückwärts
gelesen das gleiche ergibt.
:::
