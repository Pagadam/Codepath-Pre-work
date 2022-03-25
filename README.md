# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **FREDERICK PAGADAM**

Time spent: **4** hours spent in total

Link to project: (https://fluorescent-foam-baryonyx.glitch.me/)

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
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [x] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://i.imgur.com/vePNMpq.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[MDN Documentation, W3 Schools, Colorhunt.co]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[Before starting out this project I had some HTML and CSS background from my personal studies. However, there were some syntaxes I had learnt before but didn’t have real practice with them and some of which were very new to me. As a result, I had to follow the instructions on those side very carefully and had to consult the external resources recommended on the guidelines to better understand how those features work. For example, the JavaScript audio library was new to me thus, I had to research on online using the MDN documentation and the listed online resource, the-art-of-web.com, to better under understand how those three functions implementing the audio library were working.
Aside these kinds of difficulties I encountered, I also wanted to have more control over the work I was doing thus had to delete all the boiler template provided by Glitch. Because of that, I forgot to add the JavaScript line in the HTML before the closing tag for the body. After I was done with the start and stop button, I wanted to test them out, but they were not working. Which I didn’t realize was a result of the JavaScript tag causing that. I tried going through both the index.html and the script.js to see where I had made a mistake including checking the html ids. After having finished debugging the html and their attributes, I had to apply the console.log and alert syntax in the script.js where I realized they were still not working. After that I realized it was something to do with my JavaScript invocation. I then went to the index.html file and replaced the JavaScript tag and the buttons features started working as I wanted.
]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[I have not had a lot of experience with Web Development until recently when I started my position as a web developer in the Residential and Housing Department at Michigan State University where I have been getting experience on how to build Drupal website using devil box and Docker in the command line which is giving me a lot of experience. However, there are couple of things about web development I am hoping to understand such as how the blackened process correlates with the frontend like how the JavaScript, CSS and the html files coordinated in this project to create this game. I would also want to understand how large organizations maintain their websites, and their database systems. For instance, if I were to be deploying the Light and Sound Memory game where many people would be using it how do I maintain its efficiency.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[4.	Working on this project has been very fun and a learning experience as well.
However, as a guitarist, I was thinking about how I could implement my musical ideas into this project. I was thinking about making all the randomly generated notes be in a specific music key. Each time the game begins there would be alternation of a different key, ranging from natural minor, harmonic minor, and the major scale. For example, at the start of the game the key could be in C with each of the pattern indexes representing the notes C, D, E, F, G, A, B. Then the next time could go to C natural minor scale. I could also include accidentals thus enhancing more ear training. 
Aside that I also would want to add an audio song which would play when the user gets an attempt wrong and another which would play when the user wins.
By reading about the MDN documentation, I realized I would be able to achieve this without having to use the audio library which was provided in the instructions by applying event listeners and query selectors, which would listen for each button clicks and apply the appropriate tone associated with it functionality. I think writing out my own code on this feature would have given me more freedom and also reduced code lines.
]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/26ec4e6700894bf8a4d428dedfb40e98)


## License

    Copyright [FREDERICK PAGADAM]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.