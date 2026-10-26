# Spezifikation des Terminplaners — Gliederung und Beispiele

Mitgearbeitet haben (GitHub-Benutzernamen, auch bei Einzelarbeit): @Pusher63

## 1. Ziel und Zweck des Systems

Die THM möchte ein System zur Planung und Vereinbarung von Sprechstunden- und Prüfungsterminen bereitstellen.

## 2. Benutzergruppen

### 2.1 Studierende

Studierende können verfügbare Termine einsehen und buchen.

### 2.2 Lehrende

Lehrende können Sprechstunden und Prüfungstermine anbieten.

### 2.3 Sekretariate

Sekretariate erhalten einen Überblick über die Termine.

## 3. Funktionale Anforderungen

### 3.1 Terminbuchung

Studierende können einen verfügbaren Sprechstundentermin auswählen und buchen.

### 3.2 Anmeldung

Die Anmeldung erfolgt über das Hochschulkonto.

### 3.3 Kalenderexport

Gebuchte Termine können als iCal-Datei heruntergeladen werden.

### 3.4 API für KI-Agenten

KI-Agenten können über eine API freie Termine abfragen und buchen. Nicht erlaubte Aktionen, beispielsweise das Absagen von Prüfungsterminen, werden verhindert.

## 4. Qualitätsanforderungen

Das System soll einfach zu bedienen sein, damit Studierende, Lehrende und Sekretariate es im Alltag tatsächlich nutzen.

## 5. Datenmodell

Ein Termin besitzt beispielsweise ein Datum, eine Uhrzeit, eine zugehörige Lehrperson und einen Buchungsstatus.

## 6. Schnittstellen

Das System verwendet das Hochschulkonto zur Anmeldung und stellt eine API für KI-Agenten bereit.

## 7. Abnahmekriterien

Ein Testfall prüft, ob ein Studierender nach der Anmeldung einen freien Sprechstundentermin buchen und anschließend als iCal-Datei herunterladen kann.
