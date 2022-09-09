# 🏗️ Implement Global State Using React Context API

Using the `create-react-app` command-line utility to initialize a React application can take some time. Therefore, to save time throughout this module, we will create one React application and only replace the `src` file for subsequent activities as we work on them.

To the react application, follow these steps:

  1. In the command line, navigate to `22-State/01-Activities`.

  2. Run the command `npx create-react-app 00-practice-app`.

  3. After `create-react-app` has completed (which can take a few minutes) and before each activity, copy the `src` folder from the activity and paste it into [00-practice-app](../00-practice-app/).

  4. `create-react-app` now automatically uses the latest release of React, version 18. Due to several conflicting packages with React version 18, follow the steps below to ensure that all activities work as intended.

    * Delete the `package-lock.json` file and `node_modules` folder from the `client` directory.

    * Downgrade `react` to 17.0.2 inside of the `package.json` file.

    * Downgrade `react-dom` to 17.0.2 inside of the `package.json` file.

    * Downgrade `@testing-library/react` to ^11.1.0 inside of the `package.json` file.

    * Your `package.json` file should look like the following:

      ```js
      "dependencies": {
          "@testing-library/jest-dom": "^5.16.4",
          "@testing-library/react": "^11.1.0",
          "@testing-library/user-event": "^13.5.0",
          "react": "17.0.2",
          "react-dom": "17.0.2",
          "react-scripts": "5.0.1",
          "web-vitals": "^2.1.4"
      },
      ```

    * Run `npm install` to ensure that your project is now running React version 17.

## Activity

Work with a partner to implement the following user story:

* As a developer, I want to consume data and values from a single, global source across my entire React application.

## Acceptance Criteria

* It is done when a global state object has been defined with the following properties: an array of students with `name` and `major` properties.

* It is done when the provider is made available to child components.

* It is done when the associated test suite passes with zero failures when `npm run test` is run.

---

## 💡 Hints

When defining global state, which properties should be present? Should we care what type they are initialized with?

## 🏆 Bonus

If you have completed this activity, work through the following challenge with your partner to further your knowledge:

* Can an app have multiple providers? If so, are they allowed to be nested?

Use [Google](https://google.com) or another search engine to research this.

---
© 2022 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
