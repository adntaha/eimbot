# EIM Bot

A bot for the EIM discord server.

## Developer otes

If one of your interactions might take longer than three seconds to reply, you **must** use `interaction.deferReply(...)`, and then `interaction.editReply(...)`,
otherwise the interaction's token will invalidate and you will not be able to reply.

## Credits

[Geek](https://github.com/GamingGeek) @ [FireDiscordBot](https://github.com/FireDiscordBot): The discord.js [fork](https://github.com/FireDiscordBot/discord.js) that we use.
[Polar](https://github.com/xPolar) @ [OtterDevelopment](https://github.com/OtterDevelopment): The [template](https://github.com/OtterDevelopment/typescript-discord-boilerplate) used for this bot.
