# DOWNstream For Electron [![Build Status](https://travis-ci.org/castlabs/downstream_electron.svg?branch=master)](https://travis-ci.org/castlabs/downstream_electron)

## Summary

DOWNstream is an open-source plugin for use with Electron allowing encrypted MPEG-DASH streams to be safely downloaded and stored locally on a user’s Windows or Mac computer.

## castLabs Electron Release for Content Security

To simplify the use of Widevine DRM and allow protected playback of offline content within Electron castLabs has created a fork with support for Widevine CDM installation, Verified Media Path (VMP), and protected storage of offline licenses. Such a release is installed by the default npm package scripts, see [Development](#development) and [Build](#build) sections below.

More information is available here:

https://github.com/castlabs/electron-releases

## Development
1. `npm install`
2. `npm start`

## Build
1. `npm install`
2. edit `index.js` and change line to use `downstream-electron` from `dist` folder
3. edit `examples/main/index.js` and change line to use `downstream-electron` from `dist` folder
4. `npm run build`
5. `npm start`

## Documentation 
Documentation is available publicly at 
https://castlabs.github.io/downstream_electron/

1. `npm run jsdoc`
2. Open `jsdoc/index.html` in any browser
3. If you want to generate docs with private methods run `npm run jsdoc_prv`

## ESLint 
1. `npm run eslint`

## Debugging in intellij / webstorm
1. Create new node.js configuration
2. Node interpreter: `/node_modules/.bin/electron`
3. Javascript file: `index.js`

## More information
https://castlabs.com/open-source/downstream/

## License
Copyright (C) 2017 Castlabs GmbH.
Licensed under the Apache License, Version 2.0: http://www.apache.org/licenses/LICENSE-2.0
