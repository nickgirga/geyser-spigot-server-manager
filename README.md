# Geyser-Spigot Server Manager
The Geyser-Spigot Server Manager (or GSSM) is a tool that makes setting up a cross-platform Java/Bedrock [Minecraft](https://www.minecraft.net/en-us) server with [Spigot](https://www.spigotmc.org/), [Geyser](https://geysermc.org/), and [Floodgate](https://github.com/GeyserMC/Floodgate/) super easy.

**Make sure you read about the current [issues](https://gitlab.com/nickgirga/gssm/-/issues) before using GSSM!**

**Empty `updater` folder? We recently added a submodule. Additional work is needed for it to be accessible. See [here](https://gitlab.com/nickgirga/gssm/-/issues/2#note_913892829) to set it up!**

# Getting Started
If you're interested in utilizing the Geyser-Spigot Server Manager on your server, head over to the [Wiki](https://gitlab.com/nickgirga/gssm/-/wikis/home) to find out how to get started.

# What Works?
 - Downloading Spigot BuildTools and building the server files (otherwise updating the server)
 - Downloading required plugins for Bedrock players to be able to join (otherwise updating the plugins)
 - Running the server
 - Checking the last time the server files or the plugins were updated

# What is Planned?
 - The ability to choose the version of Minecraft the Spigot server will be compatible with
 - The ability to choose the version of Java to use
 - The ability to choose the Spigot server executable to run (in the case that numerous versions are installed)
 - A full plugin manager that will allow users to view installed plugins, enable and disable them, delete them, back them up, revert to backups, download new plugins from specified sources, and keep all plugins (including the custom ones) up-to-date using the provided download sources
 - A world manager that will allow users to view existing worlds, enable and disable them, delete them, back them up, revert to backups, and rename them
 - A player manager that will allow users to view all players that have joined, edit their inventories, edit their player stats, kick/unkick them, ban/unban them, edit their scoreboard stats, and change their teams
 - A server version manager that will allow users to view all available versions of Spigot server executables and remove them
 - A self-update system for GSSM
 - A download verification system to ensure that update files have not been corrupted or tampered with
 - A config editor that allows users to quickly edit common server and plugin settings
 - A config checking system to prompt the user to fix it if they try to run the server with an invalid config
 - A full graphical user interface

 # Thanks
 I would like to give my thanks to the teams working on [Spigot](https://www.spigotmc.org/), [Geyser](https://geysermc.org/), [Floodgate](https://github.com/GeyserMC/Floodgate/), and [Minecraft](https://www.minecraft.net) itself for making this all possible.
