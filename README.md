# yt-dlp-server
A yt-dlp web server, powered by yt-dlp.

Intended to provide raw video url and other metadata as a json payload, not as a streaming server.

## Getting started
```
npm install
npm start
```

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## API

```
GET /watch?v=<YOUTUBE_VIDEO_ID_HERE>

Redirects to the raw video url.

- v: required - Url or ID of the video, same as the url parameter of GET /v1/video
```
