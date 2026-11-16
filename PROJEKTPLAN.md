# Projektplan – MACH Wurfsystem

Gantt-Chart zur Zeiterfassung und Dokumentation. GitHub rendert dieses Diagramm nativ (Mermaid).

Wochenübersicht (Projektstart 28.10.2026 = W0):

| Woche | Datum |
|---|---|
| W0 | 28.10. – 03.11.2026 |
| W1 | 04.11. – 10.11.2026 |
| W2 | 11.11. – 17.11.2026 |
| W3 | 18.11. – 24.11.2026 |
| W4 | 25.11. – 01.12.2026 |
| W5 | 02.12. – 08.12.2026 |
| W6 | 09.12. – 15.12.2026 |
| W7 | 16.12. – 22.12.2026 |
| W8 | 23.12. – 29.12.2026 |
| W9 | 30.12. – 05.01.2027 |
| W10 | 06.01. – 12.01.2027 |
| W11 | 13.01. – 19.01.2027 |

```mermaid
gantt
    title MACH Project: Wurfsystem - Projektplan (W0 = 28.10.2026)
    dateFormat  YYYY-MM-DD
    excludes    weekends

    section W0-W1 Setup & Einarbeitung
    Setup Gesamt (W0-W2)              :s1, 2026-10-28, 21d
    Git Setup                         :s1a, 2026-10-28, 7d
    URSim Setup                       :s1b, 2026-10-28, 14d
    Erste Versuche in URSim           :s1c, 2026-11-04, 14d

    section W2-W3 Physischer Roboter
    Roboter Gesamt (W2-W4)            :s2, 2026-11-11, 21d
    Inbetriebnahme am Roboter         :s2a, 2026-11-11, 7d
    Erste Versuche am Roboter         :s2b, 2026-11-18, 7d

    section W3-W6 Wurfbewegung
    Bewegung Gesamt (W3-W6)           :s3, 2026-11-18, 28d
    Wurfbewegung festlegen           :s3a, 2026-11-18, 14d
    Ball Aufnahme / Loslassen Timing  :s3b, 2026-11-25, 14d
    Zielposition festlegen Austausch  :s3c, 2026-12-02, 14d

    section W7-W11 Test & Optimierung
    Test Gesamt (W7-W11)              :s4, 2026-12-16, 35d
    Erste Wurfversuche ca 1,5 m       :s4a, 2026-12-16, 21d
    Optimierung                       :s4b, 2026-12-30, 21d
    Finale Dokumentation & Abgabe     :s4c, 2027-01-06, 14d
```

## Meilensteine

| Meilenstein | Geplantes Datum | Woche |
|---|---|---|
| Repository eingerichtet | 28.10.2026 | W0 |
| URSim lauffähig | 10.11.2026 | W1 |
| Erste URSim-Versuche abgeschlossen | 24.11.2026 | W3 |
| Erste Versuche physischer Roboter | 25.11.2026 | W4 |
| Wurfbewegung definiert | 01.12.2026 | W5 |
| Ball Aufnahme / Loslassen (Timing) | 08.12.2026 | W6 |
| Zielposition (Austausch) definiert | 15.12.2026 | W7 |
| Erste Wurfversuche (ca. 1,5 m) | 06.01.2027 | W10 |
| Projekt abgeschlossen (Optimierung) | 19.01.2027 | W11 |

## So nutzt du das

1. Die Datei `PROJEKTPLAN.md` liegt im Repository (z. B. im Ordner `docs/projektplan-gantt`).
2. Auf GitHub rendert Mermaid automatisch – du siehst die Zeitleiste mit Datum und Wochen.
3. Bei Terminverschiebungen einfach die Daten anpassen, commiten und pushen.

Die geplanten Daten sind ab dem 28.10.2026 (W0) gesetzt – passe sie an euren tatsächlichen Projektstart und die Laborverfügbarkeit im MAIRo Lab an.