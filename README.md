# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Ian Orzel**

Time spent: **2** hours spent in total

Link to project: https://glitch.com/edit/#!/volcano-goldenrod-smash

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](http://g.recordit.co/4CdMaCuPb6.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I did not use any outside resources.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One challenge that I encountered during the creation of this submission was the fact that it was not making any sounds when the buttons were pressed, and this was difficult to troubleshoot. When I first created the game, I did not have access to headphones or speakers, so I could not initially confirm whether the sounds were working. Then, when I finally had access to these tools, I realized that the sounds were not properly being output. After a little bit of digging, I realized that I had misspelled the playSound function, and this misspelling was the reason that no sound was being output. By changing the spelling on all uses of the function, I was able to fix the problem.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
The main question that I have about web development after completing this submission is the question of what is the best way to visualize what a web page will look like before the programming process begins. When messing with what the site should look like, I felt as if I was randomly fiddling with numbers to see what looked nice. It would be great if there was a way to visualize the web site or create a still version of it before starting to code the site.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would create an endless mode for the game. I would create a way to be able to toggle between normal mode and endless mode. In this endless mode, the player would have to continue the game forever until they failed, and they would have a score based on the longest pattern they were able to get right. I think it would make the game a lot more fun to continue going until you could not any more, rather than having a point where it is guarunteed to stop.



## License

    Copyright Ian Orzel

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.