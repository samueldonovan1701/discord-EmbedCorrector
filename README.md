# discord-EmbedCorrector
A simple bot to correct bad Discord embed links

## Functionality
When added to a guild, this bot will scan every message sent for embed links. If any embed link starts with "https://media.discordapp.net", the message will have it's embeds supressed (though the message will not be deleted), and the bot will send a message will all of the original's embeds, though incorrect links will be modified to start with "https://cdn.discord.com".
