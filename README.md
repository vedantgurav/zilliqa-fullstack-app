# Getting Started with Zilliqa Fullstack App

The Zilliqa Fullstack app is a full-fledged application on the Zilliqa Blockchain for listing and renting houses.

## The technology

- [Create React App](https://github.com/facebook/create-react-app) for the frontend.
- [Tailwind CSS](https://tailwindcss.com) for styling.
- The `/src/scilla` contains the Scilla contract. We can use the [Zilliqa JavaScript Library](https://github.com/Zilliqa/Zilliqa-JavaScript-Library) or the Scilla Online IDE to deploy the contract. Please add the contract address in `REACT_APP_SMART_CONTRACT_ADDRESS` variable in a `.env` file in the root of the project.

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
