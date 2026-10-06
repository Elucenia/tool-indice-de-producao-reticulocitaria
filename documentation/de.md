<!-- ELUCENIA technical documentation · indice-de-producao-reticulocitaria · de · no clinical/professional/rights approval -->

# Korrigierte Retikulozyten und Retikulozytenproduktionsindex

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/indice-de-producao-reticulocitaria)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Retikulozyten

`ret`

% · Bereich: 0–50

### Hämatokrit

`ht`

% · Bereich: 5–65

## Fassung der Methode

Hillman 1969: Hämatokrit 45%; Reifung 1/1,5/2/2,5 bei lokalen Bereichen 40/30/20

## Dokumentierte Formel

Korrigierte Retikulozyten (%) = Retikulozyten (%) × Hämatokrit ÷ 45.

RPI = Korrigierte Retikulozyten ÷ Reifungsfaktor, Faktor ist Blutreifungszeit in Tagen: 1,0 (Hämatokrit ≥ 40%); 1,5 (30–39%); 2,0 (20–29%); 2,5 (\< 20%).

## Grenzen und Population

Die Retikulozytenkorrektur hängt von der mit Anämieschwere verbundenen Änderung der Reifungszeit ab. Die Originalstudie nutzte durch Phlebotomie erzeugte Anämie bei gesunden Personen; vereinfachte lokale Bereiche wurden durch das Abstract nicht bestätigt. Der Index allein bestimmt nicht bei jeder Krankheit Ursache oder Knochenmarkreserve.

## Referenzen

- [Hillman RS. Characteristics of marrow production and reticulocyte maturation in normal man in response to anemia. J Clin Invest, 1969.](https://doi.org/10.1172/JCI106001)

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

## Dokumentierte Ergebnisse

Die folgenden Angaben bewahren die Ausgaben der Methode für synthetische Beispiele. Sie stellen keine unabhängige klinische Validierung dar.

### 1

IPR < 2: hypoproliferative Anämie (unzureichende Produktion)

| Ergebnisdetails | |
| --- | --- |
| Nach Hämatokrit korrigierte Retikulozyten | 3,3% |
| Verwendeter Reifungsfaktor | 2,0 Tag(e) |


### 2

IPR ≥ 3: adäquate Knochenmarkantwort (Hämolyse oder akuter Verlust)

| Ergebnisdetails | |
| --- | --- |
| Nach Hämatokrit korrigierte Retikulozyten | 6,7% |
| Verwendeter Reifungsfaktor | 1,5 Tag(e) |


### 3

IPR < 2: hypoproliferative Anämie (unzureichende Produktion)

| Ergebnisdetails | |
| --- | --- |
| Nach Hämatokrit korrigierte Retikulozyten | 3,0% |
| Verwendeter Reifungsfaktor | 2,0 Tag(e) |


### 4

IPR zwischen 2 und 3: grenzwertige Antwort

| Ergebnisdetails | |
| --- | --- |
| Nach Hämatokrit korrigierte Retikulozyten | 4,0% |
| Verwendeter Reifungsfaktor | 2,0 Tag(e) |

