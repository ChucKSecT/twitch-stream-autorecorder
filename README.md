# Twitch Stream AutoRecorder
It allows you to automatically record a twitch stream that just goes live.

## Requirements
[Streamlink](https://github.com/streamlink/streamlink/releases)

## Setting up
Edit file with your desired path location and the channel name you want to record

Example:
```bash
streamlink --retry-streams 90 --output "C:\recordings\{author}-{title}-{time:%H%M%S%d%m%Y}.ts" https://twitch.tv/channelname best
```

## Running
Run file as administrator
