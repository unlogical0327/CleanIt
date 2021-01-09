# *CleanIt*
#### _Open-source Autonomy Software in Rust-lang with gRPC for the Roomba series robot vacuum cleaners_

## Motivation

Motivation is to build a complete DIY autonomy software from scratch (motion planning, guidance and motion control, SLAM, mission control, 2D/3D visualization etc..) with a real-time client-server communication stream using async gRPC for intercommunication and distributed compute.

## Pre-requisites

#### *Software*

##### _Linux_
```bash
$ [sudo] apt-get install libudev-dev pkg-config
```
##### _MacOs_
```bash
$ brew install *TODO*
```

#### *Hardware*
 - iRobot Create 2 (or iRobot Roomba 6xx series with serial USB cable - https://store.irobot.com/en_US/parts-and-accessories/create-accessories/communication-cable-for-create-2/4466502.html )
 - Raspberry Pi 4 (4GB)
 - Intel RealSense D435 or D435i depth camera