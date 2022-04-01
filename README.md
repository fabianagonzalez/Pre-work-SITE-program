# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Fabiana Gonzalez**

Time spent: **5** hours spent in total

Link to project: (https://glitch.com/edit/#!/peppered-impossible-overcoat?path=README.md%3A14%3A0)

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
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
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
![](https://imgur.com/wXNUNEF.gif)
![](https://imgur.com/ssf8oIU.gif)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[One of the challenges I encountered in creating this submission was understanding the logic of some new features, such as the commands that I used to make the sound of every button. First, I did not understand how I could apply a timer so every sound could start and stop with the button. Second, I realized that I could not use the CSS for this task and that I had to use the javascript file. To achieve this, I had to include a JavaScript library called AudioContext to make the sounds of every button. Then, to make the tones start and stop when we use the button, I included the startTone and stopTone functions in the code. This function gives the opportunity that the sound will be played until the user releases the button. Also, I had to include a Global variable to know when the tone was playing or not. Finally, I included this variable at the top of the javaScript file, with the other Global variables of the game. With this unique implementation of making the sounds of the game, I was able to find the perfect match of time, buttons, and sound for the benefit of the game.   ]
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[After completing my submission, I have some questions about some commands that can make the game more friendly and global for more players. One of them is about making profiles and including the information by making users: What is the best way to include an API in an application, web page, etc.? Another question is about making a web page from scratch; since I started in this coding world and I want to make a web page, I always try to make a list of what I want the page to have, then I start to make a prototype on Adobe Xd and finally then I begin with the coding part. Finally, I would like to know if those are the correct steps to follow or I should include something else in the process?]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[If I could have a few more hours to work on this project, I would work on adding a unique feature of scores. Every game counts as 10 points, and if you win two in a row, you will have 20 points, and so on. This would make the game more competitive since you can share with your friends and family, and everyone would want to have the best score in the game. Also, I would like to make a red where everyone can see the scores of the others. So, every gamer can see who is competing. This feature would also help make the game viral so more people would want to play it.  ]



## Interview Recording URL Link

[My 5-minute Interview Recording](https://www.loom.com/share/ef6c2944ac12457dbac0e4a164ffec6e)


## License

    Copyright [Fabiana Gonzalez]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
