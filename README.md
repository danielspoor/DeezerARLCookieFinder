# Deezer ARL Cookie Finder

Chrome-extensie voor Deezer Downloader. Zodra je in Chrome bij Deezer bent ingelogd, zet de extensie je ARL-cookie automatisch in Deezer Downloader. De extensie werkt zichzelf bij.

Deze repo bevat alleen de installers. Download ze bij [Releases](https://github.com/danielspoor/DeezerARLCookieFinder/releases/latest).

## Installeren

| Computer | Bestand |
|----------|---------|
| Windows | `DeezerARLCookieFinder-Setup-Windows.exe` |
| Mac met Apple-chip (M1 of nieuwer) | `DeezerARLCookieFinder-macOS-AppleSilicon.zip` |
| Mac met Intel-chip | `DeezerARLCookieFinder-macOS-Intel.zip` |
| Linux | `DeezerARLCookieFinder-Linux.tar.gz` |

1. Download het bestand voor je computer en start de installer.
   - **Windows:** verschijnt "Windows heeft uw pc beschermd", klik dan Meer info en daarna Toch uitvoeren.
   - **Mac:** pak de zip uit en dubbelklik `DeezerARLCookieFinder-installeren`. Krijg je de melding dat het programma niet geopend kan worden, ga dan naar Systeeminstellingen, Privacy en beveiliging, en klik Open toch.
   - **Linux:** pak het bestand uit en start `./DeezerARLCookieFinder-installeren` in een terminal.
2. Ga in Chrome naar `chrome://extensions` en zet Ontwikkelaarsmodus aan (rechtsboven).
3. Klik Uitgepakte extensie laden en kies de map die de installer toont.

Er zijn geen beheerdersrechten nodig.

## Gebruik

Log in Chrome in op deezer.com en open Deezer Downloader. De extensie stuurt de ARL door als die nieuw is of als Deezer Downloader de opgeslagen ARL niet meer accepteert. Log je later opnieuw in bij Deezer, dan wordt de nieuwe ARL meteen doorgestuurd.

Klik op het icoon in Chrome voor de status.

## Bijwerken

De extensie kijkt elke dag of er een nieuwe versie is. Is die er, dan staat in de popup een melding met de knop Bijwerken. Zet Automatisch bijwerken aan om dat zonder klik te laten gebeuren. Elke versie is ondertekend; een update met een ongeldige handtekening wordt niet geïnstalleerd.

## Verwijderen

Verwijder de extensie in `chrome://extensions` en start de installer met `--uninstall`.
