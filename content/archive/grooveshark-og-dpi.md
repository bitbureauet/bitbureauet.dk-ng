+++
title = "Grooveshark-kendelse åbner for hårdhændet internetcensur "
description = "imported from wordpress"
tags = []
date = "2012-02-22"
+++

Mandag nedlagde Fogedretten på Frederiksberg [forbud overfor teleselskabet
'3'](http://3.dk/grooveshark ) mod at formidle adgang til hjemmesiden
[www.grooveshark.com](http://www.grooveshark.com/). '3' har valgt at
implementere Fogedrettens forbud ved hjælp af Deep Packet Inspection.
Grooveshark har i længere tid være hængt ud af organisationer som DPA, KODA og
RettighedsAlliancen som en ulovlig hjemmeside, da den ikke har forhandlet
aftaler på plads med danske rettighedshavere. Fordi det ikke lykkedes
RettighedsAlliancen at få Grooveshark i tale, vælger man istedet at gå efter
internetudbyderne. En dansk internetudbyder blev således trukket i retten for
at forsvare en hjemmeside, som opererer fra et andet land. Spørgsmålet er hvor
meget Rettighedsalliancen og KODA har gjort for at få Grooveshark i tale i
forhold til de danske interesser. For nyligt [besluttede Grooveshark
frivilligt at stoppe med at udbyde deres service i
Tyskland](http://venturebeat.com/2012/01/18/grooveshark-germany/) gennem
såkaldt geo-blokering, efter at forhandlinger med GEMA (den tyske udgave af
KODA) brød sammen. Det er altså lykkedes andre organisationer at få
Grooveshark i tale. Derfor virker det påfaldende at den eneste mulighed
rettighedshaverne i Danmark havde for at forsvare deres interesser var at
trække en tredjemand i fogedretten. **Det nationaliserede internet**
Internettet udfordrer den traditionelle ophavsrets infrastrukturer, især på
tværs af landegrænser. Hvor vi fra Danmark havde samme lige adgang til
Grooveshark som brugere i USA, opererer rettighedsorganisationerne stadig
inden for nationale grænser og kan ikke håndhæve danske kunstneres ophavsret
direkte i USA. Grooveshark-kendelsen betyder i princippet, at alle hjemmesider
med brugergenereret indhold skal lave aftaler med alle rettighedshavere i alle
lande, hvis de vil undgå at blive påvirket af kendelser som den i Fogedretten.
Der findes masser af store tjenester, som aldrig ville være blevet til noget
hvis de i udgangspunktet var tvunget til at have licensaftaler med alle
rettighedsorganisationenr i alle lande. Fx har Youtube endnu ikke nogen aftale
med KODA, og kan derfor, ligesom Grooveshark, hurtigt blive offer for
rettighedshavernes censurkrav. Det kræver blot at en gruppe rettighedshavere
går til Fogedretten. På sigt er vi nu på vej mod et nationaliseret internet,
hvor kun tjenester der har aftaler med danske rettighedshavere kan tilgås via
danske internetudbydere. Hvis denne tendens kommer til at gøre sig gældende i
resten af verden, vil vi hurtig se internettet blive delt op i en række
nationale 'splinter'-nets, hvor digital kommunikation på tværs af
traditionelle landegrænser besværliggøres. **Censur: Fra DNS- til DPI-
blokering** Hvordan adgangen til Grooveshark skulle blokeres fremgår ikke af
den [pressemeddelelse](http://www.domstol.dk/frederiksberg/nyheder/Pressemedde
lelser/Pages/Fogedforbudnedlagtoverforteleselskabet3.aspx), som Fogedretten på
Frederiksberg udsendte i forbindelse med kendelsen. Efter kendelserne overfor
Tele2 i 2006 om blokering af AllofMP3.com og 2008 af ThePirateBay.org, har det
været praksis i disse sager at pålægge en blokering i udbyderens DNS-server.
Blokering på DNS-niveau svarer til at fjerne Grooveshark fra
internetudbyderens telefonbog. Blokeringen har blandt it-folk været set som
[symbolsk og ineffektiv](https://bitbureauet.dk/2011/11/214/), og den har ikke
forhindet andre tjenester, som fx Google og CensurfriDNS.dk, i at udbyde DNS-
servere og således give adgang til de blokerede hjemmesider. I dag trådte '3's
blokering i kraft, men i stedet for at benytte sig af den traditionelle DNS-
blokering, har teleselskabet valgt at benytte sig af såkaldt [Deep Packet
Inspection](http://en.wikipedia.org/wiki/Deep_packet_inspection) (DPI). DPI er
et multi-funktionelt redskab, der gør det muligt at idenficere, prioritere og
blokere internetkommunikation. Tidligere er DPI anvendt til [blokering af
krypteret internettrafik i Iran](https://bitbureauet.dk/2012/02/iran-ssl-
blokering/) og til at sikre at medarbejdere i virksomheder ikke anvender
Facebook i arbejdstiden. I Kina[ anvendes DPI i så stor
stil](http://commnet.cse.usf.edu/documents/Matt-Great%20Firewall.pdf), at hvis
ordet 'Falun Gong' overhovedet indgår i din internettrafik, bliver
forbindelsen straks lukket. Ved hjælp af avancerede regler og filtre bliver
DPI også anvendt i stor stil hos mobildataleverandørere til at udbyde
differentierede services, sikre betaling for trafikforbrug og til at indsamle
viden om kundernes internetvaner. Ved at kigge i internettrafikken, kan '3'
derfor blokere adgangen til Grooveshark uden om DNS-niveau. Faktisk har '3'
også anvendt DPI-blokering af ThePirateBay.org, ved simpelthen at afbryde
internettrafikken uden at vise en meddelse om, at siden var lukket på grund af
fogedforbud. At anvende DPI til håndhævelse af påståede kænkelser af
ophavsretten er en eskalering af censurmidlerne på internettet. Hvor Danmark
tidligere, med brugen af DNS-blokering, placerede sig i gruppen af
internetcensurerende lande med Indien og Israel, placerer brugen af DPI-
blokering os sammen med lande som Kina og Iran, hvor censur og overvågning af
internettet anvendes dagligt til menneskerettighedskrænkelser. Når '3'
benytter sig af DPI-blokering betyder det, at brugerne ikke længere med meget
simple midler kan omgå blokeringen. At omgå en sådan blokering kræver
anvendelse af en krypteret internetforbindelse, fx ved hjælp af SSL-kryptering
eller ved hjælp af en VPN-forbindelse. På den lyse side kan man sige at det at
omgåelse af blokeringen nu bliver sværere, betyder at almindelige
internetbrugere vil opruste og blive endnu bedre til at beskytte deres
kommunikation på internettet. **Den eksisterende infrastruktur** At '3' har
valgt at benytte sig af DPI til blokeringen, kan bedst forklares med, at
selskabet allerede har bygget en infrastruktur op omkring total kontrol over
datatrafikken ved hjælp af DPI. Da '3' introducerede de første 3G-telefoner i
Danmark, kunne man tilkøbe forskellige pakker med indhold til sin
mobiltelefon. Istedet for at levere et standard internetprodukt, solgte
selskabet internet, som man sælger kabel-tv: i pakker. For at bruge Facebook
på mobilen skulle man fx tilkøbe den særlige Facebook-pakke. Efter
mellemkomsten af smartphones og mobilt bredbånd har markedet dog ændret sig,
og i stedet bruges DPI-teknologien på mobilmarkedet [til at prioritere
datatrafikken](http://go.radisys.com/rs/radisys/images/paper-dpi-optimizes-
mobile.pdf) for streaming af video i forhold til peer-to-peer kommunikation
samt til at håndtere trafikbetaling. Derfor har '3' allerede investeret i
udstyr fra firmaerne [Procera
Networks](http://eandt.theiet.org/magazine/2011/03/deep-packet-inspection.cfm)
og [Aptilio](http://www.prnewswire.com/news-releases/3-scandinavia-selects-
aptilo-networks-for-3g-and-lte-service-delivery-137473273.html). Med dette
udstyr kan '3' gøre sig til dommer over hvad de mener er den vigtigste, og
dermed hurtigste, internettrafik. På hvilket grundlag bliver denne beslutning
truffet? Er '3's eget Mobil-tv fx vigtigere end YouTube? Ved at bevæge sig ind
på markedet for differentierede internettilbud gør '3' sig dermed sårbare over
for at skulle censure internettet med metoder, som ellers kendes fra Egypten,
Syrien, Iran og Kina. Internetudbydere har høstet meget goodwill hos
internetgræsrødder ved ikke at blande sig i, hvad deres kunder brugte
internetforbindelserne til. Dette er et af de grundlæggende argumenter for, at
internetudbyderne ikke skal holdes ansvarlige for ophavsretskrænkelser: at de
ikke ønsker at være vidende om og derfor heller ikke er i stand til at ændre
på, hvordan deres kunder anvender internetforbindelserne. Dette princip har
'3' brudt ved at anvende udstyr, som i meget stor detalje kan logge, ændre og
blokere kundernes internettrafik. **Den tilfældige internetudbyder**
RettighedsAlliancens talsperson Maria Fredsenlund har [gentagne gange
understreget](http://www.b.dk/nationalt/fogedretten-traekker-stikket-paa-
grooveshark), at »det er helt tilfældigt, at det er Teleselskabet 3, vi har
kørt sagen mod«. Hvilke andre internetudbydere der har været i kikkerten og
hvordan '3' i sidste ende blev udvalgt, melder historien ikke noget om. Det er
ikke desto mindre påfaldende at en stor og prominenet virksomhed som Johan
Schlüter Advokatfirma, hvor RettighedsAlliancen holder til, ikke har haft
strategiske overvejelser om et så omkostningsfuldt foretagende som et søgsmål
mod en internetudbyder. Rettighedsalliancen gik tidligere, under navnet
AntiPiratGruppen, efter den lille internetudbyder Tele2 i AllofMP3- og
ThePirateBay-sagerne. I ThePirateBay-sagen støttede brancheforeningen
Telekommunikationsindustrien imidlertid Tele2, og på den måde lykkedes det at
tage sagen til Højesteret. '3' står derimod uden for
Telekommunikationsindustrien. Det er derudover ikke i internetudbydernes
interesse overhovedet at forsvare tredjeparter. For '3' er det et økonomisk
spørgsmål om, hvorvidt de vil tage en runde i Landsretten for at forsvare dels
deres kunders og en tredjeparts interresser. For udbydere vil det altid være
en økonomisk og ikke en juridisk afvejning, som ligger til grund for at
censurere indhold på internettet. Dette er imidlertid en ladeport for
potentielt at misbruge ophavsretten som censurmiddel. En [undersøgelse
foretaget i Holland viste](http://www.edri.org/edrigram/number2.19/takedown)
at 70% af udbyderne i landet på opfordring fjernede eller blokerede indhold,
uden at tage stilling til om indholdet rent faktisk krænkede nogens ophavsret.
[Google har ligeledes påpeget](http://pcworld.co.nz/pcworld/pcw.nsf/feature/93
FEDCEF6636CF90CC25757A0072B4B7) at 57% af klager virksomheden modtager over
ophavsretbeskyttet materiale er ugyldige. Når en internetudbyder bliver
stillet overfor valget om at forsvare en kunde eller tredjepart imod anklager
om ophavsretskrænkelse bliver det et spørgsmål om økonomi og ikke retfærdighed
hvorvidt udbyderen tager kampen. I den situation lægger de økonomiske byrder
forbundet med retssager op til at kunde eller tredjepart oftest vil trække det
korteste strå. **En principiel diskussion** Det er bydende nødvendigt med en
principiel diskussion om internetcensur i Danmark. Dette har der [allerede
været ønske om fra en bred vifte af
organisationer](http://www.b.dk/kommentarer/aabent-brev-om-internet-censur/).
I Bitbureauet mener vi det er nødvendigt udvide denne debat til også at
omfatte netværksneutralitet, da der, som vi nu kan se, findes tydelige overlap
mellem censur- og neutralitetsproblemet. Vi bør derudover finde en bedre
løsning på rettighedshavernes krav end at gøre det muligt at trække
uvedkommende virksomheder i fogedretten og dermed kontinuerligt udvide brugen
af censur, der har udlagt et skråplan for dansk internetpolitik siden det
først blev indført som middel.

