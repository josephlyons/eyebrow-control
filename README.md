---


---

<h1 id="eyebrow-controlled-objects---joseph-lyons">Eyebrow Controlled Objects - Joseph Lyons</h1>
<h2 id="experienceinsights">Experience/Insights</h2>
<p>I presented a series of experimental music instruments I developed at a Hackoustic Presents night at Iklektic Artlab in London. I had the opportunity to introduce myself, and my work infront at an interactive gig of musicans, audio nerds &amp; instrument hackers (similar to myself) and then give them a chance to interact with and use a series of three experimental instruments I produced for my previous project Modify Sound.</p>
<p>​</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/me-at-hackoustic.jpg?raw=true" alt="image"></p>
<p><em>Me speaking at the Hackoustic Presents night 22/02/20.</em></p>
<p>​</p>
<p>This meant that 30-40 people, over the course of a few hours, interacted with and used the instruments I developed. This gave me an amazing insight into the way in which people interact with my work and interactive objects in general.</p>
<p>​</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/IMG_4407.jpg?raw=true" alt="image"></p>
<p><em>The three presented instruents; Proximity Box, Fan Controlled Chimes &amp; Rotary Metronome.</em></p>
<p>​</p>
<p>I soon realised that battery power is <em>never</em> the way for exhibitions - having to replace &amp; change batteries throughout the event. But I also more deeply understood what it meant for people to interact with these instruments having never seen them, or had them be explained before.</p>
<p>​</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/IMG_4405.jpg?raw=true" alt="image"></p>
<p><em>Different angle on the table.</em></p>
<p>​</p>
<p>The interactions I had created allowed you to interact with the creation of <em>sound</em> in a different way. However, the interaction between the user and trigger, here a slider or the lid of a box, was still in everyday language.</p>
<p><strong>This lead me to look for new &amp; more interesting interactions.</strong></p>
<p>I took off from another previous project where I used ultrasonic sensors patched through Max for Live via Arduinos, to create a sound art installation.</p>
<p>​</p>
<p>This gave me a good starting point combining hardware &amp; software for creative means.</p>
<h2 id="expert-interview">Expert Interview</h2>
<p>Plan to interview:</p>
<p>Kyle McDonald - guy who created FaceOSC using OpenFrameworks ofxFaceTracker.</p>
<h2 id="hmw--poster">hmw / poster</h2>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/dual%20poster.jpg?raw=true" alt="image"></p>
<h2 id="software-guide">Software Guide</h2>
<p>Quick terminology guide for softwares used in this project.</p>
<p>​</p>
<p><strong>Ableton Live</strong></p>
<p>Ableton Live is a digital audio workstation for macOS and Windows.</p>
<p>​</p>
<p><strong>Max/MSP</strong></p>
<p>Max is a visual programming language for the specialized needs of artists, educators, and researchers working with audio, visual media, and physical computing.</p>
<p>​</p>
<p><strong>Max for Live</strong></p>
<p>Max for Live is a platform to build your own instruments and effects, tools for live performance and visuals, and more. It is an implementation of the Max/MSP software within Ableton Live</p>
<p>​</p>
<p><strong>Puredata</strong></p>
<p>Pure Data (or just Pd ) is an open source visual programming language for multimedia. It is very similar to Max/MSP and shares a lot of the same language and structure.</p>
<p>​</p>
<p><strong>openFrameworks</strong></p>
<p>openFrameworks is an open source toolkit for creative coding.</p>
<p>​</p>
<p><strong>ofxFaceTracker</strong></p>
<p>ofxFaceTracker is openFrameworks addon for face tracking, based on Jason Saragih’s FaceTracker library.</p>
<p>​</p>
<p><strong>FaceOSC</strong></p>
<p>FaceOSC sends as much data as possible from ofxFaceTracker via OSC, including its pose/position and gestural data, and its raw points.</p>
<p>​</p>
<p><strong>OSC</strong></p>
<p>Open Sound Control (OSC) is a protocol for communication among computers, sound synthesizers, and other multimedia devices that is optimized for modern networking technology.</p>
<p>​</p>
<p><strong>Arduino</strong></p>
<p>Open-source electronic prototyping platform enabling users to create interactive electronic objects.</p>
<h2 id="hack">Hack</h2>
<p>For my hack I combined a handful of different softwares to create a Ableton Live Plugin that allows you too control the tempo of a Live projcect using only your eyebrows.</p>
<p>I used the Max for Live Editor within Ableton Live to unpack OSC data sent from FaceOSC, trigger a tap when a threshold was reached, and combined this with a ‘tap tempo’ patch and a master tempo control patch allowing me to ‘tap’ in the beat using my eyebrows and change the tempo in real time.</p>
<p>​</p>
<p>Wikifactory Link:</p>
<p><a href="https://wikifactory.com/@josephlyons/eyebrow-controlled-tempo">https://wikifactory.com/@josephlyons/eyebrow-controlled-tempo</a></p>
<p>​</p>
<p><img src="https://wikifactory.com/files/RmlsZTozMTQ3OTE=" alt="image"></p>
<p><em>Screenshot of the Max for Live patch in edit mode.</em></p>
<p>​</p>
<p><strong>Potential Futures:</strong></p>
<p>Studio production streamlining, Live music performance, Production accessibility.</p>
<h2 id="further-hacks">Further Hacks</h2>
<p>From here I wanted to prove that I could effect the physical world using the eyebrows as a trigger. The first trigger I used was a ‘raise’, raising the eyebrows above a set height triggers a ‘bang’ in the software, and returning the eyebrows below this height sends out a 'bang too.</p>
<p><strong>EBC Pinball</strong></p>
<p>To test the ‘<strong>raise</strong>’ function I built an EBC pinball machine.<br>
​<br>
Eyebrows <strong>Raised</strong> = Pinball Flippers Raised<br>
Eyebrows Neutral = Pinball Flippers Neutral</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/animations/pinball%20gif%201.gif?raw=true" alt=""><br>
<em>Animated Gif illustrating EBC Pinball functionality.</em></p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/pinball%20top.jpg?raw=true" alt="image"><br>
<em>EBC Pinball</em></p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/pinball%202%20combined.jpg?raw=true" alt="image"><br>
<em>Back of pinball machine</em></p>
<p><strong>EBC Guillotine</strong></p>
<p>The next function I wished to test was ‘<strong>frown</strong>’.</p>
<p>Eyebrows Neutral = Blade Up<br>
Eyebrows <strong>Frown</strong> = Cut</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/silcer%20iso.jpg?raw=true" alt="image"><br>
<em>EBC Guillotine/Fruit Slicer.</em></p>
<p><strong>EBC RC Skateboard</strong><br>
I then wished to test combining both funtions in a single obect. For this I hacked an RC Skateboard, combining both the '<strong>Raise’</strong> and '<strong>Frown’</strong> functions.</p>
<p>Eyebrows <strong>Raised</strong> = Forward<br>
Eyebrows Neutral = Still/Stop<br>
Eyebrows <strong>Frown</strong> = Backward</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/skateboard.jpg?raw=true" alt="image"><br>
<em>EBC Skateboard</em></p>
<p>This was a hack using Arduino which allowed me to control a Tony Hawk Circuit Board RC Skateboard using an Arduino &amp; a handful of software. This hack allows the user to control the skateboard using only their eyebrows &amp; a webcam.</p>
<p>​</p>
<p>Wikifactory Link: <a href="https://wikifactory.com/@josephlyons/eyebrow-rc-skateboard">https://wikifactory.com/@josephlyons/eyebrow-rc-skateboard</a></p>
<h2 id="making-film">Making Film</h2>
<p>@<a href="https://youtube.com/embed/PaQ6n6Pq4DY">youtube</a></p>
<p>(featuring music by me!)</p>
<h2 id="return-to-expert">Return to Expert</h2>
<p>Plan to possibly interview:</p>
<p>Oddballs Team - <a href="https://www.kickstarter.com/projects/1535627339/oddball-the-drum-machine-crammed-in-a-ball">https://www.kickstarter.com/projects/1535627339/oddball-the-drum-machine-crammed-in-a-ball</a></p>
<p>Kyle McDonald - guy who created FaceOSC using OpenFrameworks ofxFaceTracker.</p>
<h2 id="wip-show">WIP Show</h2>
<p>Here are some photos that show how the WIP was to be set up before it was cancelled.</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/WIP%20joint%20image.jpg?raw=true" alt="image"><br>
<em>Figure X &amp; Y - Front and Back view of 3 hacks set up in the FabLab exhibition space ready for the WIP show.</em></p>
<p>Here, in figure X you can see how the hacks would have been arranged. From left to right:</p>
<p>Eyebrow Controlled Pinball,</p>
<p>Selection Slider,</p>
<p>Eyebrow Controlled RC Skateboard,</p>
<p>Eyebrow Controlled Fruit Slicer.</p>
<p>Figure Y shows how the webcam is mounted to the back of the work desk/exhibiton table.</p>
<p>​</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/birdseye%20table%20setup.jpg?raw=true" alt="image"><br>
<em>Figure Z - birds eye view of the setup used for testing and ensuring all the hacks worked using laptop.</em></p>
<p>Figure A shows a close up of the mount made for the exhibition. This makes embeds the camera within the exhibition stand making the exhibition focus on the potential uses of eyebrow controlled objects rather than an end product for this project.</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/hack%20photos/camera%20mount%20close.jpg?raw=true" alt="enter image description here"><br>
<em>Figure A - webcam mount made for exhibition</em></p>
<h2 id="conclusions-from-wip">Conclusions from WIP</h2>
<p>I designed the work for the wip show exhibition with the intention to gain insight from the exhibition itself. I wanted to listen to a wide range of peoples opinions of my work and watch people interact with what I had made.</p>
<p>Unfortunately due to the cancellation of the show I didnt get this opportunity but reflecting on the work now I have made a series of conclusions of the next steps I need to take.</p>
<p>From my testing and further hacks I have concluded that using eyebrows as the control is definitely the most controllable aspect of your face - having the ‘raise’, neutral and ‘frown’ functions allows two distinct triggers.</p>
<p>To do this I have compiled a criteria for what the end product must be.</p>
<ol>
<li>Eyebrow Controlled - obviously!</li>
<li>Open Source Design - to be made anywhere.</li>
<li>Dual Person Interactive - for two people to work together.</li>
</ol>
<h2 id="appendix">Appendix</h2>
<p><strong>Futures Wheel</strong></p>
<p>​</p>
<p>This futures wheel is based on the trend of music consumption transitioning to streaming services such as spotify and apple music.</p>
<p>​</p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/Futures%20Wheel%20-%20Streaming%20-%20Further%20Futures.jpg?raw=true" alt="image"></p>
<p><em>Figure 1 - Futures Wheel based on the trend of music streaming</em></p>
<p>​</p>
<p>The Future wheel predicts a series of outcomes related to music and its surrounding industry.</p>
<p>​</p>
<p>​</p>
<p><strong>Personal, Novel &amp; Contextual Influences for this project.</strong></p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/Novel%20Personal%20Contextual.jpg?raw=true" alt="image"></p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/PNC%20-%201PERSONAL.JPG?raw=true" alt="image"></p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/PNC%20-%202NOVEL.JPG?raw=true" alt="image"></p>
<p><img src="https://github.com/josephlyons/eyebrow-control/blob/master/images/PNC%20-%203CONTEXTUAL.JPG?raw=true" alt="image"></p>
<p>​</p>
<h3 id="making-cardboard-prototype-maze">Making Cardboard Prototype Maze</h3>
<h4 id="build-1">BUILD 1</h4>
<p>Build 1 documents process of creating the cardboard prototype to be operated by hand.</p>
<p><img src="https://github.com/josephlyons/maze-shiftrio/blob/master/maze%20on%20table.JPG?raw=true" alt=""></p>
<p><strong>Materials</strong></p>
<ul>
<li>Cardboard boxes</li>
<li>BBQ Skewers</li>
<li>Rubber Bands</li>
<li>Wire cable ties</li>
</ul>
<p><strong>Fixings</strong></p>
<ul>
<li>PVA</li>
<li>Contact Adhesive</li>
<li>Electrical Tape</li>
<li>Superglue</li>
</ul>
<p><strong>Tools</strong></p>
<ul>
<li>60cm rule</li>
<li>Stanley knife</li>
<li>Wirecutter</li>
</ul>
<p><img src="https://github.com/josephlyons/maze-shiftrio/blob/master/materials.JPG?raw=true" alt=""></p>
<p><strong>Method</strong></p>
<p>I based my design off of a common youtube design.</p>
<p>I began by cutting the main square base that would have the maze on it.</p>
<p>Then I cut pieces to be layered into double thickness to give rigidity, these became the sides and framing for the two surrounding boxes.</p>
<p>I then cut out pieces for the maze. Everything from this point was glued with PVA glue.</p>
<p>The BBQ Skewers were combined in threes to create thicker dowel.</p>
<p>The wire cable ties were then cut into small hooks and superglued to keep them in place on the underside of the maze.</p>
<p>The elastic bands &amp; string was used to tension the maze and allow the bbq/dowel when twisted to move the maze on two axies.</p>
<p><img src="https://github.com/josephlyons/maze-shiftrio/blob/master/underr.JPG?raw=true" alt=""></p>
<p>VIDEO</p>
<h4 id="build-2">BUILD 2</h4>
<p>Build 2 documents the expansion of this design to include wireless wifi enabled eyebrow controlled servo motors.</p>
<p><strong>Materials</strong></p>
<ul>
<li>2x ESP32 Development Boards</li>
<li>2x Mini Servo Motors</li>
<li>2x Micro USB Cables</li>
<li>6x Jumper Cables</li>
</ul>
<p><strong>Software</strong></p>
<ul>
<li>FaceOSC</li>
<li>Puredata Extended</li>
<li>Arduino IDE w/ ESP32 Servo Library &amp; ESP32 Board Install</li>
<li><a href="http://Shiftr.io">Shiftr.io</a> [website]</li>
</ul>
<p><img src="https://github.com/josephlyons/maze-shiftrio/blob/master/servo%20setup.JPG?raw=true" alt=""></p>
<p><em>Two ESP32 development boards being used to wirelessly control the servo attached to one of the axis on the maze game.</em></p>

