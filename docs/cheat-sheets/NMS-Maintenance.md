## NMS Record/Edit Workstation

![](http://www3.lenovo.com/medias/lenovo-workstation-thinkstation-c30-main.png?context=bWFzdGVyfHJvb3R8MTAwMDk3fGltYWdlL3BuZ3xoMWIvaDliLzk0MzQzNzU5MTM1MDIucG5nfGVlYTY0MWVjYjBkZWE4M2EyNTE0OGIzNjdmMWFiMmU0NzA2ZDViZmJjNGQ3NmE4ZmU5OTBlZTJmNmY4ZGFhMzM)

_Based on the Lenovo ThinkStation C30 Chassis_

**Hostname:** ``NMS-TV-RecEdit``

**Authentication:** Local

**Operating System:** Windows 7 Pro

**CPU:** Dual Intel Xeon Quad-Cores

**RAM:** 8GB DDR3 (2x 4GB)

**Storage:**

- ``C:\`` 500GB SATA SSD

- ``E:\`` 2TB RAID1 controlled via Intel Rapid Storage Technology

**Graphics:** [NVIDIA Quadro 600](https://www.nvidia.com/content/PDF/data-sheet/nv-ds-quadro-k600-us.pdf)

**Key Software:**

- Open Broadcaster
- Any Video Converter
- VLC Media Player
- K-Lite Codec Pack
- Notepad++

This PC's primary purpose is recording/streaming the finished output of the broadcast studio via Open Broadcaster (OBS). It can also be used as an editing workstation, and it's worth noting that the Quadro 600 GPU is CUDA 2.1 capable, so it will work with modern editors like DaVinci Resolve.

The storage configuration is redundant, and will tolerate 1 mechanical hard drive failure before losing any data. This storage array is managed through the Intel Rapid Storage Technology application, found in the system tray.

**FAQs:**

- What do I do if I get an error or warning from Intel Rapid Storage Technology Application?
  - Report it immediately, as this could mean that a hard drive in your machine is failing.

---

## NMS Video Playout/Sequencing Workstation

![](http://www3.lenovo.com/medias/lenovo-workstation-thinkstation-c30-main.png?context=bWFzdGVyfHJvb3R8MTAwMDk3fGltYWdlL3BuZ3xoMWIvaDliLzk0MzQzNzU5MTM1MDIucG5nfGVlYTY0MWVjYjBkZWE4M2EyNTE0OGIzNjdmMWFiMmU0NzA2ZDViZmJjNGQ3NmE4ZmU5OTBlZTJmNmY4ZGFhMzM)

_Based on the Lenovo ThinkStation C30 Chassis_

**Hostname:** ``NMS-TV-CasparCG``

**Authentication:** Local

**Operating System:** Windows 7 Pro

**CPU:** Dual Intel Xeon Quad-Cores

**RAM:** 8GB DDR3 (2x 4GB)

**Storage:**

- ``C:\`` 500GB SATA SSD

**Graphics:**

- [NVIDIA Quadro 600](https://www.nvidia.com/content/PDF/data-sheet/nv-ds-quadro-k600-us.pdf)
- Additional GPU to be determined

**Key Software:**

- Blackmagic ATEM Control Software
- CasparCG Server
- CasparCG Client
- Any Video Converter
- VLC Media Player
- K-Lite Codec Pack
- Notepad++
- Adobe Brackets

This PC is used for controlling the studio equipment, such as the ATEM Video Mixer. It's also used for generating and playing back motion graphics, videos, music, and other media for use on the broadcast. It's running CasparCG for planning/sequencing the shows, and for dynamically generating graphics such as the weather forecast. (The reason it runs both CasparCG server and CasparCG client is because although CasparCG is meant to be capable of multi-PC installations, we are only using one PC here.)
