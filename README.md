# MoonlightBot
This is a Discord bot written in JS for easy moderation and logging.
Note: this repository is meant for ones who'd like to make improvements to the current (total garbage) code, not for running your own instance.

Join bot support server: https://discord.gg/yjnZUQH

Invite bot: https://discordapp.com/api/oauth2/authorize?client_id=314110696071888896&permissions=470133958&scope=bot

#Config file

`config.json` is the file needed to run the bot properly, here is how it's structured:

```json

{
	"prefix": "m:", //Bot prefix. Any message starting with this wil trigger the bot
	"token": "YOUR_TOKEN_HERE", //Bot token. You get this from your Discord application page
  "owner": "YOUR_USER_ID", //Your Discord user ID, like 256460316660072448
  "DBLkey": "OPTIONAL", //Something
  "beta": false, //Internal flag for me to check if it's running the test version or anything else
  "cooldowntimer": 3000 //Cooldown after using a command
  
}
```
