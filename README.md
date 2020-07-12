# Voicegain Platform

Voicegain privides a Speech-to-Text Platform built around a Deep Neural Network ASR engine.
It supports two models - 1) large vocabulary speech transcription (invokable real-time and off-line) and 2) speech recognition using context free grammars.
Both are accessible via Web API. Realtime Audio can be streamed over WebRTC, gRPC and web-sockets. In addition, the recognizer can be accessed using MRCP.
Platform is accessible in the Cloud and can also be deployed at the [Edge](https://www.voicegain.ai/post/benefits-of-edge-deployment) (on-prem Edge Computing).

This repository tracks public components of the Voicegain Platform. Things like:
* [announcements](https://github.com/voicegain/platform/blob/master/ANNOUNCE.md),
* [release notes](https://github.com/voicegain/platform/blob/master/RELEASE.md),
* [terms of service](https://github.com/voicegain/platform/blob/master/TERMS-OF-SERVICE.md),
* [privacy policy](https://github.com/voicegain/platform/blob/master/PRIVACY.md), etc.

The Voicegain platform consists of:
* Voicegain Web API - key API methods are documented at https://voicegain.ai/api
* Voicegain Enterprise Portal at https://portal.voicegain.ai which provides access to:
  * Voicegain Transcription (incl. real time)
  * Voicegain IVR (incl GREG tool)
  * Voicegain Call Analytics (coming soon)
* Voicegain CC-App at https://cc.voicegain.ai (real-time transcription viewer)
* Voicegain Transcribe App at https://transcribe.voicegain.ai (also known as [Speech.Works](https://speech.works) app)
* Voicegain Provisioning portal at https://admin.voicegain.ai
* Tools and Utilities:
  * Voicegain Audio Sender Daemon  
  * IVR MRCP Proxy

You can learn more about Voicegain at https://voicegain.ai. BTW, we are offering [Free Trial](https://www.voicegain.ai/trial).

You can learn more about Speech.Works at https://speech.works

How-To Guides
* [Deploy Voicegain into AWS](./how-to/deploy-voicegain-into-aws.md)

---

[Voicegain Github Home](https://voicegain.github.io/)
