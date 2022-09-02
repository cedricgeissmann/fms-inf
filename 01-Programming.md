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

## Lösungsstrategie und Kommentare

Wenn Sie mit den Aufgaben von oben fertig sind, finden Sie hier noch weitere
Aufgaben. Versuchen Sie sich bei jeder Aufgabe zuerst zu überlegen wie sie
diese umsetzen möchten. Das ist unabhängig von der Programmiersprache und ist
eigentlich die Lösungsstrategie für eine Aufgabe.

Geben Sie für jede Aufgabe die Lösungsstrategie als Kommentar vor der Aufgabe
an.

**Komentare:** In Javascript ist aller Code der auf `//` folgt, ein Kommentar.
Das bedeutet für den Computer das der Text nach diesen Zeichen ignoriert wird.

::: {.example}
### Beispiel

Ersetzen Sie das erste und letzte Zeichen in der Zeichenkette mit dem
Grossbuchstaben dieses Zeichens.

::: {.code}
```javascript
// Aufgabe Beispeil:
// (1) Wähle das Zeichen an der Stelle 0 und setze es toUpperCase.
// (2) Wähle das Zeichen an der Stelle input.length - 1 und setze es toUpperCase.
function beispiel() {
    let input = read()
    input = input.split("")
    // Schritt (1)
    input[0] = input[0].toUpperCase()
    
    //Schritt (2)
    input[input.length - 1] = input[input.length - 1].toUpperCase()
    
    // Liste als Zeichenkette zusammenführen und ausgeben
    let result = input.join("")
    print(result)
}
```
:::

:::

## Weitere Aufgabe

::: {.exercise}
### Aufgabe 11

Ersetzen Sie alle Zeichen der Eingabe mit der Grossbuchstabenversion der
Zeichens.
:::

::: {.exercise}
### Aufgabe 12

Ersetzen Sie alle Zeichen der Eingabe mit der Kleinbuchstabenversion der
Zeichens.
:::

::: {.exercise}
### Aufgabe 13

Ersetzen Sie alle Zeichen der Eingabe mit einem `$` bis Sie ein `k` lesen.
:::

::: {.exercise}
### Aufgabe 14

Ersetzen Sie alle Zeichen der Eingabe mit Grossbuchstaben, bis Sie einen
Grossbuchstaben lesen.
:::

::: {.exercise}
### Aufgabe 15

Hängen Sie den ersten Buchstaben der Eingabe vorne und hinten an die
Zeichenkette an.
:::

::: {.exercise}
### Aufgabe 16

Hängen Sie die ersten 3 Buchstaben der Eingabe vorne und hinten an die
Zeichenkette an. Überprüfen Sie dass die Zeichenkette mindestens 3 Zeichen
enthält.
:::

::: {.exercise}
### Aufgabe 17

Vertauschen Sie das erste und das letzte Zeichen einer Zeichenkette.
:::

::: {.exercise}
### Aufgabe 18

Vertauschen Sie das erste und das letzte Zeichen einer Zeichenkette. Dann das
zweite und das zweitletzte und so weiter, bis Sie in der Mitte angekommen sind.
:::

::: {.exercise}
### Aufgabe 19

Löschen Sie das Zeichen in der Mitte der Eingabe, wenn die Eingabe grösser als
10 oder ungerade ist.
:::

::: {.exercise}
### Aufgabe 20

Löschen Sie Zeichen aus der Mitte der Zeichenkette, bis 2 gleiche Zeichen in
der Mitte stehen.
:::
