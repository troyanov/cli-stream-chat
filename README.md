# About project
It's a terminal client to see your online stream chat. 

## Supported features
- YouTube chat
- Twitch chat 
- Keep chat logs
- Multi-tty mode

## How to use
Clone this repo and run:
```
go run chat.go 
--twitch <twitch_channel> 
--youtube <link_to_your_youtube_stream> 
--devices /dev/tty1,/dev/tty2 
--log /path/to/your/log/directory
```

You must have golang compiler for running

## TODO features
- Fetch an active youtube live stream link by channel name (We probably can use [that](https://developers.google.com/youtube/v3/live/docs/liveBroadcasts))
- Support twitch stikers
- Write to twitch 
- Write to youtube ([API](https://developers.google.com/youtube/v3/live/docs/liveChatMessages/insert)) 
- Should we use YouTube Live Streaming API for everything?
- terminal ui
- how to distribute app

