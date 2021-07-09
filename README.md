# notes

So I've taken your code, refactored it, and put it in the create-react-app framework, read below for more info on it

I've tried to add comments in the code to explain the things I've changed/refactored, feel free to make notes on the repo or msg me if you have further questions

to run this app you'll need to do `yarn` or `npm install`, I recommend yarn, if you don't have it installed already, check here: https://classic.yarnpkg.com/en/docs/install/#mac-stable

once all the packages are installed, you can run `yarn start` to run the script in the package.json file that will run the dev server, which will refresh automatically when you save your files

if you open the javascript console in your browser it will also show you some basic styling fixes that are built in to create-react-app

All the stuff you want to edit, essentially the whole app, is in src/App.js. You shouldn't need to modify anything else for the time being

I did some minor changes to the styles but there's still more to do to pretty it up, have a go at it.

## general coding advice

* don't be afraid of descriptive variable names, even if they get a little bit longer, write for the comprehension of your future self
* react state doesn't behave like a normal variable, don't do `this.state.var = update`, the correct way is `this.setState({ var: update })`
* when comparing two variables, always use === instead of ==, double equals is very rarely used because it has some weird side effects. More info: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness
* react state is only for data that changes, if you find yourself writing data in this.state that's never likely to change, there's no reason to put it in state
* look in the comments in App.js for more tidbits


# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
