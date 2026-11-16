gantt
    title Projektplan Template – Kategorien mit Subtasks
    dateFormat  YYYY-MM-DD
    excludes    weekends

    section Kategorie 1: Planung
    Planung Gesamt              :p1, 2026-11-16, 10d
    Bedarfsanalyse              :p1a, 2026-11-16, 3d
    Konzeptentwurf              :p1b, after p1a, 4d
    Freigabe Konzept            :p1c, after p1b, 3d

    section Kategorie 2: Entwicklung
    Entwicklung Gesamt          :e1, 2026-11-26, 15d
    Architektur                 :e1a, 2026-11-26, 5d
    Implementierung             :e1b, after e1a, 6d
    Unit-Tests                  :e1c, after e1b, 4d

    section Kategorie 3: Test & Rollout
    Test & Rollout Gesamt       :t1, 2026-12-11, 10d
    Interner Test               :t1a, 2026-12-11, 4d
    Externer Test               :t1b, after t1a, 3d
    Produktion freigeben        :t1c, after t1b, 3d
