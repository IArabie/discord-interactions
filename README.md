![](https://preview.redd.it/4zh2hgl46cp51.png?width=3325&format=png&auto=webp&s=b9123bff12e1d5b86248d27a059104b4c92e05b5)

<h2 style="text-align: center;">discord-interactions</h1>

This repository is a JavaScript project that implements Discord interactions within an Express.js framework, utilizing the Discord API for robust and dynamic bot functionality.

## Usage
```js
const { Client, Events } = require('./src');
const bot = new Client({ token: '' });

bot.on(Events.ClientReady, async(user) => {
    console.log(`${user.username}'s Online!`)
})

bot.on(Events.InteractionCreate, async(Interaction) => {});

bot.connect();
```

## Examples

- [Fetch Guilds]()
- [Fetch User]()
- [Update Application Commands]()
