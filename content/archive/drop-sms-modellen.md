+++
title = "Drop SMS-modellen"
description = "imported from wordpress"
tags = []
date = "2012-06-21"
+++

[caption id="attachment_460" align="aligncenter"
width="576"][![](https://bitbureauet.dk/wp-content/uploads/2012/06/4612626924_
5f15e295d6_z.jpg)](https://secure.flickr.com/photos/swanksalot/4612626924/)
Billede: swanksalot CC-BY-SA[/caption] Der gik under 24-timer fra, at der blev
slukket for respiratoren til [brevmodellen](http://brevmodellen.dk/), og til
den vendte tilbage som en zombie fra graven; grimmere, dummere og farligere
end før. Således genopstod brevmodellen som "SMS-modellen" i gårsdagens og
dagens Politiken:

> _Når en eller anden bevæger sig ind på en ulovlig side via enten smartphone
eller smartpad, modtager vedkommende straks en sms i stil med dem man får, når
man lander i udlandet og oplyses om prisen på tale, sms og andre tjenester._
_"Det skal være sådan, at når et sim-kort bliver parret med en ulovlig
tjeneste, så ryger der automatisk sms ud, som selvfølgelig bare er en
oplysning - ikke noget, man kan bruge i en retssag. Det er jo ikke meningen,
at oplysningerne skal gemmes", siger John Kristensen fra Gramex. _Citat:
[Politiken, 21 juni
2012](http://politiken.dk/tjek/digitalt/internet/ECE1663607/nyt-forslag-send-
smser-til-netpirater/)

For at illusterere den model, som John Kristensen foreslår, har jeg tegnet et
diagram ud fra hans beskrivelse ovenfor. [![](https://bitbureauet.dk/wp-
content/uploads/2012/06/smsmodel1.png)](https://bitbureauet.dk/wp-
content/uploads/2012/06/smsmodel1.png)

  1. Telefonen downloader en liste over forbudte sites til telefonens sim-kort.
  2. Før en hjemmeside besøges, checker sim-kortet på listen om siden er forbudt. Hvis den er forbudt, kommer der en sms-besked frem på skærmen som informerer brugeren om dette.
  3. Brugeren får adgang til hjemmesiden.
Her er der tale om fantasi-teknologi, i stil med vægtløshedsbælter, flyvende
biler og tidsmaskiner. Selv hvis denne teknologi var mulig, er der allerede
store retsikkerheds- og informationsfrihedsmæssige problemer i den skitserede
model. Hvem bestemmer og hvordan skal det afgøres, om en hjemmeside skal
erklæres forbudt og havner på listen? Hvilke krav er der til dokumentation?
Hvordan kommer man af listen igen, hvis man er kommet på den uden grund? Hvis
vi skal se på hvad det rent teknisk kræver at implementere SMS-modellen, så
har jeg tegnet endnu et diagram som kan forklare hvilke skidt der er
nødvendige.

[![](https://bitbureauet.dk/wp-
content/uploads/2012/06/smsmodel2.png)](https://bitbureauet.dk/wp-
content/uploads/2012/06/smsmodel2.png)

  1. Teleudbyderen downloader en liste over forbudte sites til en database.
  2. Brugeren forsøger at hente en forbudt hjemmeside.
  3. Forespørgslen bliver samlet sammen med teleudbyderens øvrige trafik.
  4. Udbyderen sender trafikken igennem en filteringsmekanisme, kaldet DPI.
  5. Brugeren får adgang til hjemmesiden.
  6. DPI-mekanismen undersøger om trafikken indholder særlige kendetegn der kan indikere at brugeren har forsøgt at opnå forbindelse til en forbudt hjemmeside.
  7. Hvis det er tilfældet, giver DPI-mekanismen besked til en anden maskine herom.
  8. Kundeoplysninger hentes frem fra kundekartoteket, herunder telefonnummer.
  9. Telefon-netværket instrueres om at sende en SMS-besked.
  10. SMS'en sendes igennem netværket og frem til brugerens mobiltelefon.
Det er i grove træk, hvad der skal til for at sådan en løsning skal kunne
lykkedes. Og det er kun den tekniske udvikling og store økonomiske byrde,
rettighedshavere pålægger teleselskaberne, og som ender på forbrugernes
telefonregning. Dertil kommer en endnu mere vigtig diskussion omkring
propotionalitet, detaljeovervågning af internettrafikken, respekt for
privatlivets fred, [domme fra EU-domstolen som _specifikt forhindrer_ denne
slags tiltag](http://www.edri.org/sabam_netlog_win), og så om
internetudbyderne rent faktisk kan forvalte det ansvar, de har til ikke at
benytte et sådan maskineri til [andre
formål](https://bitbureauet.dk/2012/02/grooveshark-og-dpi/ "Grooveshark-
kendelse åbner for hårdhændet internetcensur" ). Så drop SMS-modellen og
venligst også alle andre uigennemtænkte forslag som tilsynelandene har fået
kreativ assistance fra manuskriptforfatterne bag CSI og dårlige Hollywoodfilm.

