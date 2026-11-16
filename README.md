# MACH Project: Throwing System

## Projektbeschreibung

Im Rahmen des MACH-Projekts bauen wir ein automatisches Wurfsystem mit einem Roboterarm.
Der Roboter (UR10e mit Robotiq Hand-E Greifer) soll autonom eine Kugel aus einer
Rückgabevorrichtung aufnehmen, etwa 1,5 Meter weit in diese Vorrichtung werfen und
die Kugel soll passiv zurückgeführt werden.

## Team

Tom, Leo & Alex: Wurfmechanismus     - Wurfbewegung und git doku
Lukas & Anna:    Rückführmechanismus - CAD und 3D-Druck

## Aufgaben

1. Object Pick-Up: Autonome Aufnahme der Kugel aus der Rückgabevorrichtung
2. Object Throwing: Werfen der Kugel in die Rückgabevorrichtung (1,5 m entfernt)
3. Return Mechanism: Passive, mobile und modulare Rückgabevorrichtung (CAD + 3D-Druck)
4. Integration: Kontinuierlicher Zyklus ohne manuelles Zurücksetzen

## Hardware

* Roboterarm: UR10e
* Greifer: Robotiq Hand-E (Paralleljaw Gripper)
* Objekte: Kugeln (Sphere)
* Fertigung: 3D-Drucker

## Software

* CAD: Autodesk Fusion
* Roboterprogrammierung: Teach Pendant (oder ROS2)

## Ordnerstruktur (vorläufig)

* cad/ — Konstruktionen für die Rückgabevorrichtung
* code/ — Roboterprogrammierung und Steuerung
* dokumentation/ — Berichte, Protokolle, Auswertung
* ressourcen/ — Datenblätter, Bilder, Vorlagen

## Git-Workflow (für das Team)

1. Vor Arbeitsbeginn: git pull
2. Eigene Änderungen in einem separaten Zweig vornehmen
3. Änderungen speichern: git add ., git commit -m "Beschreibung", git push
4. Nach Abstimmung im Team in den Hauptzweig übernehmen

## Bewertung

Bewertet werden Wiederholbarkeit, Geschwindigkeit und Designqualität.
Ziel: In mindestens zwei von drei Kategorien die besten Ergebnisse erzielen.

