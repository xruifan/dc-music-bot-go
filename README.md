A Discord bot template using [discordgo](https://github.com/bwmarrin/discordgo) that can play audio from YouTube links, primarily using code from [voice.go](https://github.com/bwmarrin/discordgo/blob/master/voice.go). 

## Requirements
`ffmpeg`, `yt-dlp`

## env
create a .env file, see env.example

## Commands
`/join` join your vc channel.

`/play` play YouTube Audio following a link.

example:
```
/play https://www.youtube.com/watch?v=dQw4w9WgXcQ
```

`/leave` leave the vc channel.
