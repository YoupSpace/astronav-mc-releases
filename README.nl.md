# AstroNav Mission Control

[English](README.md) · **Nederlands**

AstroNav Mission Control (AstroNav MC) is de officiële Windows-desktopapplicatie voor de **AstroNav Nano**-flightcontroller van [YoupSpace](https://youpspace.com). Gebruik de app om je Nano in te stellen, vluchtlogs te importeren en je missies terug te kijken, volledig offline.

**[Download de nieuwste versie](https://github.com/YoupSpace/astronav-mc-releases/releases/latest)**

## Over YoupSpace

[YoupSpace](https://youpspace.com) is de plek van Youp voor projecten, producten en meer. YoupSpace bouwt en verkoopt hardwarekits, zoals de AstroNav-flightcontrollerkit, en deelt het bouwproces online. Het motto: *anything is possible, you decide your limits.*

AstroNav begon als modelraketproject om een raket te bouwen die 200+ meter hoog vliegt. Daaruit is de **AstroNav Nano** ontstaan: een compacte flightcontroller en vluchtdatalogger voor modelraketten en vergelijkbare voertuigen. De Nano meet beweging en omgeving, herkent vluchtfasen, logt de missie en kan op het apogeum het bergingssysteem activeren als dat is ingeschakeld en ingesteld.

Ga naar [youpspace.com](https://youpspace.com) voor de shop, andere projecten, video's en het testerprogramma voor de AstroNav Nano.

## Wat AstroNav MC doet

AstroNav MC werkt met een AstroNav Nano in USB-opslagmodus. Het is een bestandsgebaseerde tool. De app geeft geen live telemetrie en stuurt geen seriële commando's.

- **Detecteren** van een AstroNav Nano via USB, ook als er meer dan één is aangesloten.
- **Bekijken** van identiteit, gezondheid, status en samenvattingen van opgenomen vluchten.
- **Instellen** van vluchtschatting en lanceerdetectie, met validatie, een lokale herstelkopie en controle door terug te lezen.
- **Importeren** van vluchtlogs in een lokaal archief dat ook zonder apparaat beschikbaar blijft.
- **Terugkijken** van missies met gesynchroniseerde grafieken voor hoogte, snelheid, versnelling, rol/pitch, temperatuur en luchtdruk, plus een indicatieve standweergave.
- **Overlay** van telemetrie op je lanceervideo en export als MP4.
- **Exporteren** van gearchiveerde vluchten als CSV-bestand.

## Installeren

1. Open de [nieuwste release](https://github.com/YoupSpace/astronav-mc-releases/releases/latest).
2. Download het Windows-installatieprogramma (`*-setup.exe`).
3. Voer het installatieprogramma uit. Je hebt geen beheerdersrechten nodig.

Vereisten: Windows 10 of 11 (64-bit) met Microsoft Edge WebView2. WebView2 zit standaard in actuele Windows-versies.

## Updates

AstroNav MC controleert deze repository op nieuwe versies en toont een melding als er een update is. Updates zijn ondertekend en worden vóór installatie gecontroleerd. Je kunt updatecontroles uitzetten via **Settings → Updates**. De updatecontrole is het enige netwerkverzoek dat de app doet. Je vluchten en instellingen blijven op je computer.

## Documentatie

- [YoupSpace Wiki](https://wiki.youpspace.com/): hardware, veiligheid, aan de slag, configuratie, vluchtfasen, pre-flightchecks, vluchtlogs en probleemoplossing voor de AstroNav Nano.
- [Handleiding AstroNav MC](https://wiki.youpspace.com/software/astronav-mc/): de volledige handleiding van deze applicatie.

> **Veiligheid:** de AstroNav Nano kan ontstekings- en bergingshardware aansturen. Lees de [veiligheidsdocumentatie](https://wiki.youpspace.com/) voordat je een batterij, E-match of andere pyrohardware aansluit. Laat **Fire apogee pyro** uitgeschakeld, tenzij je bergingssysteem is aangesloten en voor die uitgang is ingesteld.

## Ondersteuning

Lees eerst de [probleemoplossing](https://wiki.youpspace.com/). Voor andere vragen neem je contact op met YoupSpace via [youpspace.com](https://youpspace.com).

## Licentie

AstroNav Mission Control is gratis te gebruiken, maar het is **closed-source, propriëtaire software**. Je mag de app niet verspreiden, wijzigen of reverse-engineeren. Deel de link naar deze pagina in plaats van het installatieprogramma. Zie [LICENSE.nl](LICENSE.nl) ([English](LICENSE)). Bij verschillen geldt de Engelse versie.

Copyright © 2026 [YoupSpace](https://youpspace.com). Alle rechten voorbehouden.
