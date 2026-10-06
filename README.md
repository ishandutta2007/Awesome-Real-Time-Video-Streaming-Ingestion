# Awesome-Real-Time-Video-Streaming-Ingestion

## Top Real-Time Video Streaming & Ingestion Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Live Ingest, Low-Latency Delivery & Self-Hosted Media Servers*  

**Last updated: October 2026**



This repository tracks notable **commercial real-time video streaming platforms** and **open-source projects** that ingest, transcode, and deliver live video with minimal latency — from sub-second WebRTC to scalable HLS/DASH for broadcasts and interactive applications.



**Examples** include AWS Kinesis Video Streams, Cloudflare Stream, Mux Video, Wowza Cloud, Twilio Video, Agora.io, Ant Media Server, Livepeer, Bambuser, and Dyte (the category leaders).



**Open-source emphasis**: Real-time video streaming and ingestion is one of the strongest open-source domains. **SRS**, **MediaMTX**, **Ant Media Server**, **OvenMediaEngine**, **LiveKit**, **Jitsi**, and **Janus** collectively power sub-second live streaming and WebRTC at scale. **Owncast** delivers self-hosted broadcasting, **Nginx-RTMP** and **Restreamer** provide simple streaming setups, and **FFmpeg**/**GStreamer** handle media processing. **Pion WebRTC** brings pure Go WebRTC. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[AWS Kinesis Video Streams](https://aws.amazon.com/kinesis/video-streams/)**  

  **AWS's managed video streaming and ingestion service** — ingest, store, and process video for analytics and ML . **Best for AWS-native video applications** .



- **[Cloudflare Stream](https://www.cloudflare.com/products/stream/)**  

  **Cloudflare's video platform** — upload, store, and deliver video with global CDN . **Best for simple video delivery** .



- **[Mux Video](https://mux.com/)**  

  **API-first video platform** — ingest, transcode, and deliver video with analytics . **Best for developer-friendly video** .



- **[Wowza Cloud](https://www.wowza.com/)**  

  **Enterprise live streaming platform** — low-latency streaming with adaptive bitrate . **Best for broadcast-grade streaming** .



- **[Twilio Video](https://www.twilio.com/video)**  

  **Programmable video platform** — WebRTC-based video for applications . **Best for Twilio ecosystem users** .



- **[Agora.io](https://www.agora.io/)**  

  **Real-time engagement platform** — voice, video, and interactive streaming . **Best for interactive live streaming** .



- **[Ant Media Server](https://antmedia.io/)**  

  **Ultra-low latency streaming** — see Open-Source section for the community edition.



- **[Livepeer](https://livepeer.org/)**  

  **Decentralized video streaming** — open-source protocol with managed cloud . **Best for decentralized video** .



- **[Bambuser](https://bambuser.com/)**  

  **Live video shopping platform** — interactive streaming for e-commerce . **Best for live commerce** .



- **[Dyte](https://dyte.io/)**  

  **Real-time video and voice SDKs** — embed live video in applications . **Best for developer-friendly video** .



## Open-Source GitHub Projects



### Live Streaming & Ingestion Servers



- **[SRS (Simple Realtime Server)](https://github.com/ossrs/srs)**  

  **The leading open-source live streaming server**, MIT licensed with **25,000+ GitHub stars** . **Supports RTMP, HLS, SRT, WebRTC, and DASH** . **Scalable to millions of viewers** . **The de facto open-source Wowza alternative** . **Best for production live streaming and ingestion** .



- **[MediaMTX](https://github.com/bluenviron/mediamtx)**  

  **Zero-dependency real-time media server**, MIT licensed with **10,000+ GitHub stars** . **Supports SRT, WebRTC, RTSP, RTMP, HLS, and LL-HLS** . **Single binary with no dependencies** . **The simplest path to low-latency streaming** . **Best for edge and IoT streaming** .



- **[Ant Media Server](https://github.com/ant-media/Ant-Media-Server)**  

  **Ultra-low latency streaming server**, Apache-2.0 licensed with **4,000+ GitHub stars** . **Sub-second latency with WebRTC** . **Adaptive bitrate, recording, and scaling** . **Community Edition free**; Enterprise for advanced features . **Best for ultra-low latency streaming** .



- **[OvenMediaEngine](https://github.com/AirenSoft/OvenMediaEngine)**  

  **Sub-second latency streaming server**, AGPL-3.0 licensed with **3,000+ GitHub stars** . **LLHLS, WebRTC, and SRT support** . **Best for ultra-low latency** .



- **[Nginx-RTMP](https://github.com/arut/nginx-rtmp-module)**  

  **RTMP streaming module for Nginx**, BSD-2-Clause licensed . **Simple RTMP streaming with HLS/DASH output** . **Best for simple RTMP streaming and ingestion** .



- **[Restreamer](https://github.com/datarhei/restreamer)**  

  **Self-hosted live streaming**, Apache-2.0 licensed . **Web UI for streaming to multiple platforms** . **Best for multi-platform streaming** .



- **[Owncast](https://github.com/owncast/owncast)**  

  **Self-hosted live streaming and chat**, MIT licensed with **10,000+ GitHub stars** . **Own your live stream** . **Best for independent broadcasters** .



- **[RtspSimpleServer](https://github.com/aler9/rtsp-simple-server)** — Predecessor to MediaMTX, now succeeded by MediaMTX .



### WebRTC & Real-Time Communication



- **[LiveKit](https://github.com/livekit/livekit)**  

  **Open-source WebRTC platform**, Apache-2.0 licensed with **10,000+ GitHub stars** . **Scalable SFU architecture** . **SDKs for all platforms** . **Best for building scalable video applications** .



- **[Jitsi Meet](https://github.com/jitsi/jitsi-meet)**  

  **The leading open-source video conferencing platform**, Apache-2.0 licensed with **25,000+ GitHub stars** . **WebRTC-based with scalable SFU** . **Best for video conferencing** .



- **[Janus WebRTC Server](https://github.com/meetecho/janus-gateway)**  

  **General-purpose WebRTC server**, GPL-3.0 licensed . **Plugin architecture for VideoRoom, SIP, and streaming** . **Best for flexible WebRTC** .



- **[mediasoup](https://github.com/versatica/mediasoup)**  

  **High-performance SFU library**, ISC licensed . **C++ core with Node.js signaling** . **Best for building custom WebRTC applications** .



- **[Pion WebRTC](https://github.com/pion/webrtc)**  

  **Pure Go WebRTC implementation**, MIT licensed with **13,000+ GitHub stars** . **No Cgo dependencies** . **Best for Go-based WebRTC** .



- **[OpenVidu](https://github.com/OpenVidu/openvidu)**  

  **Open-source WebRTC platform**, Apache-2.0 licensed . **Build custom video applications with SDKs** . **Best for custom video apps** .



### Media Processing & Transcoding



- **[FFmpeg](https://github.com/FFmpeg/FFmpeg)**  

  **The foundational multimedia framework**, LGPL/GPL licensed . **The engine behind most streaming platforms** . **Best for media processing and ingestion** .



- **[GStreamer](https://github.com/GStreamer/gstreamer)**  

  **Pipeline-based multimedia framework**, LGPL licensed . **Modular media processing** . **Best for custom media pipelines** .



- **[OBS Studio](https://github.com/obsproject/obs-studio)**  

  **The leading open-source streaming software**, GPL-2.0 licensed with **60,000+ GitHub stars** . **Scene composition, encoding, and streaming** . **Best for content creation and ingestion** .



- **[Shaka Packager](https://github.com/shaka-project/shaka-packager)**  

  **Media packaging SDK**, Apache-2.0 licensed . **DASH, HLS, and CMAF packaging with DRM** . **Best for multi-format packaging** .



### Additional Strong Open-Source Options



- **Kurento** — WebRTC media server .

- **FreeSWITCH** — Telephony with video .

- **Asterisk** — PBX with video .

- **Red5** — Open-source Flash/RTMP server .

- **Nimble Streamer** — Lightweight streaming server .

- **Unreal Media Server** — Low-latency streaming .

- **Flussonic** — Commercial streaming server .

- **Wowza Streaming Engine** — Commercial with free trial .

- **Bento4** — MP4 and DASH tooling .

- **GPAC** — Multimedia framework with DASH/HLS .



**Frameworks for building custom real-time video streaming and ingestion solutions**: Combine **SRS** or **MediaMTX** for production live streaming with RTMP, SRT, and WebRTC ingestion . Use **Ant Media Server** or **OvenMediaEngine** for ultra-low latency sub-second streaming . Deploy **LiveKit** or **Jitsi** for WebRTC conferencing . Choose **Owncast** for self-hosted broadcasting . Integrate **FFmpeg** and **GStreamer** for media processing and transcoding . Use **OBS Studio** for content creation and ingestion . Note that true managed real-time video with global CDN, automatic scaling, and vendor-supported SLAs (Cloudflare Stream, Mux, Wowza, Agora) remains primarily commercial territory; open-source stacks provide strong streaming servers, WebRTC, and media processing foundations that require integration for complete video ingestion and delivery.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Real-time video platforms handle bandwidth-intensive workloads and may process sensitive content. Self-hosted solutions require proper security hardening, bandwidth planning, and compliance with content regulations.

- **Latency vs. scalability trade-offs** — WebRTC delivers sub-second latency but scales to hundreds; HLS/DASH scales to millions but adds 6-30 seconds latency. Choose based on use case .

- **Bandwidth costs scale linearly** — each viewer consumes bandwidth. Self-hosted streaming requires CDN or adequate egress capacity .

- **License considerations**: SRS uses MIT, MediaMTX uses MIT, Ant Media uses Apache-2.0, and OvenMediaEngine uses AGPL-3.0. Verify licensing against your use case before committing .

- The open-source ecosystem provides strong streaming servers, WebRTC, and media processing foundations, but **global CDN, automatic scaling, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for streaming engineers, media developers, and organizations seeking video streaming sovereignty.**  

Let's make real-time video streaming and ingestion more open, transparent, and accessible.
