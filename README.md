# firefox dots
A collection of my custom Firefox styling files that removes almost all roundness for Firefoxes UI.
The userContent.css is heavily inspired by https://www.youtube.com/@dacctal / https://git.symlinx.net/daccfiles/tree/.config/browser_stuff.

## How to install

 1. Open Firefox and navigate to `about:config`.
 2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to `true`.
 3. Navigate to `about:profiles` and locate your active profile's root directory.
 4. Create a folder named `chrome` inside the profile directory if it doesn't already exist.
 5. Copy `userChrome.css` and `userContent.css` into the `chrome` folder.
 6. Restart Firefox to apply the changes.

## License

This project is licensed under the GNU General Public License v3.0 (GPL-3.0). See LICENSE for details.
