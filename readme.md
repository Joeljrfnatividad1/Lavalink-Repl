# Setting Up the Latest Version

### To ensure you have the most up-to-date setup, follow these steps to replace your existing components.

# Updating Lavalink on Replit
[![Update Lavalink on Repl.it](https://replit.com/badge)](https://replit.com/github/YourGitHubUsername/YourRepoName)

## Installation and Configuration

1. Begin by forking this GitHub repository.
2. Next, create a new Replit project.
3. To streamline the installation process, you can also [automatically install it here](https://replit.com/github/YourGitHubUsername/YourRepoName).

# Utilizing the System

* Start the Replit project to initialize Lavalink.
* Copy the Replit URL generated after starting and integrate it into your bot.
### Always ensure that you omit the `https://` and establish connections through port 443.

## Handling Authentication Failures from 172.X.X.X

Encountering authentication failures, particularly when monitoring with uptimerobot or freshworks, is normal. These instances may multiply upon refreshing the Replit window.

![Authentication Error](https://cdn.discordapp.com/attachments/855346696590589976/947185882056777818/unknown.png)

Here's a sample `bot config`:

![Sample Bot Configuration](https://cdn.darrennathanael.com/assets/discord/lavalinkconfigbot.jpeg)

- - -

## Additional Information

The default port for connections is `443`, and the preset password is `maybeiwasboring`. Note that altering the lavalink port isn't feasible, as Replit enforces port 443 due to its operational mechanism.

### Keeping Replit Active with [Uptimer Discord Bot](https://discord.com/oauth2/authorize?client_id=1119828782161862818&permissions=8&scope=bot%20applications.commands)

1. Invite the [Uptimer Bot](https://discord.com/oauth2/authorize?client_id=1119828782161862818&permissions=8&scope=bot%20applications.commands) to your server.
2. Utilize the command `/monitor add` and input the generated Replit link in the bot.

- - -
In case the run button doesn't initiate the process, use the following commands in order:
```bash
chmod +x start.sh
```
```bash
./start.sh
```

Credit https://github.com/DarrenOfficial/lavalink-replit