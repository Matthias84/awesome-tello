# awesome-tello

[Tello drone](https://www.wikidata.org/wiki/Q105554279) is a wifi controlled RTF drone, developed by  by RYZE Robotics Shenzen in cooperation and sold by DJI technology. This features different models: [Tello](https://www.ryzerobotics.com/en/tello), [Tello EDU](https://www.ryzerobotics.com/en/tello-edu), RoboMaster TelloTalent, and extended kits like [battery Booster](https://m.dji.com/de/product/tello?vid=45701) or 4x drone swarm.

This is a list of Free Software that can be used esp. with this drone. Get closed source [official downloads](https://www.ryzerobotics.com/de/tello/downloads) like docs, apps, ... .

## Cockpits

Alternatives to official Android Tello apps

* [Drone-keyboard](https://github.com/dnomak/drone-keyboard) - controll & videostream, `#nodejs`
* [Telloterm](https://github.com/SMerrony/telloterm) - controll & videostram & gamepad (fka. tello-desktop), `#Go`
* [Drone-control](https://github.com/socketbind/drone-control/) - `#Go`
* [Tellodesk…](https://github.com/SMerrony/tellodesk) - controll & videostream & gamepad & map, `#Go`
* [Tello](https://tellopilots.com/threads/new-app-for-linux.5692/) - Linux GTK App, `#C`
* [Kirogi](https://invent.kde.org/utilities/kirogi/)- KDE App, different types of drones

## Scripting

Alternatives to official Android Tello Edu app or [Droneblocks](https://www.droneblocks.io/) to design batch or interactive automation for the drone.

* [Scratch3-tello](https://github.com/kebhr/scratch3-tello)
* [Node-Red-Tello-Control](https://github.com/johnwalicki/Node-RED-Tello-Control)
* [Node-Red-DroneViewer](https://github.com/johnwalicki/Node-RED-DroneViewer)

## SDK Wrappers

Tello features official interfaces to develop applications for control & video streaming:

* [SDK 1.3](https://terra-1-g.djicdn.com/2d4dce68897a46b19fc717f3576b7c6a/Tello%20%E7%BC%96%E7%A8%8B%E7%9B%B8%E5%85%B3/For%20Tello/Tello%20SDK%20Documentation%20EN_1.3_1122.pdf),
* [SDK 2.0](https://dl-cdn.ryzerobotics.com/downloads/Tello/Tello%20SDK%202.0%20User%20Guide.pdf) - supports mission pads, wifi-client mode but only for Tello EDU

Undocumented details on the wifi protocoll are listed at [Tello Pilots Wiki - Protocol](https://tellopilots.com/wiki/protocol/).

There are libraries which implement featuresets in different languages and bindings to other frameworks.

* [Tello-Python](https://github.com/dji-sdk/Tello-Python) Official SDK, `#Python2`
* [TelloPy](https://github.com/hanyazou/TelloPy) - `#Python`
    * [Fork](https://github.com/shortstheory/TelloPy/tree/F310/tellopy) - Logitech F310 gamepad support
* https://github.com/SMerrony/tello
* [DJITelloPy](https://github.com/damiafuentes/DJITelloPy) - `#Python` swarm, mission pads, CV2
* [EasyTello](https://github.com/Virodroid/easyTello) - `#Python`, unmaintained
* [dji-ryze-tello](https://github.com/m6c7l/dji-ryze-tello) - `#Python`
* [tello_edu.py](https://github.com/tariq86/tello_edu.py) - `#Python` swarms
* [TelloPython](https://github.com/jaqxues/TelloPython) - `#Python` flip, reverse engenierd
* [Tello-nodejs](https://github.com/jsolderitsch/tello-nodejs)
* [TelloJS](https://github.com/kanekotic/tellojs)
* [Tello_ROS](https://github.com/clydemcqueen/tello_ros) `#ROS` (Robot Operrating system)
* [Flock2](https://github.com/clydemcqueen/flock2) `#ROS` (Robot Operrating system) for swarms
* [Tello](https://github.com/vss2sn/tello) - `#C++`
    * [Tello](https://github.com/LucaRitz/tello) - `#C++`
* [DJITello-Cpp](https://github.com/shalinirago/DJITello-Cpp) - `#C++`
* [TelloAPI-SDK-2.0](https://github.com/marklauter/TelloAPI-SDK-2.0) - `#C#`
* [TelloCommander](https://github.com/davewalker5/TelloCommander) - `#C#`
* [RyzeTelloSDK](https://github.com/Eloncase/RyzeTelloSDK) - `#C#`
* [DJI-tello](https://github.com/grofattila/dji-tello) - `#Java`
* [Tello4J](https://github.com/FriwiDev/Tello4J) - `#Java`
* [Tello](https://github.com/muety/tello) - `#Go` (Gobot framework)
* [TelloSwift](https://github.com/liuxuan30/TelloSwift) - `#Swift`
* [TelloSwift](https://github.com/tranchis/TelloSwift) - `#Swift`
* [KTello](https://github.com/ivanocj/ktello) - `#Kotlin`
* [TelloKt](https://github.com/JakeJMattson/TelloKt) - `#Kotlin`
* [DJI-Tello-Dart-Package](https://github.com/mateustoin/DJI-Tello-Dart-Package) - `#dart`
* [TelloTS](https://github.com/siokas/tellots) - `#typescript`
* [Tello-drone-matlab](https://ww2.mathworks.cn/hardware-support/tello-drone-matlab.html) - `#Matlab`
* [Tello Rust package](https://docs.rs/tello/0.3.0/tello/) `#Rust`


## Hardware

* [telloArduino](https://github.com/akshayvernekar/telloArduino) - Control via ESP32
* [m5-block-dji-tello-drone-control](https://www.hackster.io/gperrella/m5-block-dji-tello-drone-control-c2646f) ESP32 M5Stack control with `#micropython`
* [m5stickcUartUdpBridge](https://github.com/EiichiroIto/m5stickcUartUdpBridge) Control via micro:bit with radio-UART and `#micropython`
* [raspberrypi-controlled-tello](https://github.com/erviveksoni/raspberrypi-controlled-tello )Control via RPI
* [hack_GamesirT1d](https://github.com/Diallomm/hack_GamesirT1d) Read original drone gamepad controller
* [Tello Pilots Wiki - Protocol](https://tellopilots.com/wiki/protocol/) Reverse engineered (extended) control protocol with all features of the Android App
* [RyzeTelloFirmware](https://github.com/MrJabu/RyzeTelloFirmware) - hardware details and firmware binaries
* [Tello Pilots Forum - Tello PCB and antenna to help fellow crazy modders](https://tellopilots.com/threads/tello-pcb-and-antenna-reference-to-help-fellow-crazy-modders.2985/) - PCB
* [FCC 2AOOE-WM0041801](https://fccid.io/2AOOE-WM0041801/Internal-Photos/Internal-Photos-3731020) - PCB, components

## Forums

* [DJI Tello Forum](https://forum.dji.com/forum-127-1.html) - general support
* [tellopilots.com Forum](https://tellopilots.com) - Forum & wiki discussing mods, coding, reverse-engineering

## Examples

Applications which show integration and mashups using the Tello.

* [Tello ROS ORBSLAM](https://github.com/tau-adl/Tello_ROS_ORBSLAM) - Global positioning
* [Pose Recognition Tello](https://github.com/houdinisparks/pose_recognition_tello) - Control via human body poses
* [Tello-openpose](https://github.com/geaxgx/tello-openpose)
* [DJITelloOpticalControl](https://github.com/TamasSzepessy/DJITelloOpticalControl) - Autonomous flight via markers
* [Autonomous Navigation via Deep Reinforcement Learning for Resource Constraint Edge Nodes using Transfer Learning](https://arxiv.org/pdf/1910.05547.pdf) - Autonomous flight trained by virtual 3D levels
* [Alexa controlled drone](https://github.com/erviveksoni/alexa-controlled-drone) - Control via Alexa using a RPI gateway
* [Yello](https://github.com/adriacabeza/Yello) - CV and ML using offboard Yolo v3
* [Eye in the sky](https://github.com/sushansapaliga/Eye-In-The-Sky) - Face detection and follow-me
* [Tello AI features](https://github.com/carlo98/tello-ai-features) - Face and obstacles detection
* [CV 3D Tracking of a person in lock mode no yaw](https://tellopilots.com/threads/computer-vision-3d-tracking-of-a-person-in-lock-mode-no-yaw.4330/) Person 3D tracking and follow-me
* [CoviDrone](https://github.com/altaga/CoviDrone) - Cleaning Bot with UV lamps
* [Tello Laser Shot](https://github.com/Keleas/Tello_Laser_Shot) - Find targets and point them with a laser
* [CNN based dense monocular visual SLAM forindoor mapping and autonomous exploration](http://essay.utwente.nl/81420/1/__ad.utwente.nl_Org_BA_Bibliotheek_Documentfiles_Afstudeerverslagen_Nieuw_Master%20Thesis%20Anne%20Steenbeek.pdf) - Indoor mapping
* [Object Detection using Ryze Tello Drone with Help of Mask-RCNN](https://www.researchgate.net/publication/340887697_Object_Detection_using_Ryze_Tello_Drone_with_Help_of_Mask-RCNN) - Object detection
* [Tello-drone](https://github.com/yushulx/tello-drone) - Barcode scanner

## Security

* [Drone hacking tool analysis - dronesploit](https://dronesec.com/blogs/articles/drone-hacking-tool-analysis-dronesploit) - Hijacking using [dronesploit-framework](https://github.com/dhondta/dronesploit)

