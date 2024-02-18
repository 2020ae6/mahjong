# Mah

A Mahjong Solitaire Game

The  original open source version of many Mahjong games out there. Completely free, no ads, no tracking.

Play it [here](https://ffalt.github.io/mah/)  

build with html5, svg, angular

[![license](https://img.shields.io/github/license/ffalt/mah.svg)](http://opensource.org/licenses/MIT)
![test](https://github.com/ffalt/mah/workflows/test/badge.svg)
[![developer](https://img.shields.io/badge/developer-awesome-brightgreen.svg)](https://github.com/ffalt/mah)
[![known vulnerabilities](https://snyk.io/test/github/ffalt/mah/badge.svg)](https://snyk.io/test/github/ffalt/mah)
[![codebeat badge](https://codebeat.co/badges/021d3bc7-e512-473b-b99e-80e7650ba57f)](https://codebeat.co/projects/github-com-ffalt-mah-main)

## Features:

* 56 boards to play

* 12 different tile/piece image sets; light & dark

* 8 game backgrounds, themes; light & dark

* 3 difficulties

* Automatic save & restore of game state - start game today in the bus, finish at home. You can always start a new game on the top right.

* English, Deutsch, Nederlands, Português, русский, Español

## Build Config

The default game name is "Mah Jong", to change it 
* copy file `custom-build-config.json.dist` to `custom-build-config.json`
* edit the name in `custom-build-config.json` to your desired app name

## Development server

Run `npm run start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `npm run build` to build the project. The build artifacts will be stored in the `dist/` directory. Use `npm run build:prod` for a production build.

## Running tests

Run `npm run test` to execute the unit tests via [Jest](https://jestjs.io/).
