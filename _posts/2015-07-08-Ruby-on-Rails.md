---
layout: post
title: Ruby on Rails
---

Under kursen 
[individuellt mjukvaruutvecklingsprojekt](/courses/individuellt-mjukvaruutvecklingsprojekt)
använde jag mig av Ruby on Rails för att skapa
[MC-kartan.se](http://www.mc-kartan.se) tänkte här sammanfatta min
upplevelse och första möte med Ruby och Rails.

## Intryck

Ruby känns smidigt, enkelt och lättläst. Återkommer man
till koden är allt väldigt enkelt att följa och språket känns väldigt
uttrycksfullt. Rails känns stort och det händer mycket bakom kulisserna
något som med "convention over configuration" gör att det väldigt snabbt
går att ta fram en applikation. Något med både positiva och negativa
följder. Upplever att speciellt Crud-tunga applikationer lämpar sig bra i Rails och
det känns verkligen som att jag blivit kompis med både språket och
ramverket.

Lägger man till Rspec och Cucumber öppnar sig ett väldigt trevligt
TDD/BDD arbetsflöde och och det känns verkligen som att testning och
Rails går hand i hand. 
Detta var mitt första projekt där jag prövade på TDD/BDD och jag tycker
att arbetssättet lett till att min kod är lite bättre. Men framförallt
har jag en annan koll på min kodbas och refaktorisering underlättas
extremt. 

## Modularitet

Kikade lite även på modularitet och skrev en Rails Engine som hanterar
användare. En engine mountas i en Rails app och det blir en ganska snygg
uppdelning av concerns. Kollar man även på alla de engines som finns ute
verkar Rails modularitet vara något som används väldigt väl och öppnar
upp stora möjligheter för att modularisera och återanvända kod.

## Guider och böcker

Nedan följer en sammanfattning av de olika guider och böcker jag har
använt mig av och som jag kan rekommendera.

- [TryRuby.org](http://tryruby.org/)
- [RoR guide](http://guides.rubyonrails.org/)
- [Rails for Zombies](http://railsforzombies.org)
- [Rails tutorial](https://www.railstutorial.org/)
- [Agile web development with rails 4](https://pragprog.com/book/rails4/agile-web-development-with-rails-4)

