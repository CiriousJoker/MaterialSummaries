# Lizenz - v1.0.0

Eine Zusammenfassung als Google Doc hat Vor- und Nachteile.

**Die Vorteile sollten klar sein, deshalb hier die Nachteile:**

-   Geht der Google Account des Maintainers verloren oder er hat keine Lust mehr, stirbt das Projekt
-   Es könnte mehrere inoffizielle Versionen geben und am Ende blickt keiner mehr durch
-   Wenn keiner die offizielle Version findet, gibt es keine Verbesserungsvorschläge

**Um diese Probleme zu lösen, sind hier die "Lizenzbestimmungen":**

Im Grunde kann natürlich jeder tun und lassen, was er will, aber wenn sich alle an das hier halten, sollte am Ende ein vernünftiges Ergebnis dabei herauskommen:

## Änderungsvorschläge

Änderungen, die Sourcecode (z.B. LaTeX) beinhalten, sollten zusammen mit dem LaTeX Code veröffentlicht werden (z.B. als Kommentar), um eine einfache Änderungen/Einarbeitung zu ermöglichen.

**Die aktuellen LaTeX-Files sind unter diesem Link erreichbar:**<br>
https://www.overleaf.com/read/vxcxbdmmtxyw

## Download-Paket

Wird ein Dokument zum Download angeboten, muss das .zip Archiv folgendes beinhalten:

-   **.pdf** Datei, um das Drucken zu vereinfachen
-   **.docx** Datei, damit der "Sourcecode” nicht verloren gehen kann
-   **README.txt** nach diesem Schema: [README-TEMPLATE](README-TEMPLATE.md)

Download Pakete sollten vom Maintainer erstellt werden, um Einheitlichkeit zu gewährleisten.

## Forks

Forks sind inoffizielle Versionen mit Änderungen ggü. der offiziellen Versio.

Wird eine Version veröffentlicht, die sich von der offiziellen Version unterscheidet, sollte das kenntlich gemacht werden. Am Besten geht das durch Änderung der Versionsnummer: 1.0.0 -> 1.0.0-Autor. Die Versionsnummer selbst sollte dabei gleich gelassen werden, damit man erkennt, auf welcher offiziellen Version das Dokument basiert. Die Änderungen sollten außerdem kurz erklärt werden (im Dokument, .zip Archiv oder README).

**Wichtig:** Ein Link zur offiziellen Version sollte weiterhin vorhanden sein, kann aber durch den eigenen Link ergänzt werden.

## Die offizielle Version

Für den Fall, dass die offizielle Version nicht mehr maintained wird (d.h. Änderungsvorschläge/Pull-Requests bleiben für länger als einen Monat unbeantwortet), kann jemand, der sich berufen fühlt, seine eigene Version als offizielle Version deklarieren, sollte sich aber auch entsprechend darum kümmern. In diesem Fall bitte daran denken, die Versionsnummer zu erhöhen (1.x.x -> 2.x.x) und den Wechsel kurz zu erklären (sowohl im README.txt als auch im Repository als [neuen Issue](../../issues/new)).
