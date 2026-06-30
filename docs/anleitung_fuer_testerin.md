# Anleitung für die Alpha-Testerin

**Projekt:** KI-gestützter Selbstlernkurs zu Karl Marx, *Das Kapital*, Band I  
**Alpha-Version:** v3.0-alpha.1  
**Testumfang:** Kapitel 1 – Die Ware  
**Ziel:** Prüfen, ob eine Person ohne Vorkenntnisse mit dem Material sinnvoll lernen kann.

---

## 1. Worum es geht

Du testest eine frühe Alpha-Version eines Lernsystems zu Karl Marx’ *Das Kapital*, Band I.

Es geht nicht darum, ob du „gut“ oder „schlecht“ bist. Getestet wird vor allem:

- ob die Erklärungen verständlich sind,
- ob die Reihenfolge sinnvoll ist,
- wo Missverständnisse entstehen,
- wo Begriffe zu schnell eingeführt werden,
- welche Stellen zu schwer, zu knapp oder unklar sind.

Deine Schwierigkeiten, Unsicherheiten und Missverständnisse sind deshalb ausdrücklich wichtig. Bitte teile sie mit, soweit du dich damit wohlfühlst. Gerade diese Rückmeldungen helfen, das Lernsystem zu verbessern.

---

## 2. Verbindliche Textgrundlage

Die verbindliche Primärquelle dieses Alpha-Projekts ist:

Karl Marx / Friedrich Engels: Werke, Band 23.  
Karl Marx: *Das Kapital. Kritik der politischen Ökonomie. Erster Band.*  
Buch I: Der Produktionsprozeß des Kapitals.  
Dietz Verlag Berlin, 1962.

Projektintern wird diese Quelle als `mew_band23.pdf` bezeichnet.

Die PDF wird nicht im Repository gespeichert. Sie wird nur als externe Primärquelle verwendet. Alle Erklärungen sollen zwischen drei Ebenen unterscheiden:

1. Marx im Original,
2. didaktische Erklärung,
3. heutige Einordnung.

---

## 3. Was du brauchst

Du brauchst:

- einen ChatGPT-Zugang,
- die Alpha-Masterdatei für Kapitel 1,
- den Link zur externen PDF oder Zugriff auf die PDF,
- optional: das öffentliche GitHub-Repository mit den Kursmaterialien.

Du brauchst keine Vorkenntnisse zu Marx, Ökonomie oder Philosophie.

---

## 4. Was privat bleibt

Deine persönlichen Antworten, Schwierigkeiten, Notizen und Lernspuren bleiben privat.

Du musst sie nicht an den Projektverantwortlichen schicken.

Du kannst aber freiwillig Rückmeldungen weitergeben, zum Beispiel wenn:

- eine Erklärung unverständlich war,
- ein Begriff verwirrend war,
- eine Frage zu offen oder zu schwer war,
- ChatGPT offensichtlich falsch reagiert hat,
- ein besonders großer Fehler im Ablauf passiert ist,
- du eine Stelle besonders hilfreich fandest.

Bitte teile besonders Schwierigkeiten und Missverständnisse mit, soweit du das möchtest. Diese Rückmeldungen sind für die Alpha wichtiger als perfekte Antworten.

---

## 5. Wie du eine Sitzung startest

1. Öffne einen neuen Chat in ChatGPT.
2. Füge den Startprompt aus der Alpha-Masterdatei ein.
3. Falls die Alpha-Masterdatei hochgeladen werden soll, lade sie in den Chat hoch.
4. Weise ChatGPT an, mit Kapitel 1 zu beginnen.
5. Antworte möglichst in eigenen Worten.

Du musst nicht versuchen, „wissenschaftlich“ zu klingen. Alltagssprache ist erwünscht, solange klar wird, was du verstanden hast.

---

## 6. Wie du antworten sollst

Antworte ehrlich und möglichst konkret.

