# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Diana Gonzalez-Argueta

Time spent: 18 hours spent in total

Link to project: (https://glitch.com/edit/#!/knotty-rigorous-apogee)

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

- [X] <3 Making the website aesthetically pleasing <3

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

![   Watch me beat the game here!  ](https://drive.google.com/file/d/1XMYbVqHSFmvOTCEYcsN-bzgnreZ-DfOa/view?usp=sharing)


![  Watch me lose (on purpose) here  ](https://drive.google.com/file/d/1ienOgWWJBCuHMm0OWSrKSyqCLOnhjIOZ/view?usp=sharing)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://stackoverflow.com/questions/55026293/google-chrome-javascript-issue-in-getting-user-audio-the-audiocontext-was-not
https://forum.unity.com/threads/the-audiocontext-was-not-allowed-to-start-it-must-be-resumed-or-created-after-a-user-gesture-on-t.615352/
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong
https://coolors.co/4effef-73a6ad-cccccc-d8a7ca-7752cb
https://www.w3schools.com/html/html_images.asp
https://www.canva.com/design/DAE6Ojs9mRk/ge3cwiOMJ5OhrHk6pLoMXA/edit
and I also used the support Slack channel too :) 

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

One of the biggest challenges I faced in creating this submission was that when a user made their first play in the game, after clicking on Start the game would begin with the first note and the user would repeat it back but then the game would stop. The button wouldn't go from Start to Stop, it would show the game still in progress. But the audio/lights would not resume after the user's first move in the game. I would say trying to fix this error was my most time-consuming issue and I couldn't figure out what the problem was. I had to look through my code line by line and realized the mistake was that I had a method() inside another method(). It was so relieving to find my mistake but it also made me feel silly for how miniscule the mistake was. In the process of finding my mistake I feel I've gotten to know the code really well.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

I wouldn't say I have any questions about web development after competing this submission. After working on this, I realize that web development just requires the will to learn and lots of patience because there are TONS of resources online for building cool different features.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

If I were to work a few more hours on this project, I would love to play with the music that plays with the buttons to change the frequencies. I would also love to add "aesthetic" features like more pictures and maybe a moving spotlight feature. It would also be really cool to have tabs where this website could be available in different languages.


## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Diana Gonzalez-Argueta

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
