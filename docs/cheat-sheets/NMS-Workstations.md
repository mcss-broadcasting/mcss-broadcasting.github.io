## NMS Record/Edit Workstation

![](http://www3.lenovo.com/medias/lenovo-workstation-thinkstation-c30-main.png?context=bWFzdGVyfHJvb3R8MTAwMDk3fGltYWdlL3BuZ3xoMWIvaDliLzk0MzQzNzU5MTM1MDIucG5nfGVlYTY0MWVjYjBkZWE4M2EyNTE0OGIzNjdmMWFiMmU0NzA2ZDViZmJjNGQ3NmE4ZmU5OTBlZTJmNmY4ZGFhMzM)

_Based on the Lenovo ThinkStation C30 Chassis_

**Hostname:** ``NMS-TV-RecEdit``

**Authentication:** Local

**Operating System:** Windows 7 Pro

**CPU:** Dual Intel Xeon Quad-Cores

**RAM:** 8GB DDR3

**Storage:**

- ``C:\`` 500GB Crucial SSD

- ``E:\`` 2TB RAID1 controlled via Intel Rapid Storage Technology

**Graphics:** [NVIDIA Quadro 600](https://www.nvidia.com/content/PDF/data-sheet/nv-ds-quadro-k600-us.pdf)

This PC's primary purpose is recording/streaming the finished output of the broadcast studio via Open Broadcaster (OBS). It can also be used as an editing workstation, and it's worth noting that the Quadro 600 GPU is CUDA 2.1 capable, so it will work with modern editors like DaVinci Resolve.

The storage configuration is redundant, and will tolerate 1 mechanical hard drive failure before losing any data. This storage array is managed through the Intel Rapid Storage Technology application, found in the system tray.

#### FAQs:

- What do I do if I get an error or warning from Intel Rapid Storage Technology Application?
  - Report it immediately, as this could mean that a hard drive in your machine is failing.