Gute Antworten können zum Beispiel so aussehen:

```text
Ich glaube, Marx meint damit, dass ...
```

```text
Ich verstehe den Unterschied zwischen Gebrauchswert und Wert noch nicht.
```

```text
Das Beispiel mit dem Pullover hilft mir, aber der Begriff abstrakte Arbeit ist noch unklar.
```

```text
Ich kann die Frage nicht beantworten.
```

Auch „Ich weiß es nicht“ ist eine gültige Antwort. Unsicherheit soll sichtbar bleiben, nicht versteckt werden.

---

## 7. Schwierigkeiten und Missverständnisse dokumentieren

Bitte halte während oder nach der Sitzung kurz fest, was schwierig war.

Nutze dafür in deiner privaten Alpha-Datei einen Block wie diesen:

```md
## Schwierigkeiten / Missverständnisse

- Schwierige Stelle:
- Was war unklar?
- Welche Erklärung hat geholfen?
- Was ist noch offen?
- Soll diese Rückmeldung weitergegeben werden? ja / nein
```

Beispiele:

```md
- Schwierige Stelle: Wertform
- Was war unklar? Ich wusste nicht, welche Ware den Wert ausdrückt und welche als Äquivalent dient.
- Welche Erklärung hat geholfen? Das Beispiel 1 Pullover = 2 Wollknäuel.
- Was ist noch offen? Warum daraus später Geld entsteht.
- Soll diese Rückmeldung weitergegeben werden? ja
```

```md
- Schwierige Stelle: abstrakte Arbeit
- Was war unklar? Ich habe abstrakte Arbeit zuerst als jede beliebige Arbeit verstanden.
- Welche Erklärung hat geholfen? Die Abgrenzung zu konkreter Arbeit.
- Was ist noch offen? Wie genau Arbeit gesellschaftlich vergleichbar wird.
- Soll diese Rückmeldung weitergegeben werden? ja
```

---

## 8. Was am Ende einer Lektion passieren soll

Am Ende einer Lektion soll ChatGPT einen kurzen Ergebnisblock erzeugen.

Dieser Block sollte enthalten:

- bearbeiteter Abschnitt,
- zentrale Begriffe,
- was sicher verstanden wurde,
- was unsicher blieb,
- Schwierigkeiten oder Missverständnisse,
- nächster Schritt.

Diesen Block kannst du in deine private Alpha-Datei kopieren.

Du musst nichts veröffentlichen.

---

## 9. Wann du abbrechen oder pausieren solltest

Du kannst jederzeit pausieren oder abbrechen.

Sinnvolle Abbruchpunkte sind:

- du bist müde,
- du verstehst mehrere Begriffe nacheinander nicht,
- die Sitzung wird zu lang,
- ChatGPT wiederholt sich nur noch,
- du merkst, dass du eher rätst als verstehst.

Dann schreibe einfach:

```text
Bitte die Lektion hier beenden und einen Ergebnisblock erstellen.
```

---

## 10. Was du optional zurückmelden kannst

Wenn du Rückmeldung geben möchtest, reichen kurze Punkte.

Besonders hilfreich sind:

```md
## Alpha-Feedback

- Was war verständlich?
- Was war unverständlich?
- Welche Begriffe waren schwierig?
- Welche Frage war schlecht gestellt?
- Wo hat ChatGPT geholfen?
- Wo hat ChatGPT eher verwirrt?
- Gab es einen größeren Fehler?
- Möchtest du deine privaten Antworten mitschicken? ja / nein
```

Private Antworten musst du nur mitschicken, wenn du das ausdrücklich möchtest.

---

## 11. Grundregel für die Alpha

Der Test ist erfolgreich, wenn sichtbar wird, was funktioniert und was nicht funktioniert.

Missverständnisse, Lücken und Schwierigkeiten sind kein Scheitern. Sie sind der wichtigste Teil des Alpha-Tests.
