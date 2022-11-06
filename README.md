# Twitch Stream AutoRecorder
It allows you to automatically record a twitch stream that just goes live.

## Requirement
[Streamlink](https://github.com/streamlink/streamlink/releases)

## Setting Up
Edit file with your desired path location and the channel name you want to record

Example:
```bash
streamlink --retry-streams 90 --output "C:\recordings\{author}-{title}.ts" https://twitch.tv/channelname best
```

## Running File
Run as administrator
