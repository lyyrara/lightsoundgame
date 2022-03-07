# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Bai

Time spent: 24 hours spent in total

Link to project: https://sedate-mulberry-room.glitch.me

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
* [x] More than 4 functional game buttons
* [x] Playback speeds up on each turn
* [x] Computer picks a different pattern each time the game is played
* [x] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [x] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![soundgame](https://user-images.githubusercontent.com/97574372/157124650-9b305c0a-132e-460f-8b6f-29dae4af0732.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
StackOverflow, w3schools

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The most difficult part of this submission was creating the countdown timer that would give the player a set amount of time to repeat the pattern. Because it is difficult for me to figure out the syntax behind it.
At first, I studied the setInterval() method, to understand how it works. And then write the countDown function to dislay the timeleft and stop game when the counting is over. I google the way to implement the function. However, I found it difficult to decide where to put the timer. I thought it would be enough to just have the continuous, 20 second timer when the game start. I tried to implement this in the playClueSequence() function to calculate the time left for the game. So when the game start, it will begin to countdown time, and the game will stop and reset the timer when timeout.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing this submission, I became more curious about how much one could do with just frontend languages, and also how to combine it with the backend. Since I have no experience in Javascript, I would like to learn more anout it. And I want to learn anout how to implement an e-commerce website, learn something more complicated and useful.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
Set up difficulty level for the game, like easy mode, hard mode with different numbers of patterns. 
Keep scores of the player. Like if you win the first round, you can gain 5 points. If you pass the round two, you can gain 10 points. You can get more points as the game round increases. And we can keep the record of the game. 




## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


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
