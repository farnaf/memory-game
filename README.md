# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Farnia Nafarifard

Time spent: 6-7 hours spent in total

Link to project: (https://glitch.com/edit/#!/gabby-interesting-salary)

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
- [x] Buttons use a pitch (frequency) other than the ones in the tutorial
- [x] More than 4 functional game buttons
- [x] Playback speeds up on each turn
- [x] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

## Video Walkthrough

Here's a couple walkthroughs of implemented user stories:
![](https://cdn.glitch.com/3b03b95a-24c2-45d3-81ea-95d90efae8ab%2Fezgif.com-gif-maker.gif?v=1616641808621)
![](https://cdn.glitch.com/3b03b95a-24c2-45d3-81ea-95d90efae8ab%2Fezgif.com-gif-maker%20(1).gif?v=1616642048840)

## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

   I mainly used the links and resources that were listed in the pre-work write-up:
   - https://cssreference.io/backgrounds/
   - https://www.rapidtables.com/web/css/css-color.html
   - https://www.w3schools.com/csSref/css_selectors.asp
   - https://www.w3schools.com/js/js_events.asp
   - https://www.w3schools.com/js/js_random.asp
   - https://hackmd.io/f8KTlLJMTOet9ywUmtf6wQ?view

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

   Overall, I think the pre-work write-up was well explained and did a good job of walking me through the required parts of the submission. A challenge I faced as a beginner in web development was understanding the logic that connected all three HTML, JS, and CSS files together to help me code up guess function as the last requirement of the submission.
   Specifically, for the implementation of the given logic flowchart for the guess function, I initially coded up the whole function and then started testing it. Due to a little mistake I made in my nested if statements, it was difficult to catch the error and debug my code based on the wrong behavior I was getting. Since I was sure that my logic was wrong, I decided to re-write the guess function, but this time take the time to test my program at every step of the way. For every new conditional statement I added, I would pause to double-check if my program behaves as expected. I would test my program in various ways and with all the possible/different tests and edge cases I could come up with. Besides studying other functions in my program to better grasp what variables need to change, with breaking down the logic and thoroughly testing every new change I made to the guess function, I was more efficient and successful in getting my program to work as intended. Being patient, testing thoroughly, and reading about the languages helped me get through the challenge pretty smoothly.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
   
   I am very curious to learn about the different ways that websites can be designed to be engaging and interactive. This was my first time experiencing web and game development in a way that programming logic is heavily dependent and connected to the interactions of the user with all the features and components of the program (e.g., clicking, selecting, hovering over, etc). Working closely with HTML, JavaScript and CSS in this pre-work, I am more eager to not only explore the different features of these languages and tools, but to also see how the websites I utilize and interact with daily are built and coded up underneath the surface.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   
   If I had more hours to spend on this project, I'd add more buttons to the game with different pictures that have a common theme altogether. For example, I would have 20 buttons with Disney villans as the pictures on each button. I'd also design a pattern such that if the player wins, the complete pattern (combination of the sounds produced by each button in the pattern) produces a soundtrack of one of Disney songs. Additionally, I think it would also be cool to have a drop down on the game screen for the player to select the theme of the game. I would have the different patterns and pictures ready for each theme to get the game going for the player once they select the theme they like!

## License

    Copyright Farnia Nafarifard

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
