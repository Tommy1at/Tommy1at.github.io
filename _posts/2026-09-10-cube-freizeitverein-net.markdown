---
layout: post
title: Roundcube - Webmail und Dashboard
date: 2026-09-10 16:00:00 +0200
description: Eine individuell erweiterte Webmail-Oberflaeche mit eigenem Dashboard und domainbezogener Gestaltung.
img:
fig-caption: https://cube.freizeitverein.net
tags:
- SoftwareEntwicklung
- VereinsWesen
---

Eine individuell angepasste Webmail-Umgebung auf Basis von Roundcube. Das Projekt verbindet die Verwaltung mehrerer E-Mail-Konten mit einer eigenen Uebersicht und einer abgestimmten Benutzeroberflaeche.

Der eigene Skin `adn-rc-skin` und das Plugin `adn_dashboard` bilden den gestalterischen und funktionalen Schwerpunkt. Zur Weiterentwicklung gehoeren Kontowechsel, Anzeigen fuer ungelesene Nachrichten sowie die Einbindung von Kalendern und Kontakten.

Die Gestaltung beruecksichtigt die jeweils ausgewaehlte Domain. Damit sollen Dashboard und Anmeldung die passende visuelle Zuordnung erhalten.

> Technologien: Roundcube, PHP, JavaScript, HTML, CSS, CalDAV, CardDAV.

## Weiterentwicklung – September 2026

* Dashboard kompakter gestaltet und dessen Skalierung angepasst.
* Uebersicht und Aktualisieren-Schaltflaeche neu angeordnet; die abschliessende Ausrichtung wurde bestaetigt.
* Die domainabhaengige Logo-Zuordnung fuer die Anmeldung weiterbearbeitet.
* Kontowechsel und Nachrichtenzaehler bleiben Teil der laufenden Funktionspruefung; nach wiederholtem Wechsel wurden noch abweichende Anzeigen gemeldet.

## Stand von Ende August / Anfang September 2026

* `adn-rc-skin` wurde als Bezeichnung fuer den eigenen Skin festgelegt.
* Dashboard-, Kontowechsel- und Kalenderkomponenten wurden technisch ueberprueft.
* Nach einer CalDAV-Korrektur wurde die Funktion zunaechst bestaetigt.
* Weitere Rueckmeldungen betrafen den Uebersicht-Button und die Zuordnung der Kontoanzeigen. Ein vollstaendig abgeschlossener Funktionsstand ist damit noch nicht dokumentiert.
