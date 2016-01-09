#ReconnectingWebSocket
=====================
Based on https://github.com/daviddoran/typescript-reconnecting-websocket
Usage:
a WebSocket connection that will automatically reconnect if the
connection is dropped.

It is API compatible, so when you have:

    ws = new WebSocket('ws://....');

you can replace with:

    ws = new ReconnectingWebSocket('ws://....');


