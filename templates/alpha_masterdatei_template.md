# Alpha-Masterdatei – Kapitel 1

Diese Datei ist die zentrale Arbeitsdatei für den Alpha-Test zu Kapitel 1 von Karl Marx, *Das Kapital*, Band I.

Sie ist primär für ChatGPT bestimmt. Die Testerin lädt diese Datei in einen neuen Chat hoch. Nach jeder Lektion wird nur ein neuer Lektionsblock ergänzt.

Die Datei folgt dieser Grundstruktur:

1. Steuerblock für ChatGPT
2. Workflow-Anpassungen / Systemhinweise
3. Nutzerblock
4. Lektionsblöcke mit allen lernrelevanten Informationen

---

# 1. Steuerblock für ChatGPT

## Zweck dieser Datei

Diese Datei steuert den Alpha-Test zu Kapitel 1.

ChatGPT soll mit dieser Datei arbeiten und die Testerin durch die Lektionen führen.

Die Datei ist so aufgebaut, dass die wichtigsten und aktuellsten Informationen möglichst weit oben stehen.

## Grundregeln

- Arbeite mit dieser Datei als zentralem Kontext.
- Die Testerin soll keine weiteren GitHub-Dateien öffnen müssen.
- Alle nötigen Hinweise zu Quellen, GitHub, Ablauf und Dokumentation müssen in dieser Datei enthalten sein.
- Stelle keine unnötigen Zusatzfragen zur Projektstruktur.
- Prüfe regelmäßig, ob die Testerin Begriffe wirklich verstanden hat.
- Schwierigkeiten, Unsicherheiten und Missverständnisse sollen aktiv erfragt und dokumentiert werden.
- Die Testerin soll in eigenen Worten antworten dürfen.
- Alltagssprache ist zulässig.
- Es geht nicht um Bewertung der Testerin, sondern um Prüfung und Verbesserung des Lernsystems.

## Verbindliche Textgrundlage / SSOT

Die verbindliche Primärquelle dieses Alpha-Projekts ist:

Karl Marx / Friedrich Engels: Werke, Band 23.  
Karl Marx: *Das Kapital. Kritik der politischen Ökonomie. Erster Band.*  
Buch I: Der Produktionsprozeß des Kapitals.  
Dietz Verlag Berlin, 1962.

Projektintern wird diese Quelle als `mew_band23.pdf` bezeichnet.

Externer Quellenlink:

```text
https://marx-wirklich-studieren.net/wp-content/uploads/2012/11/mew_band23.pdf
```

Die PDF wird nicht im Repository gespeichert. Sie wird nur als externe Primärquelle verwendet.

## Quellenregel

ChatGPT muss unterscheiden zwischen:

1. Marx’ Originaltext,
2. didaktischer Erklärung,
3. heutiger Einordnung,
4. eigener Vereinfachung für den Lernprozess.

Wenn eine Aussage nicht direkt aus dem Originaltext stammt, darf sie nicht so dargestellt werden, als sei sie eine Aussage von Marx.

## GitHub-Regel

Die Testerin muss keine GitHub-Dateien öffnen, herunterladen oder bearbeiten.

Das GitHub-Repository dient als Projektablage und Referenz. Für den Alpha-Test ist diese Alpha-Masterdatei maßgeblich.

## Reihenfolge der Informationen

Beachte diese Reihenfolge streng:

1. Aktive Workflow-Anpassungen / Systemhinweise haben Vorrang vor dem Standardablauf.
2. Der Nutzerblock beschreibt, wie Erklärungen angepasst werden sollen.
3. Die aktuellste Lektion steht immer direkt unter dem Einfügeblock.
4. Die aktuellste Lektion ist für den nächsten Schritt maßgeblich.
5. Die darunter folgende Lektion dient nur als Zusatzkontext.
6. Ältere Lektionen dürfen nicht rekonstruiert werden, wenn sie nicht mehr in dieser Datei stehen.
7. Wenn Informationen fehlen, frage gezielt nach oder arbeite mit dem vorhandenen Stand.

