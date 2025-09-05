# L-U-M-E-N

Lumen is a customizable and modulable personal assistant I ([@Elanis](https://github.com/Elanis)) built for myself to help my daily life and do some datamining. It was originally built in private using a PHP/Vanilla JS stack. Then an [electron](https://github.com/L-U-M-E-N/lumen-desktop) / [nodejs](https://github.com/L-U-M-E-N/lumen-server) has been built.  

## App Repository

The currently **maintained and active version** is [Lumen.App](https://github.com/L-U-M-E-N/Lumen.App) built using .NET.

## Official modules

### .NET Version

| Module | Description | API | Desktop | Grafana | Userscripts |
| --- | --- | --- | --- | --- | --- |
| [Enedis](https://github.com/L-U-M-E-N/Lumen.Modules.Enedis) | Gets data from the Enedis (French electricity network) API used on their website, using a cookie submitted by a tampermonkey userscript. | ✅ | ❌ | ❌ | ✅ |
| [GoodReads](https://github.com/L-U-M-E-N/Lumen.Modules.GoodReads) | This module will query data from a GoodReads user profile RSS feed URL to store books progress and make STATS! | ✅ | ❌ | ❌ | ❌ |
| [GRDF](https://github.com/L-U-M-E-N/Lumen.Modules.GRDF) | Gets data from the GRDF (French natural gas network) API used on their website, using a cookie submitted by a tampermonkey userscript. | ✅ | ❌ | ❌ | ✅ |
| [NotABot](https://github.com/L-U-M-E-N/Lumen.Modules.NotABot) | Query discord server stats from Not a bot stats API and store it to the database. | ✅ | ❌ | ✅ | ❌ |
| [SteamPartner](https://github.com/L-U-M-E-N/Lumen.Modules.SteamPartner) | Store followers, wishlists and package sales for games on Steam, in a database, later used for reporting/stats. | ✅ | ❌ | ✅ | ✅ |
| [Youtube](https://github.com/L-U-M-E-N/Lumen.Modules.Youtube) | This module will tell you how many videos and time is left in a specific playlist and store its history in a database table. | ✅ | ❌ | ✅ | ❌ |

If you want to create a module, see [the template repository](https://github.com/L-U-M-E-N/lumen-desktop), the [SDK repository](https://github.com/L-U-M-E-N/Lumen.Modules.Sdk) and the [CI](https://github.com/L-U-M-E-N/reusable-workflow).

### Legacy (Electron/nodejs) version

(Currently being rewritten one by one in .NET)

| Module | Description | Server | Desktop | Grafana | Userscripts |
| --- | --- | --- | --- | --- | --- |
| [calendar](https://github.com/L-U-M-E-N/lumen-module-calendar) | Store one or multiple calendar events in a database | ✅ | ❌ | ❌ | ❌ |
| [focus-stats](https://github.com/L-U-M-E-N/lumen-module-focus-stats) | (Desktop version is windows only) This module is storing current activity based on active window. | ✅ | ✅ | ✅ | ❌ |
| [personalStats](https://github.com/L-U-M-E-N/lumen-module-personalStats) | This module will help to time yourself on multiple categories of activities (Example: Work, Game, Other). | ✅ | ✅ | ❌ | ❌ |
| [power-tplink-tapo-p110](https://github.com/L-U-M-E-N/lumen-module-power-tplink-tapo-p110) | Power monitoring using TPLink Tapo P110. | ✅ | ✅ | ✅ | ❌ |

### Future

- Calendar (.NET Rework)
- Google fit
- Focus stats (.NET Rework)
- Lefant vaccum
- Mova lawn mower
- Tapo P110 (.NET Rework)

## Archived repositories

[Lumen v1 to v4](https://github.com/L-U-M-E-N/old-versions)  
[Lumen v5 (Desktop)](https://github.com/L-U-M-E-N/lumen-desktop)  
[Lumen v5 (Server)](https://github.com/L-U-M-E-N/lumen-server) and its [docker image wrapped with a seafile client](https://github.com/L-U-M-E-N/lumen-server-docker-seafile-client)

<details>
  <summary>Archived modules</summary>
  
  [Modules list repository for lumen-desktop](https://github.com/L-U-M-E-N/lumen-repository)
  
| Module | Description | Server | Desktop | Grafana | Userscripts |
| --- | --- | --- | --- | --- | --- |
| [calendar-amazonprimehistory](https://github.com/L-U-M-E-N/lumen-module-calendar-amazonprimehistory) | Store Amazon Prime watching history in the "calendar" module database | ✅ | ❌ | ❌ | ❌ |
| [calendar-netflixhistory](https://github.com/L-U-M-E-N/lumen-module-calendar-netflixhistory) | Store Netflix watching history in the "calendar" module database | ✅ | ❌ | ❌ | ❌ |
| [monitoring](https://github.com/L-U-M-E-N/lumen-module-monitoring) | This module will query every few minutes a list of website to check they are alive. | ❌ | ✅ | ❌ | ❌ |  
| [music](https://github.com/L-U-M-E-N/lumen-module-music) | This module will list local music sort them by folder, and lets you to play them. This module keeps playing music whatever is the current opened window in L.U.M.E.N. | ❌ | ✅ | ❌ | ❌ |  
| [pictureOfTheMoment](https://github.com/L-U-M-E-N/lumen-module-pictureOfTheMoment) | This module will display an image on main screen, and will change it every X minutes based on a folder filter. | ❌ | ✅ | ❌ | ❌ |  
| [steamAchievements](https://github.com/L-U-M-E-N/lumen-module-steamAchievements) | This module will display your https://achieve.games profile | ❌ | ✅ | ❌ | ❌ |  
</details>
