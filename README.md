# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: **Zhiming Ke**

Time spent: **1** hours spent in total

Link to project: (https://glitch.com/edit/#!/deadpan-reinvented-nose)

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

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [ ] Playback speeds up on each turn
- [ ] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

![](https://i.imgur.com/6957eld.gif)

continuation of the aboved Gif

![](https://i.imgur.com/9ddSAHp.gif)


## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.

- https://www.w3schools.com/

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

- I did not run into many challenges while creating this submission. The instructions were very well defined and even when I was confused on specific functions such as the setTimeout() function. There were dropdowns where I can find out more information about the function. However, I did run into a problem when I had to implement the game logic where the guesses were handled. I wrote out my nested if statements and it looked correct. The logic made sense but when I ran the game, nothing happened when the guess was correct. I spent around 20 minutes trying to figure out what is wrong but I still found no error in my logic. What I ended up doing is having console.log statements inside and outside the if statements to see where code got up to in the guess function. What I found out is that none of the guesses made it past the comparison check of the if statement. This is when I realized I was using the assignment operator ('=') instead of the comparison operator ('=='). I had been doing a lot of Ocaml, where '=' was used as the comparison operator and had made a very careless mistake. After fixing that error, the game worked like it was supposed to.  

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)

- What web technology is used in large companies such as Facebook and Google to allow them to support such a large user base? I'm taking a computer ethics class where we learn a lot about hacking and cybersecurity. So another question I have is how does a web developer protect their web application from hackers. Finally, the web application I made is very basic which is very different from the majority of modern web applications that all look visually pleasing and are packed with functions. What are the best resources that I can look into to better format and learn web development?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)

- If I had a few more hours to work on this project, first of all, I would try to implement all the optional features that were listed on the prework. After that, I would like to make a user interface where the user would be able to customize the game to their liking. The user will have a menu where they will be able to change the features of the game. For example, there can be a "difficulty" section where the user can choose how many game buttons they want, whether they want to have multiple strikes, or if they would like to have a limited amount of time. Another section can customize the look and sound of the game. The user can change the look of the buttons or the sound of the game from a pre-set database of images and sound files. Finally, I would like to add a score feature. The user will get 1 point for each pattern they get correct and the score will be reset when they lose.
## License

    Copyright [Zhiming Ke]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
