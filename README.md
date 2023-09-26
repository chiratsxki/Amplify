# Getting Started with Amplify

The Amplify project is a Notes service. Where you can share posts and images

Deployed a React application in the AWS Cloud by integrating with GitHub and using AWS Amplify. With AWS Amplify, you can continuously deploy your application in the cloud and host it on a globally available CDN.

- Authenticate a user with the Amplify CLI and libraries, leveraging Amazon Cognito, a managed user identity service.

- Added an API using the Amplify CLI and libraries. The API is a GraphQL API that uses AWS AppSync (a managed GraphQL service) which is backed by Amazon DynamoDB (a NoSQL 
  database).

- Used the Amplify CLI and libraries to create a storage service using Amazon S3.
  Finally, update the React app to enable image uploading, fetching, and rendering. 

## Usage

First you need to install Amplify CLI
```javascript
npm install -g @aws-amplify/cli
```
AWS Identity and Access Management (IAM) enables you to manage users and user permissions in AWS. The CLI uses IAM to create and manage services programmatically on your behalf through the CLI.

```javascript
amplify configure
```

We will need two Amplify libraries for our project. The main aws-amplify library contains all of the client-side APIs for interacting with the various AWS services
```javascript
npm install aws-amplify @aws-amplify/ui-react
```

To create the authentication service, use the Amplify CLI:
```javascript
amplify add auth
```

For the rest see `Learn more`
##
In the project directory, you can run:

```javascript
 npm start
```
Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.
```javascript
npm test
```
Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.
```javascript
npm run build
```
Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.


## Learn More

AWS Amplify: https://aws.amazon.com/amplify/ \
AWS API(GraphQL): https://docs.amplify.aws/cli/graphql/overview/ \
S3 bucket: https://docs.amplify.aws/cli/storage/overview/ 



