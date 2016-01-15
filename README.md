# Awesome WebRTC [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[![Build Status](https://travis-ci.org/OpenRTC-IO/awesome-webrtc.svg)](https://travis-ci.org/OpenRTC-IO/awesome-webrtc)

A curated list of awesome WebRTC modules and resources. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

- [Awesome WebRTC](#awesome-webrtc)
  - [Overview](#overview)
  - [Demos and samples](#demos-and-samples)
  - [Tutorials](#tutorials)
  - [Codelab](#codelab)
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
  - [Applications: suggestions welcome!](#applications-suggestions-welcome)
    - [getUserMedia](#getusermedia)
    - [Web Audio integration](#web-audio-integration)
    - [Recording](#recording)
    - [Chat](#chat)
    - [Games](#games)
    - [Telehealth](#telehealth)
    - [Phone](#phone)
    - [File sharing and P2P](#file-sharing-and-p2p)
    - [Other](#other)
    - [Alternatives for IE and Safari](#alternatives-for-ie-and-safari)
  - [Web Audio](#web-audio)
    - [Demos](#demos)
    - [Tutorials](#tutorials)
    - [Reference](#reference)

- - -

## Overview

* [samples](https://github.com/webrtc/samples) - WebRTC code samples.
* [Live demos](https://webrtc.github.io/samples/) - WebRTC Live demos.
* [2013 Google I/O presentation](https://www.youtube.com/watch?v=p2HzZkd2A40) - If you've never worked with WebRTC, we recommend you start with it. [slides](http://io13webrtc.appspot.com/)
* [WebRTC official site](http://webrtc.org/)

## Demos and samples

* [CUBE SLAM](https://www.cubeslam.com/) - getUserMedia, RTCPeerConnection, RTCDataChannel, WebGL, Web Audio and CSS3. [cheats](http://www.cubeslam.com/cheats.html)
* [WebRTC Experiments](https://www.webrtc-experiment.com/) - A very long list of WebRTC demos and libraries.
* [List of WebRTC demos and apps](https://docs.google.com/document/d/1hNK15_cNx3CpYsro2TKwEbdFxLv5WFe8djGHdFeZBks/edit)
* [Simplest possible getUserMedia demo](http://simpl.info/getusermedia/)
* RTCPeerConnection 'on one page', i.e. without signaling: <http://simpl.info/rtcpeerconnection/>
* WebRTC video chat: <https://www.apprtc.net/>. [source code](https://github.com/webrtc/apprtc)
* Simplest possible RTCDataChannel example:: <http://simpl.info/rtcdatachannel/>
* Data channel file transfer: <http://webrtc.github.io/samples/src/content/datachannel/filetransfer/>
* RTCPeerConnection signaling example: <http://www.w3.org/TR/webrtc/#simple-example>
* Constraints: <https://simpl.info/getusermedia/constraints/>
* [Screen capture](https://html5-demos.appspot.com/static/getusermedia/screenshare.html)
* Muaz Khan maintains a mighty assortment of experiments at <https://www.webrtc-experiment.com/>

## Tutorials

* Getting Started With WebRTC: <http://www.html5rocks.com/en/tutorials/webrtc/basics/>
* [WebRTC in the real world: STUN, TURN and signaling](http://www.html5rocks.com/en/tutorials/webrtc/infrastructure/)
* [A practical guide to WebRTC](http://www.slideshare.net/vline/a-practical): presentation slides from vLine
* Capturing audio and video in HTML5: <http://www.html5rocks.com/en/tutorials/getusermedia/intro/>
* Excellent series of articles by Louis Stowasser and Robert Nyman: <https://hacks.mozilla.org/category/webrtc/>
* Justin Uberti at Google I/O 2012: <https://www.youtube.com/watch?v=E8C8ouiXHHk>
* Cullen Jennings video: HTML5 WebRTC: <http://vimeo.com/47682405>
* [WebRTC Fundamentals](http://bit.ly/learnwebrtc): online course.

## Codelab

* Walkthrough and code for setting up a server and client for video chat: <https://bitbucket.org/webrtc/codelab>
* [Google I/O 2014 file sharing codelab](http://io2014codelabs.appspot.com/static/codelabs/webrtc-file-sharing/#1)

## Books

* <http://webrtcbook.com/>
* [Getting Started with WebRTC](http://www.packtpub.com/getting-started-with-webrtc/book)
* [Real-Time Communication with WebRTC](http://bloggeek.me/book-webrtc-salvatore-simon/)

## Developer tools and resources

* [adapter.js](https://github.com/webrtc/adapter): shim maintained by Google to cope with API changes and platform differences.
* [getUserMedia.js](https://github.com/addyosmani/getUserMedia.js): polyfill from Addy Osmani
* Chrome-Firefox: <http://www.webrtc.org/web-apis/interop>
* Stats and information for current RTCPeerConnection session: <chrome://webrtc-internals>
* File bugs at <http://crbug.com/new>

## Standards and protocols

* [Web Real-Time Communications Working Group](http://www.w3.org/2011/04/webrtc/)
* [W3C Working Draft: WebRTC 1.0: Real-time Communication Between Browsers](http://www.w3.org/TR/webrtc/)
* [Media Capture and Streams W3C Working Draft](http://www.w3.org/TR/mediacapture-streams/)
* [IETF RTCWEB](http://datatracker.ietf.org/wg/rtcweb/): protocol specifications

## Native APIs

* [Getting started with WebRTC on iOS](https://tech.appear.in/2015/05/25/Getting-started-with-WebRTC-on-iOS/)
* [Introduction to WebRTC on Android](https://tech.appear.in/2015/05/25/Introduction-to-WebRTC-on-Android/)
* [Getting Started](http://www.webrtc.org/reference/getting-started) - from <http://webrtc.org>
* [Build scripts from pristineio](https://github.com/pristineio/webrtc-build-scripts): repo with links to how-to guides for Android and iOS
* [Native API documentation](http://www.webrtc.org/native-code/native-apis)
* [libjingle Developer Guide](https://developers.google.com/talk/libjingle/developer_guide)
* [WebRTC shim for WKWebView](https://github.com/common-tater/wkwebview-webrtc-shim)

## Discussion, blogs and articles

* [discuss-webrtc](https://groups.google.com/forum/?fromgroups#!forum/discuss-webrtc)
* [@webrtc](https://twitter.com/webrtc)
* [+webrtc](https://plus.google.com/+WebRTCorg)
* [WebRTC on Stack Overflow](http://stackoverflow.com/tags/webrtc)
* [WebRTC Weekly](https://webrtcweekly.com/)
* [WebRTCHacks](https://webrtchacks.com/)

## Browser support

* <http://iswebrtcreadyyet.com/>

## JavaScript apps and frameworks

*Also take a look at the webrtcHacks [article about JavaScript libraries](https://webrtchacks.com/whats-in-a-webrtc-javascript-library/)*

### Video chat

* [appear.in](https://developer.appear.in/)
* [SimpleWebRTC](https://github.com/andyet/SimpleWebRTC)
* [EasyRTC](https://github.com/priologic/easyrtc)
* [LyteSpark](http://lytespark.com/)

### Peer-to-peer data

* [PeerJS](http://peerjs.com/): data channel abstraction
* [Sharefest](https://github.com/peer5/sharefest): share files via data channels
* [Peer5 Downloader](https://www.peer5.com/downloader): P2P file download
* [ShareDrop](https://github.com/cowbell/sharedrop): <https://www.sharedrop.io/> file sharing between devices on the same network

### VoIP/PSTN

* Open source JavaScript phone API: [Phono](http://phono.com/)
* Open source JavaScript SIP client: [sipML5](https://code.google.com/p/sipml5/)
* Open source JavaScript SIP library: [JsSIP](http://jssip.net/)
* Open source SIP proxy with WebSocket and SRTP support: [Kamailio](http://www.kamailio.org/w/)
* [FreeSWITCH](http://www.freeswitch.org/)

### Face/head tracking

* [clmtrackr](https://github.com/auduno/clmtrackr)
* [headtrackr](https://github.com/auduno/headtrackr/) - demo: <http://simpl.info/headtrackr/>

### Node

* <http://rtc.io/>
* [appear.in](https://www.npmjs.com/package/appearin-sdk)

## Services

* [OpenTok](http://www.tokbox.com/) - acquired by Telefonica Digital
* [vLine](http://www.vline.com/)
* [WebRTC Developer Tool Vendor Directory](https://webrtchacks.com/vendor-directory/)

## Applications: suggestions welcome!

### `getUserMedia`

* [ASCII camera](http://idevelop.github.com/ascii-camera) - getUserMedia + Canvas + ASCII conversion
* Movement tracking slide page controller: <http://www.slideshare.net/tsahil/kranky-geek-webrtc-show-webrtc-in-the-real-world>
* Xylophone: <http://soundstep.com/blog/experiments/jsdetection/>
* [Webcam Toy photobooth app](http://webcamtoy.com/) - Photobooth with filters, getUserMedia + WebGL
* SVG filters: <https://rawgithub.com/SenorBlanco/moggy/master/filterbooth.html>
* Face masking with WebGL: <https://auduno.github.io/clmtrackr/face_mask.html>
* Face deformation with WebGL: <https://auduno.github.io/clmtrackr/examples/facedeform.html>
* Screen capture: <http://simpl.info/mediacapture/>

### Web Audio integration

* Music production: <http://soundtrap.com/>
* Chris Wilson's input demos at <http://webaudiodemos.appspot.com/>
* Paul Lewis's gUM/WebGL demo: <http://lab.aerotwist.com/webgl/audio-room>
* RTCPeerConnection integration: <http://simpl.info/webrtcwebaudio>
* Theremin: getUserMedia + tracking + Web Audio: <http://www.g200kg.com/teburin/>
* <http://cabbibo.github.io/holly/>

### Recording

* Record and download: <https://webaudiodemos.appspot.com/AudioRecorder/index.html>
* RecordRTC: <https://github.com/muaz-khan/WebRTC-Experiment/tree/master/RecordRTC>

### Chat

* <http://talky.io/>
* <http://tawk.com/>
* <http://hu.tt/>
* [Twelephone](http://blog.twelephone.com/): chat with Twitter contacts
* <http://browsermeeting.com/>
* <http://codassium.com/>: job interview tool with live coding
* <http://appear.in/>
* <https://github.com/malditogeek/vmux>
* <http://vidtok.com/>
* <http://www.voxeet.com/>: high quality audio

### Games

* [Who Am I?](http://www.designweek.co.uk/news/magneticnorth-creates-who-am-i-game-for-google/3034813.article): second ever WebRTC game, no longer online
* WebRTC + Web Audio + WebGL: [Cube Slam](http://cubeslam.com/)
* Face tracking: <http://www.shinydemos.com/facekat/>
* RTCDataChannel + WebGL: [ ananaBread](https://hacks.mozilla.org/2013/03/webrtc-data-channels-for-great-multiplayer/)

### Telehealth

* [Regional Cystic Fibrosis Program](http://www.pulseitmagazine.com.au/index.php?option=com_content&view=article&id=1382:cystic-fibrosis-project-to-trial-webrtc-home-monitoring-and-shared-ehr&catid=16:australian-ehealth&Itemid=327)
* <http://consultdirect.com.au/>

### Phone

* [Zingaya](http://demos.zingaya.com/webrtc-pstn/)
* Disaster communications: [Tethr](http://tethr.tumblr.com/post/25513708436/tethr-and-tropo-in-the-google-i-o-sandbox)

### File sharing and P2P

* [Sharefest](http://sharefest.me/): share file by uploading and sharing link.
* <http://dropple.me/>: get a file by sending a link to a share page
* [peerCDN](https://github.com/PeerCDN): P2P CDN
* [WebTorrent](http://webtorrent.io/): BitTorrent over WebRTC
* <https://www.peer5.com/video>: P2P video
* <http://webp2p.org/>
* <http://peer5.com/downloader/land.html>: add P2P file download to your web page

### Other

* [Internet-less WebRTC](https://plus.google.com/+JohannCampbell/posts/WEmRsCfuCEb)
* [Video call between Qt app and web app](http://research.edm.uhasselt.be/~jori/page/index.php?n=Misc.QtWebRTC)

### Alternatives for IE and Safari

* [Temasys Plugin](https://temasys.atlassian.net/wiki/display/TWPP/WebRTC+Plugins)

## Web Audio

### Demos

* <http://simpl.info/webaudio>
* <http://googlechrome.github.io/web-audio-samples/>

### Tutorials

* Getting started with the Web Audio API: <http://html5rocks.com/en/tutorials/webaudio/intro>
* Audio input (with links to good, simple demos): <http://updates.html5rocks.com/2012/09/Live-Web-Audio-Input-Enabled>
* <http://creativejs.com/resources/web-audio-api-getting-started>

### Newsletters

* [Web Audio Weekly](http://blog.chrislowis.co.uk/waw.html)

### Reference

* <http://webaudio.github.io/web-audio-api/>
* <http://w3.org/TR/webaudio>
