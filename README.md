# Pre-work - *Ring Ring Listen!*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Kyle Sanders**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/edit/#!/pineapple-ahead-twine

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
![ezgif com-gif-maker](https://user-images.githubusercontent.com/91567348/160967718-b2e3a9ff-74d3-49cb-8460-3879f7112103.gif)
![](gif2-link-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[YOUR ANSWER HERE]
I used personal friends who helped me work through and distinguish steps on certain parts. More specifically, the counting mechanism for the next sequence and the button tools that were added.
2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[YOUR ANSWER HERE]

Common issues like tools and the functions of the statements were explained many times with a tip bar example that would pop out. Specifically, the class hidden feature for hiding the stop and start button upon initial creation. When initially writing the start/stop buttons, individually I attempted to create a normal id of a single "button" where it had the feature to switch to stop after onclick and start vice versa. In this instance there would not be the 2 buttons individually that hid one with the class feature and so on. Like I had mentioned before, this issue was solved with the drop down tool bar explaining the function of class with hiding elements but at least started my ingenuity to try and solve the issue before being fully explained and for my attempts for others after.

One challenging step that I encountered was the mechanism of the guess counter mentioned above. Before initially taking a peek at the example code and seeking aid from a friend, I attempted to create a basic counter with a variable set to 0 that added "progress" for each step by adding 1 to it. My roadblock was that after adding progress for each step of the first sequence I could not figure out how to add the next sequence of sounds played and the users feedback for the counter its own counter. From here I went to  my friend who helped to create an if/else function for the progress in the next steps. From there with the help of the example code I was able create the counter for multiple sequences. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

I would like to further understand mechanisms that enable multiple sequenced windows by user clicks. For example, when clicking through Google Earth, how does the movement of an individual with the arrows on the screen move through the digital representation of a location. Was it through a sequence of pre-generated hidden windows/buttons or just a larger environment that I have yet to comprehend. I'm also interested in the creation of apps and the multiple tabs that a user can be guided through. User experience for any app seems fundamental but after attempting web development first hand, how would I optimize multiple games/apps across multiple platforms, what are the most essential coding languages for web development, and how/when is it best to explore CSS selector tools for different problems.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[YOUR ANSWER HERE]

Having found out about the CodePath application soon before the deadline for the project, if I had more time to add functions and features to the game, I would take the game in a whole new direction with a new look interface and more features for the sequences. I would want to create a sequence list randomizer. This would be made with an RNG or random number generator and a random list length. I would want this so that the user cannot so easily work through the game off of a basic sequence. I would also add corresponding points that totaled over the users playing experience. If the sequences was say a length of 10 vs a sequence length 5, there would be more points for the longer one. That way I could implement a counter for the points in its own box aswell. I would want the user to also have the experience of being able to use these points to play a song sequence reward. At the bottom of the screen I would implement boxes that were different song arrangements with the sounds:Old MacDonald or Happy Birthday. The user would have a set number of attempts, also with a displayed counter. This way if you fail the game, that it is not so easy to have the redeemable songs play, thus creating the reward.



## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright [Kyle Sanders]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
