# Awesome Real Time Communications with stars

> Protocols and methodology for near simultaneous exchange of media and data.

## Contents

* [Server Software](#server-software)
  * [General Purpose](#general-purpose)
  * [SIP Servers](#sip-servers)
  * [Media Servers](#media-servers)
  * [STUN/TURN](#stunturn)
* [Clients](#clients)
* [Operations](#operations)
  * [Monitoring](#monitoring)
  * [Testing](#testing)
  * [Web/API Interfaces](#webapi-interfaces)
  * [Billing](#billing)
* [Developer Resources](#developer-resources)
  * [Tutorials](#tutorials)
  * [JavaScript Libraries](#javascript-libraries)
  * [C/C++ Libraries](#cc-libraries)
  * [Go Libraries](#go-libraries)
  * [PHP Libraries](#php-libraries)
  * [Python Libraries](#python-libraries)
  * [Erlang Libraries](#erlang-libraries)
  * [Rust Libraries](#rust-libraries)
  * [Dart Libraries](#dart-libraries)
  * [Media over QUIC](#media-over-quic)
* [Blogs](#blogs)
* [Discussion](#discussion)
* [Events and Talks](#events-and-talks)
* [Contribute](#contribute)

## Server Software

### General Purpose

* [FreeSWITCH](https://github.com/signalwire/freeswitch) ⭐ 5,326 | 🐛 1,287 | 🌐 C | 📅 2026-11-24 - Open source communications server for voice, video, messaging and conferencing.
* [Asterisk](https://www.asterisk.org/) - PBX framework supporting multiple protocols and platforms.

### SIP Servers

* [FreeSBC](https://github.com/rasonyang/freesbc) ⭐ 417 | 🐛 12 | 🌐 Go | 📅 2026-11-23 - Open source SIP/WebRTC edge proxy with an embedded RTP relay for FreeSWITCH and Asterisk.
* [Sippy B2BUA](https://github.com/sippy/b2bua) ⭐ 203 | 🐛 28 | 🌐 Python | 📅 2026-11-25 - Back-to-back user agent server written in Python.
* [Flexisip](https://github.com/BelledonneCommunications/flexisip) ⭐ 194 | 🐛 30 | 🌐 C++ | 📅 2026-11-24 - SIP server suite comprising proxy, presence and group chat functions.
* [P-KISS-SBC](https://github.com/mwolff44/pk-sbc) ⭐ 114 | 🐛 1 | 🌐 Shell | 📅 2026-10-06 - Kamailio and rtpengine-based session border controller for connecting SIP trunks and PBXs.
* [Kamailio](https://www.kamailio.org/w/) - Open source SIP server for routing, registration, presence and large-scale deployments.
* [OpenSIPS](https://opensips.org/) - Open source SIP proxy and application server for VoIP platforms.
* [Routr](https://routr.io) - Cloud-native SIP proxy, registrar and location service.

### Media Servers

* [LiveKit](https://github.com/livekit/livekit) ⭐ 22,390 | 🐛 229 | 🌐 Go | 📅 2026-11-25 - Open source WebRTC server and SDK ecosystem for real-time audio, video and data.
* [MediaMTX](https://github.com/bluenviron/mediamtx) ⭐ 20,772 | 🐛 209 | 🌐 Go | 📅 2026-11-25 - Media server and proxy bridging WebRTC, RTSP, RTMP and SRT streams, with recording and playback.
* [go2rtc](https://github.com/AlexxIT/go2rtc) ⭐ 14,725 | 🐛 1,058 | 🌐 Go | 📅 2026-11-25 - Camera streaming gateway with WebRTC viewing, RTSP restreaming and two-way audio integrations.
* [rtpengine](https://github.com/sipwise/rtpengine) ⭐ 1,014 | 🐛 106 | 🌐 Perl | 📅 2026-11-25 - RTP and UDP based media traffic proxy, usable as a kernel module.
* [SEMS](https://github.com/sems-server/sems) ⭐ 189 | 🐛 57 | 🌐 C++ | 📅 2026-11-25 - Open source media and application server for SIP based VoIP services.
* [Janus](https://janus.conf.meetecho.com) - Lightweight open source, general purpose, WebRTC gateway.
* [RTPProxy](https://www.rtpproxy.org) - General purpose high performance RTP proxy.
* [mediasoup](https://mediasoup.org) - Specialized WebRTC conferencing system.
* [Jitsi](https://jitsi.org/projects) - A collection of RTC open source projects, with a focus on conferencing software.

### STUN/TURN

* [coturn](https://github.com/coturn/coturn) ⭐ 14,597 | 🐛 314 | 🌐 C | 📅 2026-11-23 - Fully featured TURN/STUN server supporting multiple platforms.
* [STUNTMAN](https://github.com/jselbie/stunserver) ⭐ 1,619 | 🐛 14 | 🌐 C++ | 📅 2026-05-12 - RFC compliant open source STUN implementation.
* [STUNner](https://github.com/l7mp/stunner) ⭐ 1,072 | 🐛 1 | 🌐 Go | 📅 2026-11-18 - Kubernetes-native STUN/TURN gateway for WebRTC media.
* [eturnal](https://eturnal.net/) - Modern and scalable STUN/TURN server written in Erlang.

## Clients

* [baresip](https://github.com/baresip/baresip) ⭐ 2,282 | 🐛 8 | 🌐 C | 📅 2026-11-25 - Modular SIP user agent with command-line controls, audio/video calls and pluggable media modules.
* [Web SIP Phone](https://github.com/rasonyang/web-sip-phone) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-26 - Chrome extension maintaining SIP/WebRTC audio for server-controlled call center agents.

## Operations

### Monitoring

* [HOMER](https://github.com/sipcapture/homer) ⭐ 2,036 | 🐛 0 | 🌐 Go | 📅 2026-11-20 - Multi-protocol capturing and monitoring framework for RTC.
* [sngrep](https://github.com/irontec/sngrep) ⭐ 1,218 | 🐛 66 | 🌐 C | 📅 2026-11-25 - Terminal based SIP flow viewer.
* [sipgrep](https://github.com/sipcapture/sipgrep) ⭐ 179 | 🐛 0 | 🌐 C | 📅 2026-11-12 - Console tool for sniffing, capturing and exploring SIP traffic.
* [sip-exporter](https://github.com/aibudaevv/sip-exporter) ⭐ 58 | 🐛 0 | 🌐 Go | 📅 2026-11-17 - Open-source eBPF sensor exporting Prometheus metrics and Grafana dashboards for host-observed IPv4/UDP SIP and correlated RTP/RTCP.
* [rtcStats](https://github.com/rtcstats/rtcstats) ⭐ 50 | 🐛 11 | 🌐 JavaScript | 📅 2026-11-24 - WebRTC API trace and getStats collection, storage and feature extraction tooling.
* [Trickle ICE](https://webrtc.github.io/samples/src/content/peerconnection/trickle-ice) - Exposes client-side NAT traversal debug data.
* [SIP3 Community Edition](https://sip3.io/docs/InstallationGuide.html) - Open source SIP/RTP capture, analysis and monitoring components with community deployment tooling.

### Testing

* [SIPp](https://github.com/SIPp/sipp) ⭐ 1,160 | 🐛 1 | 🌐 C++ | 📅 2026-11-23 - Traffic generator and scenario-based test tool for the SIP protocol.
* [SIPVicious](https://github.com/EnableSecurity/sipvicious) ⭐ 1,115 | 🐛 0 | 🌐 Python | 📅 2026-07-10 - Suite of security tools that can be used to audit SIP based VoIP systems.
* [sipexer](https://github.com/miconda/sipexer) ⭐ 436 | 🐛 0 | 🌐 Go | 📅 2026-11-16 - Modern and flexible SIP command line tool.
* [sipsak](https://github.com/nils-ohlmeier/sipsak) ⭐ 177 | 🐛 25 | 🌐 C | 📅 2025-05-26 - SIP stress and diagnostics utility.
* [natcheck](https://github.com/1mb-dev/natcheck) ⭐ 4 | 🐛 8 | 🌐 Go | 📅 2026-11-01 - NAT diagnosis CLI that probes STUN servers and reports mapping behaviour and a WebRTC P2P forecast.

### Web/API Interfaces

* [Fonoster](https://github.com/fonoster/fonoster) ⭐ 8,172 | 🐛 5 | 🌐 TypeScript | 📅 2026-11-20 - Open source platform for programmable voice and voice AI applications.
* [Kazoo](https://github.com/2600hz/kazoo/tree/4.3) ⭐ 992 | 🐛 29 | 🌐 Erlang | 📅 2025-02-11 - Legacy open source VoIP API platform built on FreeSWITCH and Kamailio, available in the public 4.3 branch.
* [AI Native Call Center](https://github.com/rasonyang/ai-native-callcenter) ⭐ 793 | 🐛 130 | 🌐 Go | 📅 2026-11-25 - FreeSWITCH-based call center with speech-to-speech AI, agent queues and a web interface/API.
* [Sayna](https://github.com/SaynaAI/sayna) ⭐ 317 | 🐛 1 | 🌐 Rust | 📅 2026-05-31 - Real-time speech infrastructure for voice AI with WebSocket streaming, SIP telephony and pluggable STT/TTS providers.
* [IVOZ Provider](https://github.com/irontec/ivozprovider) ⭐ 228 | 🐛 97 | 🌐 PHP | 📅 2026-11-25 - Multitenant solution for VoIP telephony providers.
* [Eqivo](https://eqivo.org) - Open source programmable-voice/telephony API platform.
* [FusionPBX](https://www.fusionpbx.com) - Multitenant system built on top of FreeSWITCH.
* [FreePBX](https://www.freepbx.org) - Web Manager for Asterisk.
* [Wazo](https://wazo-platform.org) - VoIP API platform built on top of Asterisk, Kamailio and RTPEngine.
* [jambonz](https://www.jambonz.org) - Open source CPaaS built for communications service providers.

### Billing

* [CGRateS](https://github.com/cgrates/cgrates) ⭐ 532 | 🐛 63 | 🌐 Go | 📅 2026-11-24 - Open source rating, charging and billing engine for telecom and ISP services.

## Developer Resources

### Tutorials

* [WebRTC.org](https://webrtc.org/) - Official WebRTC guides, APIs and project resources.
* [Getting Started With WebRTC](https://webrtc.org/getting-started/overview) - Official introduction to media capture and peer-to-peer connectivity APIs.
* [WebRTC Samples](https://webrtc.github.io/samples) - Collection of samples demonstrating various parts of the WebRTC APIs.
* [WebRTC for the Curious](https://webrtcforthecurious.com/) - Open book explaining WebRTC protocols, architecture and practical debugging.

### JavaScript Libraries

* [simple-peer](https://github.com/feross/simple-peer) ⭐ 7,795 | 🐛 128 | 🌐 JavaScript | 📅 2024-06-26 - WebRTC wrapper for browser media streams and data channels.
* [adapter.js](https://github.com/webrtcHacks/adapter) ⭐ 3,746 | 🐛 6 | 🌐 JavaScript | 📅 2026-10-13 - JavaScript shim for abstracting WebRTC spec changes and inconsistencies.
* [werift](https://github.com/shinyoshiaki/werift-webrtc) ⭐ 650 | 🐛 33 | 🌐 TypeScript | 📅 2026-11-25 - TypeScript WebRTC implementation for Node.js with media, data channels and RTP/RTCP APIs.
* [Peerix](https://github.com/meefik/peerix) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-30 - TypeScript WebRTC library for peer-to-peer media and data with pluggable signalling drivers.
* [drachtio](https://drachtio.org) - Node.js SIP server framework.
* [JsSIP](https://jssip.net/) - Open source JavaScript SIP library with WebRTC media support.
* [PeerJS](https://peerjs.com) - Data and media peer-to-peer connection API implemented over WebRTC.
* [Longpipe](https://longpipe.dev) - Real-time video effects for WebRTC streams in the browser: virtual background, background blur, face touch-up and auto-reframe.

### C/C++ Libraries

* [libdatachannel](https://github.com/paullouisageneau/libdatachannel) ⭐ 2,793 | 🐛 166 | 🌐 C++ | 📅 2026-11-22 - Standalone C/C++ library for WebRTC data channels, media transport and WebSockets.
* [libSRTP](https://github.com/cisco/libsrtp) ⭐ 1,406 | 🐛 22 | 🌐 C | 📅 2026-11-25 - Secure Real-time Transport Protocol (SRTP) library for C.
* [icey](https://github.com/auscaster/icey) ⭐ 1,368 | 🐛 7 | 🌐 C++ | 📅 2026-10-30 - C++20 media toolkit combining WebRTC, FFmpeg, asynchronous networking and signalling.
* [usrsctp](https://github.com/sctplab/usrsctp) ⭐ 766 | 🐛 191 | 🌐 C | 📅 2026-11-23 - Portable Stream Control Transmission Protocol (SCTP) user-land stack.
* [Sofia-SIP](https://github.com/freeswitch/sofia-sip) ⭐ 358 | 🐛 133 | 🌐 C | 📅 2026-11-25 - Open source SIP library used by FreeSWITCH.
* [libre](https://github.com/baresip/re) ⭐ 197 | 🐛 14 | 🌐 C | 📅 2026-11-22 - Portable SIP, SDP, RTP, SRTP and ICE/STUN/TURN library with asynchronous I/O.
* [PJSIP](https://www.pjsip.org) - Multi-protocol RTC library written in C.
* [eXosip](http://savannah.nongnu.org/projects/exosip) - eXtended osip is a mature C library for abstracting the SIP protocol.
* [GStreamer WebRTC](https://gstreamer.freedesktop.org/documentation/webrtc/) - WebRTC elements for connecting native GStreamer media pipelines to browser peers.

### Go Libraries

* [go-diameter](https://github.com/fiorix/go-diameter) ⭐ 298 | 🐛 3 | 🌐 Go | 📅 2026-11-21 - RFC compliant Diameter protocol library.
* [Pion](https://pion.ly) - Extensive software stack for WebRTC written in Go.

### PHP Libraries

* [RTCKit/SIP](https://github.com/rtckit/php-sip) ⭐ 43 | 🐛 1 | 🌐 PHP | 📅 2024-11-11 - SIP message parsing and rendering library for PHP.

### Python Libraries

* [aiortc](https://github.com/aiortc/aiortc) ⭐ 5,134 | 🐛 8 | 🌐 Python | 📅 2026-11-25 - WebRTC and ORTC implementation for Python using asyncio.

### Erlang Libraries

* [ersip](https://github.com/poroh/ersip) ⭐ 130 | 🐛 8 | 🌐 Erlang | 📅 2024-09-25 - Library comprising building blocks for SIP applications.

### Rust Libraries

* [WebRTC.rs](https://github.com/webrtc-rs/webrtc) ⭐ 5,191 | 🐛 22 | 🌐 Rust | 📅 2026-11-07 - Asynchronous WebRTC implementation in Rust with SDP, RTP, RTCP and SRTP support.

### Dart Libraries

* [Flutter WebRTC](https://github.com/flutter-webrtc/flutter-webrtc) ⭐ 4,502 | 🐛 769 | 🌐 C++ | 📅 2026-11-25 - WebRTC bindings for Flutter applications on mobile, desktop and the web.
* [dart-sip-ua](https://github.com/flutter-webrtc/dart-sip-ua) ⭐ 375 | 🐛 168 | 🌐 Dart | 📅 2026-10-16 - Dart SIP user-agent stack with SIP over WebSocket and WebRTC media support.

### Media over QUIC

Experimental implementations for live media over QUIC and WebTransport. Supported draft versions and protocol variants differ; check compatibility before combining implementations.

* [moq](https://github.com/moq-dev/moq) ⭐ 1,642 | 🐛 70 | 🌐 Rust | 📅 2026-11-25 - Rust and TypeScript libraries, relay and browser player implementing moq-lite.
* [moq-rs](https://github.com/cloudflare/moq-rs) ⭐ 189 | 🐛 79 | 🌐 Rust | 📅 2026-11-10 - Rust implementation of Media over QUIC Transport with a relay and sample publishers.
* [moxygen](https://github.com/facebookexperimental/moxygen) ⭐ 127 | 🐛 25 | 🌐 C++ | 📅 2026-11-25 - C++ Media over QUIC Transport library with a relay, sample applications and interoperability tools.
* [moqtail](https://github.com/moqtail/moqtail) ⭐ 114 | 🐛 29 | 🌐 TypeScript | 📅 2026-11-22 - Rust and TypeScript Media over QUIC Transport libraries with a relay and example clients.
* [imquic](https://github.com/meetecho/imquic) ⭐ 84 | 🐛 3 | 🌐 C | 📅 2026-11-23 - Experimental C library for QUIC and WebTransport with RTP over QUIC and Media over QUIC Transport support.
* [libquicr](https://github.com/Quicr/libquicr) ⭐ 21 | 🐛 34 | 🌐 C++ | 📅 2026-11-25 - C++ Media over QUIC Transport library with publish, subscribe, capture and replay tools.

## Blogs

* [BlogGeekMe](https://bloggeek.me/blog) - Blog by Tsahi Levent-Levi with a strong focus on WebRTC.
* [WebRTC For Developers](https://www.webrtc-developers.com/) - Articles, examples and tools for WebRTC application developers.
* [WebRTCHacks](https://webrtchacks.com) - WebRTC blog by independent technologists.

## Discussion

* [FreeSWITCH Community](https://signalwire.community) - Discord community for FreeSWITCH and SignalWire users and developers.
* [discuss-webrtc](https://groups.google.com/g/discuss-webrtc) - Developer discussion group for WebRTC APIs, implementations and interoperability.

## Events and Talks

* [ClueCon](https://www.cluecon.com/) - Conference for communications and voice AI developers.
* [Kamailio World](https://www.kamailio.org/w/category/kamailio-world/) - Conference announcements and technical sessions covering Kamailio and open source RTC systems.
* [AstriCon](https://www.asterisk.org/astricon/) - Conference for Asterisk and FreePBX developers and users.
* [CommCon](https://commcon.xyz/) - RTC and open-media community events with a technical talk archive.
* [OpenSIPS Summit](https://www.opensips.org/Community/Summits) - OpenSIPS community conferences with technical presentations and proceedings.
* [FOSDEM](https://fosdem.org) - Free event for software developers, with a RTC component, held every year in Europe.
* [JanusCon](https://www.januscon.it/2024/) - Conference proceedings and technical talks for Janus and WebRTC developers.
* [TADHack](https://blog.tadhack.com/) - Telecom application hackathons, demos and event announcements.

## Related Lists

* [Awesome Cellular Hacking](https://github.com/W00t3k/Awesome-Cellular-Hacking) ⭐ 4,148 | 🐛 0 | 📅 2026-11-03 - Research resources in the 3G/4G/5G Cellular security space.
* [Awesome Telco](https://github.com/ravens/awesome-telco) ⭐ 1,041 | 🐛 0 | 🌐 Python | 📅 2026-11-24 - Telco resources and projects.
* [Awesome 5G](https://github.com/calee0219/awesome-5g) ⭐ 919 | 🐛 10 | 🌐 Shell | 📅 2026-02-03 - 5G frameworks, libraries, software and resources.
* [Awesome RTC Hacking](https://github.com/EnableSecurity/awesome-rtc-hacking) ⭐ 566 | 🐛 0 | 📅 2026-06-30 - Real Time Communications hacking and penetration testing resources.
* [SIP Resources](https://github.com/miconda/sip-resources) ⭐ 260 | 🐛 1 | 📅 2026-11-23 - Useful SIP resources curated by Kamailio's head developer.
* [Awesome Asterisk](https://github.com/ictinnovations/awesome-asterisk) ⭐ 13 | 🐛 0 | 📅 2026-10-24 - Asterisk tooling: ARI, AMI and AGI libraries, call audio streaming, voice AI and testing.
* [Awesome FreeSWITCH](https://github.com/ictinnovations/awesome-freeswitch) ⭐ 4 | 🐛 0 | 📅 2026-11-25 - FreeSWITCH tooling: Event Socket libraries, call audio streaming, distributions and monitoring.

## Contribute

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-25._
