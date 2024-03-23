PeerChat
A peer to peer WebRTC application with controls

Installation
1 - clone repo https://github.com/divanov11/PeerChat
2 - Create an account on agora.io and create an app to generate an APP ID
3 - Update APP ID, Temp Token and Channel Name in main.js
let APP_ID = "YOU-APP-ID"

WebRTC Documentation

https://developer.mozilla.org/en-US/docs/Web/API/WebRTC_API/Connectivity

WebSockets : have server involved where caht message reaches server and server then responds.

WebRTC : Real Time Communication between browsers . Data never touches Server .
Uses UDP

What is sent between 2 clients

A session description protocols (SDP)
ICe candidates : request STUN server to show the public IP and ICE certificates to the other candidates .
