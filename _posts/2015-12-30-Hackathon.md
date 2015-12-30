---
layout: post
title: Hackathon
---

Har nu deltagit på två hackathons hållna på/av [Plug vxo](http://www.plugvxo.se/sv). Första helgen var vi två team.
Mittteam valde att bygga en webbapp med skoldata hämtat från excel och nersparat i [Parse](https://parse.com/) som
vår Angularjs frontend kommunicerade direkt med. Användare kunde autentisera sig genom Facebook med Oauth och lämna
betyg på olika skolrelaterade punkter. Ett projekt som tyvärr haltade lite på mållinjen men ändå utforskade
lite intressanta tekniker.

Det andra teamet använde sig av Arduino för att göra ett secret knock, krypteringslås där en knackning med rätt
timing triggade en rails app att skicka ut en kryptarad fråga som knackaren förväntades att svara på. En liten 
servomotor öppnade vid korrekt svar låset. Ett projekt som var väldigt roligt att se och som kändes väldigt
inspirerande.

På det andra hackatonet, några veckor senare, hade antalet deltagande team ökat till tre. Denna gång fanns även
ett tema. Life at home. Troligtvis väldigt inspirerade av secret knock arduino teamet förra hackatonet arbetade alla
denna gång på ett eller annat sätt med arduino.

Mitt team jobbade med ett automatiskt bevattningssystem för krukväxter. Mitt första arduino baserade projekt och 
ett väldigt roligt bygge. Som stomme använde vi oss av en gammal hatthylla och komponenterna inhandlades 
på Biltema och Kjell & Co. Ett webbgränssnitt presenterade loggade temperaturer och jordens fuktighetsvärde, inläst
med en analoggivare, med hjälp av [Charts.js](http://chartjs.org). Skulle temperaturen vara onormalt hög mailades 
även en varning ut till ägaren.

![Automatiskt bevattningssystem](/public/pics/tfv.jpg)

De två andra teamen jobbade med en progammeringsbar IR kontroller som styrdes via en mobilapp. Något som såg väldigt
genomtänkt och verkade på riktigt användbar. Bland annat styrdes belysning, Appletv och en Roomba(?). Men då systemet
var programmeringsbart och spelade in IR signaler från fjärrkontroller bör det kunna styra allt som använder sig av
IR signaler.
Det sista teamet
rev ner en radiostyrd bil och via en node server på en rasperry pie, styrde via en arduino, bilen via en webbläsare. 
Teamet jobbade också en hel del med att köra dockerinstanser på raspberry pi.

Hackathonen varit väldigt roliga, inspirerande och lärorika. Ser verkligen fram mot kommande hackathon på Plug.

Se all källkod på [Plux/VXO's Github](https://github.com/plug-hackathon)


