# SIP Resources

A listing with some useful VoIP, Video Conference, and Instant Messaging resources.

## Index

* [VoIP VC IM Protocols](#voip-im-vc-protocols)
* [Compression Codecs](#compression-codecs)
  * [Speech Compression Codecs](#speech-compression-codecs)
  * [Video Compression Codecs](#video-compression-codecs)
* [Standard Specifications](#sip-standard-specifications)
  * [SIP Core](#sip-core)
  * [SDP](#sdp)
  * [H.323](#h.323)
  * [XMPP](#xmpp)
* [Online Tutorials](#online-voip-tutorials)
* [Books](#books)
* [Network Tools](#network-tools)
* [SIP Servers](#sip-servers)
* [RTP Relay](#sip-rtp-relay)
* [STUN and TURN Servers](#stun-and-turn-servers)
* [H.323 Servers](#h.323-servers)
* [Media Servers](#media-servers)
* [Multi Conference Units](#multi-conference-units)
* [Selective Forwarding Units](#selective-forwarding-units)
* [IP PBX Software](#ip-pbx-software)
* [IP PBX GUI Web Interfaces](#ip-pbx-gui-web-interfaces)
* [RTP Relay](rtp-relay)
* [Softphones](#softphones)
* [Command Line Tools](#command-line-tools)
* [Command Line Phones](#command-line-phones)
* [Hardphone Brands](#hardphone-brands)
* [Video Conference Terminals](#video-conference-terminal-brands)
* [IP PBX Hardware Brands](#ip-ipx-hardware-brands)
* [VoIP Libraries](voip-libraries)
* [VoIP Forums and Sites](#voip-forums-and-sites)
* [RTC Events](#rtc-events)

## VoIP VC IM Protocols

* Dundi 
  * Voip routing protocol
  * UDP port 4520
* H.323
  * Voip signalling protocol
* IAX2
  * UDP port 4569
* Jingle
* MeGaCo
  * Voip signalling protocol
* MGCP
  * Voip signalling protocol
* MSRP
* RTP
* RTCP
* SCCP
* SDP
* SIP
  * Voip signalling protocol
  * UDP port 5060
  * TCP port 5060 (optional)
  * TCP port 5061 (optional secure TLS)
* SIP/SIMPLE
* SRTP
* STUN
* TURN
* XCAP
* XMPP/Jabber
  * TCP port 5222 (client connection)
  * SRV resource record example: _xmpp-client._tcp.example.net. 86400 IN SRV 5 0 5222 xmpp.example.net.
  * TCP port 5223 (optional secure TLS connection)
  * TCP port 5269 (server connection)
  * SRV resource record example: _xmpp-server._tcp.example.net. 86400 IN SRV 5 0 5269 xmpp.example.net.
* ZRTP

## Compression Codecs

### Speech Compression Codecs

* ADPCM
* AMR
  * NB Narrow Band
  * WB Wide Band
* G.711 a-law (PCMA)
  * IDSN codec
  * Used in Europe
* G.711 u-law (PCMU)
  * IDSN codec
  * Used in North America
* G.719
* G.722
  * HD
* G.722.1 Siren7
* G.722.1C Siren14
* G.722.2
* G.723.1
* G.726
* G.726 AAL2
* G.729A
* GSM
* iLBC
* LPC-10
* Silk
* SpeeX
  * 4-48 kbps
* Signed Linear PCM
* Ogg Vorbis
* Opus
* WAV (SLIN)
* WAV (GSM)

### Video Compression Codecs

* H.263
* H.263p
* H.264
  * MPEG-4 AVC
* H.265
  * MPEG-H Part-2
* VP8
* VP9

## Standard Specifications

### SIP Core

* [RFC3261](http://tools.ietf.org/html/rfc3261) : SIP: Session Initiation Protocol
* [RFC3262](http://tools.ietf.org/html/rfc3262) : Reliability of Provisional Responses in the Session Initiation Protocol (SIP)
* [RFC3263](http://tools.ietf.org/html/rfc3263) : Session Initiation Protocol (SIP): Locating SIP Servers
* [RFC3265](http://tools.ietf.org/html/rfc3265) : Session Initiation Protocol (SIP)-Specific Event Notification

### SDP

* [RFC4566](http://tools.ietf.org/html/rfc4566) : SDP: Session Description Protocol (obsoleted)
* [RFC3264](http://tools.ietf.org/html/rfc3264) : An Offer/Answer Model with the Session Description Protocol (SDP)

### H.323

* [RFC3508](https://tools.ietf.org/html/rfc3508) : H.323 Uniform Resource Locator (URL) Scheme Registration
* [RFC4123](https://tools.ietf.org/html/rfc4123) : Session Initiation Protocol (SIP)-H.323 Interworking Requirements

### XMPP

* RFC6120

### Codecs

* [RFC6386](https://tools.ietf.org/html/rfc6386) : VP8 Data Format and Decoding Guide

## Online VoIP Tutorials

* [ColumbiaEdu - SIP Tutorial](http://www.cs.columbia.edu/~hgs/teaching/ais/slides/2003/sip_long.pdf)
* [CornellEdu - Understanding SIP](http://www.cs.cornell.edu/courses/cs619/2004fa/documents/siptutorial.pdf)
* [JDRosen.net - Tutorials](http://www.jdrosen.net/tutorials.html)
* [RFC3261 Simplified](http://www.siptopia.org/multimedia-tag/rfc-3261/)
* [SIP Introduction](http://www.kamailio.org/docs/tutorials/sip-introduction/)
* [SIPTutorial.net - SIP](http://www.siptutorial.net/SIP/index.html)
* [TutorialsPoint - SIP](http://www.tutorialspoint.com/session_initiation_protocol/index.htm)
* [VoIPMechanic - SIP Basics](http://www.voipmechanic.com/sip-basics.htm)
* [VoIP Protocols: Introducing SIP](http://toncar.cz/Tutorials/VoIP/VoIP_Protocols_Introducing_SIP.html)
* [Terena - SIP Tutorial](https://www.terena.org/activities/tf-vvc/voip-wsh/SIP-tutorial.pdf)
* [Oracle - SIP Tutorial](https://docs.oracle.com/cd/E19355-01/820-3007/gflsc/index.html)
* [Startrinity - SIP Articles](http://startrinity.com/VoIP/Resources/SipArticlesAndTutorials.aspx)
* [Wisdomjobs - SIP Tutorial](https://www.wisdomjobs.com/e-university/sip-tutorial-2185.html)
* [MIT - SIP Basics](https://web.mit.edu/sip/presentations/np119.pdf)
* [Leonid - SIP Tutorial](http://www.osslab.tw/@api/deki/files/4096/=sip.pdf)
* [Aarnet - SIP Tutorial](http://help.aarenet.com/wiki/Support_voip_protocol)
* [Independentsoft - SIP Tutorial](https://www.independentsoft.de/sip/tutorial/index.html)

## Books

* [SIP: Understanding the Session Initiation Protocol](http://www.amazon.com/SIP-Understanding-Initiation-Protocol-Telecommunications/dp/1607839954/httpwwwtuto0a-20)
* [SIP Beyond VoIP](http://www.amazon.com/SIP-Beyond-VoIP-Communications-Revolution/dp/0974813001)
* [Internet Communications Using SIP](http://www.amazon.com/Internet-Communications-Using-Henry-Sinnreich/dp/0471413992/httpwwwtuto0a-20)
* [SIP Demystified](http://www.amazon.com/SIP-Demystified-Gonzalo-Camarillo/dp/0071373403)

## Network Tools

* [ngrep](http://ngrep.sourceforge.net/)
* [sipcapture](http://www.sipcapture.org)
* [sipinspector](http://www.sipinspector.com/)
* [sipgrep](https://github.com/sipcapture/sipgrep)
* [siptestingtool](https://clcohio.org/sip-testing-tool/)
* [sngrep](https://github.com/irontec/sngrep)
* [tcpdump](http://www.tcpdump.org/)
* [Traceroute](https://packages.debian.org/stretch/traceroute)
* [tshark](https://www.wireshark.org/docs/man-pages/tshark.html)
* [wireshark](http://www.wireshark.org)

## SIP Servers

* {Brekeke Sip Server](https://www.brekeke.com/)
* [Kamailio](http://www.kamailio.org)
* [Linphone Flexsip Server](https://www.linphone.org/products)
* [OfficeSIP](https://officesip.com/index.html)
* [Opensips](https://www.opensips.org)
* [ReSIProcate](http://www.resiprocate.org)
* [sipXcom](http://sipxcom.org)
* [SipWise C5](https://www.sipwise.com/products/class-5-softswitch-carrier-grade-for-voice-over-ip/)
* [Kaplansoft TekSIKP](https://www.kaplansoft.com/teksip/)
* [Mobicents](http://www.mobicents.org/)
* [MyVoipipp MiniSIPServer](https://www.myvoipapp.com/download)
* [YXA](https://www.stacken.kth.se/project/yxa/index.html) (Legacy | Linux | SIP)

## SIP RTP Relay

* RTP Proxy
* RTP Engine
* Media Proxy

## STUN and TURN Servers

* [OfficeSIP](https://officesip.com/index.html)

## H.323 Servers

* [GnuGK Gatekeeper](http://www.gnugk.org)

## Media Servers

* [SIP Expess Media Server](https://github.com/sems-server/sems)
* [Linphone Meadistreamer2](https://www.linphone.org/products)

## Multi Conference Units

* Doubango Telepresence (Linux | SIP)
* Freeswitch MCU (Linux | SIP)
* i2conf (Legacy | Windows | SIP)
* Medooze MCU (Linux | SIP)
* Marakew MCU Server (Linux | SIP)
* OfficeSIP (Winodws, Linux | SIP)
* Openmcu-ru (Windows, Linux | SIP, H.323)

## Selective Forwarding Units

* Asterisk FSU (Linux | SIP, H.323)
* Janus
* Jitsi Video Bridge (Linux | XMPP)

## IP IPX Software

* [3CX](https://www.3cx.com/)
* [Askozia](https://askozia.com/) (Windows, Linux | SIP, H.323, MGCP, IAX2, SCCP, XMPP) 
* [Asterisk](http://www.asterisk.org)
* [Communigate](https://www.communigate.com/)
* [FreeSwitch](http://www.freeswitch.org)
* FusionPBX
* Bicom Systems
* Elastix
* Enswitch
* Mizutech](https://www.mizu-voip.com/Software/VoIPServer/WindowsPBX.aspx)
* Kazoo
* OfficeSIP (Windows, Linux | SIP)
* PCBest Networks SIP PBX
* Pascom MobyDick
* Thirdlane
* [Yate](https://www.yate.ro) (Windows, Linux | SIP, H.323, MGCP, IAX2, XMPP) 
* Yeastar

## IP PBX GUI Web Interfaces

* FreePBX
* Asterisk GUI

## Softphones

* 3CX Phone (Windows | SIP)
* Blink (Windows, MacOS, Linux | SIP, MSRP, XCAP)
* [Cornfed Sip User Agent](http://sipuseragent.com/)
* Counterpath Bria and Bria Teams (Winodws, Android | SIP, XMPP)
* SIP IP Communicator (Windows | SCCP)
* CSIPSimple (Android | SIP)
* Draytek Soft Phone
* Ekiga (Windows, Linux | SIP, H.323)
* [GNOME Empathy](https://wiki.gnome.org/Apps/Empathy) (Linux | SIP)
* Grandstream Wave (iOS, ANdroid | SIP)
* Jitsi (Windows, Linux | SIP, XMPP)
* [Kaplansoft TekPhone](https://www.kaplansoft.com/tekphone/) (Windows | SIP)
* Linphone (Windows, Linux | SIP)
* Microsip (Windows | SIP)
* Mizutech (Windows | SIP)
* OfficeSIP (Windows | SIP)
* Polycom RealPresence Desktop (Windows | SIP, H.323)
* Polycom Telepresence m100 (Legacy | Windows | SIP, H.323)
* Polycom PVX (Legacy | Windows | SIP, H.323)
* [SipDroid](http://sipdroid.org/) (Android | SIP)
* SNOM 360 (Windows | SIP)
* [Telephone](https://www.64characters.com/telephone/) (MacOS | SIP)
* [tSipClent](http://tomeko.net/software/SIPclient/)
* [Twinkle](http://twinkle.dolezel.info/) (Linux | SIP)
* [Twinkle]((https://mfnboer.home.xs4all.nl/twinkle/) (legacy | Windows | SIP)
* wxCommunicator (Winodws | SIP)
* Yate Client (Windows | SIP, H.323, IAX2, XMPP)
* Yealink Desktop VC (Windows | SIP, H.323)
* Zoiper3 (Legacy | Windows | SIP, IAX2, XMPP)
* Zoiper5 (Windows, Android | SIP, IAX2, XMPP)

## Command Line Tools

* sipp
* sipsak

## Command Line Phones

* [Cornfed SIP User Agent](http://sipuseragent.com/)
* [Linphonec] (Windows, Linux | SIP)
* [Pjsip pjsua] (Windows, Linux | SIP)
* [Kaplansoft SIPCLI](https://www.kaplansoft.com/SipCLI/) (Windows | SIP)
* [openRTSP](http://www.live555.com/openRTSP/) (Linux | RTSP)
* [sipcmd](http://sipcmd.sourceforge.net/) (Linux | SIP, H.323)
* [sipcmd2](https://github.com/guisousanunes/sipcmd2 ( (Linux | SIP, H.323)
* [sipsimpleclient](https://sipsimpleclient.org/testing/) (Linux | SIP)
* [Twinkle](http://twinkle.dolezel.info/) (Linux | SIP)
* [Twinkle]((https://mfnboer.home.xs4all.nl/twinkle/) (legacy | Windows | SIP)

## Hardphone Brands

* Avaya
* Cisco/Linksys
* Digium
* Elmeg
* Fanvil
* Gigaset/Siemens
* Grandstream
* HTEK
* Huawei
* Innovaphone
* Mitel/Aastra
* Obihai
* Panasonic
* Polycom
* Stentofon
* Snom
* Tiptel
* Ubiquiti
* Yealink

## Video Conference Terminal Brands

* Avercomm
* Cisco/Tandberg
* DCM
* Grandstream
* Huawei
* LifeSize
* Logitech
* Polycom
* Vaddio
* Yealink
* ZTE

## IP PBX Hardware Brands

* Atcomm
* Avaya (SIP, H.323)
* Cisco (SIP, H.323)
* Digium (SIP, H.323)
* Gigaset/Siemens (SIP)
* Grandstream (SIP, H.323)
* Yeastar

## VoIP Libraries

* Abto (SIP)
* PJSIP (SIP)
* BareSIP (SIP)
* eXoSIP (SIP)
* JAIN-SIP (SIP)
* JsSIP (SIP)
* Linphone Liblinphone SDK (SIP)
* MjSIP (SIP)
* oSIP (SIP)
* Ozeki (SIP)
* PjSIP (SIP)
* ReSIProcate (SIP)
* SIPML5 (SIP)
* SofiaSIP (SIP)

## VoIP Forums and Sites

* [Voip Info](http://www.voip-info.org)
* [Tek Tips](http://www.tek-tips.com)
* [DSL Reports](http://)
* [Packetizer](http://www.packetizer)
* [H323 Net](http://www.h323.net)

## RTC Events

* [Astricon](http://www.astricon.com)
* [Cluecon](http://www.cluecon.com)
* [Fosdem](http://fosdem.org)
* [Kamailio World](http://www.kamailioworld.com)
* [TADHack](http://www.tadhack.com)
* [VoIP2Day](http://www.voip2day.com)
