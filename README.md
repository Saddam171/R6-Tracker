# R6Bot
**Estatísticas de Rainbow Six Siege no Discord**  

**Este Bot depende do [`r6s-stats-api`](https://github.com/Saddam171/R6-Tracker) para buscar estatísticas**  

### Versão de Uso
[**node.js  `v16.15.0`**](https://nodejs.org/en/)  
[**discord.js  `v13.6.0`**](https://discord.org/en/)  


### Dependências  
* **discord.js `^13.6.0`**  
* **@discordjs/rest `^0.3.0`**  
* **r6s-stats-api `^1.0.1`**  
* **dotenv `^16.0.0`**  



# Instalação

### Clonar o repositório
```
git clone -b v2.0.0 https://github.com/Saddam171/R6-Tracker.git
```

### Instale as dependências
instalar automaticamente todas as dependências em [`package.json`](./package.json)  
```
npm install
```

### Configurar O Bot 
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
Definir o `"DEFAULT_PLATFORM"` permite que você omita essa plataforma na parte do comando
Se `LOAD_SLASH_GLOBAL` for `false` válido apenas nessa Guilda, caso contrário será válido em todas as Guildas.

## Ligando o Bot

```
node index.js
```

## Comandos

obter perfil
```
+r6 [PC/XBOX/PSN] <PLAYER_NAME>
```

obtenha estatísticas casuais, de classificação, sem classificação e de deathmatch
```
+r6 [PC/XBOX/PSN] <PLAYER_NAME> [RANK/CASUAL/UNRANK/DEATHMATCH]
```

obter estatísticas de operadores
```
+r6 [PC/XBOX/PSN] <PLAYER_NAME> operator <OPERATOR_NAME>
```

obter ajuda
```
+r6 help
```

#Ex:

![image](https://user-images.githubusercontent.com/92656405/202003954-86cbe8dd-9286-44a0-9c5b-4d7f6f2283cc.png)

![image](https://user-images.githubusercontent.com/92656405/202004142-4ee59a61-eda8-411a-a218-58cc1a1307a5.png)