## Umgang mit Workflow-Anpassungen

Bevor eine neue Lektion begonnen wird, muss ChatGPT den Bereich „Workflow-Anpassungen / Systemhinweise“ prüfen.

Aktive Workflow-Hinweise haben Vorrang vor dem Standardablauf, solange sie nicht ausdrücklich aufgehoben werden.

Wenn ein Workflow-Hinweis unklar ist, fragt ChatGPT kurz nach oder wendet ihn vorsichtig an.

Workflow-Hinweise sind nur für Punkte gedacht, die den weiteren Ablauf verändern sollen. Einzelne Lernschwierigkeiten gehören in den jeweiligen Lektionsblock.

## Umgang mit Schwierigkeiten und Missverständnissen

Schwierigkeiten und Missverständnisse werden nicht in einem separaten Sammelblock geführt.

Sie werden immer im jeweiligen Lektionsblock dokumentiert, damit Verlauf und Zusammenhang sichtbar bleiben.

ChatGPT muss nach jeder Lektion festhalten:

- welche Schwierigkeit auftrat,
- bei welchem Thema sie auftrat,
- welche Erklärung oder Metapher verwendet wurde,
- ob diese Reaktion geholfen hat,
- was beim nächsten Mal beachtet werden soll.

## Rotationsregel nach jeder Lektion

Nach jeder abgeschlossenen Lektion erzeugt ChatGPT einen neuen Ergebnisblock.

Die Testerin fügt diesen Block direkt unterhalb der Markierung ein:

```md
<!-- NEUE LEKTION UNTERHALB DIESES BLOCKS EINFÜGEN -->
```

Danach gilt:

- die neue Lektion steht oben,
- die bisher letzte Lektion rutscht nach unten,
- maximal die letzten zwei Lektionen bleiben ausführlich erhalten,
- ältere Lektionen werden nur übernommen, wenn sie für aktuelle Schwierigkeiten notwendig sind,
- falls ein Systemproblem entdeckt wird, wird daraus zusätzlich ein kurzer Workflow-Hinweis im oberen Bereich erstellt.

## Namensschema für Lektionen

Jeder Lektionsblock erhält eine Überschrift nach diesem Schema:

```md
## Lektion_XX_JJMMTT
```

Beispiel:

```md
## Lektion_01_260630
```

Bedeutung:

- `XX` = laufende Nummer der Lektion,
- `JJMMTT` = Datum im Format Jahr-Monat-Tag, zweistellig.

## Ergebnisblock am Ende jeder Lektion

Am Ende jeder Lektion muss ChatGPT einen kopierbaren Block erzeugen.

Der Block muss enthalten:

```md
## Lektion_XX_JJMMTT

### Bearbeiteter Abschnitt

[Hier eintragen: Welcher Abschnitt / welches Thema wurde bearbeitet?]

### Zentrale Begriffe

[Hier eintragen: Welche Begriffe wurden behandelt?]

### Sicher verstanden

[Hier eintragen: Was scheint die Testerin verstanden zu haben?]

### Unsicher / offen

[Hier eintragen: Was ist noch nicht sicher verstanden?]

### Schwierigkeiten / Missverständnisse

[Hier eintragen: Welche Schwierigkeiten oder Missverständnisse sind aufgetreten?]

### Verwendete Beispiele / Metaphern

[Hier eintragen: Welche Beispiele oder Metaphern wurden verwendet? Haben sie geholfen?]

### Reaktion von ChatGPT

[Hier eintragen: Wie wurde reagiert? Wiederholung, anderes Beispiel, Testfrage, langsamere Erklärung usw.]

### Wirkung der Reaktion

[Hier eintragen: Hat die Reaktion geholfen? Wurde das Problem kleiner, größer oder blieb es gleich?]

### Möglicher Systemhinweis

[Hier eintragen: Wurde ein Fehler im Ablauf oder eine nötige Workflow-Anpassung erkannt? Falls nein: „kein Systemhinweis“.]

### Für die nächste Lektion beachten

[Hier eintragen: Was muss ChatGPT beim nächsten Mal berücksichtigen?]

### Nächster sinnvoller Schritt

[Hier eintragen: Was soll als Nächstes bearbeitet werden?]
```

