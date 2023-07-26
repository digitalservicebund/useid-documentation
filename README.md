# Dokumentation der Projektergebnisse von „Digitale Identitäten“
Im Auftrag des Bundesministerium für Inneres und Heimat (BMI), haben wir uns von 2021 – 2023 mit dem Thema Digitale Identitäten auseinandergesetzt. Gemeinsam wollten wir die Online-Ausweisfunktion (eID) in den Alltag der Bürger:innen stärker integrieren. Dafür untersuchten wir zunächst die Ursachen und Hürden, die der Nutzung der eID zum damaligen Zeitpunkt im Weg standen. Anhand dieser Erkenntnisse entwickelten wir ein Lösungspaket. Hier eine erste Auswahl der Projektergebnisse:
- BundesIdent App
	- [Technische Architektur](https://github.com/digitalservicebund/useid-architecture)
	- [Backend](https://github.com/digitalservicebund/useid-backend-service)
	- [BundsIdent für Android](https://github.com/digitalservicebund/useid-app-android)
   	- [BundesIdent für iOS](https://github.com/digitalservicebund/useid-app-ios)
   	- [AusweisApp2 Wrapper iOS](https://github.com/digitalservicebund/AusweisApp2Wrapper-iOS-SPM)
   	- Eine [Beispielandwendung](https://github.com/digitalservicebund/useid-eservice-example) und das zugehörige [SDK](https://github.com/digitalservicebund/useid-eservice-sdk)
- [Pilotierung mit dem Online-Dienst „Grundsteuererklärung für Privateigentum“](#anwendungsfall-grundsteuererkl%C3%A4rung-f%C3%BCr-privateigentum)
- [Exploration eines Gerätewechsels mit WebAuthn](#exploration-ger%C3%A4twechsel-mit-webauthn)
- Überarbeitung des PIN-Briefes: [PDF](https://github.com/jerdesign/useid-documentation/files/11896471/PIN-Brief_Perso_2023_Live.pdf)
- Vorschlag für einen Einrichtungsassistenten in der AusweisApp2 erarbeitet: [Figma](https://www.figma.com/file/f6DoOUO7ggCYosH8jYhqD4/Onboarding-proposal-for-the-AusweisApp2?type=design&node-id=1608%3A949&mode=design&t=YCgYMWYrJfTqF8sB-1)
- Ergebnisbericht Usability-Test eID & AusweisApp2: [PDF](https://github.com/jerdesign/useid-documentation/files/11896120/Ergebnisbericht.Usability-Test.eID.AusweisApp2.pdf)

### Weitere Hintergrundinformationen zum Projekt finden Sie in unseren Blogposts:
- [Der Online-Ausweisfunktion zum Durchbruch verhelfen](https://digitalservice.bund.de/blog/projekt-digitale-identitaeten)
- [Erste Erkenntnisse aus dem Testbetrieb von BundesIdent](https://digitalservice.bund.de/blog/testbetrieb-von-bundesident)
- [BundesIdent läuft nach Pilotphase aus, Er­kennt­nisse fließen in Gesamt­vor­haben ein](https://digitalservice.bund.de/blog/digitale-identitaeten-bundesident-laeuft-nach-pilotphase-aus-erkenntnisse-fliessen-in-gesamtvorhaben-ein)

### Kontakt
useid@digitalservice.bund.de
## Anwendungsfall: Grundsteuererklärung für Privateigentum
![Anwendungsfall_GrundsteuererklärungFürPrivateigentum](https://github.com/digitalservicebund/useid-documentation/assets/4391042/48e06ff4-8506-4955-9605-ac43a712ea9c)
Von November 2022 bis Juni 2023 war es möglich, sich für den Online-Dienst „[Grundsteuererklärung für Privateigentum](https://www.grundsteuererklaerung-fuer-privateigentum.de/)“ mit der BundesIdent App zu identifizieren. Die Einbindung erfolgte über ein ebenfalls von uns entwickeltes [Widget](https://digitalservice.bund.de/glossar#widget). Dieses wurde so ausgestaltet, dass es die einfache Integration in vielfältige Online-Services ermöglicht und perspektivisch ein einheitliches Nutzungserlebnis bei der digitalen Identifikation bietet. [Ungekürzte Videodemo](https://github-production-user-asset-6210df.s3.amazonaws.com/4391042/256348153-26fb3a4e-c47b-47f0-808c-e0875b35493c.mp4).

### Videodemo
https://github.com/digitalservicebund/useid-documentation/assets/4391042/0187ce2d-2ebd-4bca-98a5-7c7faa6d0ace

### Exploration: Gerätwechsel mit WebAuthn
Um den Gerätewechsel zu vereinfachen, haben wir einen technischen Prototypen mit dem [WebAuthn-Standard](https://www.w3.org/TR/webauthn-3/) entwickelt.
Weitere technische Informationen unter: https://github.com/digitalservicebund/useid-architecture/tree/main/research/device-switch

https://github.com/digitalservicebund/useid-documentation/assets/4391042/51f1afb3-8d52-4ff3-9016-d451ae5c3cd9
