# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Jeron Kok

Time spent: 3 hours spent in total

Link to project: https://chlorinated-yielding-pot.glitch.me/

## Required Functionality

The following **required** functionality is complete:

* [*] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [*] "Start" button toggles between "Start" and "Stop" when clicked. 
* [*] Game buttons each light up and play a sound when clicked. 
* [*] Computer plays back sequence of clues including sound and visual cue for each button
* [*] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [*] User wins the game after guessing a complete pattern
* [*] User loses the game after an incorrect guess

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

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![](simonsays_jeronkok.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I didn't use any outside resources

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
One challenge I had in this submission was making the logic of the guessBtn function. After working on the rest of the project, I forgot what the variables that we 
initialized before did, so I first went back and read what the variables were meant to do. I did end up having to reference the solution, but after running
through what the code did in my head, I was able to understand what each part did. The way that I overcame this challenge essentially boiled down to knowing what
resources I had at my disposal, and a willingness to use them in order to face the problem. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
One thing that I am curious about is how different making a game like this is compared to making a game that is available on something like Steam 
or other platforms that have lots of games on them. I'm interested in making a game myself but am not very sure what level I need to be at to make something substantial.
I am also curious what other libraries are out there for web development that can be used to make interesting things. I know we used the audio context library to make sound, but 
I was wondering if there are libraries that are used often to make games.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
Something that I think would be cool to add is to have randomized patterns rather than the pattern being the same every time. I would also add
a leaderboard that would store the top 5 times that the game has been completed in. Also, perhaps adding an infinite pattern and adding a leaderboard for that as well. 
I think something else that would be cool is having multiple people play at the same time to see who lasts longer.



## License

    Copyright [Jeron Kok]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.