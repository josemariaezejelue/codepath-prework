# Hello Website (blank)

This is a basic static HTML starter project you can build on however you like. No need to save. While you develop your site, your changes will happen 🪄 immediately in the preview window. You can upload assets like images or audio in `assets` to the left. The rest is up to you and your imagination.

## What's in this project?

← `README.md`: That's this file, where you can tell people what your cool website does and how you built it.

← `index.html`: This is the main HTML page for your site.

← `style.css`: CSS files add styling rules to your content.

← `script.js`: If you're feeling fancy you can add interactivity to your site with JavaScript.

![Glitch](https://cdn.glitch.com/a9975ea6-8949-4bab-addb-8a95021dc2da%2FLogo_Color.svg?v=1602781328576)

## You built this with Glitch!

[Glitch](https://glitch.com) is a friendly community where millions of people come together to build web apps and websites.

<<<<<<< HEAD
The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
[](gif1-l![](https://i.imgur.com/77T1Oio.gif)
ink-here)
![](gif2-lin![](https://i.imgur.com/WCStylH.gif)
k-here)
![](gif3-link-here)
![](gif4-link-here)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
I used Stack Overflow to undertand and write the syntax used in generating random numbers in javaScript. i also used it to edit my buttons and add borders to them

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The genesis of my challenges started with getting the tones to play for the right duration and at the right time. initially after i implemented the code that adds the tone to the buttons, i noticed that the tones overlapped each other when buttons are pressed successively. Therfore i had to reduce the tone volume as well as adjust my pauseTime,holdtime and wait time appropriately in order for everything to work in sync. I  also had issues with generating a random pattern for the game. initially after i implemented the randomPattern() method, i called it in my guess function which resulted in no activity when the start button is pressed to initiate the game. i kept editing my randompattern() method thinking the problem was from my for loop. After so many tries i decided to take a little break and upon getting back to the code i went over the program flow again and debugged that calling the randomPattern() function in my guess function was wrong. i was then able to fix the bug and get the program running again. Whlie working on adding extra buttons to my project, i had a problem with editing my 6th button and making it active when clicked. my first solution was to changed the number assigned to the button because i used the copy and paste feature to make things easier. Suprisingly the bug still persisted. Learning from my previous mistake i went over my code line after line and debugged that i had nested the statement to edit my button 6 under my button 5 by ommitting "}" to close the button 5 statement. i was able to correct this and get my project running fine and good. 
3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[Being a novice javaScript programmer, i have a lot a questions about the extent of editing one can implement with css and html while developing a web page. i had fun while engaging in this exercise because it allowed me to be creative and explore different editing features similar to an artist testing out colors on a canvas . i would really like to broaden my scope on the different features that can be implemented.i would also like to know if this game can be made accesible remotely?, how can it be made remote? what methods can be implemented in order to save a users progress? How can i integrate a database that stores the users information and personalizes the app to display features such as "welcome [username]"? How can a second player feature be implemented in such a way that two friends across the world can play against each other instead of against the game itself? I,m aware most of this processes occur in the backend and i am really excited to put that into practice.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If i had more time to work on this project, i would spend time studying and implementing my own audio files into the game rather than using that provided. I would also implement a feature that makes the background flash a red color when the user makes a wrong selection as well as accompany the flash with a tone that discerns error. I also think it would fun if each click generates an animation to match each click. I would also implement a countdown timer  betwen each succesive click to keep the user in check on their time management
## Interview Recording URL Link

[My 5-minute Interview Recording](https://drive.google.com/file/d/1juYKVMFDrcGzvHIqxiyiRv--FAVoPKyf/view?usp=sharing)


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
=======
- Need more help? [Check out our Help Center](https://help.glitch.com/) for answers to any common questions.
- Ready to make it official? [Become a paid Glitch member](https://glitch.com/pricing) to boost your app with private sharing, more storage and memory, domains and more.
>>>>>>> e9c0157ab763052f609a9f02c9e55c38381f6b43
