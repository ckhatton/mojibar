# Mojibar

A menubar app adaptation of [Emoji searcher](http://emoji.muan.co).

> ⚠️ **Note:**
>
> This is a detached fork of the original [Mojibar](https://github.com/muan), which has been archived. This fork is a little more up-to-date, with updated emojilib version and audits the other packages, though lacking an offical release at the moment.
>
> For now, you can just copy the `package.json` and `package-lock.json` files into the app. You can do this be first making sure the app is closed (`cmd`+`q` when the emoji selector is open) and then right-clicking on the app icon in Applications and then selecting "Show Package Contents", then root to `Contents > Resources > app`. Replace the two files there.

![screenshot](https://cloud.githubusercontent.com/assets/1153134/12583324/7756a38a-c485-11e5-9388-3b5c61743905.gif)

## Install

### OSX

Download the latest version for Mac on the [releases page](https://github.com/ckhatton/mojibar/releases) (and drag into your apps folder).

### Linux

Download the latest version for Linux on the [releases page](https://github.com/ckhatton/mojibar/releases) (and drag into your apps folder).

You can use it without installing any font, but the not all emoji will work, to get all emoji list you can try these approach:

1. **Color** – Follow [these instructions](http://stdio.tumblr.com/post/114082931782)
1. **Black and White** – Download this [emoji font](https://github.com/eosrei/emojione-color-font)

## Usage

`control` + `shift` + `space`
Open app.

`command/control` + `,`
Open preference (while window is open).

⬆️/⬇️/⬅️/➡️
Navigate between emojis.

`enter`
Copy emoji unicode char and exit. For example: `💩`.

`shift` + `enter`
Copy emoji code and exit. For example: `:poop:`.

`space`
Next page.

`shift` + `space`
Previous page.

`/`
Jump to the search field.

`esc`
Exit.

`command/control` + `q`
Quit Mojibar (while window is open).

## Build

:construction:

```sh
> git clone https://github.com/ckhatton/mojibar.git
> cd mojibar
> npm install
> npm start
```

## Built With

- [maxogden/menubar](https://github.com/maxogden/menubar)
- [muan/emojilib](https://github.com/muan/emojilib)

❤️
