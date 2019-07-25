# Home Exercise

This is a frontend exercise using React.js to build a small timer app (we called it Rat-a-Timer - just for fun!)
Ideally it should look like the design:

![design](https://raw.githubusercontent.com/tda-soft/react-ratatimer-exercise/master/design.png)

## Objective
1. There big timer number will show the timer running (when started) in three groups of time: minutes, seconds & milliseconds.
1. There will be a big button that will toggle between start & stop - it will (as expected) start & stop the timer.
1. There will be a smaller button that will log the current time in the timer in a table below.
1. The table will show the logged time and will allow to add a small note for each logged time.
1. There will be a remove button for each row on the table (Ideally it will only be shown when hovering the table row).
1. Clicking on the remove button will remove only the single row from the table.

_Ideally, this should take around a day to finish, but let us know how much time you spent so we can calibrate our expectations!_

## Hints / Tips
- Ideally, you'll use something like `redux` to store the logged time & notes, but the exact implementation is up to you!
- It doesn't have to look pixel perfect with amazing animations, but we do care a lot about UX and usability.
  - Paying attention to details like padding, alignment, and cursors are appreciated!
  - Ideally your components would fit the grid, to make layout easy for your users.
  - Pick any UI toolkit (Bootstrap, Material, etc.), but try to make everything look consistent.
  - Handle the UX edge-cases! For example, what happens when a user resizes the screen to be smaller? Ideally a user would still be able to access all the components they placed. 


## Getting Started
- Clone or download the repository - do not fork!
- Run `npm install` & `npm start` Your browser should open up a skeleton React app. You can edit any file in `./src` and in most cases the website will hot-reload.
- All the assets already located at `./public`
- You can use the [digital-7](http://allfont.net/download/digital-7/) font for the timer & [Font Awesome](https://fontawesome.com/) for the icons.
- When ready submit your result in one of the following methods:
  - Create a new repository under your own account and send us link
  - Email us a zip file with the source code

For more info, you can check out https://github.com/facebook/create-react-app

## Requirements
- The code must compile with no errors.
- There should be no errors in the browser console.
- It should work smoothly with Google Chrome.

## Bonus
- Create a reset button that will clear the logged table & reset the timer to it's initial state.
- Don't allow logging the exact same time twice.

## Questions?

Don't hestitate to reach out to us if you have any q's :)
