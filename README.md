# Project Overview
This project is the final part of an assignment aimed at developing a secure, feature-rich employee portal using the MERN stack. This portal is designed to prioritize security and usability, adhering to the key objectives:

- Secure data transmission using SSL, along with hashing and salting for password security.
- Static login tailored to employee access.
- Integration of DevSecOps practices using CircleCI for CI/CD and SonarQube for security checks.
- Additional features to enhance user experience and project uniqueness.

# Features and Implementation

### 1. Security
- SSL on Both Frontend and Backend: SSL certificates are implemented to ensure encrypted communication between the client and server.
- Password Hashing and Salting: For enhanced password security, passwords are hashed and salted. Additional security measures include using middleware for setting HTTP headers and applying rate limiting to prevent brute-force attacks.

### 2. DevSecOps
- Continuous Integration (CI): CircleCI is set up to automate testing and deployment processes, triggered with each push to the GitHub repository.
- Code Quality and Security (DevSecOps): SonarQube is integrated to enforce security standards and code quality. Advanced implementations such as credential management ensure that credentials are dynamically handled using a secret manager to avoid hardcoding in the codebase. Automated Testing using Newman in Postman to run API tests in the CircleCI environment, and SonarQube configured rules to detect hardcoded secrets and static login information has also been used.

### 3. Static Login Feature
- Static Employee Login: This portal supports a static login without a registration feature. This feature limits access to only employees with pre-assigned credentials, reinforcing security.

### 4. User Experience Enhancements
The portal is designed with the following user experience enhancements to make it more engaging to the user:
- Responsive Design: Built with the MERN stack, using React for the frontend. Styling frameworks such as Bootstrap ensure a responsive and visually appealing interface.

## Setup and Installation

To get started with this project:

1. Clone the Repository
2. Install Dependencies
3. Configure Environment Variables
4. Run the Application
5. Testing:
   - Automated Tests: Run tests using Newman in CircleCI.
   - Code Quality Check: Run SonarQube analysis to check for security issues.

## Deployment and Continuous Integration

The CI/CD pipeline is configured to run automatically upon each push to the repository, triggering the following steps:

- Build and Test: CircleCI performs build and unit tests.
- Code Quality and Security Check: SonarQube scans for code vulnerabilities.
- Deployment: Automatic deployment to a staging/production server if all checks pass.

## YouTube Link




# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

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

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
