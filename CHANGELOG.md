# Felix App, Änderungsprotokoll

Jede Änderung bekommt eine neue Versionsnummer. Die Version steht unten in der App.
Schema: Hauptversion.Neue Funktion.Korrektur (zum Beispiel 1.1.0 für eine neue Funktion, 1.0.1 für eine Korrektur).

## 2.4.0 vom 2.10.2026
Fokus-Timer und Bewegungspause.
- Fokus-Zeit auf der großen Aufgabenkarte: 5, 10 oder 25 Minuten. Ist die Zeit um, gibt es 3 Punkte, eine Meldung und eine Erinnerung zur kurzen Pause. Mit Abbrechen gibt es keine Punkte.
- Bewegungspause auf der Startseite Heute: 5 oder 10 Minuten mit einem Vorschlag (Kniebeugen, Runde um den Block, tanzen, Treppe, dehnen, Hampelmänner), 3 Punkte bei vollendeter Zeit. "Anderer Vorschlag" wechselt die Idee.
- Es läuft immer nur ein Timer. Er läuft weiter, wenn du die Seite neu lädst oder den Reiter wechselst. Ist die Zeit abgelaufen, während die App geschlossen war, gibt es keine Punkte.
- Korrektur: Im Aufgaben-Design waren seit 2.0.0 einzelne Schriftfarben und Abstände falsch (zum Beispiel der Geschafft-Knopf mit dunkler Schrift). Jetzt wieder wie vorgesehen.

## 2.3.0 vom 2.10.2026
Aufgaben: kleine Schritte, Wenn-dann und Uhrzeit (nach Studien zu ADHS und Planung).
- Kleine Schritte: Jede Aufgabe lässt sich in bis zu 12 Schritte teilen. Jeder erledigte Schritt bringt 2 Punkte, die ganze Aufgabe weiterhin 10. Ein zurückgenommener oder gelöschter Schritt nimmt seine Punkte wieder weg.
- Wenn-dann: Zu jeder Aufgabe kann ein Auslöser stehen, zum Beispiel "Wenn nach dem Frühstück, dann Zahnarzt anrufen".
- Uhrzeit: Aufgaben mit Tag können eine Uhrzeit haben. Die Karte zeigt, wie lange es noch dauert oder wie lange die Aufgabe schon überfällig ist, und aktualisiert sich alle 30 Sekunden. Innerhalb eines Tages sortiert die Liste nach Uhrzeit.
- "Details" an jeder Aufgabe holt sie nach oben auf die große Karte, dort lassen sich Schritte, Wenn-dann und Uhrzeit ändern.
- Auf der Startseite Heute stehen Wenn-dann, Uhrzeit und der Stand der Schritte.
- Hinweis: Erinnerungen bei geschlossener App kann eine Web-App nicht zuverlässig schicken. Die Uhrzeit erinnert nur, solange die App offen ist.

## 2.2.1 vom 2.10.2026
Gegessen abhaken nimmt die Zutaten von der Einkaufsliste.
- Hakst du ein Essen auf Heute oder im Plan als "Gegessen" an, verschwinden die Zutaten dieses Gerichts aus der Einkaufsliste. Das Gericht steht dann unter "Gerichte der Woche" ohne Haken.
- Nimmst du den Haken bei "Gegessen" wieder weg, kommen die Zutaten zurück (außer du hattest das Gericht selbst abgewählt).
- Kommt dasselbe Gericht in der Woche mehrmals vor, entfallen die Zutaten für alle Termine.

## 2.2.0 vom 2.10.2026
Aufgaben mit klarem Kalendertag.
- Jede Aufgabe zeigt ihren Tag mit Wochentag und Datum, zum Beispiel "Morgen, Sa, 3. Okt".
- Neue Kalenderleiste mit den nächsten 7 Tagen. Die Zahl zeigt, wie viele Aufgaben an dem Tag offen sind. Ein Tipp auf einen Tag zeigt nur diesen Tag, "Alle" zeigt alles.
- Die Liste ist nach Tagen sortiert: Überfällig, Heute, Morgen, danach jeder Tag mit Datum, am Ende Irgendwann.
- Neue Aufgaben stehen von Anfang an auf Heute (oder auf dem gewählten Kalendertag). Unter dem Eingabefeld steht klar, für welchen Tag die Aufgabe gilt. "Anderes Datum" ist jetzt sichtbar, "Irgendwann" bleibt möglich.

