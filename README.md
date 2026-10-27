# SR-Doku

Allgemeine **Schockraumdokumentation** als offline-fähige Single-File-Web-App (PWA) nach dem (PR_E-)AUD²IT-Basisalgorithmus mit SINNHAFT-Übergabe (Gräff et al., Notfall Rettungsmed 2024; RDA Bayern/DGINA 2024). Eigenständige App neben [MEGA-CodeSR](https://github.com/LMuehlen96/MEGA-CodeSR) (Reanimation).

**Live:** https://LMuehlen96.github.io/SR-Doku/

## Nutzung auf dem iPhone
Live-URL in Safari öffnen → Teilen → **„Zum Home-Bildschirm“**. Alle Falldaten bleiben ausschließlich lokal im Browser (localStorage); es werden keine Daten an einen Server gesendet.

## Umfang
Voranmeldung & TTO I · SINNHAFT-Übergabe (N cABCDE / H Handlung) · Primary survey ABCDE mit Monitoring · TTO II (bis zu zwei Leitsymptome, vollständige ABCDE-Priorisierung) · AUD² (SAMPLER, OPQRST, Reassessment, DD, Diagnostik) · TTO III & To Do · Protokoll mit offline erzeugtem PDF (Teilen per Mail, optional nur Initialen).

## Zugang
Die App ist **nicht freigegeben** und passwortgeschützt. `index.html` enthält nur eine Sperrseite und die mit AES-256-GCM verschlüsselte App (Schlüssel per PBKDF2-SHA256 aus dem Passwort). Der Quelltext der App liegt nicht im Klartext in diesem Repository. Das Passwort erhalten berechtigte Instruktor:innen über die AG Schockraum.

## Wichtiger Hinweis
Prototyp – **kein Medizinprodukt**. Ersetzt weder ärztliche Entscheidung noch die Dokumentation im KIS. Versand von Patientendaten per Mail nur über klinikintern zugelassene Wege.


---
© 2026 Lars Mühlen · Nicht freigegebene Version.
