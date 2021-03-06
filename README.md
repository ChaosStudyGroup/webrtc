<h1 align="center">
 <a href="https://webrtc.rs"><img src="./doc/webrtc.rs.png" alt="WebRTC.rs"></a>
 <br>
</h1>
<p align="center">
 <a href="https://github.com/webrtc-rs/webrtc/actions"> 
  <img src="https://github.com/rtcrs/webrtc/workflows/webrtc/badge.svg?branch=master">
 </a> 
 <a href="https://codecov.io/gh/webrtc-rs/webrtc"> 
  <img src="https://codecov.io/gh/webrtc-rs/webrtc/branch/master/graph/badge.svg">
 </a>
 <a href="https://deps.rs/repo/github/webrtc-rs/webrtc"> 
  <img src="https://deps.rs/repo/github/webrtc-rs/webrtc/status.svg">
 </a>
 <a href="https://webrtc.rs/docs/index.html"> 
  <img src="https://img.shields.io/static/v1?label=docs&message=master&color=5479ab">
 </a>
 <a href="https://github.com/webrtc-rs/webrtc/blob/master/LICENSE">
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
 </a>
 <a href="https://seladb.github.io/StarTrack-js/#/preload?r=webrtc-rs,webrtc">
  <img src="./doc/stars.svg" alt="Github Stars">
 </a>
</p>
<p align="center">
 A pure Rust implementation of WebRTC API. Rewrite Pion WebRTC stack (<a href="http://Pion.ly">http://Pion.ly</a>) in Rust
</p>

# Roadmap

### Work in Progress Towards 1.0

- [x] SDP: 
  - sync up to [pion/sdp/v2.4.0](https://github.com/pion/sdp/tree/b29f0bbd42fc719eabdb027117217b0ddb27abf1)
- [x] RTP
  - sync up to [pion/rtp/v1.6.1](https://github.com/pion/rtp/tree/0d8026ebf7c048a65f30b053f3ce22e7d5e738ee)
- [x] RTCP
  - sync up to [pion/rtcp/v1.2.4](https://github.com/pion/rtcp/tree/d136b4927f135b17cb15c9b287e22a9e053bd498)
- [x] SRTP
  - sync up to [pion/srtp/v1.5.2](https://github.com/pion/srtp/tree/071a6b95ab38e9eab9324dacd608dde1ec0c7cd3)
- [x] DTLS
  - sync up to [pion/dtls/v2.0.0](https://github.com/pion/dtls/tree/789798433596e4dd92451b66984dddb2f8a9f165)
- [ ] STUN
  - work in progress
  - catch up [pion/stun/v0.3.5](https://github.com/pion/stun/tree/7b20b792b7e18b3846032aaa80e8c0e2d412d0f8)
- [ ] TURN
- [ ] ICE
- [ ] PeerConnection

### Road Map Towards 2.0
- [ ] SCTP
- [ ] DataChannel

### Road Map Towards 3.0

- [ ] SIP
- [ ] QUIC
- [ ] ...


# 
### Contributors or pull requests are welcome!
