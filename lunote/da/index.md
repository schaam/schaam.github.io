---
layout: default
title: LuNote Manual (DA)
---

---
Layout: Standard
Titel: Lunote Manual
---

# Lunote Brugervejledning

> Sidste opdateret: {{site.time | Dato: '%y-%m-%d'}}

Velkommen til ** Lunote **, din alt-i-en dagbog, Todo og livslogging. Denne guide fokuserer på hovedskærmskontrollerne-hvad der sker, når du trykker, dobbelttryk eller langpress-og giver et overblik over alle større funktioner, så du kan få mest muligt ud af appen.

## 1. startskærm på et øjeblik

| Område | Formål |
| ------ | --------- |
| ** Dato bar ** | Viser dagens dato. Tryk på for at åbne kalendervælgeren og hoppe til enhver dato. |
| ** Kort ** | Hurtige widgets til * i dag dagbog * preview, * d-dag * nedtælling og * trin * resume. |
| ** Bundnavigation ** | Fem faner til dagbog, todo, d-dag, statistik og indstillinger. |
| ** Floating Action (+) -knap ** | Opret nye poster hvor som helst. |

## 2. bundnavigationsknapper

| Knap | Enkelt tap | Dobbelt tryk | Lang presse |
| -------- | ----------- | ----------- | ------------ |
| ** Dagbog ** | Åben dagbogsliste til valgt dato | Rul til toppen af ​​listen | Åben dato picker |
| ** TODO ** | Skift * i dag * ⇄ * i morgen * liste | Kollaps / udvid * I dag * sektion | Marker alle Todos komplet / ufuldstændig |
| ** d-dag ** | Se nedtællingstimere | Spring til nærmeste kommende begivenhed | Sorter / filterindstillinger |
| ** Statistik ** | Åbn hovedstatistikknudepunkt | Cycle Range * 7 → 30 → 90 * dage | Eksport nuværende diagram som CSV |
| ** Indstillinger ** | Åbne præferencer | - | Se appinformation |

## 3. Floating Action -knap (+)

| Gestus | Handling |
| --------- | -------- |
| Tryk på | Vælg * Dagbog * / * TODO * / * D-DAG * Indgangstype |
| Dobbeltknap | Umiddelbar hurtigdiarisk post |
| Lang presse | Stemmekommando (beta) |

## 4. App Bar & Tool Icons

| Ikon | Handling |
| ------ | -------- |
| 🔍 ** Søg ** | Global søgning på tværs af dagbog, TODO og D-Day |
| 🔄 ** Sync ** | Manuel cloud -backup / gendannelse prompt |
| 🔔 ** Midnight Alert ** | Skift 00:00 Daglig påmindelse |
| 📊 ** Send til statistik ** | Skub aktuelle data til statistikmodul |
| ⋮ ** Flere menu ** | Eksport / import • GPS -sporing • Afstandssammenligning • Aktivitetsmønster • ** Databasestyring ** • ** Brugervejledning ** |

## 5. Bevægelser overalt

- ** Stryg til venstre ** → Slet den nuværende vare
- ** Swipe til højre ** → Rediger vare
- ** Knap ** → Juster tekststørrelse på farten
- ** Shake ** → Skift mørk tilstand

## 6. Statistik Dashboard

Åbnede via fanen ** statistik ** tilbyder instrumentbrættet flere sider:

| Side | Widgets & værktøjer |
| ------ | ----------------- |
| ** Dagbogstatistik ** | Indtastningsfrekvensvarmning, nøgleord ord-sky, humørpie diagram |
| ** Trin tæller ** | Daglige trin Linjekort, afstand og kaloriforvurderinger |
| ** Aktivitetsmønster ** | Time-for-time histogram, aktivt / tomgangsforhold |
| ** Sammenligning af afstand ** | Søjlediagram, der sammenligner Walking vs Running vs Cycling |
| ** Daglig rutekort ** | Kortoverlay af GPS -spor (kræver placeringstilladelse) |
| ** Vejr & måne ** | Vejrtrends og månefase -widgets |

Hvert diagram understøtter:*zoom / pan*med knivspids,*rækkevidde*(dobbelt-tap) og ** eksport ** som PNG / CSV / PDF via øverste højre menu.

## 7. Backup & Restore

1. Åbn ** Indstillinger ▸ Backup / Gendan **.
2. Opret forbindelse til Google Drive (kun første gang).
3. Tap ** Backup nu ** for at uploade JSON + SQLITE SNAPSHOT.
4. For at gendanne skal du vælge en sikkerhedskopi og tap ** gendanne **.

## 8. Faq

** Hvorfor vises annoncer ikke? **  
Annoncer kan være tomme i op til 48 timer efter en frisk udgivelse af play-butik. For at verificere integration skal du aktivere ** Test -annoncer ** i*Indstillinger ▸ Debug*.

** iCloud / Drive Sync sidder fast? **  
Log ud af sky -kontoen og log ind igen, og prøv derefter igen.

## 9. Support

- E -mail: [support@lunote.app] (mailto: support@lunote.app)
- Github -problemer: <https://github.com/schaam/lunote/issues>

---
Lavet med ❤ af ** lunote -teamet **