+++
date = 2019-09-01T00:00:00+02:00
draft = false
title = 'ASCI Sticker Pack'
description = 'Het verenigingserfgoed digitaal zichtbaar maken'

+++

Voor mijn oude studievereniging ASCI heb ik vele verenigingsbegrippen in WhatsApp Stickers omgezet. Hiervoor heb ik deze afbeeldingen ingetekend in Sketch en beschikbaar gemaakt als sticker pack.

## Het wiel niet opnieuw uitvinden

Ik koos ervoor om geen aparte stickerapps voor Android en iOS te schrijven, maar gebruik te maken van [Sticker Maker for WhatsApp](https://getstickerpack.com/). Dit is een bestaande app die sticker packs kan inlezen. Hiervoor gebruikt de app een Zipbestand met een specifieke indeling en extensie.

Om niet bij elke update de stickers één voor één toe te voegen in de app, bouwde ik een pipeline in GitHub Actions. Deze wordt automatisch afgetrapt als er nieuwe stickers worden toegevoegd. De pipeline runt een aantal automatische checks en pakt vervolgens de stickers in volgens het formaat dat Sticker Maker gebruikt. Deze packs kunnen door zowel Android- als iPhonegebruikers worden geopend in de Sticker Maker app.

> Ook snel sticker packs maken? Op mijn GitHub vind je alle benodigdheden: [StickerAutomation](https://github.com/leonmelein/StickerAutomation)