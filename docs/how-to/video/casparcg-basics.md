## What is a playout system?

Most of the equipment in our studio is real-time, meaning it works with live things. Microphones and cameras are live media sources. But sometimes we need to use things that _aren't_ live. When we play a logo animation, show an intro, or show a weather forecast, we are using a **playout system**. It's similar to a DVD player. It plays recordings so we can use them on our live video mixer.

## What is CasparCG?



CasparCG is a playout system (the fancy broadcast term is "character generator," hence the "CG" in the name). Although some playout systems require expensive special machines, CasparCG is just a software that runs on an ordinary computer. You control what CasparCG is playing on your computer screen, and it outputs video on a port connected to a camera input on your video mixer. It can seem complicated, but it's really just a fancy video player. You give it a video or an audio file to play, and it plays it.

![](https://s1.postimg.org/8cxtyi5q73/Simple_Playout_System.png)

_Here's an example of how CasparCG can be connected to a video mixer. This setup allows you to do things like overlay logos and text on top of the camera, play intros and short films, and play background music._

## How do you control CasparCG?

Caspar works using a **client-server model**. That means the **client** (the part you use to control it) and the **server** (the backend part that does all the heavy lifting) are actually two separate programs that talk to each other. This is so that in large news studios, you can have one client control several computers running a server, which makes CasparCG very scalable. We don't need that, so we'll be running the client and the server on the same computer. Why am I telling you this? So you're not confused when you see "CasparCG Server" and "CasparCG Client" in your programs list!

You will rarely interact directly with CasparCG Server; instead you'll use the client to tell the server what to do. The client lets you arrange your media in a **rundown**, which is a lot like a playlist. You drag and drop video/audio onto the rundown in the order you want, then you can click through each one during your broadcast.

![](https://s1.postimg.org/2bq24a24hr/OSC-2.png)

_Here's what CasparCG Client looks like. This is how you'll tell CasparCG Server what videos to play and when to play them._
