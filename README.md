# adopt-a-pet-react-router

Adopt A Pet is an app created to test my understanding of React Router. You should be familiar with object deconstruction in JavaScript. Specifically, this is a pet adoption website that allows users to view all the animals of a particular species and view the profiles of specific animals.

### App's functionality:

- The HomePage component responds to the browser’s current URL by displaying only pets of the species the user wishes to view.
- The PetDetailsPage page displays when the browser’s current URL includes a specific pet’s id.
- The PetDetailsPage displays data for the correct pet based on the id in the URL parameters’ values.
- When the user searches for a pet in the search bar, they are redirected to the SearchPage, which uses the query parameter called name to filter pets by name.
- When a user clicks a pet whose details are not available, they are redirected to a PetNotFoundPage.
- From the PetNotFound page, users can click “Go Home” button that will take them to the root path page.

### Learning objectives:

- Implement a router using React Router **(Route, RouterProvider, createBrowserRouter, createRoutesFromElements)**
- Add static and dynamic routing to the application **(Link)**
- Define and use query parameters to filter content **(useParams)**
- Implement a search feature **(useSearchParams)**
- Redirect users **(useNavigate)**

This app uses Mock Service Worker (MSW) to replicate the functionality of an external API. To use MSW, you’ll want to use Google Chrome and enable third-party cookies.

### Screenshots of finished app

Homepage
![Homepage](https://github.com/jogit82/adopt-a-pet-react-router/blob/master/Screenshot%202023-05-09%20at%205.18.46%20PM.png?raw=true)

Clicked on a pet to see more details
![Pet details page](https://github.com/jogit82/adopt-a-pet-react-router/blob/master/Screenshot%202023-05-09%20at%205.18.53%20PM.png?raw=true)

Search result automatically redirect to pet details page matching search query
![Search result automatically redirect to pet details page matching search query](https://github.com/jogit82/adopt-a-pet-react-router/blob/master/Screenshot%202023-05-09%20at%205.19.03%20PM.png?raw=true)

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
