# R6Bot
**Rainbow Six Siege stats Discord Bot**  

**This Bot depends on the [`r6s-stats-api`](https://github.com/hmes98318/r6s-stats-api) module to fetch statistics**  

### Reference version  
[**node.js  `v16.15.0`**](https://nodejs.org/en/)  
[**discord.js  `v13.6.0`**](https://discord.js.org/#/)  


### Dependencies Modules  
* **discord.js `^13.6.0`**  
* **@discordjs/rest `^0.3.0`**  
* **r6s-stats-api `^1.0.1`**  
* **dotenv `^16.0.0`**  



# Installation

### Clone the repository
```
git clone -b v2.0.0 https://github.com/hmes98318/R6Bot.git
```

### Install the depedences  
auto install all dependencies on [`package.json`](./package.json)  
```
npm install
```

### Configure Files  
[`.env`](./.env) 
```env
TOKEN = "your_token"
```
[`config.json`](./config.json)  
```json
{
    "name": "R6Bot",
    "PREFIX": "+",
    "COLOR":"#ff00ee",
    "ENABLE_DEFAULT_PLATFORM": true,
    "DEFAULT_PLATFORM": "pc",
    "SLASH_COMMANDS":true,
    "GUILD_ID":"your_GUILD_ID",
    "LOAD_SLASH_GLOBAL": false
}
```
Setting the `"DEFAULT_PLATFORM"` allows you to omit that platform in the command part  
If `LOAD_SLASH_GLOBAL` is `false` only valid in that Guild, otherwise that will valid in all Guild.

## Running the script 

```
node index.js
```

## Commands

get profile
```
+r6 [PC/XBOX/PSN] <PLAYER_NAME>
```

get Casual, Rank, Unrank, Deathmatch statistics  
```
+r6 [PC/XBOX/PSN] <PLAYER_NAME> [RANK/CASUAL/UNRANK/DEATHMATCH]
```

get Operators statistics  
```
+r6 [PC/XBOX/PSN] <PLAYER_NAME> operator <OPERATOR_NAME>
```

get help
```
+r6 help
```

[<img src="https://canary.discordapp.com/api/guilds/664835490985410588/widget.png?style=banner2">](https://discord.gg/TEMauza)

# GitHub Repositories 

[Click Here](https://github.com/Saddam171?tab=repositories) 

# Social 
<a href="https://instagram.com/rz.ung" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="rz.ung" height="30" width="40" /></a>
[Instagram](https://www.instagram.com/rz.ung/)

<a href="https://discord.gg/! ᴏғᴘ ⚡ Resilient |ᴿᴶ 🇦🇷#0019" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="! ᴏғᴘ ⚡ Resilient |ᴿᴶ 🇦🇷#0019" height="30" width="40" /></a>
[Discord](https://discord.gg/TEMauza)




