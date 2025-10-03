# My Node App

This is a basic Node.js application that demonstrates a CI/CD pipeline using GitHub Actions.

## Project Structure

```
my-node-app
├── .github
│   └── workflows
│       └── ci-cd.yaml
├── src
│   └── index.js
├── tests
│   └── index.test.js
├── dist
├── package.json
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (version 18 or higher)
- npm (Node package manager)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/your-username/my-node-app.git
   cd my-node-app
   ```

2. Install the dependencies:
   ```
   npm install
   ```

### Running the Application

To run the application, use the following command:
```
node src/index.js
```

### Running Tests

To run the tests, use the following command:
```
npm test
```

### CI/CD Pipeline

This project includes a CI/CD pipeline defined in `.github/workflows/ci-cd.yaml`. The pipeline will automatically run on pushes and pull requests to the `main` branch, executing the build, test, and deployment steps.

### Deployment

The application is set up to deploy to GitHub Pages. Ensure that the `publish_dir` in the CI/CD configuration points to the correct build output directory.