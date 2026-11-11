# Projektplan – MACH Wurfsystem

Gantt-Chart zur Zeiterfassung und Dokumentation. GitHub rendert dieses Diagramm nativ (Mermaid). Bei Terminverschiebungen einfach die Daten anpassen, commiten und pushen.

```mermaid
gantt
    title MACH Project: Wurfsystem – Projektplan
    dateFormat  YYYY-MM-DD
    excludes    weekends

    section Vorbereitung
    Git Setup                        :a1, 2026-11-11, 2d
    URSim Setup                      :a2, after a1, 3d

    section URSim
    Erste Versuche (Roboter kennenlernen in URSim)
                                     :a3, after a2, 5d

    section Physischer Roboter
    Erste Versuche am physischen Roboter
                                     :a4, after a3, 4d

    section Bewegungsplanung
    Wurfbewegung festlegen           :a5, after a4, 4d
    Ball Aufnahme / loslassen (Timing)
                                     :a6, after a5, 4d
    Zielposition festlegen (Austausch)
                                     :a7, after a6, 3d

    section Test & Optimierung
    Erste Wurfversuche (ca. 1,5 m)   :a8, after a7, 5d
    Optimierung                      :a9, after a8, 7d
```

## Meilensteine

| Meilenstein | Geplantes Datum | Abhängig von |
|---|---|---|
| Repository eingerichtet | 2026-11-12 | Git Setup |
| URSim lauffähig | 2026-11-16 | URSim Setup |
| Erste URSim-Versuche abgeschlossen | 2026-11-21 | Erste Versuche (URSim) |
| Erste Versuche physischer Roboter | 2026-11-25 | URSim-Versuche |
| Wurfbewegung definiert | 2026-11-29 | Erste Versuche (physisch) |
| Aufnahme / Loslassen (Timing) | 2026-12-03 | Wurfbewegung |
| Zielposition (Austausch) definiert | 2026-12-06 | Aufnahme / loslassen |
| Erste Wurfversuche (ca. 1,5 m) | 2026-12-11 | Zielposition |
| Projekt abgeschlossen (Optimierung) | 2026-12-18 | Erste Wurfversuche |

## So nutzt du das im Repository

1. Kopiere die Datei `PROJEKTPLAN.md` in den Hauptzweig deines Git-Repositories (z. B. `main` oder `dev`).
2. Committe und pushe:
   ```bash
   git add PROJEKTPLAN.md
   git commit -m "docs: Gantt-Chart für Wurfsystem-Projektplan hinzufügen"
   git push origin main
   ```
3. Auf GitHub öffnest du die Datei – das Diagramm wird automatisch gerendert.

## Ergänzung: Tagesaktuelle Aufgabenverfolgung

Der Mermaid-Gantt-Chart eignet sich gut für den groben Projektplan. Für die tägliche Zeiterfassung und den Status einzelner Aufgaben empfiehlt sich **GitHub Projects** (Board- oder Timeline-Ansicht) parallel dazu:

- Erstelle ein GitHub Project im Repository.
- Lege pro Gantt-Punkt ein Issue an (z. B. „URSim Setup“, „Ball Timing“).
- Verknüpfe die Issues mit dem Meilenstein und ziehe sie über „To Do → In Progress → Done“.
- In der Timeline-Ansicht von GitHub Projects siehst du dann eine Gantt-ähnliche Ansicht mit den tatsächlichen Issue-Daten.

Die beiden Ansätze ergänzen sich: `PROJEKTPLAN.md` für den festen Plan im Git-Verlauf, GitHub Issues/Projects für die laufende Erfassung.

Die geplanten Daten sind ab heute (11.11.2026) beispielhaft gesetzt – passe sie an euren tatsächlichen Projektstart und die Laborverfügbarkeit im MAIRo Lab an.