## 2.1.0 vom 2.10.2026
Alles bringt jetzt Punkte, mit Level.
- Aufgabe erledigt: 10 Punkte. Mahlzeit als gegessen abhaken (heute): 2 Punkte. Einkauf: 1 Punkt je abgehakter Zutat, 20 Bonuspunkte für die komplette Liste. Geschenk-Schritt (bestellt, geliefert, verpackt): 5 Punkte. Freizeit-Idee gemacht: 10 Punkte. Rezept im Kochbuch: 2 Punkte.
- Je 100 Punkte ein neues Level. Auf der Startseite stehen die Punkte von heute und der Weg zum nächsten Level.
- Nimmst du einen Haken zurück, geht der Punkt wieder weg. Zurücksetzen der Einkaufsliste bringt nicht noch einmal Punkte.
- Tage mit Punkten zählen für die Serie.
- Schon vorhandene Haken (zum Beispiel erledigte Freizeit-Ideen) zählen als Startguthaben, aber nicht für heute.

## 2.0.0 vom 2.10.2026
Neues Design für die ganze App, gebaut für ruhiges Arbeiten mit ADHS.
- Neue Startseite "Heute": ein nächster Schritt mit großem Abhaken-Knopf, was heute gegessen wird und wie weit der Einkauf ist.
- Feste Leiste unten mit 5 Punkten statt 9 Reitern: Heute, Essen, Einkauf, Aufgaben, Mehr. Auswahl, Rezepte, Kochbuch, Kosten, Geschenke und Freizeit liegen unter Mehr, mit Zurück-Knopf.
- Das Belohnungs-Design gilt jetzt überall. Vier Stile zur Wahl unter Mehr, Aussehen: Standard, Punk, Rock, Gothic. Der Stil bleibt gespeichert.
- Einkauf: Fortschrittsbalken und eine kleine Meldung, wenn alles abgehakt ist.
- Größere Tippflächen (mindestens 44 Pixel), größere Kästchen zum Abhaken, kürzerer Seitenkopf.
- Wer Bewegung im System reduziert hat, bekommt keine Animationen.
- Alle Daten und Funktionen bleiben unverändert.

## 1.5.0 vom 2.10.2026
Neuer Reiter Aufgaben mit Tagesziel und Belohnungen.
- Aufgaben mit oder ohne Datum. Schnellwahl: Heute, Morgen, In 1 Woche, Irgendwann. Das Datum lässt sich später ändern oder entfernen.
- Oben steht immer der nächste Schritt (zuerst Überfälliges, dann Heute, dann der Rest). "Später" schiebt eine Aufgabe nach hinten.
- Tagesziel mit 3 Aufgaben, 10 Punkte je Aufgabe, Serie der letzten 7 Tage.
- Vier Stile zur Wahl: Standard, Punk, Rock, Gothic. Der Stil gilt nur im Reiter Aufgaben.
- Gelöschte oder abgehakte Aufgaben lassen sich sofort rückgängig machen.
- Alles bleibt auf diesem Gerät gespeichert, helle und dunkle Darstellung werden unterstützt.

## 1.4.1 vom 2.10.2026
Erneute Veröffentlichung, Inhalt wie 1.4.0 (nur die Versionsnummer ist neu).

## 1.4.0 vom 2.10.2026
Eigene Einträge in der Einkaufsliste werden automatisch einsortiert.
- Ein eigener Eintrag landet selbst in der passenden Abteilung, zum Beispiel Bananen bei Obst und Gemüse oder Zahnpasta bei Haushalt und Sonstiges.
- Neue Abteilungen: Getränke und Süßes, Backen, Gewürze und Öl, Haushalt und Sonstiges.
- Die Gruppe "Eigene Einträge" gibt es nicht mehr. Eigene Einträge behalten ihr ✕ zum Löschen.
- Auch Bastelmaterial aus dem Reiter Freizeit wird so einsortiert.

