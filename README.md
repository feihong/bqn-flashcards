# Feihong's BQN Flashcards

## Installation

We want to install the BQN386 to display BQN glyphs inside Anki. Download [the
.ttf file](https://github.com/dzaima/BQN386/blob/master/BQN386.ttf) from GitHub.
Copy the downloaded file to your Anki user's media folder:

    cp ~/Downloads/BQN386.ttf ~/anki-data/User\ 1/collection.media
/_bqn386.ttf

Create a new note type called BQN Cloze based on Cloze. In the Styling tab, add
a new style:

```css
.glyph {
  font-size: 2em;
	font-family: bqn;
}
@font-face {
  font-family: bqn;
  src: url("_bqn386.ttf");
}
```

## Links

- [BQN keymap](https://mlochbaum.github.io/BQN/keymap.html)
- [Anki Manual: Installing
  Fonts](https://docs.ankiweb.net/templates/styling.html#installing-fonts)
- [Fonts for BQN](https://mlochbaum.github.io/BQN/fonts.html)
