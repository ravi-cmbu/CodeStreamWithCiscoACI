# CodeStreamWithCiscoACI
This repository contains information around setting up Cisco ACI simulator and using Code Stream to create pipeline tasks for various automation requirements



Pre-req: Knowledge on REST(level 101), Code Stream(Level 101) and Cisco ACI(Level 101) and ofcourse vSphere knowledge  




Steps to setup ACI Simulator for REST pipeline tasks

1. Download ACI simulator from Cisco site. Link below, you need to have Cisco login for this activity to complete.
   https://software.cisco.com/download/home/286283149/type/286283168/release/5.2(1g)

2. Please follow the below youtube link for instruction around downloading and setting up ACI simulator
   https://www.youtube.com/watch?v=_tmxdSkgZ3U
   In the above video, VMware workstation is used to import the ova, you might want to use vSphere environment to connect to Code Stream and create ACI pipelines.

3. In Code Stream, configure variables for the IP address/login URL for the ACI simulator, its the Out of Band Network IP Address.

4. Import the yaml for Code Stream, change the IP address and other details accordingly. Start with End to End Pipeline

5. Please ensure your Code Stream, environment variables are as per your requirement.
