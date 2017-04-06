# Awesome WebRTC [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Build Status](https://travis-ci.org/openrtc-io/awesome-webrtc.svg?branch=master)](https://travis-ci.org/openrtc-io/awesome-webrtc)

A curated list of awesome WebRTC modules and resources. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome WebRTC](#awesome-webrtc)
  - [Overview](#overview)
  - [Demos and samples](#demos-and-samples)
  - [Tutorials](#tutorials)
  - [Books](#books)
  - [Developer tools and resources](#developer-tools-and-resources)
  - [Standards and protocols](#standards-and-protocols)
  - [Native APIs](#native-apis)
  - [Discussion, blogs and articles](#discussion-blogs-and-articles)
  - [Browser support](#browser-support)
  - [JavaScript apps and frameworks](#javaScript-apps-and-frameworks)
    - [Video chat](#video-chat)
    - [Peer-to-peer data](#peer-to-peer-data)
    - [VoIP/PSTN](#voip-pstn)
    - [Face/head tracking](#face-head-tracking)
    - [Node](#node)
  - [Services](#services)
  - [Applications](#applications)
    - [getUserMedia](#getusermedia)
    - [Screen capture](#screen-capture)
    - [Web Audio integration](#web-audio-integration)
    - [Recording](#recording)
    - [Chat](#chat)
    - [Games](#games)
    - [Telehealth](#telehealth)
    - [Phone](#phone)
    - [File sharing and P2P](#file-sharing-and-p2p)
    - [Others](#others)
    - [Alternatives for IE and Safari](#alternatives-for-ie-and-safari)
  - [Web Audio](#web-audio)
    - [Demos and samples](#demos-and-samples)
    - [Tutorials](#tutorials)
    - [Reference](#reference)

---

## Overview

* [WebRTC official site](http://webrtc.org/)
* 2013 Google I/O presentation: [video](https://www.youtube.com/watch?v=p2HzZkd2A40), [slide](http://io13webrtc.appspot.com/) - If you've never worked with WebRTC, we recommend you start with it. Get an overview of WebRTC.

## Tutorials

* [Getting Started With WebRTC](http://www.html5rocks.com/en/tutorials/webrtc/basics/)
* [WebRTC in the real world: STUN, TURN and signaling](http://www.html5rocks.com/en/tutorials/webrtc/infrastructure/)
* [A practical guide to WebRTC](http://www.slideshare.net/vline/a-practical) - presentation slides from vLine
* [Capturing audio and video in HTML5](http://www.html5rocks.com/en/tutorials/getusermedia/intro/)
* [Excellent series of articles by Louis Stowasser and Robert Nyman](https://hacks.mozilla.org/category/webrtc/)
* [Justin Uberti at Google I/O 2012](https://www.youtube.com/watch?v=E8C8ouiXHHk)
* [Cullen Jennings video: HTML5 WebRTC](http://vimeo.com/47682405)
* [WebRTC Fundamentals](http://bit.ly/learnwebrtc) - online course.

## Demos and samples

* [WebRTC JavaScript code samples](http://github.com/webrtc/samples)
* [Live demos of the samples](http://webrtc.github.io/samples)
* [List of WebRTC demos and apps](https://docs.google.com/document/d/1hNK15_cNx3CpYsro2TKwEbdFxLv5WFe8djGHdFeZBks/edit) - incomplete and slightly out of date.
* WebRTC video chat: [appr.tc](https://appr.tc), [source](http://github.com/webrtc/apprtc)
* [Simple getUserMedia demo](https://simpl.info/gum)
* [RTCPeerConnection demo](https://www.simpl.info/rtcpeerconnection) - RTCPeerConnection ‘on one page’, i.e. without signaling.
* [Simple RTCDataChannel example](https://simpl.info/rtcdatachannel)
* [Data channel file transfer](http://webrtc.github.io/samples/src/content/datachannel/filetransfer)
* [RTCPeerConnection signaling example](http://w3.org/TR/webrtc/#simple-example)
* [Screen capture](https://html5-demos.appspot.com/static/getusermedia/screenshare.html)
* [WebRTC Experiments](https://www.webrtc-experiment.com/) - Muaz Khan maintains a mighty assortment of experiments.
* [Walkthrough and code for setting up a server and client for video chat](https://bitbucket.org/webrtc/codelab)
* [Google I/O 2014 file sharing codelab](http://io2014codelabs.appspot.com/static/codelabs/webrtc-file-sharing/#1)

## Books

* [WebRTCBook](http://webrtcbook.com/)
* [Getting Started with WebRTC](http://www.packtpub.com/getting-started-with-webrtc/book)
* [Real-Time Communication with WebRTC](http://bloggeek.me/book-webrtc-salvatore-simon/)

## Developer tools and resources

* [adapter.js](https://github.com/webrtc/adapter) - shim maintained by Google to cope with API changes and platform differences.
* WebRTC Troubleshooter: [web](https://test.webrtc.org/), [source](https://github.com/webrtc/testrtc)
* [getUserMedia.js](https://github.com/addyosmani/getUserMedia.js) - polyfill from Addy Osmani
* [Chrome-Firefox](http://www.webrtc.org/web-apis/interop)
* [File bugs](http://crbug.com/new)

## Standards and protocols

* [Web Real-Time Communications Working Group](http://www.w3.org/2011/04/webrtc/)
* [W3C Working Draft: WebRTC 1.0: Real-time Communication Between Browsers](http://www.w3.org/TR/webrtc/)
* [Media Capture and Streams W3C Working Draft](http://www.w3.org/TR/mediacapture-streams/)
* [IETF RTCWEB](http://datatracker.ietf.org/wg/rtcweb/) - protocol specifications

## Native APIs

* [Getting started with WebRTC on iOS](https://tech.appear.in/2015/05/25/Getting-started-with-WebRTC-on-iOS/)
* [Introduction to WebRTC on Android](https://tech.appear.in/2015/05/25/Introduction-to-WebRTC-on-Android/)
* [Build scripts from pristineio](https://github.com/pristineio/webrtc-build-scripts) - repo with links to how-to guides for Android and iOS
* [Native API documentation](http://www.webrtc.org/native-code/native-apis)
* [WebRTC shim for WKWebView](https://github.com/common-tater/wkwebview-webrtc-shim)

## Discussion, blogs and articles

* [discuss-webrtc](https://groups.google.com/forum/?fromgroups#!forum/discuss-webrtc)
* [@webrtc](https://twitter.com/webrtc)
* [+webrtc](https://plus.google.com/+WebRTCorg)
* [WebRTC on Stack Overflow](http://stackoverflow.com/tags/webrtc)
* [Tsahi Levent-Levi](https://bloggeek.me/)
* [WebRTC Weekly](https://webrtcweekly.com/)
* [WebRTCHacks](https://webrtchacks.com/)

## Browser support

* [iswebrtcreadyyet](http://iswebrtcreadyyet.com/)

## JavaScript apps and frameworks

* [webrtcHacks articles](https://webrtchacks.com/whats-in-a-webrtc-javascript-library/)

### Video chat

* [appear.in](https://developer.appear.in/)
* [SimpleWebRTC](https://github.com/andyet/SimpleWebRTC)
* [EasyRTC](https://github.com/priologic/easyrtc)
* [LyteSpark](http://lytespark.com/)

### Peer-to-peer data

* [simple-peer](https://github.com/feross/simple-peer) - data channel abstraction.
* [Sharefest](https://github.com/peer5/sharefest) - share files via data channels.
* [Peer5 Downloader](https://www.peer5.com/downloader) - P2P file download.
* ShareDrop: [web](https://www.sharedrop.io/), [source](https://github.com/cowbell/sharedrop) - file sharing between devices on the same network.

### VoIP/PSTN

* [Phono](http://phono.com/) - Open source JavaScript phone API
* [sipML5](https://code.google.com/p/sipml5/) - Open source JavaScript SIP client
* [JsSIP](http://jssip.net/) - Open source JavaScript SIP library
* [Kamailio](http://www.kamailio.org/w/) - Open source SIP proxy with WebSocket and SRTP support
* [FreeSWITCH](http://www.freeswitch.org/)

### Face/head tracking

* [clmtrackr](https://github.com/auduno/clmtrackr)
* headtrackr: [demo](http://simpl.info/headtrackr/), [source](https://github.com/auduno/headtrackr/)

### Node

* [rtc.io](http://rtc.io/)
* [appear.in](https://www.npmjs.com/package/appearin-sdk)

### Signaling

* [signalhub](https://github.com/mafintosh/signalhub) - verstaile subpub signaling server
* [simple-signal](https://github.com/RationalCoding/simple-signal) - complete signaling library for [simple-peer](https://github.com/feross/simple-peer)
* [turnserver](https://github.com/jitsi/turnserver) - open source TURN implementation
* [stunserver](https://github.com/jselbie/stunserver) - open source STUN implementation

## Services

* [OpenTok](http://www.tokbox.com/) - acquired by Telefonica Digital
* [vLine](https://github.com/vline)
* [WebRTC Developer Tool Vendor Directory](https://webrtchacks.com/vendor-directory/)

## Applications

### getUserMedia

* [ASCII camera](http://idevelop.github.com/ascii-camera) - getUserMedia + Canvas + ASCII conversion
* [Xylophone](http://soundstep.com/blog/experiments/jsdetection/)
* [Webcam Toy Photobooth app](http://webcamtoy.com/) - Photobooth with filters, getUserMedia + WebGL
* [SVG filters](https://rawgithub.com/SenorBlanco/moggy/master/filterbooth.html)
* [Face masking with WebGL](https://auduno.github.io/clmtrackr/face_mask.html)
* [Face deformation with WebGL](https://auduno.github.io/clmtrackr/examples/facedeform.html)
* [Augmented Reality Photobooth](https://picshare.jooink.com/)

### Screen capture

* [Screen recording app](https://github.com/niklasenbom/RecordingApp)

### Web Audio integration

* [Music production](http://soundtrap.com/)
* [Chris Wilson's input demos](http://webaudiodemos.appspot.com/)
* [Paul Lewis's gUM/WebGL demo](http://lab.aerotwist.com/webgl/audio-room)
* [RTCPeerConnection integration](http://simpl.info/webrtcwebaudio)
* [Theremin: getUserMedia + tracking + Web Audio](http://www.g200kg.com/teburin/)
* [cabbibo holly](http://cabbibo.github.io/holly/)

### Recording

* [Record audio and video with the MediaRecorder API](https://simpl.info/mr)
* [Voice Memos app](https://github.com/GoogleChrome/voice-memos)
* [Record and download without MediaRecorder](http://webaudiodemos.appspot.com/AudioRecorder/index.html)
* [RecordRTC](https://github.com/muaz-khan/WebRTC-Experiment/tree/master/RecordRTC)
* [media-recorder-stream](https://github.com/mafintosh/media-recorder-stream)

### Chat

* [talky.io](http://talky.io/)
* [appear.in](http://appear.in/)
* [tawk](http://tawk.com/)
* [hu.tt](http://hu.tt/)
* [Twelephone](http://blog.twelephone.com/) - chat with Twitter contacts.
* [browsermeeting](http://browsermeeting.com/)
* [codassium](http://codassium.com/) - job interview tool with live coding.
* [vmux.co](http://vmux.co/)
* [vidtok](http://vidtok.com/)
* [voxeet](http://www.voxeet.com/) - high quality audio.

### Games

* [Who Am I?](http://www.designweek.co.uk/news/magneticnorth-creates-who-am-i-game-for-google/3034813.article) - second ever WebRTC game, no longer online
* [Cube Slam](http://cubeslam.com/) - WebRTC + Web Audio + WebGL
* [Face tracking](https://github.com/operasoftware/shinydemos/tree/master/demos/facekat)
* [BananaBread](https://hacks.mozilla.org/2013/03/webrtc-data-channels-for-great-multiplayer/) - RTCDataChannel + WebGL

### Telehealth

* [Regional Cystic Fibrosis Program](http://www.pulseitmagazine.com.au/index.php?option=com_content&view=article&id=1382:cystic-fibrosis-project-to-trial-webrtc-home-monitoring-and-shared-ehr&catid=16:australian-ehealth&Itemid=327)
* [consultdirect](http://consultdirect.com.au/)

### Phone

* [Zingaya](http://demos.zingaya.com/webrtc-pstn/)
* [Tethr](http://tethr.tumblr.com/post/25513708436/tethr-and-tropo-in-the-google-i-o-sandbox) - Disaster communications

### File sharing and P2P

* [Sharefest](http://sharefest.me/) - share file by uploading and sharing link.
* [peerCDN](https://github.com/PeerCDN) - P2P CDN.
* [WebTorrent](http://webtorrent.io/) - BitTorrent over WebRTC.
* [webp2p](http://webp2p.org/)
* [peer5](https://peer5.com/) - add P2P file download to your web page.
* [pea-server](https://github.com/recap/pea-server) - browser-based ftp server over WebRTC

### Others

* [Internet-less WebRTC](https://plus.google.com/+JohannCampbell/posts/WEmRsCfuCEb)
* [Video call between Qt app and web app](http://research.edm.uhasselt.be/~jori/page/index.php?n=Misc.QtWebRTC)

### Alternatives for IE and Safari

* [Temasys Plugin](https://temasys.atlassian.net/wiki/display/TWPP/WebRTC+Plugins)

## Web Audio

### Demos and samples

* [simple webaudio demo](http://simpl.info/webaudio)
* [webaudio samples](http://googlechrome.github.io/web-audio-samples/)

### Tutorials

* [Getting started with the Web Audio API](http://html5rocks.com/en/tutorials/webaudio/intro)
* [Audio input](http://updates.html5rocks.com/2012/09/Live-Web-Audio-Input-Enabled) - with links to good, simple demos.
* [webaudio api guide](http://creativejs.com/resources/web-audio-api-getting-started)

### Newsletters

* [Web Audio Weekly](http://blog.chrislowis.co.uk/waw.html)

### Reference

* [webaudio api](http://webaudio.github.io/web-audio-api/)
* [w3c webaudio](http://w3.org/TR/webaudio)

### Related Lists
* [awesome-peer-to-peer](https://github.com/kgryte/awesome-peer-to-peer)
