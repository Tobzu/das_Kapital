# Anleitung für die Alpha-Testerin

**Projekt:** KI-gestützter Selbstlernkurs zu Karl Marx, *Das Kapital*, Band I  
**Alpha-Version:** v3.0-alpha.1  
**Testumfang:** Kapitel 1 – Die Ware  
**Ziel:** Prüfen, ob eine Person ohne Vorkenntnisse mit dem Material sinnvoll lernen kann.

---

## 1. Kurzfassung

Du brauchst für den Alpha-Test nur **eine Datei**:

```text
alpha_masterdatei_kapitel_01.md
```

Diese Datei lädst du in einem neuen Chat bei ChatGPT hoch. In dieser Alpha-Datei stehen alle weiteren Anweisungen, darunter:

- wie du den Chat startest,
- welche Primärquelle verwendet wird,
- wie GitHub zu behandeln ist,
- wie mit Quellen umzugehen ist,
- wie deine Schwierigkeiten und Missverständnisse dokumentiert werden,
- was am Ende einer Lektion gespeichert werden soll.

Du musst keine GitHub-Dateien selbst öffnen, herunterladen oder bearbeiten.

---

## 2. Worum es geht

Du testest eine frühe Alpha-Version eines Lernsystems zu Karl Marx’ *Das Kapital*, Band I.

Es geht nicht darum, ob du „gut“ oder „schlecht“ bist. Getestet wird vor allem:

- ob die Erklärungen verständlich sind,
- ob die Reihenfolge sinnvoll ist,
- wo Missverständnisse entstehen,
- wo Begriffe zu schnell eingeführt werden,
- welche Stellen zu schwer, zu knapp oder unklar sind.

Deine Schwierigkeiten, Unsicherheiten und Missverständnisse sind ausdrücklich wichtig. Bitte teile sie mit, soweit du dich damit wohlfühlst. Gerade diese Rückmeldungen helfen, das Lernsystem zu verbessern.

---

## 3. Verbindliche Textgrundlage

Die verbindliche Primärquelle dieses Alpha-Projekts ist:

Karl Marx / Friedrich Engels: Werke, Band 23.  
Karl Marx: *Das Kapital. Kritik der politischen Ökonomie. Erster Band.*  
Buch I: Der Produktionsprozeß des Kapitals.  
Dietz Verlag Berlin, 1962.

Projektintern wird diese Quelle als `mew_band23.pdf` bezeichnet.

Der externe Quellenlink lautet:

```text
https://marx-wirklich-studieren.net/wp-content/uploads/2012/11/mew_band23.pdf
```

Die PDF wird nicht im Repository gespeichert. Sie wird nur als externe Primärquelle verwendet.

Alle weiteren Quellen- und GitHub-Hinweise stehen in der Alpha-Masterdatei. Für den Test musst du diese Regeln nicht separat aus dem Repository zusammensuchen.

---

## 4. Was du brauchst

Du brauchst:

- einen ChatGPT-Zugang,
- die Datei `alpha_masterdatei_kapitel_01.md`.

Du brauchst keine Vorkenntnisse zu Marx, Ökonomie oder Philosophie.

Du brauchst keinen eigenen GitHub-Zugang.

---

## 5. Was privat bleibt

Deine persönlichen Antworten, Schwierigkeiten, Notizen und Lernspuren bleiben privat.

Du musst sie nicht an den Projektverantwortlichen schicken.

Du sollst aber Schwierigkeiten und Missverständnisse mitteilen, soweit du das möchtest. Besonders hilfreich sind Rückmeldungen wie:

- eine Erklärung war unverständlich,
- ein Begriff war verwirrend,
- eine Frage war zu offen oder zu schwer,
- ChatGPT hat offensichtlich falsch reagiert,
- ein besonders großer Fehler im Ablauf ist passiert,
- eine Stelle war besonders hilfreich.

Private Antworten musst du nur mitschicken, wenn du das ausdrücklich möchtest.

---

## 6. Wie du eine Sitzung startest

1. Öffne einen neuen Chat in ChatGPT.
2. Lade die Datei `alpha_masterdatei_kapitel_01.md` hoch.
3. Schreibe:

```text
Bitte führe die Alpha-Datei aus und beginne mit Kapitel 1.
```

4. Antworte möglichst in eigenen Worten.

Du musst nicht versuchen, „wissenschaftlich“ zu klingen. Alltagssprache ist erwünscht, solange klar wird, was du verstanden hast.

---

## 7. Wie du antworten sollst

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

## 8. Schwierigkeiten und Missverständnisse dokumentieren

Bitte halte während oder nach der Sitzung kurz fest, was schwierig war.

Die Alpha-Masterdatei enthält dafür einen eigenen Bereich. Nutze dort zum Beispiel diesen Block:

```md
## Schwierigkeiten / Missverständnisse

- Schwierige Stelle:
- Was war unklar?
- Welche Erklärung hat geholfen?
- Was ist noch offen?
- Soll diese Rückmeldung weitergegeben werden? ja / nein
```

Beispiel:

```md
- Schwierige Stelle: Wertform
- Was war unklar? Ich wusste nicht, welche Ware den Wert ausdrückt und welche als Äquivalent dient.
- Welche Erklärung hat geholfen? Das Beispiel 1 Pullover = 2 Wollknäuel.
- Was ist noch offen? Warum daraus später Geld entsteht.
- Soll diese Rückmeldung weitergegeben werden? ja
```

---

## 9. Was am Ende einer Lektion passieren soll

Am Ende einer Lektion soll ChatGPT einen kurzen Ergebnisblock erzeugen.

Dieser Block sollte enthalten:

- bearbeiteter Abschnitt,
- zentrale Begriffe,
- was sicher verstanden wurde,
- was unsicher blieb,
- Schwierigkeiten oder Missverständnisse,
- nächster Schritt.

Diesen Block kannst du in die Alpha-Masterdatei kopieren, sofern ChatGPT dich dazu auffordert.

Du musst nichts veröffentlichen.

---

## 10. Wann du abbrechen oder pausieren solltest

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

## 11. Was du optional zurückmelden kannst

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

## 12. Grundregel für die Alpha

Der Test ist erfolgreich, wenn sichtbar wird, was funktioniert und was nicht funktioniert.

Missverständnisse, Lücken und Schwierigkeiten sind kein Scheitern. Sie sind der wichtigste Teil des Alpha-Tests.
