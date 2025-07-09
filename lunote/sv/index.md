---
layout: default
title: LuNote Manual (SV)
---

---
Layout: Standard
Titel: Lunote Manual
---

# LUNOTE User Manual

> Senast uppdaterad: {{site.time | Datum: '%y-%m-%d'}}

Välkommen till ** LUNOTE **, din allt-i-ett-dagbok, TODO och livslångt följeslagare. Den här guiden fokuserar på huvudskärmkontrollerna-vad som händer när du trycker på, dubbel-klibb eller långtryck-och ger en översikt över alla större funktioner så att du kan få ut det mesta av appen.

## 1. Hemskärm på en överblick

| Område | Syfte |
| ------ | --------- |
| ** Datumstång ** | Visar dagens datum. Tryck för att öppna kalenderväljaren och hoppa till vilket datum som helst. |
| ** Kort ** | Snabb widgetar för * idag dagbok * förhandsgranskning, * d-dag * nedräkning och * steg * sammanfattning. |
| ** Navigering av botten ** | Fem flikar för dagbok, TODO, D-dag, statistik och inställningar. |
| ** Floating Action (+) -knapp ** | Skapa nya poster var som helst. |

## 2. Navigationsknappar

| Knapp | Single Tap | Double Tap | Lång press |
| -------- | ----------- | ----------- | ------------ |
| ** Dagbok ** | Öppen dagboklista för valt datum | Rulla till toppen av listan | Open Date Picker |
| ** TODO ** | Växla * Idag * ⇄ * Imorgon * Lista | Kollaps / expandera * idag * avsnitt | Markera alla Todos komplett / ofullständiga |
| ** D-dag ** | Visa nedräkningstimers | Hoppa till närmaste kommande evenemang | Sortera / filteralternativ |
| ** Statistik ** | Öppna huvudstatistiknav | Cykelområde * 7 → 30 → 90 * dagar | Exportera aktuellt diagram som CSV |
| ** Inställningar ** | Öppna preferenser | - | Visa appinformation |

## 3. Flytande actionknapp (+)

| Gest | Åtgärd |
| --------- | -------- |
| Tap | Välj * Dagbok * / * TODO * / * D-DAY * Entry Type |
| Double-Tap | Omedelbar snabbdiärpost |
| Lång press | Röstkommando (beta) |

## 4. Appstång och verktygsikoner

| Ikon | Åtgärd |
| ------ | -------- |
| 🔍 ** Sök ** | Global sökning över dagbok, TODO och D-DAY |
| 🔄 ** Sync ** | Manuell molnbackup / återställning av prompt |
| 🔔 ** Midnight Alert ** | Växla 00:00 Daglig påminnelse |
| 📊 ** Skicka till statistik ** | Tryck på aktuella data till statistikmodul |
| ⋮ ** Mer meny ** | Export / import • GPS -spårning • Distansjämförelse • Aktivitetsmönster • ** Databashantering ** • ** Användarmanual ** |

## 5. Gester överallt

- ** Svep vänster ** → Radera aktuellt objekt
- ** svep höger ** → Redigera objekt
- ** Pinch ** → Justera textstorlek i farten
- ** Shake ** → Växla mörkt läge

## 6. Statistik instrumentbräda

Tillgången via fliken ** Statistik ** erbjuder instrumentpanelen flera sidor:

| Sida | Widgets & verktyg |
| ------ | ----------------- |
| ** Dagbokstatistik ** | Inmatningsfrekvensvärmekarta, nyckelord ord-cloud, humör cirkeldiagram |
| ** Stegdisker ** | Dagliga steglinjediagram, avstånd och kalori uppskattningar |
| ** Aktivitetsmönster ** | Timme-för-timmars histogram, aktivt / tomgångsförhållande |
| ** Distansjämförelse ** | Bardiagram Jämförelse vs som kör vs cykling |
| ** Daglig ruttkarta ** | MAP Overlay of GPS -spår (kräver platstillstånd) |
| ** Weather & Moon ** | Vädertrender & månfaswidgets |

Varje diagram stöder:*zoom / pan*med nypa,*intervallomkopplare*(dubbel-tap) och ** exportera ** som PNG / CSV / PDF via den högra högra ⋮-menyn.

## 7. Backup & återställ

1. Öppna ** Inställningar ▸ Säkerhetskopiera / återställa **.
2. Anslut till Google Drive (endast första gången).
3. Tryck på ** Backup nu ** för att ladda upp JSON + SQLite Snapshot.
4. För att återställa, välj en säkerhetskopia och tryck på ** Återställ **.

## 8. Vanliga frågor

** Varför visar annonser inte? **  
Annonser kan vara tomma i upp till 48 timmar efter en ny spelbutik. För att verifiera integration, aktivera ** Testannonser ** i*Inställningar ▸ Debug*.

** iCloud / Drive Sync är fast? **  
Logga ut från molnkontot och logga in igen och försök sedan igen.

## 9. Stöd

- E -post: [support@lunote.app] (mailto: support@lunote.app)
- Github -frågor: <https://github.com/schaam/lunote/issues>

---
Gjord med ❤ av ** Lunote -teamet **