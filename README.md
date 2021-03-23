# Simon-Says
Simon Says Memory Game created with glitch
# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: James C Aquilina III

Time spent: 3 hours spent in total

Link to project: https://glitch.com/edit/#!/simon-say-memory-game

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [x] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![http://g.recordit.co/reV4HaCemW.gif]
[http://g.recordit.co/sShhHnHGvL.gif]


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[The only resource I used was W3 schools and repl.it to test code I was writing.]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[When I was trying to implement the random pattern, it was hard to know what my function was doing by only referencing the 
web dev console, so I decided to write the function for the random pattern in repl.it just to condense the scope of what I was
looking at and I could solely focus on that specific funtionality. It was tripping me up on how to create the lenght of an empty array
until I realized that I shouldn't be using a for loop, I should be using a while loop, since there was a specifc length I needed the array
to be.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[Does web development delve into the server side of code? Or is it primarily focused on the front end of the user experience, and 
handling simply request? How do websites get hosted, and how do the domain names of websites work?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I had more time I would work on adding levels to the game and include a life system and high score. You would get three lives and each level gets faster
and more difficult by making it longer. If you guessed incorrectly three times you would start over from the first level.]



## License

    Copyright [James C Aquilina III]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
