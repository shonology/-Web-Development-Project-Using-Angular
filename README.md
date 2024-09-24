# First Front End Web Development Project Using Angular🌐🕸️

Welcome to OG Supermarket Website! This document will guide you through creating, running, and debugging your Angular application. 🚀

## 📦 Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- [Angular CLI](https://angular.io/cli) (install via npm)

npm install -g @angular/cli

🛠️ Creating a New Angular Project
To create a new Angular project, use the following command:
ng new my-angular-app
Replace my-angular-app with your desired project name. Follow the prompts to set up your project.

🚀 Running the Development Server
To run your project locally during development, navigate to your project directory and use:


cd my-angular-app
ng serve

After a successful build, open your browser and navigate to:
http://localhost:4200
Your app will be live! 🎈

🔧 Building the Project for Production
To create a production-ready build, run:

bash

ng build --prod
This command will generate the build files in the dist/ directory.

🔍 Debugging the Project
To debug your Angular application, you can use the built-in developer tools in your browser (usually opened with F12). You can set breakpoints and inspect variables as needed. 🔍

🌐 Running the Production Build Locally
To view your production build locally, follow these steps:

Navigate to the dist folder:
cd dist/my-angular-app

Use a local server. For example, with http-server:
http-server

Now, open your browser and go to:
http://localhost:8080
🎉 Your Angular app is now running locally in production mode!

🙌 Conclusion
You’ve successfully created, run, built, and debugged your Angular application! Happy coding! 🌟
