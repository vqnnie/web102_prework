# WEB102 Prework - Sea Monster Crowdfunding
Submitted by: Vanessa Phan

Sea Monster Crowdfunding is a website for the company Sea Monster Games that displays information about the games they have funded.

Time spent: 18 hours spent in total

## Required Features

The following **required** functionality is completed:

* [X] The introduction section explains the background of the company and how many games remain unfunded.
* [X] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [X] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [X] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [X] Multiple CSS styling elements to enhance the website's appeal, including styling elements for the search bar and navbar.
* [X] Fully functional search bar that allows users to search for a specific game.
* [X] Fixed navbar at the top of the screen for users to jump to the games section.
* [X] Scroll animation effects using Intersection Observer to reveal content with a fade-in effect.
* [X] Custom hover effects on game cards and buttons.
* [X] Clean and modern user interface with a gradient background and box shadows.

## Video Walkthrough

Here's a walkthrough of implemented features:

<img src='https://i.imgur.com/MUGNuq5.gif' title='WEB 102 Prework Video Walkthrough' width='' alt='WEB 102 Prework Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with LiceCap!  
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

Describe any challenges encountered while building the app.

I found Challenge 3 and Challenge 4 the most challenging and I had a hard time implementing the addGamesToPage function and the .reduce() method for the totalBackers and totalRaised. I am familar with the .filter() method as I learned how to implement it in AP Computer Science Principles, but I have never heard of .reduce() so it was completely new to me. Additionally, in the beginning stages of this pre-work, I made a ridiculous mistake and spent a while to debug it. It took me about 30-45 minutes just to find out that the error in my code was because I had a typo when I was calling an event listener.

I also had trouble getting the Live Server to work. I think this was my biggest struggle, as well as getting output in my console.log. I am too familar with the VSCode website so switching to the application was a challenge in itself. The VSCode website allows live previewing in the same tab, but the application requires me to check for previews in a separate tab as far as I know. I spent way too long figuring out how to get output to my console.log because at first, I thought it would be printed in my terminal on VSCode, but when I Googled it up, Google told me that I needed to inspect my Live Server and access the console.log there. So that was exactly what I did. However, there was no output in my console.log. I searched up why that might be the case, then I realized that I implemented my console.log inside the function and I would only be able to see my output if I activated the event listener. So I tried to click the buttons for unfunded games and funded games, but nothing worked in my favor. It took a lot of trial and error before I thought about moving the console.log outside the function, then defining a constant variable that filtered the function itself and calling it using console.log. Finally, I could see the output in my console.log. But it took so long.

Overall, if I were to consider the entire pre-work as a whole, I would say that my biggest challenge was getting the secret keys for the next pre-work steps. I did not expect obtaining the secret keys to be so hard, but it was, and it made me take longer than I intended to on the pre-work. Nonetheless, it was a fun experience and I felt lke the secret keys were a really unique feature to the pre-work. 

## License

    Copyright 2025 Vanessa Phan

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
