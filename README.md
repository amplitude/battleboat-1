battleboat
==========

A JavaScript AI that beats humans at battleship.

Play the game here: [https://billmei.github.io/battleboat](https://billmei.github.io/battleboat)

If you've forked a copy of this repo or are playing around with the code on the `https://billmei.github.io/battleboat` page, please be nice and don't hack the `Stats` object. I'm using Google Analytics to collect info about the AI's win/loss percentage in order to improve the bot, so if you do look around, I kindly ask that you don't give it bad data. Thanks :)

If you want to try stuff out, run `setDebug(true);` in the console before doing anything. You'll also get access to some cool features.

Install Node & Yarn
===
1. Install [Node](https://nodejs.org/en/download/)
    1. Mac `brew install node`
    2. Windows - [Download](https://nodejs.org/en/download/)
    3. Verify installation run `npm --version`
2. Install [Yarn](https://classic.yarnpkg.com/en/docs/install)
    1. Mac `brew install yarn`
    2. NPM/Windows `npm i -g yarn`
    3. Verify installation run `yarn --version`

Run the project locally
===
1. `cd battleboat-1`
2. `yarn install`
3. `yarn start`

Rebuild on each change to `itly/index.js` and `battleboat.js`
===
You need to rerun `yarn build` each time any of the JavaScript is updated (Files: `js/**/*.js`). 

This can be automated running `yarn watch` in another terminal in addition to `yarn start`

Iteratively
===
There are some `TODO:`'s in `js/battleboat.js` showing where to add event tracking.
