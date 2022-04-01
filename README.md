# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Adrian Torres**

Time spent: **15** hours spent in total

Link to project: Live site: https://spangle-verbena-grasshopper.glitch.me Code: https://glitch.com/edit/#!/spangle-verbena-grasshopper

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [x] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

Start and stop buttons
![](http://g.recordit.co/EYQXSw9qEd.gif)

Loosing game
![](http://g.recordit.co/DAwiTssj0A.gif)

Winning game
![](http://g.recordit.co/4M6J2NLHHH.gif)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 

w3schools.com

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge I encountered in creating this submission was exporting my light and sound memory game project from Glitch to GitHub. When I watched the video on creating a repository, commit, and push using GitHub Desk, there was a step where the presenter had an existing folder with his project files, which made me think I needed to download my project from Glitch to my desktop and upload it to Github desktop and then to the Github website, which got me confused. I overcame this challenge by watching the other video in the instructions that showed how to directly upload my project to my Github repository from Glitch, using the import/export tool in Glitch. Also, a challenge I encountered was adding two additional game buttons to the four existing game buttons. After adding buttons to the HTML and CSS rules for the two new buttons, it was challenging for me at first when editing the secret pattern in script.js in order to use the additional buttons. I overcame this challenge by noticing that originally when I had only four buttons, I realized there were 6 patterns in total that ranged from 1 to 4 in the pattern global variable. Then after adding 2 more buttons I decided to add 2 more patterns into the pattern global variable totaled to 8 patterns that then ranged from 1 to 6. Afterwards, it was challenging for me when editing the freqMap object in script.js in order to include pitch frequencies for the new buttons. When I first tried to add sound synthesis numbers for buttons 5 and 6, the code was unable to run at first since I didn't formated the code correctly. I overcame this challenge by learning the correct way to format the code under the freqMap object with commas that separated the different sound synthesis for each button. Another challenge I encountered was managing my time between working on this project and my homework. I overcame this challenge by being able to complete the project by parts each day, while still doing good progress on my homework.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
* Where does back-end code come into play when creating a website that uses front-end code using HTML, CSS, and Javascript?
* How do web developers make their websites compatible with different devices such as phone, tablet, and desktop? What changes do web developers have to make in order to fit different device screens?
* How are websites improved, when technology keeps on advancing? Is code reused or is it changed to meet the needs of new technology?
* What other programming languages do web developers use other than HTML, CSS, and Javascript? Can Python APIs be used, while using Javascript?
* How do web developers divide the work for a project between each other? How long does a project usually take to complete?
* What are challenges that web developers are usually faced with?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I had a few more hours to work on this project, I would refactor some of my code. For example I would refactor my CSS style code specifically for the buttons, since it does seem to be repetetive as each button follows the same format that share the same properties that deal with background colors when the buttons are inactive and active throughout the game. One additional feature I would implement will be an option before starting the game to ask the user which difficulty level they would like to play; easy, medium, or hard. The user would press on any of the three difficulty level buttons that will prompt the program what level of difficulty of code to run when the user presses start. Easy would would include 8 patterns, medium would include 10 patterns, and hard would include 12 patterns for the user to complete. I would continue on where I left off on my project when implementing the optional feature of speeding up the clue playback on each turn with editing the clueHoldTime contant and updating the playClueSequence.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/f1f051aaa3e74520b6651f73e6499b8e)


## License

    Copyright [Adrian Torres]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