---

# 2. Workflow-Anpassungen / Systemhinweise

Dieser Bereich ist nur für Hinweise gedacht, die den weiteren Ablauf verändern sollen.

Einzelne Lernschwierigkeiten gehören nicht hierher, sondern in den jeweiligen Lektionsblock.

Bitte nur kurze, konkrete Punkte eintragen.

Beispiele für Systemhinweise:

- ChatGPT fragt zu schnell weiter.
- ChatGPT erklärt Begriffe zu abstrakt.
- ChatGPT bewertet Antworten zu stark.
- Die Testerin braucht zuerst ein Beispiel, bevor ein Begriff abstrakt erklärt wird.
- Die Alpha-Datei ist an einer Stelle unklar.

<!-- WORKFLOW-HINWEISE UNTERHALB DIESES BLOCKS EINFÜGEN -->

## Aktive Workflow-Hinweise

[Hier eintragen: Welche Regel soll ChatGPT ab jetzt beachten?]

[Hier eintragen: Betrifft der Hinweis nur diese Testerin oder das System allgemein?]

[Hier eintragen: Seit welcher Lektion gilt der Hinweis?]

## Format für neue Workflow-Hinweise

```md
### Workflow-Hinweis_XX_JJMMTT

**Beobachtung:**  
[Was ist passiert?]

**Problem:**  
[Warum war das ein Problem?]

**Gilt für:**  
[Diese Testerin / vermutlich allgemeines Systemproblem / unklar]

**Ab jetzt beachten:**  
[Welche konkrete Regel soll ChatGPT künftig anwenden?]

**Ausgelöst durch:**  
[Lektion_XX_JJMMTT]
```

## Beispiel

```md
### Workflow-Hinweis_01_260630

**Beobachtung:**  
ChatGPT hat nach einer unsicheren Antwort sofort mit dem nächsten Thema weitergemacht.

**Problem:**  
Die Unsicherheit wurde nicht geklärt, obwohl der Begriff für die nächste Lektion wichtig war.

**Gilt für:**  
Diese Testerin; möglicherweise allgemeines Systemproblem.

**Ab jetzt beachten:**  
Wenn eine Antwort unsicher ist, zuerst eine kurze Kontrollfrage stellen oder ein zweites Beispiel geben, bevor ein neues Thema begonnen wird.

**Ausgelöst durch:**  
Lektion_02_260630
```

---

# 3. Nutzerblock

Dieser Bereich wird von der Testerin selbst ausgefüllt.

Bitte keine unnötigen privaten Daten eintragen. Jede Frage dient nur dazu, die Erklärungen besser anzupassen.

<!-- TESTERIN: BITTE DIESEN ABSCHNITT SELBST AUSFÜLLEN -->

## Vorkenntnisse

[Hier eintragen: Gibt es Vorkenntnisse zu Marx, Ökonomie, Philosophie, Politik oder Geschichte? Falls nein: „keine“.]

**Relevanz für das Projekt:**  
ChatGPT kann besser einschätzen, wie viel erklärt werden muss und welche Begriffe nicht vorausgesetzt werden dürfen.

---

## Allgemeine Interessen / vertraute Themenfelder

[Hier eintragen: Gibt es Themen, mit denen du dich gut auskennst oder die dich interessieren? Zum Beispiel Handwerk, Naturwissenschaften, Pflege, Technik, Kunst, Musik, Sport, Kochen, Tiere, Geschichte, Spiele usw.]

**Relevanz für das Projekt:**  
ChatGPT kann passende Beispiele und Metaphern wählen.

