# Dokumentation der Projektergebnisse von „Digitale Identitäten“
Im Auftrag des Bundesministerium für Inneres und Heimat (BMI), haben wir uns von 2021 – 2023 mit dem Thema Digitale Identitäten auseinandergesetzt. Gemeinsam wollten wir die Online-Ausweisfunktion (eID) in den Alltag der Bürger:innen stärker integrieren. Dafür untersuchten wir zunächst die Ursachen und Hürden, die der Nutzung der eID zum damaligen Zeitpunkt im Weg standen. Anhand dieser Erkenntnisse haben wir unter anderem:
- die BundesIdent App sowie einem entsprechenden Backend und Widget entwickelt
- den PIN-Brief überarbeitet und so adressatenfreundlicher und verständlicher gestaltet
- einen Vorschlag für einen Einrichtungsassistenten in der AusweisApp2 erarbeitet:
- einen [Usability-Test der eID und AusweisApp2](https://github.com/jerdesign/useid-documentation/edit/main/README.md#usability-test-der-eid-und-ausweisapp2) durchgeführt

Weitere Informationen zum Projekt finden Sie in unseren Blogposts: [Der Online-Ausweisfunktion zum Durchbruch verhelfen](https://digitalservice.bund.de/blog/projekt-digitale-identitaeten), [Erste Erkenntnisse aus dem Testbetrieb von BundesIdent](https://digitalservice.bund.de/blog/testbetrieb-von-bundesident) und [BundesIdent läuft nach Pilotphase aus, Er­kennt­nisse fließen in Gesamt­vor­haben ein](https://digitalservice.bund.de/blog/digitale-identitaeten-bundesident-laeuft-nach-pilotphase-aus-erkenntnisse-fliessen-in-gesamtvorhaben-ein).

**Kontakt:** useid@digitalservice.bund.de
## Anwendungsfall: Grundsteuererklärung für Privateigentum
[![Anwendungsfall_ Grundsteuererklärung für Privateigentum](https://github.com/jerdesign/useid-documentation/assets/4391042/fae07c19-703b-46ef-bade-7ebf4a4a6844)](https://digitalservice.bund.de/blog)
Von November 2022 bis Juni 2023 war es möglich, sich für den Online-Dienst „[Grundsteuererklärung für Privateigentum](https://www.grundsteuererklaerung-fuer-privateigentum.de/)“ mit der BundesIdent App zu identifizieren. Die Einbindung erfolgte über ein ebenfalls von uns entwickeltes [Widget](https://digitalservice.bund.de/glossar#widget). Dieses wurde so ausgestaltet, dass es die einfache Integration in vielfältige Online-Services ermöglicht und perspektivisch ein einheitliches Nutzungserlebnis bei der digitalen Identifikation bietet. Ungekürztes Videodemo: https://user-images.githubusercontent.com/4391042/249636578-54679271-674a-460f-be26-9212a4b0e202.mp4

### Videodemo
https://github.com/jerdesign/useid-documentation/assets/4391042/2ff5542a-e692-4500-8de8-64adb0a7a571

### Exploration: Gerätwechsel mit WebAuthn
Aktuell muss die AusweisApp2 auch auf dem Computer installiert werden und mit dem Smartphone gekoppelt werden. Desweiteren müssen beide Geräte im gleichen WLAN sein. Um diesen Schritt zu vereinifachen, haben wir einen technischen Prototypen mit dem [WebAuthn](https://webauthn.io/)-Standard entwickelt.
Weitere technische Informationen unter: https://github.com/digitalservicebund/useid-architecture/tree/main/research/device-switch

https://github.com/jerdesign/useid-documentation/assets/4391042/97af0042-75b9-4441-bd0c-0c2f8fe37639

## PIN-Brief Iteration
![PIN-Brief Iteration](https://github.com/jerdesign/useid-documentation/assets/4391042/bc092971-0c43-4c40-92e1-1249f74d0d89)
[Beschreibung ergänzen]

Die neue Iteration des PIN-Briefes wird seit 2023 gedruckt: [PIN-Brief_Perso_2023_Live.pdf](https://github.com/jerdesign/useid-documentation/files/11896471/PIN-Brief_Perso_2023_Live.pdf)

## Einrichtungsassistent in der AusweisApp2

![Einrichtungsassistent in der AusweisApp2](https://github.com/jerdesign/useid-documentation/assets/4391042/08003e19-5f64-47bd-a30a-fbadd665b968)

Um Erstnutzer:innen besser abzuholen, haben wir einen Vorschlag für einen Einrichtungsassistenten in der AusweisApp2 erarbeitet:
- [Figma-Datei](https://www.figma.com/file/f6DoOUO7ggCYosH8jYhqD4/Onboarding-proposal-for-the-AusweisApp2?type=design&node-id=0%3A1&mode=design&t=SLxAANyPFITAt34F-1)
[Projekt veröffentlichen und Link aktualisieren].

## Usability-Test der eID und AusweisApp2
![Usability-Test der eID und AusweisApp2](https://github.com/jerdesign/useid-documentation/assets/4391042/883669f8-a3c3-48fd-b3e0-8a732f49d982)

Die Ergebnisse der 6 Usability-Tests haben wir hier zusammengefasst:
- [Ergebnisbericht Usability-Test eID & AusweisApp2.pdf](https://github.com/jerdesign/useid-documentation/files/11896120/Ergebnisbericht.Usability-Test.eID.AusweisApp2.pdf)
