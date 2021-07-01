# **Big Ben Bot** (as seen on tiktok @aaronr5)

# **About**
Created this bot in about 45 minutes to make a funny tik tok. With that being said don't expect a feature rich bot, it is bare bones and minimal to get the job I needed done in order to make people laugh on tiktok. As of right now I'm not sure if I have plans to add any features/capabilities to this bot. Feel free to use it as is or fork it and make changes/add features. Enjoy!

### Things to note
- This bot is only setup currently to run in one server and that is whatever server you define. You could extend it to work in multiple guilds if you wanted.
- The bot only connects to whatever voice channel you define in the .env.
- You could extend this bot to dynamically check the channels and join whatever channel has members in it. Note though a discord bot client can only connect to ONE voice channel at a time and cannot be in multiple.
- You could do any number of different things with this bot if you have the time and creativity. But as mentioned this was a simple bot I wanted to make quickly for a tik tok and can't make any promises that I personally will develop this bot any further than it's current state.
- **This bot is programmed to run in the timezone of the machine it is running on.** (this could be changed relatively easily but this satisfied my needs of the bot.)
# **Usage Instructions**

## **Prerequisites**

- ### [Node.JS](https://nodejs.org/en/) 14.0.0 or higher.
- ### You will need basic knowledge of node.js and how to navigate via cmd prompt or terminal.
- ### Setup a discord bot account and get your bot token. Instructions on this can be found [here](https://discordjs.guide/preparations/setting-up-a-bot-application.html#keeping-your-token-safe).

## **Instructions**
- ## **Step 1**: `git-clone` or download the project from this repo to your machine. CD into the project dir and run `npm install` to install dependencies.
- ## **Step 2**: In the project directory rename `.env.example` to just `.env`. Open the file with a text editor and replace the placeholder TOKEN, GUILD_ID, VOICE_CHANNEL_ID, TEXT_CHANNEL_ID(text channel is optional) with your own and save. See [this link](https://support.discord.com/hc/en-us/articles/206346498-Where-can-I-find-my-User-Server-Message-ID-) to learn how to get these id's.
- ## **Step 3**: Start the bot by navigating in CMD prompt or terminal into the project dir and running `node bot.js` or using a process manager like [PM2](https://www.npmjs.com/package/pm2)

# Tutorial Video

[![](https://res.cloudinary.com/marcomontalbano/image/upload/v1625043402/video_to_markdown/images/youtube--ObtVxV3g4aE-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ObtVxV3g4aE "Install Video")
