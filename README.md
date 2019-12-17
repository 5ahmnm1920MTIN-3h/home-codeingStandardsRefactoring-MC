Was ist Refactoring Definition in eigenen Worten?

- Refactoring beschreibt den strukturierten Vorgang des Optimierens und Ausbessern von Code, um diesen leichter verständlich zu machen, wobei jegliche Funktionen des bestehenden Programms beibehalten werden.



Welche Vorteile/Nachteile birgt Refactoring?

Vorteile: 
- Bessere Lesbarkeit und Verständlichkeit für Außenstehende
- Redundanz wird vermieden
- Bessere Testbarkeit
- Code leichter erweiterbar
- Übersichtlicher

Nachteile: 
- Neue unerwartete Fehler können auftreten
- Testaufwand
- Abstimmungsaufwand zwischen Programmierern


Was sind die Refactoring-Schritte?
- Testcase definieren
- Testen ob Programm zu diesem Stand funktioniert bzw. was alles funktioniert
- Einen „Code Smell“ ausbessern 
- Testen ob das Programm noch alle zuvor bekannten Funktionen erfüllt
- Commit
- Wiederhole Schritt 3, 4 ,5 bis alle Smells ausgebessert sind
- Projekt pushen


Prinzipien von guten Code?
- DRY - Don’t Repeat Yourself Unnötige wiederholte/redundante Sachen können reduziert werden. KISS - Keep it Simple, Stupid Außenstehende sollten den Code auch verstehen können. YAGNI - You Ain’t Gonna Need Code der nicht benutzt wird kann gelöscht werden. Principle of least Astonishment Der User soll nie überrascht werden und jegliche Benennungen sollen klar erkenntlich angegeben sein was diese erfüllen. SoC - Separation of Concerns Der Code soll zusammengehörige Funktionen in diverse Abschnitte gliedern.


Was versteht man unter Code Smell?
- Der Begriff beschreibt funktionalen Code, welcher jedoch keine gute Strukturierung aufweist und oft unnötig komplex ist.



Recherche von 10 Code Smells die Eure Projekt betreffen können, inkl. Beschreibung und Beispiel.
- Kommentare
Keine unnötigen Kommentare

- Aussagekräftige Namen
Variablen- und Klassennamen sollten ihren Zweck beschreiben

- Keine Coderedundanz
Ein Code sollte nur einmal vorkommen.

- Methoden kurz halten
Methoden am besten so kurz wie möglich halten.

- Nichts unnötig Verschachteln
Unnötige Verschachtelungen machen den Code unübersichtlich