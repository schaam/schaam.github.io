---
layout: default
title: LuNote Manual (FI)
---

---
Asettelu: oletusarvo
Otsikko: Lunote -käsikirja
---

# Lunote -käyttöohje

> Viimeksi päivitetty: {{Site.Time | Päivämäärä: '%y-%m-%d'}}

Tervetuloa ** LUNOTE **, all-in-one-päiväkirjaasi, TODO- ja Life-Loging Companion. Tämä opas keskittyy päähallinohjaimiin-mitä tapahtuu, kun napautat, kaksoisnauhat tai pitkäpuristus-ja antaa yleiskuvan jokaisesta tärkeästä ominaisuudesta, jotta voit saada kaiken irti sovelluksesta.

## 1. Aloitusnäyttö yhdellä silmäyksellä

Ja Alue | Tarkoitus |
| ------ | --------- |
Ja ** Päivämääräpalkki ** | Näyttää tämän päivän päivämäärän. Napauta avataksesi kalenterin poiminta ja hyppää mihin tahansa päivämäärään. Ja
Ja ** Kortit ** | Nopeat widgetit * Tänään päiväkirja * Esikatselu, * D-Day * Countdown ja * Vaihe * Yhteenveto. Ja
Ja ** Pohja navigointi ** | Viisi päiväkirjan, TODO: n, D-päivän, tilastojen ja asetusten välilehteä. Ja
Ja ** kelluva toiminta (+) -painike ** | Luo uusia merkintöjä mistä tahansa. Ja

## 2. Pohja navigointipainikkeet

Ja Painike | Yksi napautus | Kaksinkertainen napautus | Pitkä lehdistö |
| -------- | ----------- | ----------- | ------------ |
Ja ** päiväkirja ** | Avaa päiväkirjaluettelo valitulle päivämäärälle | Vieritä luettelon kärkeen | Avaavan päivämäärän poiminta |
Ja ** TODO ** | Vaihda * tänään * ⇄ * Huomenna * Lista | Romahtaminen / laajennus * tänään * -osa | Merkitse kaikki TODO: t täydellinen / epätäydellinen |
Ja ** D-päivä ** | Näytä lähtölaskenta -ajastimet | Hyppää lähimpään tulevaan tapahtumaan | Lajittele / suodatinvaihtoehdot |
Ja ** Tilastot ** | Avoin päätilastot Hub | Syklialue * 7 → 30 → 90 * päivää | Vie nykyinen kaavio CSV |
Ja ** Asetukset ** | Avoimet asetukset | - | Näytä sovellustiedot |

## 3. Kelluva toimintapainike (+)

Ja Ele | Toiminta |
| --------- | -------- |
Ja Napauta | Valitse * päiväkirja * / * TODO * / * D-Day * Entry Type |
Ja Kaksinkertainen napautus | Välitön pika-diary-merkintä |
Ja Pitkä lehdistö | Äänikomento (beeta) |

## 4. Sovelluspalkki ja työkalukuvakkeet

Ja Kuvake | Toiminta |
| ------ | -------- |
Ja 🔍 ** Haku ** | Globaali haku päiväkirja-, TODO- ja D-päivä |
Ja 🔄 ** Sync ** | Manuaalinen pilvivarmuuskopio / palautuskehote |
Ja 🔔 ** Midnight Alert ** | Vaihda 00:00 päivittäinen muistutus |
Ja 📊 ** Lähetä tilastoille ** | Paina nykyisiä tietoja tilastomoduuliin |
Ja ⋮ ** Lisää valikko ** | Vie / tuonti • GPS -seuranta • Etäisyysvertailu • Aktiviteettikuvio • ** Tietokannan hallinta ** • ** Käyttöohje ** |

## 5. Eleet kaikkialla

- ** pyyhkäise vasemmalle ** → Poista nykyinen kohde
- ** pyyhkäise oikeaa ** → Muokkaa kohdetta
- ** Pinch ** → Säädä tekstin koko lennossa
- ** ravista ** → Vaihda tumma tila

## 6. Statistics -kojelauta

Pääsyyn ** tilastojen ** -välilehden kautta, kojelauta tarjoaa useita sivuja:

Ja Sivu | Widgetit ja työkalut |
| ------ | ----------------- |
Ja ** Päiväkirjatilastot ** | Sisäänkäynnin taajuuden lämpökartta, avainsanan sanapilvi, mielialan piirakkakaavio |
Ja ** askel tiski ** | Päivittäiset vaiheet linjakaavio, etäisyys- ja kaloriarviot |
Ja ** Aktiviteettikuvio ** | Tunnin kerrallaan histogrammi, aktiivinen / tyhjäkäyntisuhde |
Ja ** Etäisyysvertailu ** | Baarikartta vertaamalla kävelyä vs. juokseminen vs. pyöräily |
Ja ** Päivittäinen reittikartta ** | GPS -jäljen karttapäällyste (vaatii sijaintiluvan) |
Ja ** Sää ja kuu ** | Säätrendit ja kuuvaihehäiriöt |

Jokainen kaavio tukee:*zoom / pann*Pinch,*Range Switch*(kaksoisnap) ja ** vienti ** PNG / CSV / PDF-valikon kautta.

## 7. Varmuuskopiointi ja palautus

1. Avaa ** Asetukset ▸ Varmuuskopio / palauta **.
2. Yhdistä Google Driveen (vain ensimmäinen kerta).
3. Napauta ** Varmuuskopio nyt ** ladata JSON + SQLite -tilannekuva.
4

## 8. UKK

** Miksi mainokset eivät näy? **  
Mainokset voivat olla tyhjiä jopa 48 tuntia tuoreen leikkikaupan julkaisun jälkeen. Integraation varmistamiseksi ota ** testimoimaukset ***Asetukset ▸ Debug*.

** iCloud / Drive Sync on jumissa? **  
Kirjaudu ulos pilvitililtä ja kirjaudu takaisin sisään ja yritä sitten uudelleen.

## 9. Tuki

- Sähköposti: [support@lunote.app] (mailto: support@lunote.app)
- Github -ongelmat: <https://github.com/schaam/lunote/issues>

---
Valmistettu ❤️: llä ** LUNOTE -joukkue **