## 1.3.0 vom 2.10.2026
Neuer Reiter Freizeit mit Basteln und Unternehmungen.
- 26 Ideen für Kinder von etwa 4 bis 9 Jahren, passend zu Herbst und November (12 zum Basteln, 14 Unternehmungen).
- Ideen der Woche: Jeden Montag wechselt eine Auswahl von 5 Ideen, gemischt aus Basteln und Unternehmungen.
- Filter: Basteln, Unternehmungen, bei Regen, gemerkt, gemacht.
- Je Idee: Beschreibung, Material zum Besorgen, was meist schon da ist, Tipp, Notiz, als gemacht abhaken, merken.
- Das Material lässt sich mit einem Tipp auf die Einkaufsliste setzen und wieder entfernen.
- Eigene Ideen hinzufügen und löschen. Termine: Halloween, St. Martin, erster Advent.

## 1.2.0 vom 2.10.2026
Die Einkaufsliste ist nach Zutaten statt nach Gerichten sortiert.
- Gleiche Zutaten aus verschiedenen Gerichten werden zusammengerechnet (zum Beispiel Eier: 15).
- Sortierung nach Abteilung: Obst und Gemüse, Milch, Käse und Eier, Brot, Nudeln, Reis und Konserven, Kühlregal, Tiefkühl.
- Salz, Öl, Gewürze und Ähnliches stehen am Ende unter "Vorrat prüfen" und zählen nicht im Zähler.
- Nimmst du bei einem Gericht den Haken raus, passen sich Zutaten und Mengen an.
- Geschenke und eigene Einträge bleiben in eigenen Gruppen.

## 1.1.1 vom 2.10.2026
Einkauf: Die Gerichte der Woche stehen jetzt unter der Einkaufsliste.

## 1.1.0 vom 2.10.2026
Die Einkaufsliste richtet sich jetzt nach den Gerichten der Woche.
- Alle gewählten Wochengerichte sind angehakt, ihre Zutaten stehen in der Liste.
- Nimmst du bei einem Gericht den Haken raus, verschwinden seine Zutaten. Mit dem Haken kommen sie zurück. Neu: "Alle anhaken" und "Alle abwählen".
- Gerichte aus einem gewählten Auswahl-Plan kommen automatisch dazu.
- Die Gerichte stehen jetzt oben, die Einkaufsliste darunter. Die feste Grundliste enthält nur noch Frühstück und Snacks, damit nichts doppelt steht.

## 1.0.1 vom 2.10.2026
Fehlerkorrekturen nach einer Gesamtprüfung.
- Geschenke: Preise mit Tausenderpunkt (z. B. 1.299,00) werden jetzt richtig gelesen, negative Eingaben zählen nicht mehr.
- Einkaufsliste: Käse auf 800 g und Zwiebeln auf 4 erhöht, damit die Mengen zu den Rezepten passen.
- Einkaufsliste: Hinweis, dass die Grundliste die Gerichte der Woche schon enthält, damit Zutaten nicht doppelt gekauft werden.
- Rezepte: Parmesan und Gorgonzola sind jetzt als vegetarisch (ohne tierisches Lab) gekennzeichnet.
- Rezepte: Hinweistext nennt jetzt auch die Rezepte für 2 Personen. Linsen-Curry zeigt den Airfryer für das Naan.
- Plan: Der Tipp zum Nudelauflauf verschwindet, wenn Sonntag oder Montag geändert wurde.
- Kosten: Hinweis, dass die Schätzung nur für den ursprünglichen Plan Freitag bis Dienstag gilt.

## 1.0.0 vom 2.10.2026
Erster versionierter Stand.
- Plan Freitag bis Dienstag mit Rezepten, Notizen, Kochbuch mit Fotos
- Auswahl: 36 Pläne für 12 Termine (Di und Do, 6 Wochen), Di bis Do für 2 Personen
- Bearbeiten: jede Mahlzeit lässt sich ändern und zurücksetzen
- Einkauf: eigene Einträge, Gerichte der Woche an und abwählbar, Geschenke auf der Liste
- Geschenke: Ideen mit Person, Preis, Shop und Status (bestellt, geliefert, verpackt)
- Darstellung für 2 Herdplatten, Backofen und Airfryer
