# Electron PWA Wrapper

A sample wrapper app to package your Progressive Web App into a Desktop Application using [Electron](https://github.com/electron/electron).

Drafted for the future Desktop-version of my [Leasing Calculator](https://www.leasingrechnen.at) Web App using [React](https://github.com/facebook/react), [Redux](https://github.com/reactjs/redux), [Materialize.css](https://github.com/Dogfalo/materialize) and a lot of Offline-First love over at [leasingrechnen.at](https://www.leasingrechnen.at).

### Early development stage, please don't use for your projects yet.

## Features
- loading animation window for first boot
- handle connectivity issues natively in the wrapper

## Upcoming Features
- build witch electron-builder

## Wanna give it a try?
- clone repository, *cd* into the directory
- run `npm install` to get the dependencies
- run `npm run electron` to start the app
- check out */app/constants.js* for some options (e.g. setting your own URL)

## Building with [electron-builder](https://github.com/electron-userland/electron-builder)
Electron-PWA-Wrapper comes with *electron-builder* preconfigured for MacOSX (dmg, mas) and Windows (Appx + Portable).

### Preperations
- You'll need to 
-- look up your `package.json` and put in your App's values in the *build* section
-- and put all the required graphics into the `build` directory.
-- See the [electron-builder Docs](https://www.electron.build) for further details!
- run `electron-builder build` or `./node_modules/.bin/electron-builder build` (depending on your OS) to start the build.

### Build for OSX App Store
- Detailed Build-instructions coming soon!

### Build for Windows App Store
- Detailed Build-instructions coming soon!


## License
[GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html) - if you use it, we wanna see it!
