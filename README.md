# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Tahmid Asif**

Time spent: **3** hours spent in total

Link to project: (insert your link here, should start with https://glitch.com...)

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
![](https://i.imgur.com/ROB9cDN.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources to complete my submission. 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
A challenge I experienced while creating this submission was 
ensuring that the “Start” and “Stop” buttons were working properly. 
Initially, the “Stop” button did not appear when the game had started 
after clicking the “Start” button. At first, I looked at my code and it 
seemed like there were no issues. I did not see any warning or error messages 
on the terminal which led me to believe there were no syntax issues or 
functions being called that were not defined. As I continued debugging my 
code, I noticed the add and remove methods were not switched in my function 
“stopGame().” This simple mistake was a roadblock but a learning experience. 
After completing this project, I can confirm that debugging is just as 
important as writing the code. Additionally, I learned to check your code 
frequently by running the terminal after each task or function is completed 
to avoid searching for the problem within the long blocks of code. Although 
this may be common knowledge, but after completing this project, I also 
learned that having patience is crucial to being a successful programmer. 
Often times, it does become frustrating when the code is not working properly 
but this is part of the learning process and in my opinion, the fundamentals 
of computer science which requires problem solving.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
I really admired how this project shed light on web development and how it 
is used to interact with users. A question I have is what are the most common 
languages employers usually work with in web development? Also, when one is 
working with their team on a specific task and looking at their code, is there 
a general rule of thumb for organizing code so it is easier for others to read 
and understand? Lastly, what is your least favorite aspect of web development?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I was given a few more hours to work on this project, I would try to 
allow the user to have three chances in the game instead of one. Also, as 
the game progresses, I would try to slowly increase the level of difficulty 
in the game by speeding up the clue playback after each level of completion. 
When the user loses that specific level, he would lose a life but the clue 
playback speed would stay the same at that level and the game would save the 
user’s progress so that they would not have to return back to the first level. 
Perhaps, after each level, there would be a pop-up message indicating the 
completion of each level and a button to move on to the next level. 


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
