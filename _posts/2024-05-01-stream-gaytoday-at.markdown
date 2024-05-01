---
layout: post
title: GayToday - Streaming
date: 2024-05-01
description: Der Dienst wurde mittels Icecast2, OpenWRT, busybox, DDNS, Raspberry Pi 3b, Mixxx und iziCast realisiert.
img: stream.gaytoday.at.png
fig-caption: https://Stream.GayToday.at
tags: [VereinsWesen, GayToday]
---
Der Dienst wurde mittels Icecast2, OpenWRT, busybox, DDNS, Raspberry Pi 3b, Mixxx und iziCast realisiert.
Die dauerhafte Bespielung mittels Playlisten sowie die automatisierten Uebergaben je nach Input sowie individuelle Intros waren eine entscheidende Frage bei der Konzeptionierung.

CI/CD wurden selbst entwickelt.

## Die Letzte Ueberpruefung
>... fand am 01. Mai 2024 statt.

* Die Seite selbst ist fertig und aktuell.
* Die Kontaktdaten wurden kontrolliert.
* Das Ergebnis der Delay-Tests ist zufriedenstellend.
* Es gibt noch ein Problem welches den automatischen Playlist-Start nach einem Stomausfall zeitweise untergraebt.
* Da manche von A1 vergebenen IPs von einem Backbone in Irland an der Weiterleitung nach Canada gehindert werden ist nicht staendig gewaehrleistet, dass die DDNS-IP-Updates zeitgerecht ankommen.
