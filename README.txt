BILDERGALERIE – STATISCHE WEBSITE

1. Entpacke den Ordner.
2. Öffne index.html im Browser.
3. Lege dein Hintergrundbild unter assets ab und benenne es:
   hintergrund-platzhalter.svg
   (oder ändere den Dateinamen in style.css bei --background-image).
4. Ersetze assets/platzhalter-kachel.svg durch deine Kachelbilder.
   Für unterschiedliche Kachelbilder passe die src-Angaben in index.html an.
5. Lege die zwölf Detailbilder unter diesen Namen in assets ab:
   detail-01.jpg bis detail-12.jpg
   Alternativ kannst du die Dateinamen im bilder-Objekt in detail.html ändern.

Die Startseite enthält 4 Spalten × 3 Zeilen. Auf kleineren Bildschirmen
wird das Raster responsiv auf 3 bzw. 2 Spalten reduziert.
Die Detailseite bleibt eine eigenständige statische HTML-Datei und lädt
das passende Motiv über den URL-Parameter ?bild=bild-01 usw.
Alle Dateien funktionieren lokal ohne Backend oder Webserver.
