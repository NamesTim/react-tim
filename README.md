# Hey there, I made this repo to document my journey learning ReactJS.
To follow along, be sure to:
1. install NodeJS add it to your path/environment. https://nodejs.org/en/download/
2. install react globally(not a good practice, but for simplicity just do this for first timers). ``
3. undestand basic JS.
4. have an idea of commonJS vs ES modules and how each is implemented.

# Typical JS runtime/build enviroment
1. package manager, `npm`, `yarn`, `vite` or `nix` npm and yarn are the most common. nix is very powerful, highly customizable, vite is fast, very fast.
2. bundler e.g `snowpack`, `parcel`, `webpack`
3. compiler e.g `babel`, babel performs some polyfill so your code is compatible with most browsers

## Where I'm at. Completed items are marked, those I'm yet to master are not.
- [x] components
- [x] props
- [x] state
- [x] hooks
- [ ] redux 

# Edit, 10/10/2022.
React is a library that runs on the Node runtime The problem it seeked to solve at the time of it's creation was to brng reusable UI components that can persist state to web applications.
Two packages that facilitate this in the library are:
  i. react: creates the views/components
  ii. react-dom: renders the views you created in the browser.

You can choose to use the template when creating your app, or, in a true minimalist style, create and bundle from scratch using your own choice of build tools and add other tools like grunt/gulp to your dev pipeline. read more [here](https://medium.com/edonec/how-to-create-a-react-app-without-create-react-app-aa0b5adba4cd).

If you decide to use a template: run this in your CLI, you can rename my-app to whatever you like, `npx create-react-app my-app`, `cd` into the `my-app` directory and run `npm start`. 

If you made it this near:smile:, then congrats, if not, tell me what you don't get so we can hack together. NOTE that this is not production ready.
