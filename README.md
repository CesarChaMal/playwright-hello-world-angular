# Playwright Hello World Angular

This project is a simple Angular application integrated with Playwright for end-to-end testing. It demonstrates basic Angular features and Playwright testing capabilities.

## Features

- **Angular Application**: Includes routing and SCSS styling.
- **Unit Testing**: Configured with Karma and Jasmine.
- **End-to-End Testing**: Powered by Playwright.
- **Configurable Environments**: Separate development and production configurations.

## Prerequisites

Ensure you have the following installed:

- **Node.js**: Version 14 or higher.
- **npm**: Version 6 or higher.
- **Angular CLI**: Version 14.0.6 or higher.

## Getting Started

Follow these steps to set up and run the project:

### 1. Install Dependencies

Run the following command to install project dependencies:

```sh
npm install
```

### 2. Install Playwright Browsers

Playwright requires browser binaries to run tests. Install them using the following command:

```sh
npx playwright install
```

### 3. Run the Development Server

Start the Angular development server:

```sh
npm start
```

The application will be available at [http://localhost:4200](http://localhost:4200).

### 4. Run Unit Tests

Execute unit tests using Karma:

```sh
npm test
```

### 5. Run End-to-End Tests

Run Playwright tests:

```sh
npx playwright test
```

### 6. Build for Production

Generate a production build:

```sh
npm run build
```

The build output will be located in the `dist/playwright-hello-world` directory.

## Project Structure

- **src/**: Contains the Angular application source code.
- **e2e-playwright/**: Includes Playwright test files.
- **karma.conf.js**: Configuration for Karma unit testing.
- **playwright.config.ts**: Configuration for Playwright end-to-end testing.

## Resources

- [Angular Documentation](https://angular.io/docs)
- [Playwright Documentation](https://playwright.dev/docs)
- [Karma Documentation](https://karma-runner.github.io/latest/index.html)

## License

This project is licensed under the MIT License.