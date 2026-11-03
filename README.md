# Happy Birthday, Kriti 🌻

A single-page birthday site. No build step, no installing anything — just open
`index.html` in a browser.

## Before you share it, do these two things

### 1. Set her birthday

Open `index.html`, search for `BIRTHDAY`, and change this one line
(it's near the bottom):

```js
const BIRTHDAY='2026-11-03T00:00:00+05:30';
```

Format is `YYYY-MM-DDTHH:MM:SS+TZ`. `+05:30` is India, `+05:45` is Nepal.
So for 14 March 1999, 9:30am India time:

```js
const BIRTHDAY='1999-03-14T09:30:00+05:30';
```

The counter counts **up** from a past date and **down** to a future one, and
the heading above it changes to match.

### 2. Add her photos

Put them in the `photos/` folder named `1.jpeg` through `8.jpeg`
(lowercase `.jpeg`, exact names). Photos 1–6 fill the slideshow,
1–8 fill the floating gallery. Missing ones show a placeholder, so it's fine
to start with just a few.

## Putting it on GitHub Pages

1. Create a new repository on GitHub (public).
2. Upload everything in this folder — `index.html`, the `photos/` folder, and
   both `.mp3` files. Keep the folder structure as it is.
3. In the repo: **Settings → Pages → Source: Deploy from a branch →
   `main` / `root` → Save**.
4. Wait a minute, then open `https://<your-username>.github.io/<repo-name>/`.

It has to be a **public** repo for Pages to work on a free account.

## Other things you can change

Everything is plain text inside `index.html`:

| What | Search for |
|------|-----------|
| The letter | `Dear Kriti` |
| The eight wishes | `wish 1` |
| Photo captions | `ss-cap` (slideshow) or `fpcap` (gallery) |
| Closing message | `you always stop` |
| Name in the opening and the big title | `Kriti` |

Background music is `birthday-song2.mp3`. To swap the song, replace that file
and keep the name.

## Good to know

- It's built for a phone first — that's where she'll most likely open it.
- Tap the opening screen to get in. Tap it once more if you want to skip ahead.
- The tree blooms when you tap it. The meter fills as you tap anywhere.
- Top right switches between the warm and cool themes.
- Music starts on its own where the browser allows it; otherwise tap the
  button in the bottom-right corner.
- Shortcuts on a laptop: `N` theme, `M` music, `C` confetti, `L` love,
  `I` infinity.
