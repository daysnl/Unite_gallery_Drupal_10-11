Bespreking van Unite Gallery module versie 2.2.0

De Unite Gallery module integreert naadloos met Drupal ^10 en ^11 en biedt een breed scala aan aantrekkelijke manieren om afbeeldingen en video's te presenteren. Unitegallery.net, hoewel niet meer actief, stond bekend om zijn diverse en indrukwekkende voorstellingswijzen.

Voor één node voorzie ik twee presentatiestijlen voor afbeeldingen:

Justified Tiles
Compact Slider
Daarnaast zijn er verschillende presentatiemogelijkheden voor een view die alle afbeeldingen in een afbeeldingsveld van een inhoudstype weergeeft, waaronder:

Tiles Columns
Tiles Nested
Tiles Grid
Tiles Justified
Slider Carousel
Slider Compact
Slider Grid Theme
Ik voorzie ook een presentatieoptie voor YouTube-video's. Bijna alle instellingen zijn configureerbaar, zoals afmetingen, achtergrondkleur, en afbeeldingsstijl. De programmering wordt volledig uitgevoerd met Twig, zonder dat er PHP aan te pas komt. Alles is volledig responsive, werkt in meerdere browsers en is geschikt voor verschillende apparaten.

Werkwijze:

Installeer de third-party library:
Plaats het bestand unitegallery_third_party.zip in de map libraries en zorg ervoor dat de uitgepakte map de naam unitegallery heeft.
Installeer en activeer de module:
Voeg de module unite_gallery.zip toe aan je site en activeer deze.
Instellingen verfijnen:
Om didactische redenen heb ik sommige velden niet verborgen in de weergaves. Je kunt de instellingen verder aanpassen naar eigen wens. Gebruik de Asset Injector om de JavaScript-bestanden alleen op de benodigde pagina's te laden, zodat je prestaties optimaliseert.
Gebruik van afbeeldingsstijl:
Ik maak gebruik van de afbeeldingsstijl big, waarmee afbeeldingen op ware grootte worden weergegeven. Je kunt ook eigen afbeeldingsstijlen aanmaken, indien nodig met de module Focal Point.
Rest van de configuratie:
Wijst zich vanzelf.

Vereisten:
Zorg ervoor dat de benodigde modules zijn geïnstalleerd en geactiveerd.

asset_injector(ontbreekt) https://www.drupal.org/project/asset_injector
color_field(ontbreekt) https://www.drupal.org/project/color_field
conditional_fields(ontbreekt) https://www.drupal.org/project/conditional_fields
Field
File
Image
Language
Menu UI
Custom Menu Links
Link
Node
Text
Filter
User
System
Options
Path
Path alias
twig_field (ontbreekt) https://www.drupal.org/project/twig_field
The CodeMirror Editor (ontbreekt) https://www.drupal.org/project/codemirror_editor	
twig_tweak (ontbreekt) https://www.drupal.org/project/twig_tweak
bamboo_twig (ontbreekt) https://www.drupal.org/project/bamboo_twig
bamboo_twig_loader (ontbreekt)
