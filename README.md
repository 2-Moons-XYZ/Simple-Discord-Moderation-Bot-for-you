### Simple Discord Bot

## Simple Discord Moderation Bot

### Introduction

This simple Discord moderation bot provides basic moderation functionalities for your Discord server. It allows you to customize the embed color and prefix to match your server's theme and preferences.

### Features

* **Kick and Ban Users:** Kick or ban users who are violating server rules or engaging in disruptive behavior.
* **Mute Users:** Temporarily mute users who are spamming or sending inappropriate messages.
* **Clear Messages:** Clear a specified number of messages from a channel to remove unwanted or harmful content.
* **Customizable Embed Color:** Set the embed color for all bot messages to match your server's theme.
* **Customizable Prefix:** Set a custom prefix for all bot commands to easily distinguish them from user messages.

### Installation and Setup

1. **Create a Discord Developer Account:** If you don't already have one, create a Discord Developer account to access the Discord Bot API.

2. **Create a New Bot:** Visit the Discord Developer Portal and click on the "New Application" button. Choose "Bot" as the application type and give it a name.

3. **Copy the Bot Token:** Click on the "Bot" tab and scroll down to the "Token" section. Copy the bot token, as you will need it later.

4. **Invite the Bot to Your Server:** Click on the "Invite" button and select your server from the dropdown menu. Make sure to grant the "Administrator" permission for full moderation capabilities.

5. **Set the Embed Color:** You can set the embed color using the `setcolor` command followed by the desired color code or hex value (e.g., `!setcolor #FF0000`).

6. **Set the Prefix:** You can set the custom prefix using the `setprefix` command followed by your desired prefix (e.g., `!setprefix $`).

### Usage

The bot responds to commands starting with the defined prefix. For example, if the prefix is `$`, you would use commands like `$kick @username` or `$mute @username 10m`.

### Commands

* `$kick [@username] [reason]`: Kicks the specified user from the server. An optional reason can be provided.

* `$ban [@username] [reason]`: Bans the specified user from the server, preventing them from joining in the future. An optional reason can be provided.

* `$mute [@username] [duration]`: Mutes the specified user for the specified duration. The duration can be in minutes (m), hours (h), or days (d).

* `$clear [number]`: Clears the specified number of messages from the current channel.

* `$setcolor [color code or hex value]`: Sets the embed color for all bot messages.

* `$setprefix [prefix]`: Sets the custom prefix for all bot commands.

### Additional Notes

* The bot requires the "Administrator" permission to perform moderation actions.

* The bot will log all moderation actions to a dedicated channel for transparency.

* You can add more moderation commands or customize existing ones to suit your server's needs.

* Feel free to contribute to the bot's development or report any issues on the project's GitHub repository.
