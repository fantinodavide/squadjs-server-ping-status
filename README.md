# Server Ping Status Plugin

A Discord plugin that displays server ping information from different regions.

## Installation

1. Place `server-ping-status.js` in your plugins directory
2. Add the plugin configuration to your server config file

## Configuration

```json
{
  "plugin": "ServerPingStatus",
  "enabled": true,
  "discordClient": "discord",
  "messageStore": "mysql",
  "channelID": "YOUR_CHANNEL_ID"
}
```

Replace `YOUR_CHANNEL_ID` with your Discord channel ID.

## Features

- Displays server ping information from all regions
- Color-coded ping quality indicators
- Shows current player count, game mode, and map
- Updates automatically at configurable intervals