+++
title = "Sådan omgår du dansk internetcensur"
description = "imported from wordpress"
tags = []
date = "2011-11-12"
+++

Domain Name System (DNS) er den måde din webbrowser finder vej på internettet.
Når du skriver en adresse på en hjemmeside i din browser (fx
www.bitbureauet.dk), er det DNS der oversætter adressen til det IP-nummer, som
er den fysiske adresse på den server, hvor hjemmesiden bliver hentet fra (i
dette eksempel 85.17.173.130). Normalt bruger din computer automatisk din
internetudbyders DNS-server til at oversætte hjemmesideadresser til IP-numre.
Danske internetudbydere pålægges imidlertid i stigende grad at censurere
internettet og forhindre internetbrugere i Danmark i at besøge bestemte
hjemmesider. Denne censur foregår normalt gennem DNS-blokering. DNS-blokering
kan dog nemt omgås ved i stedet at benytte ucensurerede DNS-serverer. Herunder
kan du se hvordan du indstiller din computer til at bruge andre DNS-servere
end dem din internetudbyder stiller til rådighed. Bitbureauet anbefaler at du
benytter censurfridns.dk's DNS-servere:

  * **89.233.43.71**
  * **91.239.100.100**
Eller du kan vælge på denne [liste over alternative DNS-
servere](http://en.cship.org/wiki/DNS).

## Eksempler på hvordan du indstiller din computer til at benytte andre DNS-
servere:

**Microsoft Windows**

  * Åben 'Kontrolpanel' fra Start-menuen
  * Klik på 'Netværk og internet'
  * Klik på 'Vis netværksstatus og -opgaver'
  * Klik på 'Rediger indstillinger for netværksskort'
  * Højreklik på den forbindelse du bruger nu, fx. 'Trådløs netværksforbindelse' og vælg 'Egenskaber'
  * Klik på 'TCP/IPv4 (internet Protocol Version 4) og tryk 'egenskaber'
  * Vælg 'Brug følgende DNS-serveraddresser' og indtast **89.233.43.71 **samt** 91.239.100.100**
_Gentag for hver type netværk du ønsker at benytte de nye DNS-servere på, fx.
trådløse og LAN forbindelser. Du skal måske genstarte din browser og forbinde
til det lokale netværk igen før ændringen træder i kraft._ **Apple Mac OS X**

  * Åben 'Systemindstillinger' via Apple-menuen
  * Klik på 'Netværk'
  * Vælg den forbindelse du bruger nu, fx. 'Airport'
  * Klik på 'Advanceret'
  * Klik på 'DNS'-tabben
  * Fjern de eksisterende DNS-servere med '-'-knappen
  * Tilføj **89.233.43.71** og **91.239.100.100** med '+'-knappen
  * Klik på 'OK'
_Gentag for hver type netværk du ønsker at benytte de nye DNS-servere på, fx.
trådløse og LAN forbindelser. Du skal måske genstarte din browser og forbinde
til det lokale netværk igen før ændringen træder i kraft._ **Ubuntu Linux**

  * Klik på netværksindikatoren (hvor du normal kan vælge trådløse netværk, mm.) i statuslinjen øverst til højre på skrivebordet
  * Klik på 'Edit Connections'
  * Vælg den aktive internetforbindelse du bruger nu, fx 'Wired Connection 1'
  * Klik på 'Edit'
  * Klik på 'IPv4 Settings'
  * I menuen 'Methods' vælger du 'Automatic (DHCP) addresses only'
  * I feltet 'DNS servers' indtaster du **89.233.43.71, 91.239.100.100**
  * Klik på 'Save'
_Gentag for hvert netværk du ønsker at benytte de nye DNS-servere på, fx.
forskellige trådløse og kablede netværk. Du skal m__åske genstarte din browser
og forbinde til det lokale netværk igen før ændringen træder i kraft._ Hvis du
ønsker mere information om hvordan forskellige former for internetcensur
virker og hvordan de omgås, anbefaler Bitbureauet den gratis e-bog [How To
Bypass Internet Censorship](http://howtobypassinternetcensorship.org/).

