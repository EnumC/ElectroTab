# ElectroTab: The electrifying new tab experience!
<img align="left" src="src/assets/images/favicon.png" alt="Favicon" width="24%">

## Built with [Angular](https://angular.io/) and [Firebase](https://firebase.google.com/) with styles and components from [MaterializeCSS](http://materializecss.com/). Current support for Chrome and Chromium.

**Master Status:** [![Build Status](https://travis-ci.org/dbqeo/ElectroTab.svg?branch=master)](https://travis-ci.org/dbqeo/ElectroTab)

**Develop Status:** [![Build Status](https://travis-ci.org/dbqeo/ElectroTab.svg?branch=develop)](https://travis-ci.org/dbqeo/ElectroTab)

## Discord Server
We use **Discord** for realtime collaboration (it's not just for gaming!) Our invite code is https://discord.gg/FnvQ6MG. **Everyone is welcome to join!**

## API Reference
Need help? View the documentation for the [ElectroTab API](https://github.com/dbqeo/ElectroTab/wiki).

## Current Features
 - **Support for Google Chrome/Chromium.** View the `chrome-extension` branch for the extension's source code.
 - **Modularity** New features can be added without disrupting any other modules! Users can easily enable and disable modules.
 - **Drag and Drop Interface** Widgets can be rearranged, resized, added, and removed. All changes are automatically synced with the Firebase database.
 - **Themes:** Change the color scheme! (That's about it for now, kind of sad.)
 - **Accounts:** Sign in with your Google or GitHub account, or make one using your email! All of your settings are saved with your account, no matter what device you use.

## Planned Features
 - **Support for Safari, Firefox, and Edge.** Shouldn't be too hard.
 - **Better Theme System** Customize everything, from fonts to icons. Save your themes and share them with your friends!
 - **Custom Widgets** Design your own widgets using HTML, CSS, and JavaScript! Submit them to a database where others can use your creations!

## Start Guide
 1. Clone or fork the git repository (https://github.com/dbqeo/ElectroTab).
 2. Ensure you have the latest version of node.js installed.
 3. Run `npm install`.
 4. Run `npm start`. This will serve the app to localhost:4200.
 5. Open your web browser (hopefully Chromium/Chrome) to localhost:4200. Enjoy :)

## Deploy Guide
 1. Run `ng build --prod --output-hashing=bundles --no-aot` -> Start new build with partial hashing and uglifyJS. This will ensure that the cache will be refreshed quickly with new updates.
 **Note:** The `--no-aot` flag is a temporary workaround that will be removed in the next update.
 2. Run `firebase deploy` -> Deploy new build to Firebase

 If you do not have access to our Firebase database, you can still deploy the build on your own website to test.

## Contributing
Please read our [Contribution Guide](CONTRIBUTING.md) for step-by-step instructions on how to contribute to ElectroTab.

## Branches
 - **master:** This is the release branch. Please do not submit any pull requests directly to master. This branch will frequently be built and deployed directly to all of our users.
 - **develop** This is the branch containing the latest semi-stable changes. Commits should not be directly created to develop. Instead, create a new branch or fork the repository.
 - **chrome-extension** This is the source code for the ElectroTab Chrome extension. It is an orphan branch, so pull requests may be created directly to this branch without problem. You are welcome to contribute however you like to this extension plugin.
 - **Upcoming Branches** Safari, Edge, and Firefox extension support.

## Messed Up?
 1. Run `git fetch --all`
 2. Run `git reset --hard origin/master`

 ## Want To Combine Commits(Squashing)?
  1. Run `git reset --soft HEAD~xxx` <- Replace xxx with an int of how many commits you want to squash
  2. Run `git commit -m "New message for the combined commit"`
  3. Run `git push origin +name-of-branch` <- BE CAREFUL. MAKE SURE you are pushing to the desired branch!!!

#### This project adheres to [Semantic Versioning](http://semver.org/).
