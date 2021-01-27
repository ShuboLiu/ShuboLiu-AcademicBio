---
title: NIUVS Open Source Scheme
subtitle: "NIUVS Open Source Scheme: 5G-UVS project is now available on Gitee.com!"

# Summary for listings and search engines
summary: "NIUVS Open Source Scheme: 5G-UVS project is now available on Gitee.com! One may fork or git it from gitee,com freely"

# Link this post with a project
projects: [5G-UVS Project]

# Date published
date: "2020-12-13T00:00:00Z"

# Date updated
lastmod: "2020-12-13T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ''
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin
- Hongsheng Zhang

tags:
- Aerial Robotics
- 5G-UVS Project
- NIUVS Team

categories:

---


 Welcome to NIUVS (Neted Intelligent Unmanned Vehicle System) Open Source Scheme. This is 5G Unmanned Aerial System Program!

 NIUVS Open Sources Scheme focus on the reserch and development of neted unmanned system, intending to offer an open sources platform to develop unmaned system technology. We hope to Let Unmanned Vehicle Benifits More.

 5G-UAS project tends to develop Neted Aerial Vehicle that can be remotely controled via 5G network. Based on which, one could develop all kind of intelligent industial applications.
 
 
 
## What will you need to make 5G-UAS

1. A drone that contain frame, motors, ESCs, rotors and other optional devices that you may need;

2. Pilot Board that runs PX4 flight controal systems;

3. An onboard computer with Linux4 or above (Nvidia TX2, Nvidia Jetson Nano, Raspberry Pi 3B/3B+/4 or other) Tip: The onboard computer must be arm64-based

## How to install

1. Setup your operation system on your onboard computer, Ubuntu 18.04 is recommended (For Raspberry Pi computer, Raspberry Pi OS will be recommended)

2. Setup the internet connection of your onboard computer

3. Open terminal and 


```
git clone https://gitee.com/liushubo99/niuvs.git
cd niuvs
chmod u+x
sudo ./uav_install.sh
```

4. Connect you PX4 Pilot board with a Windows host computer via USB

5. Download XXX file to the Windows host computer and unzip. Open ```Beacon.exe```, connect the pilot board by press the ```Connect``` button upright and flash ```./Parameter/YourPilotDevices.param``` into your PX4 pilot board

6. Connect your onboard computer with PX4 Pilot board via USB.

7. Open ```Beacon.exe``` on your Ground Control Station. Enable the Joysticker. Choose ```UDP``` item and press ```Connect``` button. Keep the listening port default ```14550```.

8. Control the aerial vehicle as you like, enjoy!

## Contributer

Shubo Liu, contact shubo.liu@se17.qmul.ac.uk

Jack Honson, contact JackHonsen@foxmail.com

## Acknowledge
Thank to the supporting of Robotic Innovation Lab, Training Centre for Engineering Practices, NPU.

