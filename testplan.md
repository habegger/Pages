## Testplan template

| Version | Projektname | Autor | Status | Datum | Kommentar |
| --- | --- | --- | --- | --- | --- |
| 0.1 | Abstract Translator |
Sean Leichtle

Matthias Walther-Büel

Patrick Habegger

Marco Lichtsteiner

| in Bearbeitung | 19.09.2022 |   |

## 1\. Einführung

Die Nutzerinnen der Software JabRef sollen durch unsere Erweiterung bei jedem in nichtdeutscher und von Google-Translator übersetzbaren Sprache verfassten Eintrag der bibliographischen Daten die Möglichkeit erhalten, die Zusammenfassung (Abstract) in deutsche Sprache übersetzen zu lassen.

## 1.1 Zweck

Der Zweck des vorliegenden Dokuments ist es, Aufschluss über den Testplan der JabRef-Erweiterung “Abstract Translator” zu geben. Es listet alle identifizerten Aufgaben des Testens unserer Erweiterung auf, wie zu testende Merkmale, Vorgehensweise beim Testen und die jeweiligen Testfälle. Das Dokument selbst richtet sich hauptsächlich an interne Testteams. 

_(Wozu dient das Dokument und an wen richtet es sich (Kunde, Internes Testteam, …))_

## 1.2 Beziehung zu anderen Dokumenten

Die vorliegende Dokumentation ergänzt das Pflichtenheft (siehe [https://rb.gy/bnclhf)](https://rb.gy/bnclhf)) sowie die Technische Dokumentation (siehe [https://rb.gy/60fwsc](https://rb.gy/60fwsc)) für das Projekt “Abstract Translator: eine Erweiterung für JabRef”. Aus den im Pflichtenheft dokumentierten Anforderungen werden die unten erläuterten Testfälle abgeleitet.

_Hier kann auf andere Dokumente referenziert werden die für den Testplan relevant sind. Das kann zum Beispiel eine Anforderungsspezifikation oder ein Designdokument sein. Stellen sie sich vor, dass die Tests typischerweise von einem eigenen Testteam durchgeführt werden._

## 2\. Systemübersicht

Beim Abstract Translator handelt es sich um eine Erweiterung für das open source Literaturverwaltungsprogramm JabRef (vgl. [https://www.jabref.org](https://www.jabref.org/)). Das Ziel der Erweiterung ist es, das Abstract-Feld eines Aufsatzes von einer nichtdeutschen Sprache ins Deutsche zu übersetzen. Getestet werden v.a. die Komponeten des GUI's. 

_(Hier sollte eine kurze übersicht über das System geben werden, mit besonderem Fokus auf die zu testenden Komponenten.)_

## 3\. Merkmale

### 3.1 Zu testende Merkmale (Features / Funktionen)

#### 3.1.1 Funktionale Anforderungen

Welche spezifizierten Funktionalen Anforderungen werden getestet? Referenzieren sie auch mittels dem Identifier (z.B. /LF10/ ) im Pflichtenheft.

### 3.2 Nicht zu testende Merkmale (Features / Funktionen)

Welche Aspekte werden explizit nicht getestet?

## 4 Vorgehensweise

### 4.1 Komponenten und Integrationstests

Hier können sie angeben wie sie diese Tests durchführen möchten. Wir empfehlen wenn möglich die Komponenten mittels automatischen Unit Tests zu testen.

### 4.2 Funktionstest

Wie werden die funktionalen Anforderungen getestet? Beispielsweise können sie angeben, dass die Funktionalität via Graphischer Benutzeroberfläche getestet wird.

### 5 Hardware und Softwareanforderungen

Was gibt es für spezielle Hardware oder Softwareanforderungen um die Tests durchzuführen?

z.b. Internetzugriff, Account bei Google, spezielle Software, …

## 6 Testfälle

### 6.1 Modultests

Falls die Module durch automatisierte Unit Tests durchgeführt werden, können diese hier kurz (tabellarisch) aufgelistet werden.

<table style="background-color:rgb(242, 242, 242);border:1px solid rgb(55, 55, 55);">
    <tbody>
        <tr>
            <td style="border:1px solid rgb(55, 55, 55);padding:10px;">Name der Klasse</td>
            <td style="border:1px solid rgb(55, 55, 55);padding:10px;">Name des Testfalls</td>
        </tr>
    </tbody>
</table>

Ansonsten müssen die Testfälle hier detailliert aufgeführt werden.

##### **Testfall: /TM10/**

_Testziel:_

_Voraussetzung:_

_Eingabe:_

_Erwartete Ausgabe:_

_Abhängigkeiten:_

### 6.2 Funktionstests

Beschreiben sie für die spezifizierten Anforderungen wie sie diese Testen. Für jede Anforderung sollten sie mindestens einen Test schreiben, der das gewünschte Verhalten überprüfen.

##### **Testfall: /TF10/**

_Testziel:_

_Voraussetzung:_

_Eingabe:_

_Erwartete Ausgabe:_

_Abhängigkeiten:_