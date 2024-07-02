# Discord Music Bot

A feature-rich Discord music bot built using [JDA](https://github.com/DV8FromTheWorld/JDA) and [Lavaplayer](https://github.com/lavalink-devs/lavaplayer).

## Supported Sources

* YouTube
* SoundCloud
* Bandcamp
* Vimeo
* Twitch streams
* Deezer
* Spotify
* Apple Music
* Yandex Music
* HTTP URLs

## Features

- **Rich Command Set**: Over 20 commands for managing playback, playlists, and more.
- **High-Quality Audio**: Enjoy high-quality audio playback with Lavaplayer.

## Commands

Here are some of the commands you can use with this bot:

- `play [url]` - Play a track from the given URL.
- `pause` - Pause the current track.
- `resume` - Resume the paused track.
- `stop` - Stop playback and clear the queue.
- `skip` - Skip to the next track in the queue.
- `queue` - View the current queue.
- `nowplaying` - Show information about the currently playing track.
- `volume [level]` - Set the playback volume (0-100).
- `seek [time]` - Seek to a specific point in the current track.
- `loop` - Toggle looping for the current track.
- `shuffle` - Shuffle the current queue.
- `remove [index]` - Remove a track from the queue by its index.
- `playlist [name]` - Save the current queue as a playlist.
- `loadplaylist [name]` - Load a saved playlist.
- `clearqueue` - Clear the current queue.
- `join` - Make the bot join your voice channel.
- `leave` - Make the bot leave the voice channel.
- `lyrics` - Fetch lyrics for the currently playing track.
- `info` - Get information about the bot.
- `ping` - Check the bot's response time.

## Setup

### Prerequisites

- Java 11 or higher
- A Discord bot token (create one [here](https://discord.com/developers/applications))

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/ferrymehdi/LavaPlayer-Bot.git
   cd LavaPlayer-Bot
2. Configure the bot by creating a .env file in the root directory with the following structure:
   ```env
   TOKEN= #Your Bot Token
   Prefix="!" #Your Bot Prefix
   Spotify_clientId=""
   Spotify_clientSecret=""
   AppelMusic_mediaAPIToken=""
   Deezer_masterDecryptionKey=""
   YandexMusic_AccessToekn=""
4. Build and run the bot:
   ```sh
   mvn clean install
   java -jar target/MusicFile.jar
### Usage

1. Invite the bot to your Discord server using the OAuth2 URL generated in the [Discord Developer Portal](https://discord.com/developers/applications).
2. Use the [commands](https://github.com/ferrymehdi/LavaPlayer-Bot/tree/main?tab=readme-ov-file#commands) listed above to interact with the bot.