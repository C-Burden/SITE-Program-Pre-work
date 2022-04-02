# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Christina Burden

Time spent: **4** hours spent in total

Link to project: https://glitch.com/edit/#!/light-and-sound-memory-game-cb

## Required Functionality

The following **required** functionality is complete:

- [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [x] "Start" button toggles between "Start" and "Stop" when clicked.
- [x] Game buttons each light up and play a sound when clicked.
- [x] Computer plays back sequence of clues including sound and visual cue for each button
- [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [x] User wins the game after guessing a complete pattern
- [x] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [x] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [x] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/101878146/161336807-8d9c92c9-c841-49de-bfb5-da3302dc97e6.gif)
![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/101878146/161337047-43a0ad53-4307-4509-8af7-c16429b0e7e0.gif)
![ezgif com-gif-maker (5)](https://user-images.githubusercontent.com/101878146/161338007-4688e495-284f-4251-a59a-ba163f7d3d65.gif)
![ezgif com-gif-maker (6)](https://user-images.githubusercontent.com/101878146/161338169-acd21954-e524-40d2-aa5b-98513b0a2c79.gif)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   https://www.w3schools.com/js/default.asp
   https://developer.mozilla.org/en-US/docs/Web/JavaScript

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it?

   A challenge I ran into while creating the game was implementing one of the additional features. I was unsure of how to create a new unique pattern every time the game would run. Before this project, I did not have much experience with javascript, which let me know I needed to do some research on the features. I knew how to randomize numbers in java but not javascript. To create the logic for this feature, I researched and found the “Math.random” function which worked in the program. After figuring out how to create random numbers I researched how to put the randomly generated numbers into an array. I was not familiar with how arrays work in javascript, which meant that I did not have a frame of reference for how they worked. When I researched their function in JavaScript I could quickly grasp how to use them in the pre-work. I specifically used the “push” function to add the random numbers generated to the array in a loop and completed that feature of the game. Another small problem I ran into was that the game was not playing the last part of the game sequence. The main challenge in fixing this bug was finding what the cause of the bug was. To find the bug, I carefully went through the code of the game, making sure every function worked properly while checking to see what was logged in the console. I eventually found that the time increment I had created was too large, making the buttons sound for less than a second, which made it appear as if they did not sound at all. I was able to fix this by decreasing the time of the increment.

3. What questions about web development do you have after completing your submission?

   After completing my submission I have questions about data storage. I specifically want to research and learn how to store and display information entered into a website or display information hosted on other websites. I am curious about this because I thought a feature the game could have was to display the best score achieved by the player. However, with the program currently, the games won by the user disappear when the page is refreshed. I want to further research how this problem can be solved and if other programming languages would be required to do this, or if something like this would be achievable in JavaScript.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

   The first thing I would do if I worked on the project further would be to add an infinite sequence pattern that could be guessed in the game. Instead of ending the game when the user guesses the entire 8 number long pattern, I would make the game last until the user guessed incorrectly. The score of the user would be the length of the array up until the incorrect input. This would be displayed as a high score and would be replaced if the user is able to beat their previous high score. I believe that with more time I would be able to implement this utilizing the current programming languages in the project. However, to get the high score to stay once the page is refreshed may require the use of another language.

## Interview Recording URL Link

https://drive.google.com/file/d/1e116DS5-i6KXtsuLnTNIyhMrxNdAiPMH/view?usp=sharing

## License

    Copyright Christina Burden

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
