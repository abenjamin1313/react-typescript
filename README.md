## Adding TypeScript to a ReactJS SPA 

TypeScript works well with many 3erd party JavaScript libraries. ReactJS is one of the most popular JavaScript libraries for building amazing fast user interfaces. TypeScript is not the default in ReactJS projects but it is extremely simple to integrate TypeScript into any ReactJS single page application.

## Installation

### 'npx create-react-app my-app --template typescript'
or
### 'yarn create react-app my-app --template typescript'

If you want to change a existing project over to TypeScript, first install the below:

### 'npm install --save typescript @types/node @types/react @types/react-dom @types/jest'
or
### 'yarn add typescript @types/node @types/react @types/react-dom @types/jest'

Now you have to rename any file that ends in .js with .tsx (e.g. src/index.js to src/index.tsx) and restart your development server! Type errors will show up in the same console, you will have to fix the type errors before you continue development or build your project.

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
