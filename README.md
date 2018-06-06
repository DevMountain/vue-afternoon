# Vue Afternoon Project

**Note:** This project is intended to mimic a potential coding challenge from a company to a job applicant. You recently applied to Mountain Peak Software for a front end position and you recieved the following coding challenge:

-------------------------------------------------------------------
Applicant,

Thank you for your interest in our company and the front end developer position that we are currently trying to fill. At Mountain Peak Software, we pride ourselves on staying on the cutting edge of technology within the relm of web development. This means that we expect our entire dev team to be continuously learning.

We would like to build a portion of our website in VueJS and we are looking for a front end dev who can demonstrate that they can competently code in VueJS. If you don't know VueJS, or if you are new to VueJS, this is your chance to prove to us that you can learn quickly and adapt.

Requirements:

We want you to show a little of your fun/creative side and build us a app called "Battle Bots". You need to be able to display two main things:

1. A form to create a new battle bot with a name, attack value, and health value
2. A list of all battle bots that have been created

HINT: If you do not know how to set up routes using vue-router, then you should fake your routes by conditionally rendering either your create form or your list of robots (using v-if or v-show).

You should also be able to select two of your battle bots from the list and have them 'battle'--and by 'battle' we mean randomly select a winner and alert the winner's name. 

Here is an example of what is described above: https://joeblank.github.io/sample-vue-afternoon-project/ 

We do not care about styling, we assume you know how to use a little CSS. Your focus should be on the logic of this app. Only spend time to make things look good if you have extra time to do so.

NOTE: If you look at the source code, you are only cheating yourself. Work hard and learn something today that your future self will thank you for.

We expect to see your submission for this coding challenge before 5pm today. Good luck!

-- The Mountain Peak Software Team

-------------------------------------------------------------------


You are on the clock! Mountain Peak Software expects this VueJS project back to them by 5pm today! 

Start here:

* Mock up some light wireframes of the app you want to create (less than 5 mins).
* Draw out your component tree and figure out where you will store your data, like the list of battle bots. Your component tree could look something like this (less than 5 mins):
```
          App.js
          /   \
     Create   BotList
                \
                Bot
```
* If you need the `Create` component to add a new battle bot to the list of bots AND the `BotList` component needs to render the entire list of battle bots, which component should probably store the list of battle bots?

Dont forget about the VueJS docs: https://vuejs.org/v2/guide/

## Black Diamond

If you finish this project early, here is what you should do next:
1. Make your battle bot's health and attack editable.
2. Write an algorithm to decide the battle winner, no longer random.
3. Use a little CSS and make your app look good.
4. Figure out how to use vue-router to replace your fake routes.

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2017. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<p align="center">
<img src="https://devmounta.in/img/logowhiteblue.png" width="250">
</p>
