# Discomods

Discord CSS mods by Tech Norris. Custom themes, user tags, and profile styling for Discord clients that support custom CSS.

## What is here

**Synthesis.theme.css** (v1.2.1) - "Tech Norris - Main". The main theme. A complete BetterDiscord theme built around the RadialStatus addon, with Inter for UI text and Fira Code for code blocks. **synth.min.css** is the minified build of the same theme.

**main.css** - A terminal style neon theme. Near black background with neon green text in Share Tech Mono, plus custom online/idle/do-not-disturb/streaming status colors. It pulls in the user tag and popout snippets below.

**user-tags.css** and **usertags.css** - Custom tags that appear next to usernames in chat, including an author badge.

**donator-tags.css** - Special badge tags granted to specific user IDs.

**tag-animations.css** - Animations for the tags above: pulse, pop-in, and fall-and-bounce effects on hover.

**userPopouts.css** - Restyles user popouts to support USRBG profile banners (uses the MIT licensed snippet from the USRBG project).

**usrbg.css** - The USRBG user background database (about 4 MB, too large to preview on GitHub). This is the data file that maps users to custom profile banners.

**title.svg** - A small title graphic for the repo.

## How to install

These files are made for Discord clients that allow custom CSS, such as BetterDiscord, Vencord, or Replugged.

1. Download **Synthesis.theme.css** (or **synth.min.css** for the smaller build).
2. Drop it into your client's themes folder (in BetterDiscord: Settings, Themes, Open Themes Folder).
3. Enable it in the Themes settings page.

For **main.css** and the tag/popout snippets, add them through your client's Custom CSS editor instead. Load order matters: the snippets are imported at the top of main.css, so keep those import lines intact.

Note: Discord changes its internal class names over time. If parts of a theme stop applying after a Discord update, the selectors in these files may need refreshing.

## Screenshots

No screenshots yet. If you use one of these themes, a screenshot of it in action would be a welcome addition here.
