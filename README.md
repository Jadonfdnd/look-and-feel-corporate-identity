# Corporate Identity

Ontwerp en maak voor een opdrachtgever een website op basis van een bestaande huisstijl.


# Snappthis
Snappthis is een project in opdracht van Marije ten Brink met als doel een oplossing te creeeren voor gezamenlijke brainstorming en documentatie met behulp van foto's.

## Beschrijving
Het project biedt functionaliteiten zoals het delen van foto's door groepsleden, het overzichtelijk bekijken van verzamelde content in groepen, zowel voor professionele als persoonlijke doeleinden. Het is dus een gebruiksvriendelijke en efficiënte manier om in groepen gezamenlijke mindmaps (Snappmaps) te creëren.

<img width="414" height="559" alt="image" src="https://github.com/user-attachments/assets/b2203e3e-a4d2-43e8-9d5a-2d83fe597395" />
https://jadonfdnd.github.io/look-and-feel-corporate-identity/


## Kenmerken

HTML Structuur
- <header>: Bevat de primaire navigatie-elementen zoals de back-knop en de interactiebuttons (Like, Tomato, Star).
- <main>: De hoofdcontainer voor de content, zoals de fotogalerij of de detailpagina.
- .metadata-wrapper: Een div op de detailpagina om de tags (ul.image-tags) en de tijd/datum (time.photo-datetime) te groeperen voor een responsive layout.

CSS
1. De styling is mobile first
   Onder 678px gebruikt het een enkel kolom Grid (grid-template-column: 1fr)
2. Desktop: boven 678px schakelt het over naar 2 koloms grid (2fr 1fr) en wordt     de image aan de linker kant geplaatst en de metadata-wrapper rechts. 


## Bronnen
https://github.com/fdnd-agency/snappthis/wiki/Design-Challenge
## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
