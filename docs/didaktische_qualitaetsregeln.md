# Didaktische Qualitätsregeln

**Projekt:** KI-gestützter Selbstlernkurs zu Karl Marx, *Das Kapital*, Band I  
**Status:** öffentliche Qualitätsregeln für Alpha-Lernchats  
**Geltung:** Kapitel 1 und spätere Kapitel, soweit passend  

---

## 1. Zweck

Diese Datei sammelt übertragbare didaktische Regeln, die den öffentlichen Alpha-Test stabiler machen sollen.

Sie enthält keine privaten Lernantworten und keine Rohlogs. Sie beschreibt nur allgemeine Regeln für bessere Lernchats.

Ziel:

- Begriffe nicht zu früh als verstanden behandeln,
- Terminologie stabil halten,
- Wiederholungen sinnvoll einsetzen,
- Tests von neuen Inhalten trennen,
- Beispiele und Metaphern kontrolliert verwenden,
- private Lernspuren aus dem öffentlichen Repository heraushalten.

---

## 2. Erwähnt ist nicht eingeführt

Ein Begriff gilt nicht als eingeführt, nur weil er in einer Erklärung vorkommt.

Ein Begriff zählt erst als eingeführt, wenn er:

```text
1. benannt wurde,
2. kurz definiert wurde,
3. im Argument verortet wurde,
4. an einem Beispiel oder einer Anwendung erklärt wurde,
5. von typischen Verwechslungen abgegrenzt wurde,
6. im Lektionsblock oder in einer Kapiteldatei dokumentiert wurde,
7. bei Bedarf gegen die Primärquelle geprüft wurde.
```

Mögliche Statuswerte:

```text
not introduced
mentioned only
partly introduced
introduced
needs repetition
stable enough
unstable
confused with another concept
pending source check
```

Für die Alpha reicht nicht aus, dass eine Definition einmal genannt wurde. Lernende sollen den Begriff in eigenen Worten anwenden und abgrenzen können.

---

## 3. Terminologie stabil halten

Zentrale Begriffe dürfen nicht frei mit ähnlichen Wörtern abgewechselt werden.

Regel:

```text
kanonischer Begriff zuerst
Hilfswort als Hilfswort markieren
Synonym nur nach ausdrücklicher Zuordnung
andere Begriffe nicht als Synonyme behandeln
```

Für Kapitel 1 besonders sensibel:

```text
Ware / nützliches Ding
Gebrauchswert / Wert
Tauschwert / Wert / Preis
konkrete Arbeit / abstrakte Arbeit
individuelle Arbeitszeit / gesellschaftlich notwendige Arbeitszeit
relative Wertform / Äquivalentform
allgemeine Wertform / allgemeines Äquivalent
Geldform / Geld als praktisches Tauschmittel
Warenfetischismus / moralischer Konsumvorwurf
```

Wenn ein Hilfswort benutzt wird, muss klar bleiben, ob es nur erklären soll oder ein Fachbegriff ist.

---

## 4. Beispiele und Rollen dürfen nicht driften

Didaktische Beispiele sind erlaubt, aber ihre Rollen müssen stabil bleiben.

Wenn ein Beispiel mit zwei Waren arbeitet, muss klar sein:

```text
Welche Ware wird erklärt?
Welche Ware drückt den Wert aus?
Welche Ware dient als Äquivalent?
Welche Rolle hat das Beispiel im Argument?
```

Eine Sache darf innerhalb desselben Beispiels nicht stillschweigend die Funktion wechseln.

Wenn ein Rollenwechsel nötig ist, muss eine neue Variante markiert werden:

```text
Variante A: Ware X drückt ihren Wert in Ware Y aus.
Variante B: Ware Y drückt ihren Wert in Ware X aus.
```

---

## 5. Lektionskopf verwenden

Jede fachliche Lerneinheit soll mit einem kurzen Lektionskopf beginnen.

Mindestform:

````markdown
## Lektion [Kapitelnummer].[Lektionsnummer] – [Arbeitstitel]

**Modus:** [neues Wissen / Wiederholung / Test / Review / Feedback]  
**Quelle:** [Kapitel, Abschnitt, ggf. genauer Primärquellenbezug]  
**Anschluss:** [woran die Einheit anschließt]

### Terminologie-Lock

Für diese Einheit benutzen wir stabil:

```text
[Begriff 1] = [kurze Arbeitsdefinition]
[Begriff 2] = [kurze Arbeitsdefinition]
```

Nicht verwechseln:

```text
[Begriff A] ≠ [Begriff B]
```
````

Der Terminologie-Lock darf nicht nur Begriffe aufzählen. Jeder neue Begriff braucht eine kurze Arbeitsdefinition.

---

## 6. Kapitelbezogene Lektionszählung

Lektionstitel sollen kapitelbezogen gezählt werden.

Richtig:

