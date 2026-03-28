## About

Programmed in [TypeScript](https://github.com/microsoft/TypeScript), [Vue.js/3](https://github.com/vuejs/core) and [Electron](https://github.com/electron/electron),
this tool will help you fuel your toxicity by showing your enemies ranks and thereby how scuffed SBMM in VALORANT really is.
Spying on your enemies loadouts to feel bad about the amount of skins you own. Get yourself banned and
make your lobby feel awkward by exposing Rito-Buddy-Owners and possible VALORANT employees.
**That's what I've ever dreamed of.**



## Installation


### Building the executables yourself:

Requirements: `windows@>=19044`, `node.js@>=18.12.1`, `git`.

```bash
git clone https://github.com/DevNucleus86/Valorant-Companion
```
```bash
cd Valorant-Companion
```
```bash
npm ci
```
```bash
npm run build
```
The project is built and located at `dist_electron\win-unpacked`.



## Preview Images

### Current Match
Show other's level, current/worst/best rank, equipped skins and details of their past 9 competitive games.

<img src="https://raw.githubusercontent.com/DevNucleus86/Valorant-Companion/master/assets/preview_current_match.png">

### Account Switcher
Automatically adds accounts you're playing on. Share accounts with other Valorant Companion users with the integrated export-feature and see the shops and nightmarkets of accounts without logging into them. Can be opened by pressing F2 or in the Account Dropdown-Menu. (Drag'n'Drop your accounts in your desired order.)

<img src="https://raw.githubusercontent.com/DevNucleus86/Valorant-Companion/master/assets/preview_account_manager.png">

### Loadout Manager
Manage skins, update favourites, equip buddies, change pre-/mid-/post-round sprays and pick your banner.

<img src="https://raw.githubusercontent.com/DevNucleus86/Valorant-Companion/master/assets/preview_loadout_manager.png">

### Match History
See all your recorded valorant matches and some details. More information be available soonTM.

<img src="https://raw.githubusercontent.com/DevNucleus86/Valorant-Companion/master/assets/preview_match_history.png">

## Acknowledgements

* [LukenSkyne](https://github.com/LukenSkyne), for comforting me during development and being a good friend. <3
* [Valorant-API](https://github.com/valorant-api), for actively updating assets required for this project.
* [techchrism](https://github.com/techchrism/valorant-api-docs), for providing unofficial Valorant API documentation.

## Disclaimer

This project is not affiliated, authorized or endorsed by Riot Games, and all associated properties are trademarks or registered trademarks of Riot Games, Inc.
