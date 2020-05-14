# Epitech Discord Bot Workshop - Part 2

## Let's start at the beginning
### Event handling
## Important

* You should take a look at [**Part 1**](Part1_basics.md) if you weren't there last time.
* For our examples, our command prefix is `db!`, but you can change it by one of your choice.

## More things about commands
### Some options that can be cool to use
> In part 1, we saw the basics of a discord bot. Here, we will see more tools that you can use to improve your commands

 1) Now, let's try to add some aliases to already existing commands. With aliases you are able to call the same command but using a different name. `!hoi`, `!salut` and `!hey` must do the same thing.
 2) Do the same with other commands that will be normal to call them differently than you did.
 
 
Responding in raw messages can be hard to read when the messages traffic is important (like `!help`). You can make them prettier and easier to read by using **embeds**!

### Embeds

1) Create a basic Embed and set the differents options:
    * Title
    * Description
1) Create and add fields for all your commands and aliases to your Embed.
1) Now that you have an idea of how to use it, let's recreate the `!help` command but with an Embed this time.

### Kick and ban

Now that you're good at it try to make 2 more commands:

1) A `!kick [USERNAME]` to kick someone of the server
1) A `!ban [USERNAME]` to ban someone of the server

You might thought of a problem because anyone on the server can kick or ban anyone else even yourself...
Change those commands so only people with `moderator` can kick and `admin` can ban.
