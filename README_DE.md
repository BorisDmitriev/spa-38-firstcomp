# `06` Deine erste funktionale Komponente

Wenn du Funktionen erstellst, die HTML zurückgeben, kannst du sie in JSX als **"Komponenten "** behandeln, d.h. sie werden zu deinen eigenen HTML-Tags.

## Erstellen unserer ersten funktionalen Komponente

Dank JSX können wir unter anderem Funktionen so aufrufen, als wären sie ein HTML-Tag, zum Beispiel:
```js
// if we declare a function called MyFunction
const MyFunction = () => {
    return <h1>I Love React</h1>;
}

// we can call the function as an HTML tag like this:
<MyFunction />

// instead of the typical way of using round brackets
MyFunction();
```

Wenn du eine Funktion auf diese Weise aufrufst, wird sie zu einer **"React-Komponente "**, also einer Funktion, die dynamisch HTML erzeugt (zurückgibt). Was auch immer die Funktion zurückgibt, wird an der gleichen Stelle ersetzt, an der die ursprüngliche `<MyFunction />` platziert war.

## :speech_balloon: Anleitung

Ändere in der 9. Zeile von index.js die Art und Weise, wie die Funktion aufgerufen wird, und rufe die Funktion als **"React-Komponente "** auf, indem du `<` und `>` wie einen HTML-Tag verwendest (anstelle von Klammern).
