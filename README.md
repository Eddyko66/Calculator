#  Calculator Website

Ein selbst programmierter Web-Taschenrechner, den ich mit **HTML, CSS und JavaScript** umgesetzt habe.  
Der Fokus lag darauf, die Grundrechenarten und eine saubere, dunkle UI einfach und verständlich umzusetzen.

##  Features

- Grundrechenarten: **Addition, Subtraktion, Multiplikation, Division**
- **Komma/Dezimalzahlen** über den `,`-Button (`.` in JavaScript)
- **DEL-Button**, um die Eingabe schrittweise zu löschen
- Ergebnis-Berechnung über eine selbst aufgebaute Ausdruckszeichenkette
- Vollbild-Layout: Ergebnisbereich oben, Tasten unten als Grid
- Hover-Effekte für Buttons

##  Umsetzung (Technik)

- **HTML**
  - Anzeige-Bereich: `div#resultArea`
  - Buttons als `table` mit `td`-Elementen
  - `onclick`-Handler an den Zellen für direkte Bedienung

- **CSS**
  - Dark-Mode-Look mit Grautönen
  - Klare Trennung: oberer Ergebnisbereich (`30vh`), Tastenbereich (`70vh`)
  - Hover-Effekt auf Tasten
  - Hervorhebung von Operatoren (`.highlight`) und `=`-Button (`#result`)

- **JavaScript**
  - `appendOperation(operation)`  
    → Hängt Zahlen/Operatoren an den Text im `resultArea`
  - `calculateResult()`  
    → Liest den Ausdruck aus `resultArea` und berechnet das Ergebnis
  - `deleteLast()`  
    → Entfernt das letzte Zeichen/den letzten Teil aus der Eingabe
  - Ausdruckslogik über einen Zeichenketten-Ansatz (Expression-String)

##  Live-Demo

Die Seite ist hier erreichbar (GitHub Pages):

 **https://eddyko66.github.io/Calculator-Website/**

## ▶ Lokal starten

1. Repository herunterladen oder klonen  
2. Ordner öffnen  
3. `index.html` im Browser öffnen (Doppelklick reicht)

##  Motivation

Dieses Projekt habe ich erstellt, um:
- die Grundlagen von **HTML, CSS und JavaScript** an einem praktischen Beispiel zu üben  
- eigene UI-Elemente (Buttons, Layout, Dark-Theme) umzusetzen  
- ein kleines, aber vollständiges Projekt für meine **Bewerbungen im IT-/Entwicklerbereich** zu haben
