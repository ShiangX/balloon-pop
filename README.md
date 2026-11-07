# Balloon Pop

A letter typing game for a 5-year-old. A balloon with a letter floats up and the matching key lights up on the on-screen keyboard. Pressing that key pops the balloon. Confetti flies, a picture appears, and a voice says "B! B is for bear." Every pop earns a star, and every 10 stars starts a party.

There is no timer, no score that goes down, and no game over. A wrong key makes the balloon wiggle. After three wrong keys the voice says "Look for B!" and the right key hops.

## Play

Open `index.html` in Chrome or Safari on a laptop. Click Play and the game goes full screen. Press Esc to leave full screen.

The speaker button in the top corner mutes the sound and voice. On a tablet with no keyboard, tapping the glowing key on screen works too.

## How it's built

`index.html` holds everything: the page, styles, and script. It loads the Fredoka font from Google Fonts and nothing else. The voice uses the browser's built-in speech, and the sounds come from the Web Audio API, so there are no audio files.

The letter words and pictures live in the `LETTERS` table at the top of the script. Edit that table to change a word.
