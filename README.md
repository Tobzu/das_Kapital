# Das Kapital – KI-gestützter Selbstlernkurs

Dieses Repository enthält öffentliche Projektmaterialien für einen strukturierten Selbstlernkurs zu Karl Marx, *Das Kapital*, Band I.

Der aktuelle Arbeitsstand ist eine kleine Alpha-Version zu:

```text
Kapitel 1 – Die Ware
```

Die Alpha-Version ist darauf ausgelegt, mit möglichst wenig Zusatzaufwand getestet zu werden. Die Testerin benötigt nur eine Datei:

```text
alpha_masterdatei_kapitel_01.md
```

Diese Datei wird in einem neuen Chat bei ChatGPT hochgeladen und steuert den Alpha-Test.

---

## Single Source of Truth

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

Die PDF wird im Repository nicht gespiegelt. Sie wird nur als externe Primärquelle referenziert.

Alle Lernmaterialien müssen unterscheiden zwischen:

1. Marx’ Originaltext,
2. didaktischer Erklärung,
3. heutiger Einordnung,
4. eigener Vereinfachung für den Lernprozess.

---

## Repository-Struktur

```text
README.md
LICENSE.md
NOTICE.md
alpha_masterdatei_kapitel_01.md
docs/
templates/
kapitel-01/
optional-scripts/
```

Wichtige Dateien:

| Datei | Zweck |
|---|---|
| `alpha_masterdatei_kapitel_01.md` | Upload-Datei für die Alpha-Testerin |
| `docs/anleitung_fuer_testerin.md` | menschlich lesbare Anleitung für die Testerin |
| `docs/anweisung_fuer_chatgpt.md` | operative Regeln für ChatGPT im Alpha-Test |
| `docs/ssot_und_quellenregeln.md` | Quellen- und Abgrenzungsregeln |
| `kapitel-01/kapitel_01_lernpfad.md` | Lernpfad für Kapitel 1 |
| `kapitel-01/kapitel_01_quellenanker.md` | Orientierungspunkte im Primärtext |
| `kapitel-01/kapitel_01_begriffe_und_fallstricke.md` | zentrale Begriffe und typische Fehler |
| `kapitel-01/kapitel_01_minitests.md` | kurze Verständnisfragen |
| `templates/` | Vorlagen für spätere Überarbeitung und Auswertung |

---

## Datenschutz und Alpha-Test

Die öffentlichen Dateien enthalten keine privaten Antworten der Testerin.

Private Lernspuren bleiben außerhalb des Repositorys. Dazu gehören insbesondere:

- ausgefüllte Nutzerblöcke,
- konkrete Antworten im Lernchat,
- persönliche Schwierigkeiten,
- private Notizen,
- nicht freigegebene Alpha-Rückmeldungen.

Öffentlich werden nur bereinigte, allgemeine Materialien und Templates geführt.

---

## Lizenz

Die eigenen Projektmaterialien stehen unter CC BY 4.0, soweit nichts anderes angegeben ist.

Die Lizenz gilt nicht für:

- den Originaltext von Karl Marx,
- MEW Band 23,
- die externe PDF,
- fremde Editionen, Scans oder Kommentarapparate,
- private Lernlogs oder Alpha-Antworten.

Details stehen in `LICENSE.md` und `NOTICE.md`.
