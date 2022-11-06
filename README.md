# Twitch Stream AutoRecorder
It allows you to automatically record a twitch stream that just goes live.

## Requirement
- [Streamlink (Windows Installer)](https://github.com/streamlink/windows-builds/releases)

## Setting Up
Edit file with your desired path location and the twitch channel URL you want to record

Example:
```bash
streamlink --retry-streams 90 --output "C:\recordings\{author}-{title}.ts" https://twitch.tv/channelname best
```

## Running File
Run as administrator
