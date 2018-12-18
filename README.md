# Firestore CMS

A free, flexible and easy to use CMS for Google Firestore 🎉

This project is under development and not ready yet. This project primarily aims at providing an out of the box solution for managing your Firestore collections and documents.

## Installation

To install, add the package as a dev dependency:

`yarn add firestore-cms --dev`

## Configuration

After that, create a configuration file called `firestore-cms.config.js` in the root of your project.
See [Configuration](/configuration) on how to create a configuration file.

`./firestore-cms.config.js`

## Test & build

To test and debug, you can run a reloading dev server using:

`yarn firestore-cms start`

And use the following command to build a production build:

`yarn firestore-cms build`

This will generate a static website in `/firestore-cms-build`.

## License

[MIT](./LICENSE.txt)
