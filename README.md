# SpionCamp: Tatort Schulnetz

Fortsetzung des Lernspiels „Störfall im Schulnetz“ (https://nb-gsn.github.io/Netzwerke/): Jemand hat sich Zugang zum Notenserver verschafft. Der Kurs ermittelt als Forensik-Team in sechs Missionen (je ca. 45 Minuten) zu symmetrischen, asymmetrischen und hybriden Verfahren.

**Camp-Seite:** https://nb-gsn.github.io/SpionCampQ2/

1. Die abgefangene Nachricht: Fachbegriffe, Caesar von Hand, Kerckhoffs
2. Das Java-Labor: Caesar in BlueJ programmieren (Basis, Standard, Experte)
3. Angriff auf Caesar: Brute Force, Häufigkeitsanalyse, Vigenère, Schlüsselraum (25, 26ᴸ, 2¹²⁸)
4. Das Schlüsselproblem: Schlüsselaustausch, n(n−1)/2, Farbmisch-Experiment
5. Echt oder gefälscht? Schlüsselpaar, Hashwert und Signatur (Live-Demo), Schutzziele, Man-in-the-Middle, Zertifikate
6. Finale: Angriff rekonstruieren, Täter überführen, Sicherheitskonzept, Schutzziele zuordnen, hybride Verfahren, Abschlussquiz

**BlueJ-Projekt:** `SpionCamp_Caesar.zip` (in BlueJ über Projekt → ZIP/JAR öffnen). Klassen: `Caesar` (Lückentext L1–L12), `Beweismittel` (abgefangene Nachrichten), `Pruefstand` (Selbsttest je Stufe).

## Für die Lehrkraft

- Lehrermodus: https://nb-gsn.github.io/SpionCampQ2/#lehrkraft (alle Missionen offen, Klassenübersicht aus Stand-Codes, CSV-Export)
- Jede Mission besteht aus 3 bis 4 Schritten, die sich nacheinander öffnen. Fortschritt bleibt im Browser des Teams.
- „Stand sichern“ zeigt einen Standbericht mit Punkten, Fehlversuchen, genutzten Hilfen und einem Stand-Code. Die Teams fotografieren ihn am Stundenende. Mit Teamname und Code geht es beim nächsten Mal weiter (auch auf einem anderen Rechner).
- Java-Labor als Lückentext (L1 bis L12) mit gestuften Hilfen auf der Seite. Im BlueJ-Projekt stehen an denselben Stellen kompilierbare Platzhalter.
- Transferaufgabe nach Mission 4: Klasse `Vigenere` ohne Lücken selbst schreiben (5 gestufte Hilfen auf der Seite, Test `pruefeVigenere()`), +6 Punkte.
- Mission 6: Abschlussbericht an die Schulleitung als Klausurtraining auf Papier (30 min, 20 Punkte, Operatoren wie im Abitur).
- Abi-Spickzettel Kryptografie (`Abi-Spickzettel_Kryptografie.pdf`): eine Seite mit allen Fachbegriffen, Schutzzielen und Schlüsseltabelle, wird nach Mission 6 im Team ausgefüllt.
- Quiz: 10 Fragen, bis zu 20 Punkte. Camp gesamt: 92 Punkte.
- QR-Code: `qr-plakat.png` (Beamer/Aushang, mit Geheimbotschaft in Caesar k = 3) und `qr-code.png`.
