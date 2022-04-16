# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Courtney Thang

Time spent: 4.5 hours spent in total

Link to project: https://glitch.com/edit/#!/slender-repeated-quality

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] Computer picks a different pattern each time the game is played

The following **additional** features are implemented:

- [ ] The duration set for each clue to play was shortened

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![Game-button-demo](https://user-images.githubusercontent.com/99851691/163685798-aacd947e-120c-4912-bbe7-54ee163d9c71.gif)
![Losing-game-demo](https://user-images.githubusercontent.com/99851691/163685804-3ebd6c54-e0b4-4f5e-80a6-bb75fe9a725e.gif)
![Winning-game-demo](https://user-images.githubusercontent.com/99851691/163686061-da26167f-48ec-4874-93d5-ed39c944a0fb.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://developer.mozilla.org/en-US/docs/web/javascript/reference/global_objects/math/random
https://stackoverflow.com/questions/66753746/how-to-implement-random-pattern-in-javascript-game

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

A challenge I encountered when creating this submission was understanding the formatting of Javascript and HTML. I have very limited background in those two languages and am most familiar with Python. Therefore, when going through each function of this project, and reading about what each of the components of Javascript and HTML do, it was hard to visualize the specifics and remember them. To develop a better understanding of these functions and formatting, I went through each line of the project and looked at what does each part of the line do to the game. By seeing the changes they made to the game, I grasped a better understanding of the formatting and functions. I also struggled with trying to develop a new function that would generate a random pattern for the game. I read the given link about the Math.random() function to familiarize myself with the code but I looked to stackoverflow for another explanation. I found the code to use for it and an explanation as to what the lines do for this function and understood how to use it. After finishing my code, I tested different variables and values to see how the game changes to further understand the impact of my code to the game. I lowered the clueHoldTime constant and saw that the duration for the clues were decreased and made the game a little bit more difficult. I also changed the new clueLength variable I created for the random generator function and saw that it increased or decreased the number of levels to the game. After making changes, and looking more in depth to the code, I am more familiar with these languages and can understand what specific functions of the code do.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

After completing this project, I am very curious about how much you can really do with web development and the languages used in this project. When thinking about web development, I always thought about simple websites. I had no idea that I was able to create an interactive game using these languages. I am interested in learning more about the capabilities of full stack web development. Some questions I have are what is web development capable of? How many different types of website/web applications can be developed? What are the different frameworks and how do you use them for each specific language? How can I implement front-end software engineering with back-end software engineering?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I were given more time to work on this project, I would be interested in adding additional features to this game. One additional feature that I want to implement is a timer additional feature however, the timer will speed up with every level increase. This will increase the difficulty of the game and will make the user more invested in winning. The second additional feature I'm interested in adding is adding a difficulty option. User's are able to pick Easy, Medium, or Hard and the clueHoldTime constant will vary based on the difficulty and other additional features can be adjusted based on difficulty level. Another additional feature I want to add is after a set interval of levels, the number of buttons increases. If the user was given the option to pick difficulty and were to pick the hard difficulty level, the number of buttons increases and makes the game increasingly difficult as it progresses. The last additional feature I want to implement is if given a difficulty option and the hard difficulty was chosen, the positions of the colored blocks change as the levels increase. This will create more difficulty and will increase the users' interest.

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
