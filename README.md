## Steps invloved while uploading react app on github
1) First you will create a repository without read.md (cuz it will be automatically provided by react app)
2) You dont need to clone that repository yet just keep on working with local machine.
3) then you need to intall packages for react in some folder (later we will be pushing this folder to remote repository).
4) npm/npx will solve this problem for us. HOW?
5) you need to type a command "npx install -g creat-react-app" on terminal with in same folder/directory [It will basically create a react env at your local machine]
6) you will be needing that env at your local machine WHY? [cuz we need to do every task for testing purpose and other packges required for creating a react app]
7) What is the difference b/w YARN NPM NPX?
8) npm is the oldest version for managing all packages stuff for node, NPX is even smarter than npm especailly suitable when we are working on our local machine on the other hand YARN is the latest and the most powerful package management system. so, it will help you managing your packages while you are woking on github.
9) Now after consulting point number (3) you will need to create a project with create-react-app package.
10) you can do with the help of following command:
[create-react-app myfolder] --> remeber create-react-app wont allow you to capitalizae your project name aka the directory.
11) You need to execute another command within same directory before pushing [surge token] and copy it to clipboard for later work (make sure you must have installed surge on your local machine and you can find a little demo of intsalling and creating account with surge under link https://surge.sh).
11) When you done with that after some process time, you will have to push that directory to main repository that you hva ecreated recently by a traditinal way i.e. git init , git add . , git commit and push bla bla.....
12) When you are done whith that stuff, next task is to create workflow for your github repository where you have pushed your recently created react setup.
13) you can find contents in main.yml under workflow directory of this repostory.
14) Make sure you have to put your own key in main.yml file in under --token ${{secrets.YOUR_TOKEN_NAME}}
15) commit changes and run your provided domain under surge section in main.yml
# You are done now



This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
