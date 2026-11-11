# Projektplan – MACH Wurfsystem


```mermaid
gantt
    title MACH Project: Wurfsystem – Projektplan
    dateFormat  YYYY-MM-DD
    excludes    weekends

    section Vorbereitung
    Git Setup                        :a1, 2026-11-11, 2d
    URSim Setup                      :a2, after a1, 3d

    section URSim
    Erste Versuche Roboter kennenlernen in URSim
                                     :a3, after a2, 5d

    section Physischer Roboter
    Erste Versuche am physischen Roboter
                                     :a4, after a3, 4d

    section Bewegungsplanung
    Wurfbewegung festlegen           :a5, after a4, 4d
    Ball Aufnahme loslassen Timing   :a6, after a5, 4d
    Zielposition festlegen Austausch :a7, after a6, 3d

    section Test und Optimierung
    Erste Wurfversuche ca 1,5 m      :a8, after a7, 5d
    Optimierung                      :a9, after a8, 7d
```
