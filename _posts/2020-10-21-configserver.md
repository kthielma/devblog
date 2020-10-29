---
layout: [post, post-xml]              # Pflichtfeld. Nicht ändern!
title:  "Welcher Config-Server passt zu meinem Projekt?"         # Pflichtfeld. Bitte einen Titel für den Blog Post angeben.
date:   2020-10-29 10:25              # Pflichtfeld. Format "YYYY-MM-DD HH:MM". Muss für Veröffentlichung in der Vergangenheit liegen. (Für Preview egal)
author: kaythielmann                  # Pflichtfeld. Es muss in der "authors.yml" einen Eintrag mit diesem Namen geben.
categories: [Architekturen]           # Pflichtfeld. Maximal eine der angegebenen Kategorien verwenden.
tags: [Java, AWS, Cloud, Springboot, Config-Server]         # Bitte auf Großschreibung achten.
---

Mit zunehmendem Alter einer Applikation ergeben sich immer wieder neue Optionen, wie diese konfigurierbar sein soll. 
Es ist nicht immer leicht schon zu Beginn eines Projekts abzusehen welche Einstellungen von außen konfigurierbar sein müssen und wie viele es am Ende werden.
Auch technische Limitierungen können einen in einem fortgeschrittenen Projekt noch unverhofft überraschen.
So ist es zum Beispiel uns in einem Projekt ergangen, welches bereits längere Zeit in der AWS-Cloud betrieben und stetig weiterentwickelt wird.