```text
Lektion 1.1 = erste fachliche Lektion aus Kapitel 1
Lektion 1.2 = zweite fachliche Lektion aus Kapitel 1
Lektion 2.1 = erste fachliche Lektion aus Kapitel 2
```

Nicht verwenden:

```text
Lektion 01
```

wenn damit eigentlich die erste Lektion eines Kapitels gemeint ist.

Für bestehende Alpha-Blöcke kann eine ältere technische Benennung vorkommen. Neue Dokumentation soll aber kapitelbezogen sein.

---

## 7. Wiederholung als eigener Modus

Wiederholung ist kein Scheitern.

In Wiederholung wechseln, wenn:

- ein Grundbegriff unsicher ist,
- ein Begriff nur erwähnt, aber nicht eingeführt wurde,
- eine typische Verwechslung sichtbar wird,
- eine Antwort geraten wirkt,
- neues Material sonst auf instabiler Grundlage aufbauen würde.

Wichtig:

```text
Kurze Aktivierung ≠ volle Wiederholung.
```

Wenn eine kurze Eingangssicherung zu einer längeren Klärung wird, muss der Modus ausdrücklich auf Wiederholung wechseln.

---

## 8. Falsche Wiederholung vermeiden

Wiederholung ist über mehrere Lektionen hinweg sinnvoll.

Innerhalb derselben Lektion darf ein bereits geklärter Punkt aber nicht erneut mit demselben Prüfziel gestellt werden, als sei er noch offen.

Regel:

```text
Wenn ein Punkt wiederholt wird, muss die Wiederholung als Brücke markiert werden.
Sie muss einen neuen Schritt vorbereiten.
```

Beispiel:

```text
Nicht: „Was ist Gebrauchswert?“ immer wieder ohne neuen Zweck.
Besser: „Wir nutzen Gebrauchswert jetzt als Brücke zur Unterscheidung von konkreter und abstrakter Arbeit.“
```

---

## 9. Tests prüfen Verständnis, nicht bloß Erinnerung

Während eines Tests gilt:

- keine neuen Fachbegriffe einführen,
- keine verdeckte Hilfe geben,
- Fehler nach Typ benennen,
- bei Unsicherheit Wiederholung auslösen,
- nicht nur richtig/falsch bewerten.

Mögliche Fehlerarten:

```text
Begriff nicht abrufbar
Begriff teilweise verstanden
Begriff mit anderem Begriff verwechselt
Beispiel passt nicht zur Rolle
Argumentkette bricht ab
heutige Einordnung wird als Marx-Original behandelt
```

---

## 10. Alltagswörter mit fachlicher Funktion erklären

Manche Wörter wirken alltäglich, bekommen im Lernkontext aber eine fachliche Funktion.

Für Kapitel 1 betrifft das besonders:

```text
Form
Ausdruck
Erscheinung
Substanz
Größe
abstrakt
relativ
Äquivalent
allgemein
Fetisch
```

Wenn ein solches Wort wichtig wird, muss ChatGPT klären:

```text
1. Was ist hier gemeint?
2. Welche Funktion hat das Wort im Argument?
3. Was darf daraus nicht geschlossen werden?
4. Ist es Fachbegriff, Hilfswort oder didaktische Vereinfachung?
```

---

## 11. Quelle, Erklärung und Einordnung trennen

Jede fachliche Antwort soll trennen zwischen:

```text
Marx im Original / textnahe Rekonstruktion
Argumentfunktion
didaktische Erklärung
Beispiel oder Metapher
heutige Einordnung
Unsicherheit
```

Eine heutige Einordnung darf nicht als Marx-Original formuliert werden.

Eine didaktische Vereinfachung darf nicht als vollständige Theorie ausgegeben werden.

---

## 12. Lektionsabschluss dokumentieren

Am Ende einer abgeschlossenen Einheit soll der Lektionsblock mindestens festhalten:

```text
bearbeitete Einheit
Modus
neu eingeführte Begriffe
nur erwähnte Begriffe
sicher verstanden
unsicher / offen
typische Verwechslungen
verwendete Beispiele / Metaphern
nächster sinnvoller Schritt
```

Zusätzliche Qualitätsprüfung:

```text
lesson header used: yes / no
terminology lock complete: yes / partly / no
new everyday words explained before use: yes / partly / no
glossary or Begriffsliste needs update: yes / no
```

---

## 13. Datenschutzregel

Private Lernspuren gehören nicht in das öffentliche Repository.

Nicht veröffentlichen:

- ausgefüllte Nutzerblöcke,
- konkrete Antworten der Testerin,
- persönliche Schwierigkeiten,
- private Notizen,
- fortlaufend gepflegte Alpha-Masterdateien,
- nicht freigegebene Rückmeldungen.

Öffentlich geeignet sind nur bereinigte, allgemeine Regeln, Templates und Auswertungen ohne private Inhalte.
