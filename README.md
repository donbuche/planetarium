# Planetarium

![A screenshot of the app](preview.png)

An interactive Solar System made with Three.js, React and Vite.

## How to use

- Run `npm run dev` to initialize the app in your localhost.
- Run `npm run build` to build a distributable version of the app in a `/dist` fodler.

## Node version
This app uses Node version v18.14.1.

## Credits

This is a fork from [x3malmusic/react-3d-solar-system](https://github.com/x3malmusic/react-3d-solar-system). Please visit their Github page for further information about the original project.

## Known issues
The migration to Vite is still work in progress. 

There are some incompatibilites between the current version of `React` (18.2.0) and the `material-ui/core` library, so the Sidebar.jsx component has been mostly commented out until I figure out an alternative to Material UI.