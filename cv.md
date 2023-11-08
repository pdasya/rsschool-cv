# rsschool-sv
## Full Name
Pashkova Daria
## Contact Information
* Email: dar.pashcovaa@gmail.com
* Telegram: @dariapashkovaa
* Phone number: +7 989 096-69-58
## Self-Introduction
Hey everyone! I'm Daria and I'm passionate about frontend development. I have some experience as Functional QA Engineer as well as freelance layout designer. For me RS School is an opportunity to improve both my hard skills by productive learning and sost skills by communicating with motivated people and recieve an experience on exciting projects. 
## Skills
* Basics: HTML, CSS, JavaScript, SASS
* Workflow: Git, Jira, Confluence
* Automation testing: Jest framework
## Code Examples
Example of functions ipToInt and intToIp that converts IP-address representation from decimal format with dots into a 32-bit decimal number and vice versa:

import chunk from 'lodash/chunk.js';

export const ipToInt = (ip) => {
  const ipInHex = ip
    .split('.')
    .map((octet) => Number(octet).toString(16).padStart(2, 0))
    .join('');

  return parseInt(ipInHex, 16);
};

export const intToIp = (int) => {
  const ipInHex = int.toString(16).padStart(8, 0);

  return chunk(ipInHex, 2)
    .map((octet) => parseInt(octet.join(''), 16))
    .join('.');
};

## Work experience
* Hangman game
In the game, you are invited to guess the hidden word by guessing letters one by one. For each incorrect letter, a part of the 'hangman' is drawn, and your task is to guess the word before the drawing is completed. Join us and enjoy playing 'Hangman' right now!

Technologies used: JavaScript, HTML, TailwindCSS, ViteJS

Link: https://pdasya.github.io/hangman-game/

* Candles store 

This website is developed using HTML, SCSS, and JavaScript, and it's also adapted for ease of use on various devices. Our candles and courses are art accessible to everyone, and we look forward to sharing it with you.

Technologies used: JavaScript, HTML, SCSS

Link: https://github.com/pdasya/candles

* Mind games 

"Mind Games" a collection of 5 console mathematical games for brain training: brain-even,
brain-calc, brain-gcd, brain-progression, brain-prime.

Technologies used: JavaScript

Link: https://github.com/pdasya/mind-games-project

* Cognitive bias project
The "Cognitive Biases in Programming" project is a study and informational resource dedicated to cognitive biases that newcomers encounter in programming. Cognitive biases are systematic errors in thinking that can lead to incorrect decisions, incorrect conclusions, and stress in the process of learning and software development.

Technologies used: HTML, CSS, SCSS

Link: https://delicious-bell.surge.sh/

* Music box portal 
Implementation project of a music website similar to Spotify. On the website, users can enjoy an endless stream of music from various genres and artists, create their own playlists, share them with friends, and even download tracks for offline listening. The service offers various subscription plans, including free access with ads and a premium subscription with additional features such as downloads and ad-free listening. Our website also has a mobile app compatible with Android and iOS devices, providing the convenience of listening to music anytime, anywhere.

Technologies used: HTML, SCSS

Link: https://pdasya.github.io/music-box-portal/

## Education
* 2023 - Master's degree - NUST MISIS, Moscow, Russia - Computational Material Science
* 2023 - Hexlet.io - Frontend Developer

## Languages proficiency
* English - Upper Intermediate B2 - Correspondence in English with partners, reading literature without a dictionary, oral presentations and consultations at exhibitions.
* Japanese - Beginer A1 - Understanding the meaning of information in advertisements in everyday life Writing about a familiar topic using familiar vocabulary and characters. 