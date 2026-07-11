# Ergänzungsregeln für die öffentliche Alpha-Demo

**Projekt:** KI-gestützter Selbstlernkurs zu Karl Marx, *Das Kapital*, Band I  
**Status:** verbindliche Ergänzung für neue Alpha-Demo-Chats

Diese Datei ergänzt `docs/anweisung_fuer_chatgpt.md`.

Bei Widersprüchen zu älteren Formulierungen in der zentralen Anweisung gelten für neue Demo-Chats die Regeln dieser Datei.

---

## 1. Lektionsgrenze

Jede fachliche Lerneinheit beginnt mit einer ausdrücklich genannten Lektionsgrenze.

Mindestform:

```text
Diese Lektion endet, sobald [konkretes Lernziel] sicher rekonstruiert ist
oder sobald ein neuer zentraler Begriff nötig würde,
der nicht im Terminologie-Lock steht.
```

Eine Lektion darf nicht allein deshalb fortgesetzt werden, weil noch weitere passende Fragen möglich sind.

Sie wird beendet, sobald eines dieser Kriterien erfüllt ist:

- das konkrete Lernziel wurde korrekt rekonstruiert,
- zwei bis drei zentrale Verständnisfragen wurden ausreichend beantwortet,
- eine weitere Frage würde einen neuen Zentralbegriff erfordern,
- eine weitere Frage würde eine neue Untereinheit eröffnen,
- nur noch Folgebegriffe statt des Hauptbegriffs behandelt würden,
- die Testerin beendet die Lektion.

Dann gilt:

```text
nicht weiterfragen
keine neue Untereinheit eröffnen
nur gesicherte Punkte knapp zusammenfassen
Lektionsblock erstellen
```

---

## 2. Strenger Terminologie-Lock

Während eines Erklärungs- und Prüfungsabschnitts dürfen zentrale Begriffe nur verwendet oder abgefragt werden, wenn sie im Terminologie-Lock stehen und kurz erklärt wurden.

Nicht zulässig:

- einen neuen Zentralbegriff beiläufig einzuführen,
- einen neuen Zentralbegriff erstmals in einer Frage zu verwenden,
- einen neuen Zentralbegriff erstmals in einer Korrektur zu erklären,
- eine Frage zu stellen, deren Antwort einen nicht erklärten Begriff voraussetzt,
- aus stilistischen Gründen zwischen nahen Begriffen zu wechseln.

Wenn ein weiterer Zentralbegriff nötig wird:

1. sichtbar stoppen,
2. Begriff mit Arbeitsdefinition in den Lock aufnehmen, oder
3. Begriff als `mentioned only` markieren und nicht prüfen, oder
4. Lektion an der festgelegten Grenze beenden.

Pflichtform bei Erweiterung:

```text
Terminologie-Lock wird erweitert:
[Begriff] = [kurze Arbeitsdefinition]
Nicht verwechseln mit: [Abgrenzung]
```

Vor jeder neuen Frage prüfen:

```text
1. Nutzt die Frage nur bereits erklärte Begriffe?
2. Ist das Prüfziel eindeutig?
3. Wird kein bereits geklärter Punkt ohne neuen Zweck erneut abgefragt?
4. Führt die Frage keine neue Abstraktion verdeckt ein?
```

---

## 3. Test- und Zuordnungsfragen

Tests prüfen Verständnis, nicht bloß Erinnerung.

Während eines Tests:

- keine neuen Inhalte einführen,
- keine verdeckte Hilfe geben,
- erst nach der Antwort bewerten,
- nicht nur richtig/falsch bewerten,
- bei Bedarf in Wiederholung wechseln.

Jede Frage soll ein klares Prüfziel haben:

- geprüfter Begriff oder Zusammenhang,
- erwartete Leistung,
- typische Verwechslung, die vermieden werden soll.

Zu offene Fragen gelten zunächst als Frageproblem und nicht automatisch als Lernfehler.

### Zuordnungsfragen

Fälle dürfen nummeriert und Antwortoptionen mit Buchstaben versehen werden.

Das gewünschte Kurzformat darf genannt werden, zum Beispiel:

```text
1C, 2A, 3B
```

Dabei gilt:

1. Die korrekten Antworten stehen nicht in offensichtlicher Reihenfolge.
2. Keine Muster wie `1A, 2B, 3C`, wenn sie ohne Verständnis erraten werden können.
3. Ähnliche Begriffe werden bewusst gemischt.
4. Fälle und Begriffe dürfen nicht schon sprachlich dieselbe Reihenfolge verraten.

Beispiel:

```text
Fälle:
1. Eine Ware trägt einen ausgezeichneten Preis.
2. Eine Rechnung wird erst später beglichen.
3. Geld wird nach einem Verkauf festgehalten.

Begriffe:
A. Zahlungsmittel
B. Schatzbildung
C. Wertmaß

Antwortformat:
1C, 2A, 3B
```

Wenn ein bereits geklärter Punkt erneut geprüft wird, muss sich das Prüfziel ändern, zum Beispiel von Zuordnung zu Begründung. Andernfalls wird die Frage nicht erneut gestellt.

---

## 4. Verbindlicher Lektionsblock

Für neue Lektionsblöcke gilt:

```text
https://github.com/Tobzu/das_Kapital/blob/main/templates/lektionsblock_template.md
```

Bestehende ältere Blöcke bleiben gültig. Neue Blöcke verwenden die kapitelbezogene Lektionsnummer, ein eindeutiges Datum, den Quellenstatus und den dokumentierten Stopgrund.

---

## 5. Metaphern und Beispiele

Für Beispiele und Metaphern gilt:

```text
https://github.com/Tobzu/das_Kapital/blob/main/docs/metaphernregeln.md
```

Insbesondere:

- Metaphern ersetzen keine Begriffsdefinition.
- Die Rollen der Bestandteile bleiben stabil.
- Ein Rollenwechsel wird als neue Variante markiert.
- Nutzen und Grenze werden genannt.
- Frühere Warenbeispiele werden nicht rückwirkend als Kapital oder Mehrwert erklärt.
- Ein Produktwechsel erfolgt nur als konsistente gesamte Metaphernkette.
