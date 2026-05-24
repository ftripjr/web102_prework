# WEB102 Prework - *Name of App Here*

Submitted by: Frederic Triplett

**Kraken's Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **5** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding.
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:

<video src='kraken crowdfunding demo.mp4' title='Video Walkthrough of Kraken Crowdfunding Website' width='' alt='Video Walkthrough of Kraken Crowdfunding Website. Demo video shows the introduction section explaining the company background, the stats section with required metrics, and the Our Games section with three buttons. The user clicks each button and renders a list of funded games, unfunded games, and finally the entire library of games on Sea Monster Crowdfunding.' />

Video created with [OBS Studio](https://obsproject.com).


## Notes
Challenges 0-2 were a great orientation into the project and refresher for programming and web development again. Excited to get back to the IDE! 

Challenge 3 was enjoyable because I felt my HTML fundamentals returning after not using them in awhile. I enjoyed looking back through the JavaScript documentation to get familiar with the DOM again and using the template literals to manipulate the contents of the DOM. 

I was never good with arrow functions so I struggled a bit with Challenge 4, but after slowing down and wrestling a bit with `reduce()`, I feel more confident about using them in place of traditional functions. I understood their flexibility before, but I preferred using traditional functions - it felt more readable to me. 

I got stumped for a bit on challenge 5 due to a funny little error of adding the parentheses to the function name in the `addEventListener` method for my buttons. I was wondering what was wrong with my code for a good minutes before I realized that was the error. Glad I didn't restart my code from the end of Challenge 4!

Challenge 6 is feeling like the final stretch of the project. I feel all the things I learned in the previous lessons coming together. I'm using arrow functions to implement more complex statements for data validation! It's feeling really great learning more JavaScript. Getting more excited for the last lesson and the course!

Challenge 7 - I haven't gotten the chance to really get my hands dirty with React yet, so I hope I can learn from this lesson and the unit in the course. 

Destructuring? Something new! Can't wait to use a new concept. It seems similar to declaring multiple variables at once like I've seen Python do. I think I've seen that in C++ before too. I've never seen the spread operator `...` either, but it seems convenient enough. 

It is convenient, but it took some getting used to. At first, I tried to use destructuring to hold the first two games as 2 separate elements of `sortedGames`, but that kept giving an error about expecting a `,`. So I looked back through the lesson to properly use the spread operator and hold `otherGames`. 

Customizations and Feature Ideas  - 
I added some styling to the stats cards when they hover to show some basic interactivity on the webpage. I tried adding a search bar to find games based on queries, but I was unable to implement it. I'll try tackling it again sometime in the future but for now, I'm glad to have my web dev gears turning again. I would like to add a function the displays modals for each game and all their information on clicking the game cards in the games container. I think that and a navbar bar that sends users to the sections of the home page would be great starter features.

## License

    Copyright 2026 Frederic Triplett, Jr (ftripjr.dev)

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
