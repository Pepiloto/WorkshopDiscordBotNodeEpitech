# Epitech Discord Bot Workshop - Part 1

## Let's start at the beginning
### Event handling

When anything happens on a Discord server, a corresponding event is triggered. There are currently half a hundred different types of events.
You have, for example, events for when a user joins the server, when someone sends a message, when the bot loses connection, and many more.

1) When the bot logs in, print a greetings message to the console.
3) Make the bot answer `pain au chocolat` if anyone's message contains `chocolatine` (case insensitive).
4) When a user changes his nickname, annouce it by sending a message on the channel of your choice.
   * Example message: `Clément changed his nickname to kirikou!`

### Discord presence

Your Discord presence contains your online status (online, away, busy, invisible), an activity (Playing XXX, Listening to XXX, Streaming, Custom Message, ...) and an AFK status.

When the bot logs in:
1) Change the bot's activity to a custom message of your choice.
1) Change the bot's status to "do not disturb".

### Commands

Discord.js makes our lives easier by providing an easy way to create commands. We can assign aliases, permissions, descriptions and much more.

1) Assign a command prefix of your choice. (we will use `!` for the examples)
    * It is possible to have a multi-character command prefix!
1) Create a `!ping` command that answers "pong".
1) Create a `!info` command that answers some informations about the caller:
    * Username
    * Discriminator (this is the #0000 part)
    * Display name (user's current server nickname, if any)
    * User account creation date
    
1) Create a `!nick` command that changes the bot's nickname to what's been passed as parameters.
    * If no argument is given, it resets the bot's nickname.
    
### Embeds

Responding in raw messages can be hard to read when the messages traffic is important (like `db!info` above). You can make them prettier and easier to read by using **embeds**!

1) Create a basic Embed and set the differents options:
    * Description
    * Color
1) Create and add two fields of your choice to your Embed
1) Now that you have an idea of how to use it, let's recreate the `!help` command but with an Embed this time. The command will display all the commands the bot has and how to use them.
