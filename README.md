# psicore-binaries

This repo contains the custom psiphond server binary that supports the usual psiphon protocols plus the new custom psiphon protocols i.e.
1. *UNFRONTED-WS-OSSH*
1. *UNFRONTED-WSS-OSSH*
1. *FRONTED-WS-OSSH*
1. *FRONTED-WSS-OSSH*

These custom protocols use OSSH (Obfuscated SSH) over websocket. Websocket may be plain (WS) or secure (WSS) and unfronted or fronted over a CDN.

### NOTE: 
These protocols are only supported by the [NapsternetV android app](https://play.google.com/store/apps/details?id=com.napsternetlabs.napsternetv) and this psiphond binary.

The binary can be used just like the usual psiphond server binary in terms of commands, arguments, etc.