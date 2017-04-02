## Midi-Keyboard ##<br>
<br>
Partner 1:
<h3>Derek Ross</h3>
<h3>DerekR0123</h3>
<br>
Partner 2:
<!--- Patrick Driscoll had to drop the class --->
<br>
<br>
## Overview ##
<h4>What and How?</h4><br>
<!--- Derek's Section --->
So what exactly is a Midi-Keyboard and why did we choose it? Well a Midi-Keyboard is a keyboard that you can hook up to your computer
and use it with different music creation software to produce all sorts of cool results! Our goal is to have the program read sheet music
from a library and have the key that reperesents the note being played light up from an LED underneath it! In order to do this we need a few non traditional things such as an Arduino Unit, Serial-to-midi conversion software, LED's, and a keyboard to test it all with. The way it works is it uses a midi-input instead of serial input along with an Arduino made by Patrick Driscoll. The goal is to have the library read music into the program and the program will dictate which keys from there represent what and will light up accordingly.
<br><br>
<h4>Why?</h4><br>
We chose this project after discussing about things we were passionate about. This turns out to be something that Patrick is very passionate about and takes his personal time outside of school and work to learn about. He wanted to incorporate something through
coding that could teach people how to play the piano by following the lights of the keys on the keyboard!<br>
<!--- End of Dereks Section --->



<br>
<br>

<!--- Google Image - Derek --->
Here is a similar idea of what it looks like in the real world<br>
<br>
<img src="https://i.ytimg.com/vi/-dhS0qbpMqM/maxresdefault.jpg" width="15%"></img> <br>
<br>
<br>
<!--- End of Image --->

<!--- Dereks Section --->
<h3>What Approaches from class will we bring?</h3><br>
<br>
<h5>Data Abstraction</h5> - The goal would to create some objects that represent the keyboard and the notes. From there each key needs to be assigned and we can do that using object orientation and assignment.<br>
<br>
<h5>Recursion</h5> - I beleive we could incorperate this by making a function that recursively assigns the notes to keys at the start of the
program provided we order the keys / notes the way we want. If this is too far out then I still think we could atleast make a light
show from recursion.<br>
<br>
<h5>Map / Filter / Reduce</h5> - At this current point in implementation I have a plan to possibly have a container for notes left to go in
a song and it could be filtered out for things that are played which could be placed in another list for comparison. Its kind of a far
stretch but if there's time and its possible this is one form of an idea. <br>
<br>
<h5>Object-Orientation</h5> - Kind of building back on to the data abstraction the goal is to create objects for the keyboard and notes. In order to assign them we need objects and in order to be abstract we need objects to assign this too.<br>
<br>
<h5>Functional Approaches</h5> - I would like to see possibly a few functions that can map the keys once we get set up and possibly may even be
able to play a song using like a recursive call going down a list of planned notes! <br>
<br>
<h5>State-Modification Approaches</h5> - As of right now the objects will be changing often depending on what note they encapsulate. So long answer is yes, short answer is theres a good possibility.<br>
<br>
<h5>Expression Evaluator</h5> - As of right now I don't see this or map/filter/reduce really fitting into the project. I dont want to bite off more then we can chew yet but I can see us making something to evaluate notes for a template song that someone can learn piano by following - which is what Patricks passion / goal was in the first place. <br>
<br>
<h5>Lazy Evaluation</h5> - At this current time we have not learned about it so I can't say for sure but as the project goes on and I learn more about what the concept is , it is completely up in the air for using it.<br>
<br>
<!--- End of Dereks Section --->
<br>

<h3>External Technologies:</h3><br>
I sort of touch on this in the first paragraph of this proposal, but essentially we need a few hardware components and one software component that don't include the standard things required to code in Racket. We need a Keyboard with LED's, An Arduino device with ability to be attatched to the keyboard, Conversion software for the music and arduino, and lastly sheet music which I beleive we can use one of the audio libraries for. For more detail on how they incorporate into the project please see the first paragraph in the proposal!<br>
<br>

<h3>Deliverable's and Demonstration's</h3><br>
The goal (High level) at the end of this project is to have a keyboard that is lit only by one key at a time. During which when the user presses thaat key it should play the note associated with it. Every time a key is pressed the note is removed from a queue in which the rest of the sheet music is following behind thus allowing the user to follow along with a song.<br>
What I plan to acheive for a minimum standard is a mapping from notes to keys in a representation of object orientation and then follow it up with a way to recursively map all the keys on the keyboard to some form of note. This would allow me to get a good demonstration of what I learned in class and get the goal of the assignment done. Provided I have more time I will attempt to go for the High level overview with sheet music.<br>
Lastly the goal would be to have either the professor or someone in class come up and try the project out for themselves! What could be cooler then to see something work in your own hands!<br>
<br>
<br>
<h3>Evaluation of Results<h3>
How Will I know if I will be successful? Well this is something that Patrick is deeply passionate about and has already gone out of his way to get the arduino end done so we are well on our way. I truly beleive any time you care enough about something you are bound to excel at it. I love music and I would love to bring something as cool as this to life and with proper planning over the next few weeks this will become a reality.<br>
<br>
<br>
<h3>Architecture</h3>
If you trace back to this repository you will find a powerpoint with details of how we plan to carry out this project and all the things it entitles.</h3>
<br>
<br>
<h3> Schedule / MileStone's </h3>
First Week / Milestone: The first week will be sound evaluation. I will work on getting sounds to play in racket. The goal would be to have it load some mp3 file and be able to play that song on command.<br>
<br>
Second Week / Milestone: The second week's goal will to work on mapping keys. I will try to get them to do simple things first followed by mapping the commands of playing sounds to the keys. <br>
<br>
Final Week(s): The goal from here on out is to now incorporate lessons from OPL into the above things. Once this is done if there is any remaining time from then on out the goal is to acheive coordinated lighting based on the notes for a song. We would need to then take the song from a library, take week 1 and 2's work and incorporate it to a data structure that will read each peice into a key and highlight it one at a time and dequeue it when pressed. Most likely this is a far fetched idea but I'd rather have idea's early then run out of things to do later. <br>
<br>
Public Presentation: The goal would to have someone come up and try the program out. They should be able to push a key and have it perform some sort of music playback. Provided we get further then this they could even go through the tutorial and learn how to play a song or atleast be a cool DJ for the moment!<br>
<br>
<br>
<h3>Group Responsabilities</h3>
Derek Ross @DerekR0123 <br>
At this current time I will be writing and working on ALL features.
