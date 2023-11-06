# Dokumentation der Projektergebnisse von „Digitale Identitäten“
Im Auftrag des Bundesministerium für Inneres und Heimat (BMI), haben wir uns von 2021 – 2023 mit dem Thema Digitale Identitäten auseinandergesetzt. Gemeinsam wollten wir die Online-Ausweisfunktion (eID) in den Alltag der Bürger:innen stärker integrieren. Dafür untersuchten wir zunächst die Ursachen und Hürden, die der Nutzung der eID zum damaligen Zeitpunkt im Weg standen. Anhand dieser Erkenntnisse entwickelten wir ein Lösungspaket. Hier eine Auswahl der Projektergebnisse:
1. [BundesIdent App](#1-bundesident-app)
2. [Anwendungsfall: Grundsteuererklärung für Privateigentum](#2-anwendungsfall-grundsteuererklärung-für-privateigentum)
3. [PIN-Brief-Iteration](#3-pin-brief-iteration)
4. [Handlungsempfehlungen für den Abbau von Nutzungshürden](#4-handlungsempfehlungen-für-den-abbau-von-nutzungshürden)
5. [Exploration eines Gerätewechsels mit WebAuthn](#5-exploration-gerätwechsel-mit-webauthn)
6. [Entwurf eines Einrichtungsassistenten für die AusweisApp2](#6-entwurf-eines-einrichtungsassistenten-für-die-ausweisapp2)
7. [Ergebnisbericht: Usability-Test eID & AusweisApp2](#7-ergebnisbericht-usability-test-eid--ausweisapp2)
8. [Ergebnisbericht: Nutzung der eID durch Diensteanbieter](#8-ergebnisbericht-nutzung-der-eid-durch-diensteanbieter)
9. [Fünfzehn allgemeine Handlungsempfehlungen für eine erhöhte Verbreitung der Online-Ausweisfunktion basierend auf qualitativer Forschung aus 2021](#9-fünfzehn-allgemeine-handlungsempfehlungen-für-eine-erhöhte-verbreitung-der-online-ausweisfunktion-basierend-auf-qualitativer-forschung-aus-2021)
10. [Nutzungsreise der Bürger:innen und Diensteanbieter](#10-nutzungsreise-der-bürgerinnen-und-diensteanbieter)
11. [Mögliche Ansatzpunkte zur Anpassung von technischen eID-Richtlinien und der Personalausweisverordnung anhand von Beobachtungspunkten der User-Journey mit der eID](#11-mögliche-ansatzpunkte-zur-anpassung-von-technischen-eid-richtlinien-und-der-personalausweisverordnung-anhand-von-beobachtungspunkten-der-user-journey-mit-der-eid)


### Weitere Hintergrundinformationen zum Projekt finden Sie in unseren Blogposts:
- [Der Online-Ausweisfunktion zum Durchbruch verhelfen](https://digitalservice.bund.de/blog/projekt-digitale-identitaeten)
- [Erste Erkenntnisse aus dem Testbetrieb von BundesIdent](https://digitalservice.bund.de/blog/testbetrieb-von-bundesident)
- [BundesIdent läuft nach Pilotphase aus, Er­kennt­nisse fließen in Gesamt­vor­haben ein](https://digitalservice.bund.de/blog/digitale-identitaeten-bundesident-laeuft-nach-pilotphase-aus-erkenntnisse-fliessen-in-gesamtvorhaben-ein)

### Kontakt
useid@digitalservice.bund.de

## 1. BundesIdent App
![BundesIdent_App](https://github.com/digitalservicebund/useid-documentation/assets/4391042/dc2fe213-0e52-42d7-b652-bc6a83c65751)

Mit der BundesIdent App und einem digital fähigen Ausweisdokument können sich Nutzer:innen online identifizieren. Nutzer:innen werden Schritt für Schritt durch den gesamten Identifizierungsprozess geführt. Mithilfe des Web-Widgets wird der Einstieg in die App erleichtert. Durch ein zeitgemäßes Design und einer bundesnahen Gestaltung durch die Orientierung am Corporate Design Styleguide wird Vertrauen in die Lösung geschaffen und damit die Akzeptanz der Online-Ausweisfunktion gestärkt. Auf Basis der Nutzungsdaten wurde das Nutzungserlebnis kontinuierlich optimiert (u.a. durch A/B-Tests) und das Produkt ziel- und nutzerorientiert um weitere Funktionen ergänzt. So konnten Abbruchquoten durch iterative und schnelle Weiterentwicklung reduziert werden.

- [Technische Architektur](https://github.com/digitalservicebund/useid-architecture)
- [Backend](https://github.com/digitalservicebund/useid-backend-service)
- [BundesIdent für Android](https://github.com/digitalservicebund/useid-app-android)
- [Design der BundesIdent App für Android in Figma](https://www.figma.com/file/8fQmmojhiBHUd43MD9DlFP/BundesIdent-Android?type=design&node-id=1%3A14259&mode=design&t=0uw69h5khNrGNoRo-1)
- [BundesIdent für iOS](https://github.com/digitalservicebund/useid-app-ios)
- [AusweisApp2 Wrapper iOS](https://github.com/digitalservicebund/AusweisApp2Wrapper-iOS-SPM)
- [Design der BundesIdent App für iOS in Figma](https://www.figma.com/file/mHFbvYT7vdX0v0FcLxnIbw/BundesIdent-iOS?type=design&node-id=95%3A26004&mode=design&t=GP4aS6eWJ70qmvb8-1)
- [User Flow als PDF](https://github.com/digitalservicebund/useid-documentation/files/12646866/UserFlow_BundesIdent.pdf)
- [Beispielandwendung](https://github.com/digitalservicebund/useid-eservice-example) und das zugehörige [SDK](https://github.com/digitalservicebund/useid-eservice-sdk)
- [Widget](#widget)
- [Illustrationen](#illustrationen)

### Illustrationen
![Illustrationen_BundesIdent](https://github.com/digitalservicebund/useid-documentation/assets/4391042/f5d70381-fd99-45ad-afd5-84d0dfe5a681)

Um die App aufzulockern, haben wir eine Reihe an Illustrationen in Auftrag gegeben. Die Illustrationen kommen vor allem dann zum Einsatz, wenn es einen Fehler gibt oder für die Nutzenden ein Mehraufwand entsteht.

### Widget
![Widget](https://github.com/digitalservicebund/useid-documentation/assets/4391042/1bdc1929-0a34-4734-97fb-82437ecfe360)

Die Einbindung von BundesIdent in den Online-Dienst „[Grundsteuererklärung für Privateigentum](https://www.grundsteuererklaerung-fuer-privateigentum.de/)“ erfolgte über ein ebenfalls von uns entwickeltes Widget. Dieses wurde so ausgestaltet, dass es die einfache Integration in vielfältige Online-Services ermöglicht und perspektivisch ein einheitliches Nutzungserlebnis bei der digitalen Identifikation bietet.

### Erste Designidee für das Widget 2.0 | Nicht mit Nutzer:innen getestet
![Widget_2 0](https://github.com/digitalservicebund/useid-documentation/assets/4391042/b723e06e-4d72-4313-a6f1-68baba8dc134)

Das Widget beim Online-Dienst ist ein Berührungspunkt mit viel Potential, vor allem bei der Erstnutzung. In einem Prototypen haben wir erarbeitet, wie eine Ausbaustufe des Widgets funktionieren könnte: [www.widget-iteration.webflow.io](https://widget-iteration.webflow.io/) Das Widget wird dabei auf einen Button reduziert: »Mit Ausweis identifizieren«. Wenn eine eID-App bereits installiert ist, öffnet sich nach einem Tap die App. Wir können hier nämlich davon ausgehen, dass sich die Nutzer:innen bereits erfolgreich mit der eID identifiziert haben. Sollte noch keine eID-App installiert sein, werden die Nutzer:innen mit einfachen Fragen im Widget durch die Erstnutzung geleitet. Dabei werden Schritt für Schritt die Anforderungen abgefragt. Dazu gehören unter anderem ein kompatibles Smartphone, ein kompatibler und gültiger Ausweis sowie die PIN oder der PIN-Brief. Wird eine dieser Anforderungen nicht erfüllt, kann frühzeitig im Widget eine Lösung aufgezeigt werden und somit die Abbruchquote verringert werden. Dieser Prototyp wurde noch nicht mit Nutzer:innen getestet.

## 2. Anwendungsfall: Grundsteuererklärung für Privateigentum
![Anwendungsfall_GrundsteuererklärungFürPrivateigentum](https://github.com/digitalservicebund/useid-documentation/assets/4391042/ee6d3a43-d1b1-47d2-9711-e00e86ae2c28)

Von November 2022 bis Juni 2023 war es möglich, sich für den Online-Dienst „[Grundsteuererklärung für Privateigentum](https://www.grundsteuererklaerung-fuer-privateigentum.de/)“ mit der BundesIdent App zu identifizieren. Die Einbindung erfolgte über ein ebenfalls von uns entwickeltes [Widget](https://digitalservice.bund.de/glossar#widget). Dieses wurde so ausgestaltet, dass es die einfache Integration in vielfältige Online-Services ermöglicht und perspektivisch ein einheitliches Nutzungserlebnis bei der digitalen Identifikation bietet. [Das ungekürzte Videodemo](https://github-production-user-asset-6210df.s3.amazonaws.com/4391042/256348153-26fb3a4e-c47b-47f0-808c-e0875b35493c.mp4).

### Grundsteuerflow
[Grundsteuerflow vom 8. Mai 2023 als PDF](https://github.com/digitalservicebund/useid-documentation/files/12894997/Grundsteuer-Flow_2023_05_08.pdf)

![Flow_Grundsteuer](https://github.com/digitalservicebund/useid-documentation/assets/4391042/fb387721-b8ed-4bc1-93c0-655c59f28c7d)

### Videodemo
https://github.com/digitalservicebund/useid-documentation/assets/4391042/0187ce2d-2ebd-4bca-98a5-7c7faa6d0ace

### Zahlen und Fakten
- 83.000 App Downloads für iOS & Android von Januar bis Juni 2023
- 30.000 Identifizierungen mit BundesIdent von Januar bis Juni 2023
- 23.000 Neueinrichtungen des Online- Ausweises von Januar bis Juni 2023
- 34 Deployments im Januar 2023
- 10 App-Releases seit Launch von November 2022 bis Juni 2023

### Umfrageergebnisse von Nutzenden zur Verwendung von BundesIdent imOnline-Service „Grundsteuererklärung für Privateigentum”
![Umfrageergebnisse_Grundsteuer](https://github.com/digitalservicebund/useid-documentation/assets/4391042/830c5019-2a3c-44d5-9db6-317605f3b765)

#### „Warum haben Sie sich gegen eine Identifikation mit dem Ausweis entschieden?“
Frage an die Nutzenden nach dem Abbruch der Identifikation mit BundesIdent.

1460 Rückmeldungen vom 7. März bis 31. Mai 2023.
- Etwa 82 % der Nutzenden erfüllten die Voraussetzungen nicht.
	- ca. 73 % ohne PIN/PIN-Brief
	- ca. 6 % ohne kompatiblen Ausweis
	- ca. 3 % ohne kompatibles Smartphone
- Etwa 9 % gaben an, dass der Prozess insgesamt zu kompliziert war bzw. einfach nicht funktionierte.
- Etwa 2 % gaben Probleme beim Scannen als Abbruchgrund an.
- Zu je 1 % wurden fehlende Erläuterungen sowie der Umweg einer notwendigen Identifizierung am Mobiltelefon genannt, der zu kompliziert
war und mehr Führung gebraucht hätte. Wenn die Person am Desktop startete, musste sie sich mit dem Magic Link auf dem Mobilgerät
anmelden, bevor eine Identifizierung möglich war.
- 5 % gaben sonstige Rückmeldungen.

#### „Was sollte an der Identifikation mit dem Ausweis verbessert werden?“
Frage an die Nutzenden nach erfolgreicher Identifizierung.

232 Rückmeldungen vom 23. März bis 31. Mai 2023. Daten sind wegen der geringen Anzahl an Rückmeldungen nicht aussagekräftig.
- Etwa 20 % der Nutzenden waren zufrieden.
- Etwa 28 % der Nutzenden brauchten viele Versuche und fanden den Prozess insgesamt zu schwierig.
- Etwa 16 % merkten an, dass das Scannen schwierig war.
- Etwa 10 % fanden den Desktop-Workaround zu schwierig.
- Zu je 5-6 % wurde angemerkt, dass Erläuterungen fehlten und dass es nur eine App geben sollte – nicht AA2 und BundesIdent parallel.
- 15 % gaben sonstige Rückmeldungen, die teilweise ohne Bezug zu BundesIdent waren.

## 3. PIN-Brief-Iteration
![PIN-Brief](https://github.com/digitalservicebund/useid-documentation/assets/4391042/34bec366-b3ee-40ac-ab59-18e53a58c14d)

Der [neue PIN-Brief als PDF](https://github.com/digitalservicebund/useid-documentation/files/12176778/PIN-Brief_Personalausweis_2023_Live.pdf) und der alte [PIN-Brief als PDF](https://github.com/digitalservicebund/useid-documentation/files/12646248/PIN-Brief_Personalausweis_2022.pdf). [Design und Entwürfe in Figma](https://www.figma.com/file/uqkgjv2znYCxSs2ys92WLH/PIN-Brief-iteration-2023?type=design&node-id=662%3A55767&mode=design&t=I4xA6TI6b37fNsfU-1).

Um die Erstnutzung zu erleichtern, haben wir die Texte gekürzt und vereinfacht. Die sechs Anwendungsbeispiele inklusive Logo der Diensteanbieter machen den Mehrwert verständlicher. Die drei Prozessschritte mit ihren Grafiken auf der zweiten Seite verdeutlichen den Einrichtungsprozess. Bei der nächsten Version könnten die Texte und das Layout weiter iteriert werden, auch vom PIN-Rücksetztbrief. Eine detailliertere Analyse des PIN-Briefes gibt es im [Ergebnisbericht Usability‑Test eID & AusweisApp2](#7-ergebnisbericht-usability-test-eid--ausweisapp2).

## 4. Handlungsempfehlungen für den Abbau von Nutzungshürden

### Gerätewechsel

| Empfehlung aus der Analysephase*  | Erfahrungen aus dem Live‑Betrieb** | Weitergehende Empfehlung |
| :---  | :---  | :---  |
| Nutzende sollten einen Service auf ihrem Desktop-Computer starten und sich mittels Smartphone identifizieren können, ohne dabei zwei Apps installieren und die Geräte koppeln zu müssen. Ziel: eine nahtlose Nutzungserfahrung. | Anfragen aus dem Support und weitere Nutzertests zeigen: Hier springen Nutzer:innen ab. Deshalb wurde auf dem Standard [WebAuthn](https://webauthn.io) basierend technisch ein Flow getestet, um Sicherheit und Nutzungsfreundlichkeit zu gewährleisten. [Aktueller Stand auf Github](https://github.com/digitalservicebund/useid-architecture/tree/main/research/device-switch). | Es muss ein nahtloser User-Flow ermöglicht werden. Dazu sollte ein optimierter Flow mit Nutzer:innen getestet und zum MVP entwickelt werden. Parallel sollte ein Konto-basierter Flow, z.B. mithilfe der BundID, getestet werden. |

### Ersteinrichtung & PIN-Management

| Empfehlung aus der Analysephase*  | Erfahrungen aus dem Live‑Betrieb** | Weitergehende Empfehlung |
| :---  | :---  | :---  |
| PIN-Brief und AusweisApp2 können akut verbessert werden, um schnell Erfolge zu erzielen. Ziel: Bürger:innen kennen die PIN für ihren Ausweis und das Rücksetzen ist einfacher. | Eine erste Iteration des PIN-Briefes wurde umgesetzt ([PDF](https://github.com/digitalservicebund/useid-documentation/files/12176778/PIN-Brief_Personalausweis_2023_Live.pdf)). Der Einrichtungsassistent für die AusweisApp2 ([Figma](https://www.figma.com/file/f6DoOUO7ggCYosH8jYhqD4/Onboarding-proposal-for-the-AusweisApp2?type=design&node-id=1608%3A949&mode=design&t=YCgYMWYrJfTqF8sB-1)) inklusive Styleguide wurde übergeben, ebenso wie der Ergebnisbericht des Usability-Test der eID und AusweisApp2 ([PDF](https://github.com/digitalservicebund/useid-documentation/files/12176788/Ergebnisbericht.Usability-Test.eID.AusweisApp2.pdf)). Rückmeldung aus Umfrage: Bis zu 70 % der interessierten Nutzer:innen haben ihre PIN nicht. | Weitere Revision des PIN-Briefs & Verbesserung der 5- und 6-stelligen PIN-Struktur. PIN-Rücksetzdient (PRS) prominent platzieren, auch innerhalb der BundID. Der PRS sollte nahtlos in einen eID-Client integriert sein, ohne Umwege über weitere Domains. |

### Geführtes Nutzungserlebnis (UX)

| Empfehlung aus der Analysephase*  | Erfahrungen aus dem Live‑Betrieb** | Weitergehende Empfehlung |
| :---  | :---  | :---  |
| Ohne grundlegende Verbesserung der UX von Beantragung bis zu Anwendungsfällen ist es unwahrscheinlich, dass die Verbreitung signifikant steigen wird. Um die Markenbildung zu unterstützen, empfehlen wir, für Diensteanbieter feste Module (Buttons, Erklärungen etc.) zur Verfügung zu stellen, die sie direkt im richtigen Design implementieren können.  | Widget erprobt: Als erste Komponente wurde ein Widget für Desktop und mobile Anwendungen entwickelt, welches in den Testservice ‘Grundsteuererklärung für Privateigentum’ eingebunden war. Es unterstützt die Nutzerführung im eID-Flow.  | Es braucht ein stringentes Service-Design: Nutzende werden klar, einfach und einheitlich durch den Service geführt. Wir empfehlen für eine verbesserte Markenbildung und einheitliche Erklärung: Ausbau des Widgets als Hilfestellung der Nutzer:innen zur Erfüllung der technischen & PIN- Voraussetzungen sowie für den Gerätewechsel. Für Dienste sollte es einheitliche Komponenten zur Integration geben, wie standardisierte Ident-Button und Erklärtexte. |

### Kommunikation & Testanwendung

| Empfehlung aus der Analysephase*  | Erfahrungen aus dem Live‑Betrieb** | Weitergehende Empfehlung |
| :---  | :---  | :---  |
| Um effektivere Kommunikation zu gewährleisten und die vielen wertvollen Inhalte zu vermitteln, sollte das Personalausweisportal nutzerzentriert teilweise neu gestaltet werden. Damit das mit voller Wirksamkeit möglich ist, muss der Government-Site- Builder modernisiert oder durch ein anderes CMS ersetzt werden. Um die erste Nutzung der eID zu erleichtern, sollte eine unverbindliche und neutrale Testanwendung angeboten werden.  | Das Nutzerfeedback sowie Supportanfragen zeigten, wie erklärungsbedürftig die Begrifflichkeiten sind. Es wurde eine Iteration der Beschreibungen in der App vorgenommen und außerdem  Feedback-Umfragen durchgeführt. In einem internen Hackathon wurde eine Beispielanwendung entwickelt. | Die eID sollte besser erfahrbar gemacht werden. Dazu braucht es zugängliche Informationen, bspw. über ein Info-Portal als Website. Begrifflichkeiten auf dieser Website müssen vereinheitlicht und vereinfacht werden. Mindestens ein realer Anwendungsfall sollte als Testanwendung bereitgestellt werden – insbesondere vor dem Hintergrund einer möglichen Kampagne. Funktionen müssen bekannt gemacht und durch informierte Mitarbeitende in Bürgerämtern unterstützt werden. |

### Wiedererkennbarkeit & Marke

| Empfehlung aus der Analysephase*  | Erfahrungen aus dem Live‑Betrieb** | Weitergehende Empfehlung |
| :---  | :---  | :---  |
| Um den Wiedererkennungswert der Online-Ausweisfunktion zu steigern, empfehlen wir, die Marke eID weiter zu gestalten und als starke, wiedererkennbare (Sub)Marke zu etablieren. So motiviert man Personen, die der Funktion zum zweiten oder dritten Mal begegnen, sich damit stärker zu beschäftigen. Wir empfehlen, die Marke stark mit dem Corporate Design des Bundes zu assoziieren. | Der [Corporate Design Styleguide der Bundesregierung](https://styleguide.bundesregierung.de/sg-de/) wurde angewendet, der Bundesadler zur staatlichen Wiedererkennung genutzt und der Produktname BundesIdent in einem ausführlichen Prozess in der Interaktion mit Bürger:innen generiert. | Wir empfehlen die Vereinheitlichung der beteiligten Komponenten anhand des Bundes-Styleguides, idealerweise mit dem Ziel einer einheitlichen Dachmarke. Zudem, siehe oben,  muss es leicht integrierbare Komponenten für Diensteanbieter geben, wie das Widget, für einen einheitlichen Einstieg in den Identifizierungsprozess über Dienste hinweg. |

### Inklusion & Alternativen

| Empfehlung aus der Analysephase*  | Erfahrungen aus dem Live‑Betrieb** | Weitergehende Empfehlung |
| :---  | :---  | :---  |
| Derzeit ist die Online-Ausweisfunktion auf Basis der physichen ID-Karte per se nicht inklusiv und für alle nutzbar. Wir empfehlen eine Erweiterung um additive Komponenten, z. B. europäisch regulierte qualifizierte elektronische Signaturen (QES), um eine durchgängige Nutzung am Mobiltelefon zu ermöglichen und so Inklusivität zu stärken. | Im ersten Anwendungsfall „Grundsteuererklärung“ gab es alternative Möglichkeiten zur Identifizierung. Dies ist aus Inklusionsgründen wichtig. Bis zum Schluss entschieden sich nur 20 % der Nutzer:innen für eine Identifizierung mit dem Ausweis. | Es müssen alternative Identifikationsoptionen zur eID ermöglicht werden. Gleichzeitig sollte von anderen erfolgreichen  europäischen Identifizierungs- lösungen gelernt und EU-Standards wie die QES breitflächig angeboten werden. Dies beinhaltet auch, Diensten eine Vorgabe zu den erforderlichen Vertrauensniveaus zu machen. |

\* Übergabe der Handlungsempfehlungen aus der Analysephase an das BMI im Februar 2022

** November 2022 – Juni 2023

## 5. Exploration: Gerätwechsel mit WebAuthn
https://github.com/digitalservicebund/useid-documentation/assets/4391042/51f1afb3-8d52-4ff3-9016-d451ae5c3cd9

Um den Gerätewechsel zu vereinfachen, haben wir einen technischen Prototypen mit dem [WebAuthn-Standard](https://www.w3.org/TR/webauthn-3/) entwickelt. Der Vorteil: Es muss keine Desktopapp heruntergeladen werden. Um den Flow zu vereinfachen, könnte ein QR-Code-Scanner direkt in die App integriert und überflüssige Schritte entfernt werden. Desweiteren könnten ergänzende Erklärtexte besser durch den neuartigen Flow mit Passkeys leiten.
Weitere technische Informationen unter: https://github.com/digitalservicebund/useid-architecture/tree/main/research/device-switch 

## 6. Entwurf eines Einrichtungsassistenten für die AusweisApp2
![Einrichtungsassistent_AusweisApp2](https://github.com/digitalservicebund/useid-documentation/assets/4391042/a2e8ac68-275a-4e2c-8f3d-98d23c88ff90)

In der ersten Projektphase haben wir einen Einrichtungsassistenten für die AusweisApp2 auf Desktop und Mobile entworfen: [Design in Figma](https://www.figma.com/file/f6DoOUO7ggCYosH8jYhqD4/Onboarding-proposal-for-the-AusweisApp2?type=design&node-id=1608%3A949&mode=design&t=YCgYMWYrJfTqF8sB-1). Unsere Hypothese: Wie in einem Gespräch hilft der Einrichtungsassistent,
die eID mit der AusweisApp2 einzurichten. Modernes Auftreten und freundliche, wenig technische Texte vermitteln Spaß beim Kennenlernen der neuen Technologie. Ein strukturierter Dialog unterstützt Bürger:innen beim Einrichten der 6-stelligen Wunsch-PIN und lässt sie den nicht-trivialen Prozess der Identifizierung mit eID in der AusweisApp2 kennenlernen.

## 7. Ergebnisbericht Usability-Test eID & AusweisApp2
![Ergebnisbericht-Usability-Test-eID- -AusweisApp2](https://github.com/digitalservicebund/useid-documentation/assets/4391042/fc8ab724-89e8-46aa-8e29-22536f41d8d6)

Der [Ergebnisbericht Usability‑Test eID & AusweisApp2 als PDF](https://github.com/digitalservicebund/useid-documentation/files/12729446/Ergebnisbericht_Usability-Test_eID_AusweisApp2.pdf). 2021 haben wir sechs qualitative Interviews á 60 Minuten geführt. Die Teilnehmer:innen sollten online ihre Punkte in Flensburg nachgucken. Dazu war die Ersteinrichtung der eID mithilfe des PIN-Briefes und die Nutzung der AusweisApp2 notwendig. Unsere Haupterkenntnisse:
- Der Mehrwert der eID ist nicht eindeutig für Bürger:innen. Somit ist das Interesse zum initialen Einrichten nicht hoch.
- Bürger:innen wissen nicht, was „NFC“ ist und ob ihr Smartphone NFC-fähig ist.
- Der PIN-Brief kommuniziert die Notwendigkeit der AusweisApp2 nicht. Die Notwendigkeit wird erst auf der Seite des Diensteanbieters klar. Unklar bleibt, dass damit auch eine Desktop-App gemeint ist.
- Da die Handhabung der Kombination von Smartphone als Lesegerät und der Desktop-App nicht verstanden wird, bleiben die meisten Nutzer:innen auf dem Smartphone.
- Der Scan-Vorgang zur Authentifizierung kann schnell erlernt werden und begeistert Nutzer:innen. Allerdings wird nicht klar, warum der Ausweis beim Diensteanbieter wiederholt gescannt werden muss.
- Insgesamt gibt es innerhalb der AusweisApp2 keine großen Usability-Probleme. Es sind die Erwartungen der Nutzer:innen und der unhandliche Kopplungsprozess, sowie der Wechsel zwischen Diensteanbieter und AusweisApp2, die die Nutzung verkompliziert.

## 8. Ergebnisbericht: Nutzung der eID durch Diensteanbieter
Der [Ergebnisbericht: Nutzung der eID durch Diensteanbieter als PDF](https://github.com/digitalservicebund/useid-documentation/files/13266394/Ergebnisbericht_Nutzung.der.eID.durch.Diensteanbieter_Projektphase.Research_2022_Januar.pdf). Ende 2021 haben wir 25 qualitative Interviews á 60 Minuten geführt und den Markt analysiert.

### Unsere Leitfrage für die Recherche
Die Frage ist nicht nur, welche Hürden die eID-Einführung an sich hat, sondern warum sich die eID als Lösung aktuell nur schwer gegen die anderen etablierten Identifizierungsoptionen durchsetzen kann.

### Unser Fazit
Organisatorische, technische und wirtschaftliche Anforderungen stellen nicht die größte Hürde dar. Damit Diensteanbieter die eID neben anderen Optionen der Identifizierung anbieten, muss eine höhere Nutzer:innen-Basis mit eingerichteter PIN gewonnen sowie die Erfahrung der Bürger:innen mit der staatlichen digitalen Identität verbessert werden. Gleichzeitig sollten durch weiteren aktiven Austausch Erkenntnisse und Bedürfnisse der Privatwirtschaft in die Weiterentwicklung der digitalen Identität einfließen.

## 9. Fünfzehn allgemeine Handlungsempfehlungen für eine erhöhte Verbreitung der Online-Ausweisfunktion basierend auf qualitativer Forschung aus 2021
Die Handlungsempfehlungen basieren auf qualitativer Forschung Expert:innen- und Nutzer:inneninterviews, Usability Tests, Resonanztests, Expertenanalysen des Teams sowie der im September 2021 durchgeführten quantitativen Studie.

### 1. eID als starke Marke bzw. Submarke

#### Empfehlung
Um den Wiedererkennungswert der Online-Ausweisfunktion zu steigern, empfehlen wir, die Marke eID weiter zu gestalten und als starke, wiedererkennbare Marke anzustreben. So motiviert man Personen, die der Funktion zum zweiten oder dritten Mal begegnen, sich damit stärker zu beschäftigen. Wir empfehlen auch, die Marke stark mit dem Corporate Design des Bundes zu assoziieren, die Vorteile der Marke Staat zu nutzen.

#### Problem / Evidenz
Bestehende Anwendungsfälle werden nicht mit einem einheitlichen System assoziiert, welches nur einmal eingerichtet und verstanden werden muss. Dadurch erscheint die Komplexität unverhältnismäßig zum Aufwand der Einrichtung.

#### Maßnahmen
Einheitliche Vorgaben, was die Einbindung und Beschreibung der Online-Ausweisfunktion betrifft. Mehr Klarheit in der Präsentation und Verfügbarkeit der Empfehlungen, wie z.B. langen Fließtext vermeiden, Personalasuweisportal als zentrales Portal nutzen und Anbieter stärker koordinieren. Gestaltung stets als Marke des Bundes, nicht getrennt davon.

**Zielgruppe**: Alle

**Quelle**: Interviews, Resonanz- testing, Studie

**Adressat:innen der Empfehlung**: Kampagne

### 2. Dediziertes Team für strategische Verbreitung der eID

#### Empfehlung
Um die Verbreitung der eID kontinuierlich und nachhaltig zu steigern, empfehlen wir ein Koordinationsteam, welches die verschiedenen Angebote koordiniert und die übergreifende Strategie für das Ökosystem entwickelt.

#### Problem / Evidenz
Es gibt viele engagierte Akteure, die zur Weiterentwicklung der eID beitragen. Allerdings sind diese überwiegend eng an ihre Zuständigkeiten gebunden und fördern so nur das sehr konkrete Element des Gesamtsystems, für welches sie verantwortlich sind. Die Verbreitung wird aber durch das Zusammenspiel all dieser Elemente gesteigert.

#### Maßnahmen
Analyse und kontinuierliche Einschätzung der angebotenen Integrationsmodelle, Koordinierung übergreifender Kommunikation, stärkere Integration der Akteure, wie z.B. Identifizierungsdiensteanbieter, in die Gesamtplanung, Betrachtung der eID als Gesamtangebot.

**Zielgruppe**: Alle

**Quelle**: Experten-Interviews, Analyse

**Adressat:innen der Empfehlung**: BMI

### 3. Wertversprechen eID

#### Empfehlung
Um das Wertversprechen der eID realistisch an die Nutzer:innen zu kommunizieren und keine falschen Erwartungen zu erzeugen, sollten die realen Vorteile, wie z.B. zeitsparend und ortsunabhängig, der eID kommuniziert werden.

#### Problem / Evidenz
Die Identifikation per eID ist komplex und benötigt etwas Zeit, was einem gründlichen Identifikationsverfahren inhärent ist. Die eID ist aktuell noch kein intuitiver und einfacher Prozess. Erwartungen in der Gesellschaft sind aber geprägt durch weniger sicherheitsrelevante Abläufe wie z.B. PayPal, E-Mail, Anmeldung mit Google. Diese Vergleiche werden durch die Nutzung des Wortes „einfach“ in diesem Kontext hervorgerufen.

#### Maßnahmen
„Einfach“ als Wertversprechen vermeiden; „zeitsparend“, „ortsunabhängig“, „flexibel“ und synonyme erwägen; als Vergleichswert den Gang zum Amt positionieren.

**Zielgruppe**: Alle

**Quelle**: Interviews, Quantitative Studie

**Adressat:innen der Empfehlung**: Kampagne

### 4. Bausteine für Diensteanbieter

#### Empfehlung
Um die Markenbildung zu unterstützen, empfehlen wir für Diensteanbieter, einzelne Module wie zum Beispiel Buttons und Erklärungen zur Verfügung zu stellen, die sie direkt im richtigen Design implementieren können.

#### Problem / Evidenz
Jeder Anwendungsfall hat eine abweichende Kommunikation der eID. Begrifflichkeiten werden unterschiedlich, teilweise falsch verwendet. Die Gestaltung der Integration ist komplett unterschiedlich.

#### Maßnahmen
Eine von Integrationsoptionen unabhängige bzw. übergreifende Anlaufstelle mit offen verfügbaren Bausteinen, die schnell und einfach übernommen werden können. Beispiel: https://stripe.com/docs/payments/elements

**Zielgruppe**: Unternehmen, IT-Dienstleister

**Quelle**: Experteninterviews

**Adressat:innen der Empfehlung**: Kampagne

### 5. Priorisierung regelmäßiger Alltags- Anwendungsfälle

#### Empfehlung
Um die Anlässe der Nutzung der eID zu steigern, sollte die Schaffung und Weiterentwicklung der Nutzungsanlässe priorisiert werden, die regelmäßig im Alltag der Bürger:innen vorkommen.

#### Problem / Evidenz
Die Bürger:innen müssen Anlässe zur Nutzung der eID erhalten in Situationen, in denen sie sich sowieso regelmäßig befinden.

#### Maßnahmen
Integration der eID in häufig genutzte Verwaltungsleistungen in OZG-Umsetzung priorisieren.

**Zielgruppe**: Nutzer:innen

**Quelle**: Interviews, Quantitative Studie

**Adressat:innen der Empfehlung**: BMI, Länder, Kommunen

### 6. Strategie für Anlaufstellen im Netz (Landingpages)

#### Empfehlung
Um den schnellen Einstieg in das eID Ökosystem zu ermöglichen, sollten die im Netz verfügbaren Ressourcen und Anlaufstellen möglichst reduziert und maximal klar positioniert werden. So können Interessierte auf den ersten Blick verstehen, ob sie an der richtigen Stelle sind, und wenn nicht — wohin sie weiter müssen.

#### Problem / Evidenz
Aktuell werden das Personalausweisportal sowie der Webauftritt der AusweisApp2 häufig in der Kommunikation zur eID referenziert. Durch die Vielzahl an Anlaufstellen im Netz sind besonders neue und potenzielle Nutzer:innen verwirrt und verunsichert; sie haben Schwierigkeiten, die richtigen Informationen zu finden.

#### Maßnahmen
Die Positionierung der verschiedenen Portale stärker differenzieren, vor allem in Abgrenzung zueinander; eine Anlaufstelle als zentral für die Online-Ausweisfunktion als solche definieren und zumindest in der offiziellen Kommunikation berücksichtigen; neue Anlaufstellen vermeiden.

**Zielgruppe**: Alle

**Quelle**: Interviews, Usability Tests

**Adressat:innen der Empfehlung**: Kampagne

### 7. Kommunikation über Fließtext reduzieren

#### Empfehlung
Um effektivere Kommunikation zu gewährleisten, sollte Informationsmaterial möglichst knapp und visuell aufbereitet sein.

#### Problem / Evidenz
Inhalte sind teilweise schwer auffindbar, weil sie in langen Fließtexten integriert sind. Beispiele: Im Personalausweisportal werden mögliche Integrationsmöglichkeiten für neue Diensteanbieter unbetitelt in einem Introtext untergebracht, obwohl sie eine der wichtigsten ersten Informationen sind. Ein Großteil der Startseite des AusweisApp-Portals besteht aus einer Fließtextbeschreibung, der Interaktive Teil ist erst am Ende der Seite zu finden.

#### Maßnahmen
Angemessener Satz für alle Inhalte; strukturierte Darstellung von Textmengen in kleineren, inhaltlich passenden Gruppen.

**Zielgruppe**: Alle

**Quelle**: Usability Test, Expertenanalyse

**Adressat:innen der Empfehlung**: BMI, BSI, Governikus

### 8. [Personalausweisportal](https://www.personalausweisportal.de) (PAP) / [Government-Site-Builder](https://produkt.gsb.bund.de) (GSB)

#### Empfehlung
Um effektivere Kommunikation zu gewährleisten und die vielen wertvollen Inhalte zu vermitteln, sollte das Personalausweisportal nutzerzentriert teilweise neu gestaltet werden. Damit das mit voller Wirksamkeit möglich ist, muss der GSB modernisiert oder gegebenenfalls durch ein anderes CMS ersetzt werden.

#### Problem / Evidenz
Die Navigation sowie allgemeine Informationsarchitektur des Personalausweisportals fördert derzeit nur bedingt die Auffindbarkeit von Informationen. Bspw. verfügt der „Behördenportal“-Teil nicht über eine dedizierte Navigation, wodurch Nutzer:innen wissen müssen, wonach sie suchen, um auf bestimmte Inhalte zu stoßen. An vielen anderen Stellen werden Grundprinzipien einer effektiven Informationsarchitektur nicht berücksichtigt. Die Machbarkeitsanalyse hat ergeben, dass diese Tatsachen stark durch die Funktionsweise und den Umfang des GSB beeinflusst und die Seite nicht frei umgestaltet werden kann.

#### Maßnahmen
Prüfung, ob der GSB ein geeignetes System für die Bereitstellung von bürgerfreundlicher und verständlicher Kommunikation ist. Nutzertests und anschließende Gestaltung entlang von Nutzungszielen und -pfaden.

**Zielgruppe**: Alle

**Quelle**: Usability Tests, Machbarkeitsanalyse, Expertenanalyse

**Adressat:innen der Empfehlung**: BMI

### 9. Positionierung von Apps

#### Empfehlung
Um einen schnellen Einstieg in das eID Ökosystem zu ermöglichen, empfehlen wir, die Ausweis-App des Bundes AusweisApp2 auch so zu positionieren. Um die Offenheit des Ökosystems zu behalten, kann entsprechende Kommunikation ergänzt werden, bzw. weitere Maßnahmen in diese Richtung ergriffen werden.

#### Problem / Evidenz
Der Vertrauensbonus, den man durch einen „Bundes“-Herausgeber (BSI, BMI, Bundesdruckerei) der Apps und die Gestaltung konform mit dem [Corporate Design Styleguide der Bundesregierung](https://styleguide.bundesregierung.de) via Schriften und Bundesadler bekommt und die Resilienz und Motivation der Nutzer:innen, die man dadurch steigern kann, tritt bei der AusweisApp2 nicht ein. Es wird damit argumentiert, dass die AusweisApp2 nicht die einzige App ist und andere Apps nicht benachteiligt werden sollen. Diese Apps werden aber bereits benachteiligt, da sie weder so prominent auf dem [Personalausweisportal](https://www.personalausweisportal.de), noch in der Kommunikation in den Anwendungsfällen berücksichtigt werden. So hat man alle Nachteile und keine der Vorteile.

#### Maßnahmen
Anwendung des [Corporate Design Styleguides der Bundesregierung](https://styleguide.bundesregierung.de), Herausgeber in den App Stores BSI, BMI oder Bundesdruckerei welche intuitiv mit Ausweiswesen assoziiert wird

**Zielgruppe**: Nutzer:innen

**Quelle**: Usability Tests, Interviews

**Adressat:innen der Empfehlung**: BMI, BSI

### 10. Behördenportal Bekanntheit

#### Empfehlung
Um einen effektiven Kommunikationskanal mit den Bürgerämtern und -büros zu schaffen, empfehlen wir als Teil der Kampagne auch das Behördenportal bei Behördenangestellten zu bewerben.

#### Problem / Evidenz
Das Behördenportal innerhalb des [Personalausweisportals](https://www.personalausweisportal.de) ist vielen Sachbearbeiter:innen in Bürgerämtern nicht bekannt. Gleichzeitig wissen wir aus der quantitativen Studie, dass Bürger:innen aktuell vor allem beim Beantragen des Personalausweises überhaupt von der eID erfahren. Die Mitarbeiter:innen in Behörden und Bürgerämtern/ -büros als erster Kontaktpunkt der Nutzer:innen mit der eID müssen entsprechend gut informiert werden.

#### Maßnahmen
Behördenangestellte als Zielgruppe der Kampagne

**Zielgruppe**: Mitarbeiter:innen in Behörden und Bürgerämter/ -büros

**Quelle**: Interviews, Quantitative Studie

**Adressat:innen der Empfehlung**: Kampagne

### 11. Testausweise für Bürgerämter

#### Empfehlung
Um Mitarbeiter:innen Behörden und Bürgerämter/ -büros den einfachen Zugang zur Online-Ausweisfunktion zu ermöglichen, können Testausweise eine wertvolle Bereicherung des Infomaterials sein, damit die eID-Nutzung für die Mitarbeiter:innen erfahrbar wird.

#### Problem / Evidenz
Nur wenn eine Erfahrung selbst gemacht wird, kann sie wirklich verstanden und verinnerlicht werden. Die Mitarbeiter:innen der Bürgerbüros, mit denen wir Gespräche geführt haben, hatten die eID selbst bisher nicht benutzt. Entsprechend unmöglich ist es für sie, informiert und emphatisch Fragen zum Wert, zum Aktivieren oder zur Benutzung der eID den Bürger:innen zu beantworten.

#### Maßnahmen
Behördenangestellten das Ausprobieren der eID ermöglichen

**Zielgruppe**: Mitarbeiter:innen in Behörden und Bürgerämter/ -büros

**Quelle**: Resonanztests

**Adressat:innen der Empfehlung**: BMI

### 12. Wissenstransfer Bürgerämter

#### Empfehlung
Um Mitarbeiter:innen in Behörden und Bürgerämtern/ -büros als ersten wichtigen Kontaktpunkt der Nutzer: innen mit der eID wertvoll zu machen, braucht es viele verschiedene Wege zum Wissenstransfer, wie Spickzettel, Behördenportal, Schulungen, Ausbildungsmodul, E-Mail / Updates.

#### Problem / Evidenz
Viele Mitarbeiter:innen in Behörden und Bürgerämtern/-büros haben ein Bedürfnis nach mehr Information. Die Art und Weise, wie sie diese am besten erhalten und in ihren Arbeitsalltag gut integrieren können, muss weiter iterativ erforscht werden.

#### Maßnahmen
Wissenstransfer in die Bürgerämter und -büros weiterverfolgen

**Zielgruppe**: Mitarbeiter:innen in Behörden und Bürgerämter/ -büros

**Quelle**: Interviews, Resonanztests, Quantitative Studie

**Adressat:innen der Empfehlung**: BMI

### 13. Testanwendung

#### Empfehlung
Um die erste Nutzung der eID zu erleichtern, sollte eine unverbindliche und neutrale Testanwendung angeboten werden.

#### Problem / Evidenz
Nutzer:innen sind motiviert, direkt nach Erhalt des Ausweises die neue Funktion auszuprobieren, es fehlen oft relevante Anlässe in dem Moment; echte Anbieter kommunizieren den Ablauf teilweise nicht optimal und sind daher ein schlechter erster Einstieg.

#### Maßnahmen
Selbstauskunft um eine Browser- Komponente erweitern, um den Wechsel zwischen Anbieterseite und AusweisApp üben zu können.

**Zielgruppe**: Nutzer:innen, Mitarbeiter:innen in Behörden und Bürgerämtern/- büros

**Quelle**: Resonanztests, Quantitative Studie

**Adressat:innen der Empfehlung**: BMI

### 14. Broschüre zur eID Ausgabe im Bürgeramt/ -büro

#### Empfehlung
Um den ersten wichtigen Kontaktpunkt der Nutzer:innen mit der eID wertvoll zu gestalten, sollte die Broschüre zu eID, die beim Beantragen/ Abholen des neuen Personalausweises im Bürgeramt/ -büro ausgegeben wird, auf Basis von echtem Nutzer:innen-Feedback weiterentwickelt werden.

#### Problem / Evidenz
Die Situation des Beantragens oder Abholen des Personalausweises selbst kann lediglich zum Erregen von Aufmerksamkeit genutzt werden und nicht zur umfassenden Informationsvermittlung. Die Aufmerksamkeit kann zu einer Auseinandersetzung mit der eID konvertiert werden, wenn zeitnah eine wertvolle Information folgt, z. B. über die Broschüre.

#### Maßnahmen
Iterative Weiterentwicklung der Broschüre zur eID auf Basis von echtem Nutzer:innen-Feedback.

**Zielgruppe**: Nutzer:innen im Bürgeramt/ -büro

**Quelle**: Interviews, Quantitative Studie

**Adressat:innen der Empfehlung**: Kampagne

### 15. Sparen bei eID-Nutzung

#### Empfehlung
Um die Nutzung der eID attraktiver zu machen, können finanzielle Ermäßigungen oder der Erlass von Bearbeitungsgebühren eingesetzt werden.

#### Problem / Evidenz
Nutzer:innen wählen oft den bekannten Weg zum Amt, auch wenn sie diesen als lästig empfinden, weil sie sich nicht mit der technischen Lösung auseinandersetzen wollen und nicht genügend intrinsische Motivation dafür haben.

#### Maßnahmen
Vertesten von verschiedenen Ideen zur Senkung der Hürde, wie Gebühren ermäßigen oder erlassen, wenn Anliegen online erledigt werden.

**Zielgruppe**: Nutzer:innen

**Quelle**: Resonanztests, Quantitative Studie

**Adressat:innen der Empfehlung**: BMI, Länder, Kommunen

## 10. Nutzungsreise der Bürger:innen und Diensteanbieter
![Nutzungsreise_eID](https://github.com/digitalservicebund/useid-documentation/assets/4391042/bb76e75f-8e39-4c07-9dc7-8870a013c6e2)

Die aus den qualitativen Interviews mit Nutzer:innen, Expert:innen und Mitarbeitenden in Verwaltung und Bürgerbüros entstandene Nutzungsreisen zeigen, dass die Akzeptanzprobleme der eID schon beim Erhalt des Personalausweises einsetzen. Die [Nutzungsreise aus Sicht der Bürger:innen als PDF](https://github.com/digitalservicebund/useid-documentation/files/13266457/Nutzungsreise_eID_BurgerInnen.pdf) und die [Nutzungsreise aus Sicht der Diensteanbieter als PDF](https://github.com/digitalservicebund/useid-documentation/files/13266458/Nutzungsreise_eID_Diensteanbieter.pdf). Unsere Haupterkenntnisse:

- Die Erfahrung auf dem Amt bei Beantragung eines neuen Personalausweises trägt nicht zu dessen Nutzung im digitalen Raum bei. Teilweise wird Bürger:innen sogar aktiv abgeraten, die Online-Ausweisfunktion zu nutzen.
- Der PIN-Brief zur Aktivierung der Online-Ausweisfunktion verwirrt die Nutzer:innen. Sie können seine Relevanz nicht einschätzen.
- Es vergeht zu viel Zeit, Monate bis Jahre, zwischen Erhalt des Personalausweises mit Online-Ausweisfunktion und der ersten Nutzung: die eID gerät in Vergessenheit.
- Es gibt zu wenig konkrete Anwendungsfälle, die zur Nutzung motivieren.
- Die initiale Nutzung der eID ist komplex, es fehlt an Übung und Erklärung.
- Es ist unklar, wie genau die eID genutzt wird.

Weitere Informationen in unserem Blogpost: [Der Online-Ausweisfunktion zum Durchbruch verhelfen](https://digitalservice.bund.de/blog/projekt-digitale-identitaeten).

## 11. Mögliche Ansatzpunkte zur Anpassung von technischen eID-Richtlinien und der Personalausweisverordnung anhand von Beobachtungspunkten der User-Journey mit der eID
![Nutzungsreise_eID](https://github.com/digitalservicebund/useid-documentation/assets/4391042/8f97f346-5fe7-4c42-8340-ecaf7c7d7aee)

Dies ist ein Arbeitsstand aus der Pilotphase der BundesIdent App. Die übergreifende Zielsetzung der Ideen ist, das Nutzungserlebnis mit der eID wesentlich zu verbessern. Dazu schlagen wir vor, bestehende Entscheidungen zu hinterfragen und offen über mögliche
Änderungen zu diskutieren.

### Hinweis
Einer Ideensammlung wie dieser wohnt inne, dass die meisten Ideen wohl an der weiteren Validierung der Nutzerbedarfe, Sinnhaftigkeit
oder Machbarkeit scheitern werden. Deshalb ist diese Sammlung von UX-Hürden und Ideen als Gedankenanstoß gedacht.

### Vorgehen
Die meisten Hürden und Ideen sind aus der Pilotphase der BundesIdent App entstanden, welche qualitative wie quantitative Nutzungsdaten
generiert hat. Regelmäßige Tests mit Nutzenden sowie technische Explorationen haben diese Erkenntnisse ergänzt.

### Legende
⚡️ Hürden

💡 Erste Ideen, die weiter zu validieren sind

### Erhalt des PIN-Briefes

- ⚡️ Nutzende erhalten einen neuen Ausweis und richten diesen jedoch nicht direkt ein beziehungsweise nutzen ihn nicht direkt.
- ⚡️ Nutzende bringen den PIN-Brief nicht in Verbindung mit dem Ausweis, den sie physisch im Bürgerbüro erhalten.
- 💡 Den Prozess in den Bürgerbüros analysieren und gegebenenfalls anpassen.
	- PIN direkt im Bürgeramt setzen und/oder einen Service vor Ort nutzen.
	- Hilfestellung für Nutzende anbieten, die nicht digitalaffin sind.
- 💡 Den zeitlichen Abstand und somit den Bruch zwischen Erhalt des Ausweises und Erhalt des PIN-Briefes eliminieren.

### PIN vergessen
Relevante technische Richtlinien und Verordnung: [BSI TR-03124 eID-Client](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/Technische-Richtlinien/TR-nach-Thema-sortiert/tr03124/TR-03124_node.html), [TR-03128 Teil 3](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Publikationen/TechnischeRichtlinien/TR03128/BSI_TR-03128_Teil3.pdf?__blob=publicationFile&v=2) & [PAuswV](https://www.gesetze-im-internet.de/pauswv/index.html)

- ⚡️ Nutzende erwarten bei der Funktion einer PIN-Rücksetzung das gleiche Nutzungserlebnis wie bei einer gewöhnlichen „Passwort
vergessen“-Funktion. Der PIN-Rücksetzdienst sowie der CAN- und PUK-Flow erfüllt diese Erwartungen nicht.
- ⚡️ User-Flow über mehrere Produkte, Medien oder Anbieter kann verwirren:
	- Der PIN-Rücksetzbrief leitet auf die Website, von der aus wiederum in die App weitergeleitet wird, in der die PIN eingegeben werden
muss.
	- Führung der Nutzenden über die externe Domain der Bundesdruckerei ist vorgeschrieben, da BDR als Anbieter des Dienstes
festgelegt §7 PAuswG [4] (3a) ist. Zudem ist die Umsetzung in Form einer Website festgeschrieben.
- ⚡️ Die Kommunikation rund um den Aktivierungscode sowie eine neue PIN ist verwirrend.
- ⚡️ Briefversand verhindert Servicenutzung in einem konkreten Moment und erhöht die Abbruchquote stark. Der Briefversand ist
deshalb eine UX-Hürde.
	- Zustellung des PIN-Rücksetzbriefes nach Überprüfung der Identitätsangaben durch Vorlage des Personalausweises
vorgeschrieben, PAuswV [6] Neusetzen der PIN in §20 (2).
- 💡 Quick Fix: PIN-Rücksetzbrief direkt aus der App beantragen, ohne Wechsel zur Website.
- 💡 Alternativen für eine digitale PIN-Rücksetzung explorieren.

### Transport-PIN vs. persönliche Ausweis-PIN
Relevante technische Richtlinie: [BSI TR-03124 eID‑Client](https://www.bsi.bund.de/DE/Themen/Unternehmen-und-Organisationen/Standards-und-Zertifizierung/Technische-Richtlinien/TR-nach-Thema-sortiert/tr03124/TR-03124_node.html)

- ⚡️ Nutzende verstehen den Unterschied zwischen einer fünfstelligen Transport-PIN und der sechsstelligen persönlichen Ausweis-PIN
nicht. Nutzende verstehen nicht, dass die Einrichtung vom Ausweis abhängig ist und nicht vom Gerät (so kennen sie es von Banking-
Apps).
- ⚡️ Nutzende verstehen daher nicht, dass die fünfstellige Transport-PIN nach einmaliger Eingabe verfällt. Nutzende geben die bereits
verwendete Transport-PIN erneut ein, weil sie denken, sie müssen den Ausweis auf dem Gerät nochmals einrichten. Das technische
Framework wiederum kann nicht feststellen, ob ein Ausweis bereits eingerichtet wurde. Dies führt dann zu einer Sperrung.
- ⚡️ Wir Es wird komplett den Nutzenden überlassen zu verstehen, ob sie den Ausweis bereits eingerichtet haben. Das führt dazu, dass
sie gefragt werden müssen, ob sie eine fünf- oder sechsstellige PIN haben. Wenn Nutzende jetzt im CAN-Szenario landen, müssen
diese wieder eine neue sechsstellige Nummer eingeben. Im schlimmsten Fall auch noch die zehnstellige PUK, da nur diese die erneute
sechsstellige PIN-Eingabe freischaltet. Das stresst und frustriert die Nutzenden, da die Situationen, in denen sie sich ausweisen
müssen, meistens dringend sind (Führungszeugnis, Grundsteuererklärung).
- 💡 Dem Framework die Möglichkeit geben, eigenständig zu erkennen, ob ein Ausweis bereits eingerichtet ist. So wird verhindert, dass
ein Ausweis fälschlicherweise gesperrt wird.
- 💡 Anwendung der CAN hinterfragen beim Anwendungsfall, dass jemand seinen PIN tatsächlich vergessen hat. Hier kann auch ein
direkter Link zum PIN-Rücksetzdienst hilfreich sein.
- 💡 Der Aufbau der CAN sollte sich von der persönlichen PIN unterscheiden bzw. die CAN auf dem Ausweis könnte z. B. mit einem
Label versehen werden, um Verwirrung zu vermeiden.

### Scannen des Ausweises
- ⚡️ Das Scannen des Personalausweises ist eine neue Erfahrung für die Nutzenden. Es ist daher ein natürliches Verhalten, den
Ausweis hin und wieder vom Smartphone wegzubewegen. Doch wenn der Ausweis während des Scanvorgangs entfernt wird, meldet
das Framework eine Fehlermeldung. Der Scanvorgang kann weder automatisch noch direkt in der App erneut gestartet werden.
Nutzende müssen die Identifizierung jetzt erneut beim Diensteanbieter starten. Dieser Medienbruch führt zu Verwirrung.
- 💡 Das Framework erlaubt bei einer Fehlermeldung den Scanvorgang automatisch bzw. direkt in der App auf dem Smartphone erneut
zu starten.

### Gerätewechsel zwischen Desktop/Tablet zu Smartphone
Relevante technische Richtlinie: [TR‑03112‑6 - eCard‑API-Framework](https://www.bsi.bund.de/SharedDocs/Downloads/DE/BSI/Publikationen/TechnischeRichtlinien/TR03112/TR-03112-api_teil6_ergaenzung.pdf?__blob=publicationFile&v=3)

- ⚡️ Die Gerätekopplung der aktuellen Desktop-Version der AusweisApp2 (AA2) mit der mobilen Version der AA2 stellt eine sichere,
jedoch schwierig zu nutzende Lösung dar, die sich nicht etablieren konnte. Beispiele für UX-Hürden: Beide Versionen der App müssen
installiert sein, die Geräte müssen sich im gleichen WLAN befinden und die Kopplung als Vorgang selbst.
- ⚡️ Aus der Privatwirtschaft sind die Nutzenden einfache Flows für den Gerätewechsel gewohnt, die jedoch häufig mit nicht mitigierten
Risiken des Phishings einhergehen. Private Diensteanbieter nutzen zum Beispiel einen QR-Code für den Gerätewechsel, jedoch ohne
weitere Sicherheitsmaßnahmen.
- 💡 Für die Erarbeitung eines sicheren sowie nutzungsfreundlichen Gerätewechsels schlagen wir die Erprobung neuster
Sicherheitsstandards wie WebAuthN oder auch die geräteübergreifende Identifizierung mit Hilfe eines Nutzerkontos wie der BundID vor.
Erste Explorationen dazu wurden veröffentlicht.
