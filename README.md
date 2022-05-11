# BotTelegramDoc
Se documenta practica de Bot de telegram, la practica se encuentra en repo Fizz

## En construcción...

Dependencias utilizadas:

node-telegram-bot-api 
Para no versionar token por seguridad: npm install dotenv --save , esta nos ayuda a tener configuración externalizada.

## Bot Telegram

Pasos que segui:
1. Necesitas una cuenat de telegram activa
2. Entrar aBot Father: https://telegram.me/BotFather
3. En el chat del bot father envía un mensaje con el texto: /newbot
4. Te pedirá un nombre para tu bot, nombralo: FizzbuzzLaunchXBot
5. Guarda el token de tu nuevo bot, esta es información sensible 5112341234:AAFB-c7Jau2TNt0-s6ioQGOAiUtqcsdewdwedwo.
Así mismo te dará una url para que abras un nuevo chat con tu bot, enseguida presiona el botón de START, necesitas realizar este paso.

Algo asi se vera:

![image](https://user-images.githubusercontent.com/99162884/167800070-e706d00a-aef3-4c24-9ee9-c9c81cf198d4.png)


Start para comenzar

Instala la dependencia: npm install node-telegram-bot-api --save
Crea un nuevo script llamado lib/bot.js
Modifica tu package.json , dentro de scripts agrega: "bot": "node ./lib/bot.js"
Y crea un archivo bot.js, en este archivo estarán las referencias


Propiedades de msg de bot de telegram

![image](https://user-images.githubusercontent.com/99162884/167801977-dbdc87bb-a7ae-48cc-af9b-87601f35b8a0.png)





[Manual de bot Telegram](https://core.telegram.org/bots)


