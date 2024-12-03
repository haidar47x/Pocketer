## Pocketer

A user-friendly extension to manage your [Pocket](https://getpocket.com) bookmarks and read later items inside Google Chrome.

<br>
<p align="center"><img src=".github/screenshot.png" alt="Screenshot"></p>
<br>

You can download it from [Chrome Web Store](https://chrome.google.com/webstore/detail/in-your-pocket).

### Development

You need to [download](https://nodejs.org) and install `npm` on your machine. Clone the repository and install the dependencies using `npm install`.

* `npm run watch`: Packs the source using development config and runs webpack in watch mode.
* `npm run build`: Packs the source using production config.
* `npm run clean`: Wipes out the output folder.
* `npm run build`: Wipes out the existing packed source code and re-build.
* `npm run pack`: Creates a clean build and zips it.