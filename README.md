# ThrottleLibrary.Client
 A client library for working with model railroad protocols, such as SRCP and WiThrottle.


### Development References
Protocols
* [WiThrottle](https://www.jmri.org/help/en/package/jmri/jmrit/withrottle/Protocol.shtml)
  - [WiThrottleProtocol](https://github.com/flash62au/WiThrottleProtocol)  (more advanced fork)
  - [WiThrottleProtocol](https://github.com/davidzuhn/WiThrottleProtocol)  (original repository)
  - [PiThrottle](https://github.com/dpcryer/pithrottle/blob/master/pithrottle.py)
  - [LocoNetControlStation](https://github.com/positron96/LocoNetControlStation)
* [SRCP](http://srcpd.sourceforge.net/srcp/)
  - [Android SRCP Client](https://github.com/upost/Signalbox)
  - [Android SRCP Client](https://github.com/srsoftware-de/SRCPC)
  - [iThrottle for iOS](https://github.com/andbet39/iThrottle)
  - [model-rail-control](https://github.com/StephanRichter/model-rail-control)
  - [SRCP.NET](https://github.com/mesheets/SRCP.NET)
  - [Java SRCP Client](https://github.com/forkch/jsrcpc)
  - [microSRCP](https://github.com/mc-b/microSRCP)
  - [RailuinoSrcp (for Maerklin)](https://github.com/Eurostar64/RailuinoSrcp)
* SRCP REST
  - [srcp-rs](https://github.com/cbiever/srcp-rs/blob/master/docs/index.md)
  - [Gember](https://cbiever.github.io/gember/)
* [DCC++ EX](https://dcc-ex.com/reference/)
  - Documentation
    + [Command Summary](https://dcc-ex.com/reference/software/command-summary.html)
    + [Command Reference](https://dcc-ex.com/reference/software/command-reference.html)
    + [Technical Reference for Throttle Developers](https://dcc-ex.com/throttles/tech-reference.html)
  - Examples
    + [DCC++ EX Protocol Parsing](https://github.com/DCC-EX/CommandStation-EX/blob/master/DCCEXParser.cpp)
    + [WiThrottle Protocol Parsing](https://github.com/DCC-EX/CommandStation-EX/blob/master/WiThrottle.cpp)
* LocoNet
  - [Digitrax LocoNet Protocol Documentation](https://www.digitrax.com/static/apps/cms/media/documents/loconet/loconetpersonaledition.pdf)
  - [LocoNet Library](https://github.com/mrrwa/LocoNet/blob/master/LocoNet.cpp)
  - [Loconet2 Library (Development Branch)](https://github.com/mrrwa/LocoNet2/tree/development)
  - [LNetSerialMaster (based in part on RocRail)](https://github.com/habazut/LNetSerialMaster)
  - [LNetDCCpp (DCC++ command station with added Loconet support)](https://github.com/ClubNCaldes/LNetDCCpp/blob/master/BaseStation-1.2.1/DCCpp_Uno/LNetCmdStation.cpp)
  - [DCCSpider (uses Loconet to communicate with throttles and boosters)](https://github.com/orvio/DCCSpider/blob/145169c551c3dc0e245eefe44c2b87bc678494df/LoconetMaster.cpp#L71)
  - [JMRI LocoNet](https://github.com/JMRI/JMRI/tree/master/java/src/jmri/jmrix/loconet)
    + [Loconet Message Interpreter](https://github.com/JMRI/JMRI/blob/master/java/src/jmri/jmrix/loconet/messageinterp/LocoNetMessageInterpret.java)
  - [RocRail LocoNet](https://github.com/schelli04/Rocrail/blob/master/rocdigs/impl/loconet/lnmaster.c#L94)
* XpressNet
  - [Documentation (German)](https://www.lenz-elektronik.de/src/pdf/Lenz_XpressNet_Doku.pdf)
  - [XpressnetLib (.NET binary)](http://xpressnetlib.brozek.org/)
* [Z21](https://www.z21.eu/media/Kwc_Basic_DownloadTag_Component/root-en-main_47-1652-959-downloadTag-download/default/d559b9cf/1646977702/z21-lan-protokoll-en.pdf) (from [Manuals Page](https://www.z21.eu/en/downloads/manuals))
* Command Stations
  - [DCC++ EX](https://dcc-ex.com/)
  - [IoTT](https://github.com/tanner87661/IoTTStick)
  - [LocoNet Control Station](https://github.com/positron96/LocoNetControlStation)


Langauge: [Haxe](https://haxe.org/)
* [Try](https://try.haxe.org/)
* Setup
  - [Haxe C# Backend](https://lib.haxe.org/p/hxcs)
  - [Target .NET Core 2.1 for .NET Standard 2.0 Compatibility](https://devblogs.microsoft.com/dotnet/announcing-net-standard-2-1/)
* Components
  - [Task Library: hxbolts](https://lib.haxe.org/p/hxbolts/)