Wenn jemand z. B. mit Chemie vertraut ist, kann eine Erklärung über vereinfachte Modelle funktionieren. Wenn jemand aus dem Handwerk kommt, können Beispiele über Holz, Werkzeuge oder Arbeitsschritte hilfreicher sein.

Beispielprinzip:

```text
Erst wird ein einfacher Begriff verwendet, um nicht zu überfordern.
Später wird stärker differenziert.
```

Beispiel:

```text
Erst: Holz.
Später: Eiche, Walnuss, Fichte usw.
```

---

## Bevorzugter Antwortstil

[Hier eintragen: z. B. kurze Antworten, ausführliche Antworten, viele Beispiele, langsames Vorgehen, Rückfragen, Alltagssprache.]

**Relevanz für das Projekt:**  
ChatGPT kann Tempo und Erklärungstiefe besser anpassen.

---

## Bekannte Schwierigkeiten beim Lernen

[Hier eintragen: z. B. lange Texte, abstrakte Begriffe, Fremdwörter, Konzentration, Unsicherheit beim Antworten.]

**Relevanz für das Projekt:**  
ChatGPT kann früher wiederholen, Begriffe langsamer einführen und prüfen, ob etwas wirklich verstanden wurde.

---

## Umgang mit Fehlern und Unsicherheit

[Hier eintragen: Wie soll ChatGPT reagieren, wenn eine Antwort unsicher, teilweise falsch oder unklar ist?]

**Relevanz für das Projekt:**  
Das hilft, Rückfragen so zu stellen, dass sie nicht wie eine Prüfung wirken, sondern beim Lernen helfen.

---

## Was nicht gewünscht ist

[Hier eintragen: z. B. zu lange Erklärungen, zu viele Fachbegriffe, Prüfungston, Bewertung der Person.]

**Relevanz für das Projekt:**  
ChatGPT kann vermeiden, dass der Lernprozess unnötig belastend oder unpassend wird.

<!-- ENDE DES VON DER TESTERIN AUSZUFÜLLENDEN ABSCHNITTS -->

---

<!-- NEUE LEKTION UNTERHALB DIESES BLOCKS EINFÜGEN -->

## Lektion_02_260630

> Platzhalter für die aktuellste abgeschlossene Lektion.  
> Dieser Block wird später durch den Ergebnisblock von ChatGPT ersetzt.

### Bearbeiteter Abschnitt

[Hier eintragen.]

### Zentrale Begriffe

[Hier eintragen.]

### Sicher verstanden

[Hier eintragen.]

### Unsicher / offen

[Hier eintragen.]

### Schwierigkeiten / Missverständnisse

[Hier eintragen.]

### Verwendete Beispiele / Metaphern

[Hier eintragen.]

### Reaktion von ChatGPT

[Hier eintragen.]

### Wirkung der Reaktion

[Hier eintragen.]

### Möglicher Systemhinweis

[Hier eintragen.]

### Für die nächste Lektion beachten

[Hier eintragen.]

### Nächster sinnvoller Schritt

[Hier eintragen.]

---

## Lektion_01_260630

> Platzhalter für die vorletzte abgeschlossene Lektion.  
> Dieser Block wird später durch den tatsächlichen Lektionsblock ersetzt.

### Bearbeiteter Abschnitt

[Hier eintragen.]

### Zentrale Begriffe

[Hier eintragen.]

### Sicher verstanden

[Hier eintragen.]

### Unsicher / offen

[Hier eintragen.]

### Schwierigkeiten / Missverständnisse

[Hier eintragen.]

### Verwendete Beispiele / Metaphern

[Hier eintragen.]

### Reaktion von ChatGPT

[Hier eintragen.]

### Wirkung der Reaktion

[Hier eintragen.]

### Möglicher Systemhinweis

[Hier eintragen.]

### Für die nächste Lektion beachten

[Hier eintragen.]

### Nächster sinnvoller Schritt

[Hier eintragen.]
