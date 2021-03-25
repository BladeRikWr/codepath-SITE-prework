# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Nathan Lim**

Time spent: **1** hours spent in total

Link to project: [https://glitch.com/edit/#!/lim-codepath-site](https://glitch.com/edit/#!/lim-codepath-site)

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
  * To create a more pleasing melody when played in order :)
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](https://cdn.glitch.com/f770344e-9232-4d71-8c15-3717ef427f15%2Fcodepath.gif?v=1616641587440)


## Reflection Questions
1. **If you used any outside resources to help complete your submission (websites, books, people, etc) list them here**. 
N/A

2. **What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)**

I used ScreenToGif on Windows to record my GIF and kept running into issues where ScreenToGif would crash with a "out of memory" exception! Super weird.
I poked around in the settings and played with the values a little bit to try and resolve the issue.
For some reason, Windows didn't like the program using DirectX to record the screen (it's either that or ScreenToGif has a bad implemenetation of the DirectX library).
I told ScreenToGif to use another recording library and was able to record my GIF with no interruptions!

3. **What questions about web development do you have after completing your submission? (recommended 100 - 300 words) **

Is the DOM to the browser, much like machine code is to a processor? Further more, we code websites with languages like HTML, CSS, and JavaScript, can we classify these as high level languages compared to the DOM, much in the way that Python and Java are high level languages?
Is web development really all about... websites? There has to be more to front end work... I guess that's what a designer role is like!

4. **If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) **

I'd probably adopt a uniform color scheme for the app styling. A high score leaderboard would also be kinda cool. OH and I'd add a secret, 1x1 pixel button that would maybe do something weird to the browser, like start making the screen shake.



## License

    Copyright: Nathan Lim

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
