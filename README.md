# Azure Node.js sample app

For further info: <https://www.freecodecamp.org/news/how-to-deploy-your-super-cool-node-app-to-azure-from-github-47ebff6c5448/>

### 1. File structure

You must have a `package.json` with npm start script inside of it, a `web.config` which is saying iis, that this is a node application and last but not least the `server.js` file, which is the entry point for your node app.

### 2. Save code to GitHub repo

In the second step, upload your node app to a repository on GitHub or a similar webservice.

### 3. Deploy from GitHub

Go into Azure portal and deploy your app from your GitHub repository in the deployment center.

### 4. Compile application

If you have to compile your app from a script like `npm run compile` to build all assets and codes for productive mode, go to console in azure portal and run your build command.

### 5. The final hack

Go to the application settings and add the variable `WEBSITE_NODE_DEFAULT_VERSION` with value `8.9.4`. Ready! :rocket: