# Tag 1: Einführung in HTML und CSS

## Ziel
- Verstehen der Grundstruktur einer HTML-Seite.
- Einführung in grundlegendes CSS zur Gestaltung von Webseiten.
- Erste Änderungen in einem bestehenden Projekt vornehmen.
- Grundlagen des responsiven Designs kennenlernen.

## Aufgaben

### Aufgabe 1: HTML bearbeiten
1. Öffne die Datei `index.html`.
2. Ergänze die Seite mit folgenden Inhalten:
   - Einen neuen Abschnitt `<section>`, der Informationen über dich enthält.
   - Eine Überschrift `<h2>` und einen kurzen Absatz `<p>` im neuen Abschnitt.

### Aufgabe 2: CSS anpassen
1. Öffne die Datei `assets/styles.css`.
2. Ändere die Hintergrundfarbe der Seite.
3. Passe die Schriftfarbe und Schriftart des Headers an.

### Aufgabe 3: Bereich "Meine Projekte" hinzufügen
1. Ergänze unter dem "Über mich"-Bereich einen neuen Abschnitt `<section>` mit der Überschrift `<h2>Meine Projekte</h2>`.
2. Füge drei Projekte hinzu, die jeweils enthalten:
   - Ein Bild `<img>` (Platzhalter-Bild verwenden: `https://via.placeholder.com/150`).
   - Einen kurzen Text `<p>` zur Beschreibung des Projekts.

### Aufgabe 4: Responsives Design (für Fortgeschrittene)
1. Sorge dafür, dass die Projekte auf großen Bildschirmen nebeneinander dargestellt werden.
2. Auf kleineren Bildschirmen (z. B. Smartphone) sollen die Projekte untereinander angezeigt werden.
3. Nutze hierfür CSS-Media-Queries:
   ```css
   @media (max-width: 768px) {
     .projekte {
       display: block;
     }
   }

   @media (min-width: 769px) {
     .projekte {
       display: flex;
       justify-content: space-between;
     }
   }
   ```

## Hinweise
- Nutze einen Texteditor oder eine IDE wie Visual Studio Code, um die Dateien zu bearbeiten.
- Öffne `index.html` im Browser, um die Änderungen live zu sehen.
- Für fortgeschrittene Teilnehmer: Experimentiere mit verschiedenen Breakpoints in den Media-Queries.

Viel Spaß beim Experimentieren! 😊
