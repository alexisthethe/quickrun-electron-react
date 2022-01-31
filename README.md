# quickrun-electron-react
Quickrun project with Electron and React

## Documentation

This quickrun project has been created from the Medium article [Building an Electron application with create-react-app](https://www.freecodecamp.org/news/building-an-electron-application-with-create-react-app-97945861647c/).

## Setup

Install NPM dependencies:
```
npm install
```

## Development

In the project directory, you can run:

* `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

* `npm run dev`

Runs the app for Electron development mode.\
The command run the React app in the backrgound and display it in an Electron window.

Same as `npm start`, the page will reload when you make changes.\
You may also see any lint errors in the console.

## Build for production

1. `npm run make`

Build the react project using `npm run build` and build the electron wrapper with `electron-packager`

2. `npm run package`

To package the project in a `.tgz` tarball
