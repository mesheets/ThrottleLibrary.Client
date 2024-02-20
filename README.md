# ThrottleLibrary.Client
 A client library for working with model railroad protocols, such as DCC++EX, SRCP, LocoNet, and WiThrottle.


## References
### Protocols
* [WiThrottle](https://www.jmri.org/help/en/package/jmri/jmrit/withrottle/Protocol.shtml)
  + [WiThrottleProtocol C++ Library](https://github.com/flash62au/WiThrottleProtocol)  (more advanced fork)
    - [WiThrottleProtocol C++ Library](https://github.com/davidzuhn/WiThrottleProtocol)  (original repository)
    - [Heart of the protocol command processing](https://github.com/mesheets/WiThrottleProtocol-Cpp/blob/3964b93098710d8d9ede280e4f7e999f1425b233/src/WiThrottleProtocol.cpp#L343)  (local fork)
  + [PiThrottle](https://github.com/dpcryer/pithrottle/blob/master/pithrottle.py)
  + [LocoNetControlStation](https://github.com/positron96/LocoNetControlStation)
  + __[PyWiThrottle Python Library](https://github.com/modelrailwaysascode/pywithrottle)__
* [SRCP](http://srcpd.sourceforge.net/srcp/)
  + [Android SRCP Client](https://github.com/upost/Signalbox)
  + [Android SRCP Client](https://github.com/srsoftware-de/SRCPC)
  + [iThrottle for iOS](https://github.com/andbet39/iThrottle)
  + [model-rail-control](https://github.com/StephanRichter/model-rail-control)
  + [SRCP.NET](https://github.com/mesheets/SRCP.NET)
  + [Java SRCP Client](https://github.com/forkch/jsrcpc)
  + [microSRCP](https://github.com/mc-b/microSRCP)
  + [RailuinoSrcp (for Maerklin)](https://github.com/Eurostar64/RailuinoSrcp)
* SRCP REST
  + [srcp-rs](https://github.com/cbiever/srcp-rs/blob/master/docs/index.md)
  + [Gember](https://cbiever.github.io/gember/)
* [DCC++ EX](https://dcc-ex.com/reference/)
  + Documentation
    - [Command Summary](https://dcc-ex.com/reference/software/command-summary.html)
    - [Command Reference](https://dcc-ex.com/reference/software/command-reference.html)
    - [Technical Reference for Throttle Developers](https://dcc-ex.com/throttles/tech-reference.html)
  + Examples
    - [DCC++ EX Protocol Library](https://github.com/DCC-EX/DCCEXProtocol/blob/main/src/DCCEXProtocol.cpp#L532)
    - [DCC++ EX Protocol Parsing](https://github.com/DCC-EX/CommandStation-EX/blob/master/DCCEXParser.cpp)
    - [WiThrottle Protocol Parsing](https://github.com/DCC-EX/CommandStation-EX/blob/master/WiThrottle.cpp)
* LocoNet
  + Licensing and Documentation
    - [Digitrax LocoNet Architecture](https://www.digitrax.com/support/loconet/home/)
    - [Digitrax LocoNet Protocol Documentation](https://www.digitrax.com/static/apps/cms/media/documents/loconet/loconetpersonaledition.pdf)
    - [Licensing and Licensees](https://www.digitrax.com/support/loconet/loconet-licensees/)
  + Projects
    - [LocoNetSharp](https://www.parksq.co.uk/dotnet-core/loconet-sharp) (targets .NET Standard 2.0)
      - [NuGet Package](https://www.nuget.org/packages/ParkSquare.LocoNetSharp)
      - Based on [LocoNetToolbox](https://github.com/chrissharp/LoconetToolbox) (.NET Framework app) by ChrisSharp
    - [LocoNet Library](https://github.com/mrrwa/LocoNet/blob/master/LocoNet.cpp)
      - [Arduino Reference](https://www.arduino.cc/reference/en/libraries/loconet/)
    - [Loconet2 Library (Development Branch)](https://github.com/mrrwa/LocoNet2/tree/development)
    - [LNetSerialMaster (based in part on RocRail)](https://github.com/habazut/LNetSerialMaster)
    - [LNetDCCpp (DCC++ command station with added Loconet support)](https://github.com/ClubNCaldes/LNetDCCpp/blob/master/BaseStation-1.2.1/DCCpp_Uno/LNetCmdStation.cpp)
  + [DCCSpider (uses Loconet to communicate with throttles and boosters)](https://github.com/orvio/DCCSpider/blob/145169c551c3dc0e245eefe44c2b87bc678494df/LoconetMaster.cpp#L71)
  - [JMRI LocoNet](https://github.com/JMRI/JMRI/tree/master/java/src/jmri/jmrix/loconet)
    - [LocoNet Constants/OpCodes](https://github.com/JMRI/JMRI/blob/master/java/src/jmri/jmrix/loconet/LnConstants.java)
    - [LocoNet Message Interpreter](https://github.com/JMRI/JMRI/blob/master/java/src/jmri/jmrix/loconet/messageinterp/LocoNetMessageInterpret.java)
  + [RocRail LocoNet](https://github.com/schelli04/Rocrail/blob/master/rocdigs/impl/loconet/lnmaster.c#L94)
* XpressNet
  + [Documentation (German)](https://www.lenz-elektronik.de/src/pdf/Lenz_XpressNet_Doku.pdf)
  + [XpressnetLib (.NET binary)](http://xpressnetlib.brozek.org/)
* [Z21](https://www.z21.eu/media/Kwc_Basic_DownloadTag_Component/root-en-main_47-1652-959-downloadTag-download/default/d559b9cf/1646977702/z21-lan-protokoll-en.pdf) (from [Manuals Page](https://www.z21.eu/en/downloads/manuals))
  + __[z21-Drive Java API](https://github.com/grizeldi/z21-drive)__
  + [z21 Typescript Client Library](https://github.com/jormc/z21)

&nbsp;

### Open Source Software and Command Stations
* [JMRI](https://jmri.org/)
  - [JMRI Network Connections](https://www.jmri.org/help/en/html/doc/Technical/Networking.shtml)
* [DCC++ EX](https://dcc-ex.com/)
* [IoTT](https://github.com/tanner87661/IoTTStick)
  + Many designes largely built around the [M5Stack M5StickC](https://shop.m5stack.com/products/stick-c?variant=43982750843137)…
  + …which is itself basd on the [Espressif ESP32](https://m5stack.oss-cn-shenzhen.aliyuncs.com/resource/docs/datasheet/core/esp32-pico-d4_datasheet_en.pdf)
  + Grove connector on one end; for interfacing with Arduino or similar, jumper cables might be useful
    - [4-pin male](https://www.seeedstudio.com/Grove-4-pin-Male-Jumper-to-Grove-4-pin-Conversion-Cable-5-PCs-per-Pack.html)
    - [4-pin female](https://www.seeedstudio.com/Grove-4-pin-Female-Jumper-to-Grove-4-pin-Conversion-Cable-5-PCs-per-PAck.html)
* [LocoNet Control Station](https://github.com/positron96/LocoNetControlStation)
* [DCC Lite](https://github.com/bcsanches/DCCLite/): Includes [LocoNet to WiThrottle Bridge](https://groups.io/g/jmriusers/message/204985)
* [LocoDuino](https://www.locoduino.org/) ([Google Translate](https://www-locoduino-org.translate.goog/?_x_tr_sl=auto&_x_tr_tl=en&_x_tr_hl=en-US&_x_tr_pto=wapp))
* [Atanisoft ESP32 Command Station](https://github.com/atanisoft/ESP32CommandStation): Supports LCC
* [Railroad Automation (RRA)](https://www.perecli.com/rrauto/) ([GitHub Repository](https://github.com/Perecli/RRAuto))
  + Currnetly only supports LocoNet via serial (or serial over USB) connections (no LbServer support)
  + Does provide .NET libraries that can be used to create your own implementations and customizations

### Free (but Closed Source) Software
* [Rocrail](https://rocrail.net/)
  + Formerly Open Source, then went closed source
  + Repo [moritzmhmk/Rocrail](https://github.com/moritzmhmk/Rocrail) appears to be the most advanced fork before Rocrail went closed source
  + Some functionality now only available via an [annual subscription fee](https://wiki.rocrail.net/doku.php?id=donate-en)

### Commercial Multi-Protocol Command Stations
* [Digikeijs DR5000](https://www.digikeijs.com/en/dr5000-dcc-multi-bus-central.html)
  + [Product Information](https://www.ironplanethobbies.com/product/digikeijs-dr5000-15v-command-station-booster-throttle-32-channel-detection-mid-set/)
  + [Wiki: Capabilities and Limitations](https://www.ironplanethobbies.com/digikeijs-dr5000-wiki/)
  + No plans to support LCC
* [Z21](https://www.z21.eu/en)
* [TCS DCC](https://tcsdcc.com/commandstation)
  + Reported that Digitrax [denied them a LocoNet license](https://groups.io/g/jmriusers/message/204987)

### Throttles (mostly closed source)
#### Windows
* [Train Throttle](https://apps.microsoft.com/detail/9NBLGGH4VF5J) - includes support for Windows 10 Mobile

#### Android
* [Engine Driver](https://enginedriver.mstevetodd.com/)
  + [Source Code](https://github.com/JMRI/EngineDriver)
* [DCC Throttle](https://www.alfray.com/trains/cab_app.html)

#### iOS
* [SRCP Client by IO-Expert](https://www.io-expert.com/srcpclientios/) (also supports z21 and DCC++ EX protocols)
* [Train Driver by IO-Expert](https://io-expert.com/traindriver/) (also supports z21 and DCC++ EX protocols)

&nbsp;

## Alternative Decoders and Electronics
### Arduino-Based DCC Decoders
* [Arduino DCC Decoder](https://electronics-diy.com/arduino-dcc-decoder.php): Use an Arduino Mini as a DCC decoder

### WiFi Decoders
* [WifiTrax](http://www.wifitrax.com/): Control a locomotive directly over WiFi via WiThrottle

### Bluetooth Decoders
* [BlueRail Trains](https://bluerailtrains.com/): Control a locomotive directly over Bluetooth via a custom app (currently iOS only)

### RF Decoders
* [Ring Engineering RailPro](https://www.ringengineering.com/RailPro.htm): Control a locomotive using special RF throttles and decoders

### Electronics
* [Azatrax](https://www.azatrax.com/): Exhibit controllers and sensors
* [Iowa Scaled Engineering](https://www.iascaled.com/): ProtoThrottle, sensors, and exhibit controller
  + Reported that Digitrax [denied them a LocoNet license](https://groups.io/g/jmriusers/message/204987)
* [Model Train Technology](https://modeltraintechnology.com/): Lighting and sensors
  + [Passenger Car Lighting](https://modeltraintechnology.com/wp-content/uploads/HO-scale-LED-Board-wt-Decoder-7-12-192mm-2000-4.jpg)

&nbsp;

## Development References and Resources
### Arduino
* [evive](https://hackaday.io/project/13091-evive-a-prototyping-platform-for-makers/): A prototyping platform for Arduino MEGA
* [VSCodium](https://vscodium.com/): A true open source release of Visual Studio Code
* [Visual Studio Code Extension for Android](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino): Facilitates use of VS Code / VSCodium for Arduino development
  + [Guide to Configuring for Debugging](https://devblogs.microsoft.com/iotdev/debug-your-arduino-code-with-visual-studio-code/)

### [Haxe](https://haxe.org/)
* [Try](https://try.haxe.org/)
* Setup
  + [Haxe C# Backend](https://lib.haxe.org/p/hxcs)
  + [Target .NET Core 2.1 for .NET Standard 2.0 Compatibility](https://devblogs.microsoft.com/dotnet/announcing-net-standard-2-1/)
* Components
  + [Task Library: hxbolts](https://lib.haxe.org/p/hxbolts/)

### .NET
* .NET Standard ([support](https://learn.microsoft.com/en-us/dotnet/standard/net-standard)  [tables](https://dotnet.microsoft.com/en-us/platform/dotnet-standard#versions))
  + v2.0 for best cross-compatibility between .NET (formerly .NET Core) and .NET Framework
  + v1.4 to support Windows 10 Mobile and earlier versions of Windows 10 (pre-10.0.16299 [1709 Fall Creators Update for Desktop; Mobile version of 1709 is 10.0.15254.603])
* [Avalonia UI](https://avaloniaui.net/): Cross-platform UI framework similar to WPF [(GitHub)](https://github.com/AvaloniaUI/Avalonia)
* [Uno Platform](https://platform.uno/): Make C# and XAML or WinUI apps cross-platform
