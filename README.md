Step-by-step to install in the end

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

STEP-BT-STEP

1. Open cmd as admin and run `npm i` in the root folder. Do the same in the folders 'frontend' and 'backend'.
2. In this project, I'm using a bootstrap template from [Bootswatch](http://www.bootswatch.com). If you want, you'll need to add a template manually. In person, my template is [Litera](http://www.bootswatch.com/litera). Otherwise, use default Bootstrap and correct the importation in `index.js` file
3. Now, you'll need to set up your MySQl database. Basicaly, run the query present in '_database/query'. This will create the database, and the respectives tables. Attention to configure your connection string of the file 'backend/Index.js' with yours specifics values.
4. Finally, run `npm start` in root to run the front and the backend. Hope you like :)

And rember, this is in development yet. I have no hurry to finish this project. This is for academic purposes only.