# deploy-slash-commands-script
- A script for deploying slash commands made for Discord.js v14 bots. Uses config.json

## How To Use:
This slash command deployer gets the development server guild id, the client id, and the bot token from a config.json file. If your bot uses dotenv, please use another tool.

This file should be located inside of a "utils" folder in your bots code, this allows the code to execute properly.

This command deployer supports development server only commands, you can make a command like this by adding this to your specific commands export:
`config: { 
development: true
},`

After setting up the deployer, you can run the script by using `node utils/deployCommands.js`.
