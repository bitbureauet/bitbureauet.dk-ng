+++
title = "Kryptologi for journalister og andre"
description = "imported from wordpress"
tags = []
date = "2013-11-28"
+++

I kølvandet på NSA-afsløringerne har flere spørgsmål presset sig på for
journaliststanden: Kan vi være sikre på, at vores kilder har ordentlig
kildebeskyttelse i en virkelighed, hvor snart set enhver bevægelse på
internettet gemmes af USAs og andre nationers efterretningstjenester? Og selv
ved forsikringer om, at man intet har at frygte hvis man intet har at skjule,
bør man da give afkald på information som ret beset ikke vedkommer nogen andre
end en selv? Disse spørgsmål er vigtige at få afklaret, for hvad _kan_
kryptologien egentlig hjælpe os med? Og hvor kommer den til kort? Navnlig det
sidste spørgsmål er relevant, for selv små fodfejl kan ende med at ødelægge
den ellers private kommunikationskanal.

## Kryptologi 101

Kryptologi er videnskaben at kode en besked på en måde så en eventuel aflytter
ikke vil kunne lære noget af at lytte med — at have _sikker kommunikation_
over en _usikker kanal_. Det er en gammel videnskab, som historisk har været
brugt af hærførere til at kunne kommunikere til deres soldater hvad det næste
»træk« skulle være, men også mere nutidigt til at varetage sikker
kreditkorthandel, NemID, VPN-løsninger og meget andet. Det bliver også brugt
til helt almindelig sikker kommunikation, hvor man af den ene eller anden
grund vil sikre sig at ingen kan lytte med. Når Alice skal kommunikere privat
med Bob skal de blive enige om to ting:

  1. Hvilken kryptografisk algoritme, der kommunikeres med. Kryptologi er ikke en statisk ting, man kan gøre brug af for at sikre sit privatliv, det er en aktiv forskningsgren i matematikken, hvor forskere hele tiden søger at angribe hinandens
  2. En kryptografisk nøgle til algoritmen. Denne nøgle skal være privat mellem Alice og Bob, og er det eneste, der behøver at være hemmeligt i hele konstruktionen (dvs. man kan antage at ens modstander ved hvilken algoritme, man bruger til at kryptere — dette kaldes [Kerchoffs princip](http://en.wikipedia.org/wiki/Kerckhoffs's_principle))

## Hvem vil man beskytte sig imod?

Før man begynder at sætte sin sikkerhed op skal man afveje hvilken modstander,
man er parat til at skulle beskytte sig imod; dette kaldes at opstille en
_trusselsmodel_. Selvom tanken om, at end ikke NSA skal kunne komme til ens
data er besnærende, men kan ende med at blive alt for besværlig at have med at
gøre; hvis man skal holde sit data sikkert fra en modstander som NSA bør man
nok helt lade være med at slutte den til internettet! Journalister på danske
aviser er antagelig ikke under samme pres som fx Glenn Greenwald og Laura
Poitras, så samme foranstaltninger som dem bliver næppe relevante — men det er
rart at vide, at det faktisk _kan_ lade sig gøre.

## Hvad kan NSA når det kommer til stykket?

Det er vigtigt at betragte alle led i kæden når man vil sikre sin
kommunikation, for selv hvis man bruger kryptologi, som end ikke NSA kan bryde
(det findes!), så rækker det ligevidt hvis NSA har fjernadgang til din
computer mens du krypterer. Dette kaldes en _side-channel_. Forskellen mellem
angreb på matematikken bag kryptologien og en side channel er, at kryptologien
historisk set har krævet astronomisk regnekraft for at kunne bryde »med vold«.
Side channel-angreb er gratis i regnekraft, men de kræver noget forarbejde.
Enten placerer NSA en trojansk hest på folks computere, eller også har de en
bagdør til noget software, som folk stoler på. Hvis NSA skal knække kryptering
i en setting, hvor side channels ikke er en mulig vej, er de nødt til enten at
prøve alle mulige nøgler (_brute force_) eller kende til en ikke-offentlig
matematisk »smutvej« til at komme frem til kildeteksten udfra det krypterede,
_kryptoanalyse_. Den første mulighed anses for umulig, selv for NSA, hvis man
anvender moderne kryptologi, mens den anden giver lidt mere anledning til
diskussion. Kryptoanalyse foregår både offentligt i akademia, men også privat
hos efterretningstjenesterne.

## Teknologier

Der er forskellige teknologier, når man skal br

### PGP

Man kan lave nøgler med pseudonymer. Behøver ikke sende ting over mail.

### Tor

Brug det til noget legitimt! Lav en læktjeneste.

### Full-disk encryption

Hvem vedligeholder TrueCrypt?

### Cryptocat

## Kryptologiens akilleshæl: Nøglestyring

Hvorfor trykker Politiken ikke fingerprints? bit.ly-adresser. Overvej
strategi.

## Hvad kan danske medier gøre fremadrettet?

