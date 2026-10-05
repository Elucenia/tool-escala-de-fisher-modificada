<!-- ELUCENIA technical documentation · escala-de-fisher-modificada · de · no clinical/professional/rights approval -->

# Modifizierte Fisher-Skala

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/escala-de-fisher-modificada)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Befund im CT bei Aufnahme

`grau`

- `0` — 0 – Keine SAB und keine intraventrikuläre Blutung
- `1` — 1 – Dünne SAB (fokal oder diffus), ohne intraventrikuläre Blutung
- `2` — 2 – Intraventrikuläre Blutung ohne SAB oder mit dünner SAB (fokal oder diffus)
- `3` — 3 – Dicke SAB (fokal oder diffus), ohne intraventrikuläre Blutung
- `4` — 4 – Dicke SAB mit intraventrikulärer Blutung

## Fassung der Methode

Modifizierte Fisher-Skala — Frontera et al., 2006, Tabelle 1: fehlende, dünne oder dicke SAB und intraventrikuläre Blutung; Grade 0–4

## Dokumentierte Formel

Klassifiziert das Aufnahme-CT nach dem Vorhandensein und der Dicke des subarachnoidalen Blutes (SAB) und dem Vorhandensein einer intraventrikulären Blutung (IVH). Grad 0: keine SAB und keine IVH; Grad 1: dünne SAB ohne IVH; Grad 2: IVH bei fehlender oder dünner SAB; Grad 3: dicke SAB ohne IVH; Grad 4: dicke SAB mit IVH. Bei Frontera et al. (2006) ordneten die lokalen Untersucher das Blut anhand ihres Gesamteindrucks als dünn oder dick ein, ohne ausdrückliche Kriterien zur Dicke. Das Werkzeug erfasst den vom Untersucher gewählten Grad; es interpretiert keine Bilder.

## Grenzen und Population

CT-Einstufung, untersucht zur Vorhersage symptomatischer Vasospasmen nach Subarachnoidalblutung. Die eingesehene Studie umfasste Patienten aus den Placeboarmen von vier Studien. Sie liefert allein weder eine Vasospasmusdiagnose noch Vorhersage aller Endpunkte oder eine Behandlungsindikation.

## Referenzen

- [Frontera JA et al. Prediction of symptomatic vasospasm after subarachnoid hemorrhage: the modified Fisher scale. Neurosurgery, 2006.](https://doi.org/10.1227/01.NEU.0000218821.34014.1B)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
