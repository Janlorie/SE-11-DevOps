# Gebruik Ontwikkelstraat
Uitleg principes, instellingen, gebruik ontwikkelstraat, gekozen methodes.

## Communicatie met SE-11
Om ervoor te zorgen dat jullie goed met ons kunnen communiceren hebben we een aantal manieren om met ons in contact te komen.

- Whatsapp: mocht je een korte vraag hebben aan ons dan kan je gebruik maken van de groepschat(waar jullie als het goed
 is bijzitten). Bij deze vorm van communicatie zullen we waarschijnlijk het snelst reageren. Mocht het een langere 
 discussie worden, dan verplaatsen het gesprek het liefst verder naar discord.

- Discord: hierbinnen kunnen we onder andere langere gesprekken houden, scherm delen en elkaar spreken.

- Email: mochten we niet reageren via discord of whatsapp dan kun je altijd nog een email sturen:  
  - Jan: 15055620@student.hhs.nl
  - Martijn: 14078635@student.hhs.nl
  

## Branch Policies
Er zijn bij de master branche enkele branch policies ingevoerd om deze te beschermen, code quality te waarborgen en 
reviews. Voordat er een commit naar master kan worden uitgevoerd worden. Sommige van deze policies worden ook echt 
enforced, maar van sommige policies wordt verwacht dat je ze naleeft alleen.

Momenteel zijn er de volgende branch policies op de master branch:
  - **Pull requests(PR)**: het is niet mogelijk om direct naar de master branch te pushen, dit gaat altijd via een pull 
  request. Een pull request kan worden aangemaakt in het overzicht van de branches.
  
  - **Review**: de pull request moet doormiddel van een code review worden gekeurd op kwaliteit, dit moet gebeuren door 
  alle        groepsleden. Mocht je er mee eens zijn met de toevoegingen/wijzigingen dan kun je PR approven. Mocht je 
  nog feedback hebben voor de iemand, dan kan je een suggestie doen. Als je het er niet mee eens bent met de PR dan kun 
  je deze rejecten. De PR zal pas gemerged worden met de master als iedereen de PR approved heeft (mochten andere eisen 
  naast de review geslaagd zijn).
  
  - **Build**: er zijn 2 pipelines aangemaakt voor dit project: een voor de webapplicatie en een voor de 
  desktopapplicatie. Deze pipelines zullen proberen jullie PRs proberen te builden om te kijken of er niet onverwachte 
  fouten optreden. Een eis voordat een PR gemerged wordt, is dat de build succesvol is. Mocht dit niet lukken dan kan 
  er het best gekeken worden naar welke build errors er zijn en deze oplossen.
  
  - **Tests**: Alle gemaakte unit tests moeten succesvol worden uitgevoerd worden voordat er gemerged kan worden met 
  master. Ook moet de test coverage hoger zijn dan de vorige succesvolle PR.

## Feature branches
Omdat er niet direct in de master branch gewerkt kan worden zullen we hiervoor nieuwe branches voor moeten aanmaken. 
Hierbij kan er gebruik worden gemaakt van feature branches. Om traceerbaarheid te verbeteren zijn taken verbonden 
met feature branches, zo is meteen te zien in welke branch al gewerkt wordt aan deze taak. Houd ook een duidelijk 
format aan bij het benamen van je feature branches bijv. `features/feature-name`

Dit werkt als volgt:
  **Taak** > **Meer opties taken** > **New branch** (je kan ook meer taken toewijzen aan een branch)

## Discord
Zoals al eerder uitgelegd bij **Communicatie met SE-11** kan discord gebruikt worden om te communiceren. Een van de 
channels binnen de server staan allemaal build messages. Hier zal een bot een bericht met de meest essentiële build 
informatie plaatsen, mocht er ooit door iemand of automatische een build worden uitgevoerd.

## Definition of Done

1. De eisen van de taak zijn volbracht
2. Er zijn voldoende comments geplaatst om de code onderhoudbaar te houden
3. Het ontwerp is up-to-date gebracht mocht dit nodig zijn
4. Er zijn unit tests geschreven die minimaal 80% coverage hebben
5. Er is een pull request(PR) aangemaakt om te mergen met de master branch
6. De PR is doormiddel van code review beoordeeld. Alle comments zijn beantwoord en mogelijke wijzigingen zijn doorgevoerd
7. De PR wordt succesvol gebuild 
8. De taak wordt als voltooid aangevinkt op het board


