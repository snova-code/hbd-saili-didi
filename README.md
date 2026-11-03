# Happy Birthday, Kriti 🌻

A single-page birthday site. No build step, no installing anything — just open
`index.html` in a browser.

## Before you share it

### Add her photos

Put them in the `photos/` folder named `1.jpeg` through `8.jpeg`
(lowercase `.jpeg`, exact names). Photos 1–6 fill the slideshow,
1–8 fill the floating gallery. Missing ones show a placeholder, so it's fine
to start with just a few.

That's the only thing left to do — her birthday is already set.

### Settings (already filled in)

Near the top of `index.html` there's one small block with everything you might
want to change:

```js
const DEFAULT_THEME = 'sunlight';                  // or 'aurora'
const BIRTHDAY      = '1996-11-03T00:00:00+05:45'; // Nepal time
```

**`DEFAULT_THEME`** is which of the two looks the page opens in — the warm
`'sunlight'` one or the cool `'aurora'` one. Change the word, save, done. The
toggle in the corner still works either way; this only sets the starting side.

**`BIRTHDAY`** is set to 3 November 1996, Nepal time. The format is
`YYYY-MM-DDTHH:MM:SS+TZ` — `+05:45` is Nepal, `+05:30` is India. The counter
counts **up** from a past date and **down** to a future one, and the heading
above it changes to match.

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

## The background

It's a cosmos drawn live on a canvas — nebulae, two spiral galaxies, four
depths of stars, shooting stars, and planets that drift along on their own
with moons circling them. The layers all move at different speeds as you
scroll, which is what gives the depth, and they follow the pointer slightly
on a laptop.

Nothing to install or configure. It recolours itself when you flip the theme,
goes still if the device asks for reduced motion, and uses fewer, smaller
pieces on phones so it stays smooth.

## Good to know

- It's built for a phone first — that's where she'll most likely open it.
- Tap the opening screen to get in. Tap it once more if you want to skip ahead.
- Tapping anywhere launches a shooting star from that spot.
- The tree blooms when you tap it. The meter fills as you tap anywhere.
- Top right switches between the warm and cool themes.
- Music starts on its own where the browser allows it; otherwise tap the
  button in the bottom-right corner.
- Shortcuts on a laptop: `N` theme, `M` music, `C` confetti, `L` love,
  `I` infinity.
