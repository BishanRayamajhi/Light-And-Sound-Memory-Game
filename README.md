# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Bishan Rayamajhi

Time spent: approximately 5 to 7 hours spent in total

Link to project: https://glitch.com/edit/#!/lightandsoundmemorygame?path=README.md%3A1%3A0

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
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![x](https://i.imgur.com/lPb2etf.gif)
- Two mistakes and game over!!

![x](https://i.imgur.com/C9YsVN9.gif)
- Random pattern

![x](https://i.imgur.com/koX1dJl.gif)
- Complete game





## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- I mostly followed the instruction as it was very clear. For the most part, it was easy to follow through, but for the additional parts, I had to do some research on websites.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
- I had a few challenged while I encountered in creating this submission. To be specific, the clue holds time and when there are two mistakes, the game has to show it is over. For the clue hold time, I had no clue how it works at first because I was just adding random codes which did not even make any sense. After tries and fail, I figured out that it was just a line of code that I had to subtract from. I tried random numbers at first, and the problem with that was when the random pattern shows the same button twice, the program only shows one long hold time. So, I had to try many different numbers so that the program does not hold one button for a long period when the next pattern is on the same button. Additionally, another challenge I encountered was when we had to give the user two tries or two mistakes, and the same supposed to be over. The problem was encountered after the second pattern because it was giving the user more than two changes. Like wisely, for the first two patterns, the game worked fine but after the third pattern ends and the user made two mistakes it would give them an additional mistake to do after the pattern goes on. So, I had to figure out for the whole game there are supposed to have two mistakes only. I added the else and if statement for the program to run successfully and have two mistakes throughout the whole game.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
- After completing my submission, this prework gave me more interest in going into the web development field. Although it was pretty simple to work, there has to be a complex feature which I am looking forward to in the future. I wonder if automatically website builder would take over the feature of coding yourself in the future because the website builder is much quicker and simpler rather than programming yourself a website. People would choose an easier and lazy option. Platforms like Shopify, Squarespace, etc. are taking over the web development platform. I personally have used one of these platforms and it is much more easier as a single piece of code was not written by me. I just had to design how my website looks on the outer. So, this made me wonder if the different platforms would gradually take over the traditional way of making a website.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
- This program is supposed to be a very simple game where the user wins by following the pattern and loses when he makes mistakes. There is not much to add to this, but I would definitely add more additional features by making it more user interactable. Maybe adding some type of prize when the user wins and adding some type of music or tunes for each button so that the user can remember the tune and also the button to make it interesting as well. Making it more user-friendly so that they can get interested rather than just following the patterns with a tune.



## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
