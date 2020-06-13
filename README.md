![CartManila](http://cartmanila.com/static/shopper/img/default_img/cart_manila_logo.png)

# Cartmanila (Seller Dashboard)
> This project will be used to provide portal for `cartmanila` sellers


## Requirements

node: `>= 8.10`
npm : `>= 5.6`

## Environments

| Environment              | Description                 |
|--------------------------|-----------------------------|
| `.env.development`       | For Development.            |
| `.env.testing`           | For Testing.                |
| `.env.staging`           | For Staging.                |
| `.env.production`.       | For Production.             |

### Development
```
REACT_APP_SITE_NAME=Seller Cart Manila
REACT_APP_BASE_URL=http://localhost:7770
REACT_APP_JWT_SECRET=efd867c142b7734fc7732f3bd19c7e9b
```


### Testing
```
REACT_APP_SITE_NAME=Seller Cart Manila
REACT_APP_BASE_URL=http://localhost:7771
REACT_APP_LOGIN=/login
REACT_APP_REGISTER=/register
REACT_APP_FORGOT_PASSWORD=/forgot-password
REACT_APP_RESET_PASSWORD=/reset-password
REACT_APP_RESEND_EMAIL=/reset-email
REACT_APP_ACTIVATE_ACCOUNT=/account/activate
REACT_APP_HOME=/home
REACT_APP_JWT_SECRET=acb5bb620882b0aeb03f9751227a924c
```

### Staging
```
REACT_APP_SITE_NAME=Seller Cart Manila
REACT_APP_BASE_URL=http://localhost:7772
REACT_APP_JWT_SECRET=b65fd4b29901c7d93c060fa6d5128ed4
```

### Production
```
REACT_APP_SITE_NAME=Seller Cart Manila
REACT_APP_BASE_URL=http://seller.cartmanila.com
REACT_APP_JWT_SECRET=fa2ebdef1ce7c7c864576b01d20c3df9
```

This project was
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
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

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `yarn build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
