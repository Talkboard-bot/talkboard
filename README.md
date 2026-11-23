# Talk Board (free web app)

A free talk board for autistic children and others who are learning to communicate.
It works in any modern browser on tablets, phones and computers. Once opened, it keeps
working without internet, and it can be added to the home screen like an app.

- No sign-up, no ads, no tracking. Nothing is sent anywhere.
- Everything (words, photos, passport, settings) is saved in the browser on that device.
  Use **Settings > Download backup** to keep a copy or move it to another tablet.

## Put it online for free

These files are a complete static website. Pick one option.

### Option 1: Netlify Drop (about 2 minutes, no coding)
1. Unzip this folder.
2. Go to https://app.netlify.com/drop and sign up for a free account.
3. Drag the unzipped `talkboard` folder onto the page.
4. Netlify gives you a link like `https://something.netlify.app`. In Site settings you can rename it,
   for example `https://talkboard-free.netlify.app`.

### Option 2: GitHub Pages
1. Create a free account at https://github.com and a new **public** repository, e.g. `talkboard`.
2. Click **Add file > Upload files**, drag in all the files from this folder, and click **Commit changes**.
3. Go to **Settings > Pages**, set Source to **Deploy from a branch**, Branch **main**, folder **/ (root)**, and Save.
4. After a minute the app is live at `https://<your-username>.github.io/talkboard/`.

## Install it on a tablet
- **Android (Chrome):** open the link, tap the menu (three dots) > **Add to Home screen** or **Install app**.
- **iPad / iPhone (Safari):** open the link, tap **Share > Add to Home Screen**.
- To keep a child in the app: Android **screen pinning**, or iPad **Guided Access**.
- Voices come from the device. Check Android Settings > Text-to-speech, or iPad Settings > Accessibility > Spoken Content > Voices.

## Files
- `index.html` the whole app
- `symbols.json` the built-in pictures
- `sw.js` lets it work offline
- `manifest.webmanifest`, `icon*.png`, `icon.svg` let it install with an icon

## Licence
The app's code is free to use, share and change under the MIT licence (see LICENSE).

The built-in pictures (in `symbols.json`) come from two free sets:
- [Mulberry Symbols](https://mulberrysymbols.org), an AAC symbol set, licensed [CC BY-SA 2.0 UK](https://creativecommons.org/licenses/by-sa/2.0/uk/).
- [OpenMoji](https://openmoji.org), the open-source emoji project of HfG Schwäbisch Gmünd, licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), used where Mulberry has no symbol.
If you change and share those pictures, share them under the same licence and keep this credit.

## Vocabulary
About 500 words on 19 pages. The 48 core words stay in fixed places. The core lists draw on research
on the words young children and AAC users say most often (Banajee, DiCarlo & Stricklin 2003;
Marvin, Beukelman & Bilyeu 1994; Project Core's Universal Core). Topic pages add chat phrases,
feelings, people, body, food, drinks, play, places, school, home, clothes, animals, actions,
describing words, time and weather, going out, and care.
