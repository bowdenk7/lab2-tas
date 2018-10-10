# Lab 2 - Try App Service

This lab will walk you through using an Azure App Service to host a simple express app. 

## Get the code
1. Navigate to [https://vscode-ppe.azurewebsites.net/tryappservice](https://vscode-ppe.azurewebsites.net/tryappservice).
This site will provision you a temporary App Service that you can play with.
2. Select **React** base template
3. Authenticate with one of the social providers
4. Wait for the App Service to provision (should take ~10 seconds). You should see something like this:
<img width="1186" alt="image" src="https://user-images.githubusercontent.com/820883/46752696-bcc27a00-cc72-11e8-939b-b264cb0f1846.png">
5. Click **Clone with VS Code** in Step 1 and follow the prompts to clone and open in VS Code.

## Your First Deployment
1. Open `src/App.js` and make a change.
2. Run `npm run build` and `npm run start` to test the app on [localhost](https://localhost:3001). 
3. When everything looks good locally, commit and push your changes using git
```
git add -A
git commit -m "<commit message>"
git push origin master
```

## Summary
This lab walked you through how you can deploy back-end apps to Azure App Service using VS Code. 

## All Done!
