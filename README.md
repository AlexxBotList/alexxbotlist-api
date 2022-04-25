# alexxbotlist-api
Support : https://alexxbotlist.xyz/dc
Package : https://npmjs.com/package/alexxbotlist-api
<a href="https://nodei.co/npm/alexxbotlist-api/"><img src="https://nodei.co/npm/alexxbotlist-api.png"></a>

# Installation
## `npm i alexxbotlist-api`

# Description
## *Ce package est **`l'API Officiel de AlexxBotList.xyz`**. Tutoriel pour mettre en place en dessous.*
# Mise en place
Pour avoir le token rendez-vous sur : 
https://alexxbotlist.xyz/bot/BOTID/edit.
Vous aurez 3 tirés (ou pas), et vous cliquez sur `token`
```js
const alexxbotlist = require("alexxbotlist-api");
const dbl = new alexxbotlist("TOKEN-HERE", client);
```
# Server Count
```js
 client.on("ready", async => {
  setInterval(() => {
  dbl.serverCount();
  console.log("Stats posted on AlexxBotList.xyz") 
   }, 30000); //choose your time
})            //ex: 3000 = 3s
  ```

# Tout

```js
const alexxbotlist = require("alexxbotlist-api ")
const dbl = new alexxbotlist("TOKEN-HERE", client)

client.on("ready", async => {
  setInterval(() => {
  dbl.serverCount();
  console.log("Stats posted on AlexxBotList.xyz") 
   }, 30000); //choose your time
})            //ex: 3000 = 3s 
```
