# Raspberry Pi Live Camera Streaming

A fork of the tutorial: http://thejackalofjavascript.com/rpi-live-streaming/

Simple Node.js server side application which communicates with the camera module
on a Raspberry Pi. It exposes a websocket server web browser can connect to,
continously getting new images as they are taken by the camera module.

## Start server

```bash
$ npm install
$ node .
```

Then open http://localhost:3000 in your favorite browser.

## LICENSE

MIT