---
layout: post
title: GayToday - Streaming
date: 2026-09-10 14:00:00 +0200
description: Der Dienst wurde mittels Icecast2, OpenWRT, BusyBox, DDNS, RaspberryPi, Mixxx und iziCast realisiert.
img: stream.gaytoday.at.png
fig-caption: https://Stream.GayToday.at
tags: [VereinsWesen, GayToday]
---

Eine eigene Streaming-Infrastruktur fuer automatisiertes Musikprogramm und Live-Uebertragungen – umgesetzt mit Raspberry Pi, OpenWrt und Icecast.

Das Projekt verbindet playlistbasierte Wiedergabe mit Live-Einspeisungen aus Studio und mobilen Anwendungen. Im Mittelpunkt stehen die kontinuierliche Bespielung und die Uebergabe zwischen unterschiedlichen Audioquellen.

Die technische Basis bildet ein Raspberry Pi mit OpenWrt und Icecast2. IceS uebernimmt die Wiedergabe der Playlisten; fuer Live-Einspeisungen kommen Mixxx und iziCast zum Einsatz. Die Erreichbarkeit ueber eine wechselnde oeffentliche IP-Adresse wird mittels Dynamic DNS organisiert.

Fuer die verschluesselte Wiedergabe ist NGINX als Reverse Proxy vorgeschaltet. Er stellt den HTTPS-Zugang bereit und leitet die Anfragen an Icecast weiter.

CI/CD wurden selbst entwickelt.

> Technologien: Raspberry Pi, OpenWrt, BusyBox, Icecast2, IceS, NGINX, ACME, Dynamic DNS, Mixxx und iziCast.

## Weiterentwicklung – August 2026

* HTTPS-Zugang und Zertifikatskonfiguration ueberarbeitet.
* Automatische Zertifikatserneuerung mittels ACME eingerichtet.
* Wiedergabe im Player nach der Zertifikatskorrektur erfolgreich bestaetigt.

## Stand vom 01. Mai 2024

* Die Seite selbst ist fertig und aktuell.
* Die Kontaktdaten wurden kontrolliert.
* Das Ergebnis der Delay-Tests ist zufriedenstellend.
* Es gibt noch ein Problem welches den automatischen Playlist-Start nach einem Stromausfall zeitweise untergraebt.
* Da manche von A1 vergebenen IPs von einem Backbone in Irland an der Weiterleitung nach Canada gehindert werden ist nicht staendig gewaehrleistet, dass die DDNS-IP-Updates zeitgerecht ankommen.
