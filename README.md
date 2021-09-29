# psicore-binaries

This repo contains custom binaries that support the usual psiphon protocols plus new custom protocols used by NapsternetV i.e.
1. *UNFRONTED-WS-OSSH*
1. *UNFRONTED-WSS-OSSH*
1. *FRONTED-WS-OSSH*
1. *FRONTED-WSS-OSSH*

These custom protocols use OSSH (Obfuscated SSH) over websocket. Websocket may be plain (WS) or secure (WSS) and unfronted or fronted over a CDN.

### NOTE: 
The custom protocols are only supported by the [NapsternetV](https://play.google.com/store/apps/details?id=com.napsternetlabs.napsternetv) android app and binaries from this repo.

The psiphond server binary which supports these custom protocols can be got [here](/psiphond/psiphond)