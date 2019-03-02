# Bros. in Arms

### *A weirdly familiar HTML adventure*

**Bros. in Arms** was written to show [Mission Bit](https://missionbit.com) web development students a working example of an HTML adventure game.

You can play it at [http://johncip.github.io/bros-in-arms](https://johncip.github.io/bros-in-arms).

## HTML Games

You can make an adventure game using just HTML! It helps to think of your game as a fixed set of **states** (the pages) and the **transitions** (the `<a>` tags) that take players between them. For example:

* If you make a **dungeon crawler**, your states will be rooms in the dungeon, and your transitions will be movement between rooms.
* If you make a **choose your own adventure story**, your states will be parts of the story, and your transitions will be the choices that the main character makes.

One of your states will be a **start state** (probably your `index.html` file) and some will be **end states**: some game overs, and maybe a happy ending?

Note: [It's possible to do some incredible things with only HTML and CSS](https://codepen.io/jcoulterdesign/pen/NOMeEb).

## Tips & Tricks

I left lots of comments in both `index.html` & `assets/style.css`. Check out the source! Many comments show how I did fancy styling things like:

* using [CSS variables](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables) to name colors
* making the links look like 3D buttons, and using [`inline-block`](http://dustwell.com/div-span-inline-block.html) to lay them out side-by-side
* grabbing a custom font from [Google Fonts](https://fonts.google.com/)
* using the `<meta>` tag to [make emojis show up properly](https://www.kirupa.com/html5/emoji.htm)!

## Guess what?

These games are real-life instances of the computer science concept of **finite state machines**. FSMs show up often in both software and actual machinery -- other examples of FSMs are combination locks and elevators. 

Even modern, professionally-made video games sometimes use FSMs internally to [solve certain kinds of problems](http://gameprogrammingpatterns.com/state.html#finite-state-machines-to-the-rescue). And programmers often use a related tool called **regular expressions** to answer questions like "is this a valid phone number?"

FSMs can be described visually using [state diagrams](https://en.wikipedia.org/wiki/State_diagram). If you reach the end of **Bros. in Arms**, you'll see a link to the dungeon map, which is pretty close to being a state diagram.
