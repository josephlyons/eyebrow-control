# Eyebrow Controlled Objects - Joe Lyons

_How Might We:_

**Control the world with our eyebrows?**



Exploring the potential of facially controlled objects.



## Futures Wheel - Music Streaming

This futures wheel is based on the trend of music consumption transitioning to streaming services such as spotify and apple music.
​

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/Futures%20Wheel%20-%20Streaming%20-%20Further%20Futures.jpg?raw=true)
_Figure 1 - Futures Wheel based on the trend of music streaming_


The Future wheel predicts a series of outcomes related to music and its surrounding industry.

## Personal/Novel/Contextual

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/Novel%20Personal%20Contextual.jpg?raw=true)

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/PNC%20-%201PERSONAL.JPG?raw=true)

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/PNC%20-%202NOVEL.JPG?raw=true)

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/PNC%20-%203CONTEXTUAL.JPG?raw=true)

## Experience/Insights

I presented a series of experimental music instruments I developed at a Hackoustic Presents night at Iklektic Artlab in London. I had the opportunity to introduce myself, and my work infront at an interactive gig of musicans, audio nerds & instrument hackers \(similar to myself\) and then give them a chance to interact with and use the instruments.


![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/me-at-hackoustic.jpg?raw=true)

_Me speaking at the Hackoustic Presents night 22/02/20._

​

This meant that 30-40 people, over the course of a few hours, interacted with and used the instruments I developed. This gave me an amazing insight into the way in which people interact with my work and interactive objects in general.

​

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/IMG_4407.jpg?raw=true)

_The three presented instruents; Proximity Box, Fan Controlled Chimes & Rotary Metronome._

​

I soon realised that battery power is _never_ the way for exhibitions - having to replace & change batteries throughout the event. But I also more deeply understood what it meant for people to interact with these instruments having never seen them, or had them be explained before.

​

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/IMG_4405.jpg?raw=true)

_Different angle on the table._

The interactions I had created allowed you to interact with the creation of _sound_ in a different way. However, the interaction between the user and trigger, here a slider or the lid of a box, was still in everyday language.


This lead me to look for new & more interesting interactions.


## Expert Interview

Plan to interview:

Kyle McDonald - guy who created FaceOSC using OpenFrameworks ofxFaceTracker.

## hmw / poster

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/dual%20poster.jpg?raw=true)


## Software Guide

Quick terminology guide for softwares used in this project.


**Ableton Live**

Ableton Live is a digital audio workstation for macOS and Windows.


**Max/MSP**

Max is a visual programming language for the specialized needs of artists, educators, and researchers working with audio, visual media, and physical computing.

**Max for Live**

Max for Live is a platform to build your own instruments and effects, tools for live performance and visuals, and more. It is an implementation of the Max/MSP software within Ableton Live


**Puredata**

Pure Data \(or just Pd \) is an open source visual programming language for multimedia. It is very similar to Max/MSP and shares a lot of the same language and structure.


**openFrameworks**

openFrameworks is an open source toolkit for creative coding.

​

**ofxFaceTracker**

ofxFaceTracker is openFrameworks addon for face tracking, based on Jason Saragih's FaceTracker library.



**FaceOSC**

FaceOSC sends as much data as possible from ofxFaceTracker via OSC, including its pose/position and gestural data, and its raw points.

​

**OSC**

Open Sound Control \(OSC\) is a protocol for communication among computers, sound synthesizers, and other multimedia devices that is optimized for modern networking technology.

​

**Arduino**

Open-source electronic prototyping platform enabling users to create interactive electronic objects.


## Hack

For my hack I combined a handful of different softwares to create a Ableton Live Plugin that allows you too control the tempo of a Live projcect using only your eyebrows.

I used the Max for Live Editor within Ableton Live to unpack OSC data sent from FaceOSC, trigger a tap when a threshold was reached, and combined this with a 'tap tempo' patch and a master tempo control patch allowing me to 'tap' in the beat using my eyebrows and change the tempo in real time.


Wikifactory Link:
https://wikifactory.com/@josephlyons/eyebrow-controlled-tempo


![image](https://wikifactory.com/files/RmlsZTozMTQ3OTE=)

*Screenshot of the Max for Live patch in edit mode.*

**Potential Futures:**
Studio production streamlining, Live music performance, Production accessibility.

## Further Hacks

From here I developed 3 eyebrow controlled \(EBC\) objects:

**EBC RC Skateboard**
![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/skateboard.jpg?raw=true)
_EBC Skateboard_

This was a hack using Arduino which allowed me to control a Tony Hawk Circuit Board RC Skateboard using an Arduino & a handful of software. Allows the user to control the skateboard using only their eyebrows & a webcam.

Wikifactory Link: https://wikifactory.com/@josephlyons/eyebrow-rc-skateboard

​
**EBC Pinball**
![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/pinball%20top.jpg?raw=true)
_EBC Pinball_


![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/pinball%202%20combined.jpg?raw=true)
_Back of pinball machine_

​
**EBC Guillotine**
![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/silcer%20iso.jpg?raw=true)
_EBC Guillotine/Fruit Slicer._


## Making Film


@[youtube](https://youtube.com/embed/PaQ6n6Pq4DY)

\(featuring music by me!\)

## Return to Expert

Plan to possibly interview:

Oddballs Team - https://www.kickstarter.com/projects/1535627339/oddball-the-drum-machine-crammed-in-a-ball

Kyle McDonald - guy who created FaceOSC using OpenFrameworks ofxFaceTracker.

## WIP Show

Here are some photos that show how the WIP was to be set up before it was cancelled.


![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/WIP%20joint%20image.jpg?raw=true)
_Figure X & Y - Front and Back view of 3 hacks set up in the FabLab exhibition space ready for the WIP show._


Here, in figure X you can see how the hacks would have been arranged. From left to right:

Eyebrow Controlled Pinball,
Selection Slider,
Eyebrow Controlled RC Skateboard,
Eyebrow Controlled Fruit Slicer.

Figure Y shows how the webcam is mounted to the back of the work desk/exhibiton table.

![image](https://github.com/josephlyons/eyebrow-control/blob/master/images/birdseye%20table%20setup.jpg?raw=true)
Figure Z - birds eye view of the setup used for testing and ensuring all the hacks worked using laptop.
