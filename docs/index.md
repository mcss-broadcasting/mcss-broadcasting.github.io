# Parts of the Studio

Before we go into specific details, we need to go over how the studio is put together, and how it actually works. We'll split the studio into a few parts:

- Video Production
- Audio Production
- Recording/Streaming

The general idea is that video and audio are produced separately, with audio being handled by the sound mixer and video being handled by the video mixer/playout system. These two systems are almost totally separate until they finally come together at the recording/streaming system. Almost all broadcast studios are built around this concept.

```
+---------------+                             
|               |                             
|  Video Mixer  |                             
|               |                             
+---------------+                             
        |                                     
        |        +---------------------------+
        +--------|                           |
                 |Recording/Streaming System |
        +--------|                           |
        |        +---------------------------+
        |                                     
+---------------+                             
|               |                             
|  Audio Mixer  |                             
|               |                             
+---------------+                             
```
