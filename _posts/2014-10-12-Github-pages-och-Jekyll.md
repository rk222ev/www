---
layout: post
---

Då är sidan uppe på riktigt och lösningen känns ganska trevlig. Tog ett litet tag innan alla pusselbitar föll på plats då jag,
som vanligt, gör först och läser sedan. Men resultatet är uppnått och jag känner mig ganska tillfreds med hur utfallet blev.
Tänkte gå igenom lösningen här nedan.

##Statiskt genererat inehåll med Jekyll
Som jag skrev i förra posten använder jag mig av [Jekyll](http://www.jekyllrb.com) och "Butlern" [Poole](http://getpoole.com) som 
tillhandahåller grundläggande funktionalitet och utseende.

Igångkörningen gick ganska snabbt. Lite mycket paket som skulle installeras innan jag kunde generera sidorna med [Jekyll](http://www.jekyllrb.com) som bygger
på [ruby](http://www.ruby-lang.org) och [nodeJS](http://nodejs.org/) som jag inte hade installerat sedan innan.
Men att generera själva sidorna är till om man vill lokalt testa att bygga sidorna innan man kör upp dom till github eller om 
man vill hosta dom på ett annat sätt.

##Github pages
Det är github som hostar sidan via [Github pages](https://pages.github.com/). Det är inte sämre än att det även generarar själva 
HTML filerna direkt från [Jekyll](http://www.jekyllrb.com) filerna skrivet i markdown och gjort med templates.

För att skapa ett nytt inlägg skapar jag bara en ny markdown fil och fyller på med mitt innehåll. [Github](http://pages.github.com ser sedan till att 
allt presenteras snyggt i HTML. Alltså behöver jag inte, om jag inte vill, installera [Jekyll](http://www.jekyllrb.com) på min lokala dator. 


##Domän
För att få sidan att fungera med en domän pekar man bara domänen på användarnamn.github.io med hjälp av CNAME. Vilket i praktiken 
innebär att man skapar en fil i sitt github repo med
namnet CNAME och innehåller den subdomän man vill ska leda till repot. I mitt fall är det www-subdomänen som jag vill använda mig av.
Alltså blir inehållet i min CNAME-fil "www.rpkn.se".

Läs mer om hur [Github](http://www.github.com fungerar med domäner på [Github pages hjälpavsnitt.](https://help.github.com/categories/github-pages-basics/).
