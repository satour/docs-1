---
lastUpdated: 2019-01-09
---

# Flow Deployment {#Flow Deployment}

Deploying flows to various environments and operating systems is a feature of Enebular.
This tutorial will do 'deploy a flow to Heroku'.(Time required 40 minutes)

To complete this tutorial you will need to understand how to create an [Asset(Flow)](./Introduction.md) and registered [Heroku](https://heroku.com).


## Table of Contents {#Table of Contents}
1. [Ready to deploy flow to Heroku](#ReadytodeployflowtoHeroku)
1. [Deploy Settings](#DeploySettings)
1. [Creating an app with the Heroku Button](#CreatinganappwiththeHerokuButton)
1. [Deploying](#Deploying)

## Ready to deploy flow to Heroku {#Ready to deploy flow to Heroku}

![flow](./../../img/GetStarted/FlowDeployment-flow.png)

Create flow (If flow has already been created, it can also be used).

![createFlow](./../../img/GetStarted/FlowDeployment-createFlow.png)

Click on the "Deploy" button to save the flow.

![deployButton](./../../img/GetStarted/FlowDeployment-deployButton.png)

## Deploy Settings {#Deploy Settings}

Configure your flow deployment by clicking on Deploy.

![otherEnvDeploy](./../../img/GetStarted/FlowDeployment-otherEnvDeploy.png)

Click on the "Add Connection".

![addConnection](./../../img/GetStarted/FlowDeployment-addConnection.png)

Select "Heroku" for "Select Connection Type".

Input a "Connection Name". Get the "Heroku API Token" from the Heroku settings screen.

![selectHeroku](./../../img/GetStarted/FlowDeployment-selectHeroku.png)

Click "Account Settings".

![accountSettings](./../../img/GetStarted/FlowDeployment-accountSettings.png)

Go to "Account" on the "Manage Account" page.

![account](./../../img/GetStarted/FlowDeployment-account.png)

Go to the API Key section and display the API Key with "Reveal".

![revealApikey](./../../img/GetStarted/FlowDeployment-revealApikey.png)

Copy the API Key into "Heroku API Token" and click "Save".

![inputAPIkey](./../../img/GetStarted/FlowDeployment-inputAPIkey.png)

Click created connection.

![createdConnection](./../../img/GetStarted/FlowDeployment-createdConnection.png)

We can create a Heroku app from the "Deploy to Heroku" button on the bottom.

![herokuButton](./../../img/GetStarted/FlowDeployment-herokuButton.png)

## Creating an app with the Heroku Button {#Creating an app with the Heroku Button}

Use the Heroku button to create the app. This step can be skipped for those who have already created one.

![loginHeroku](./../../img/GetStarted/FlowDeployment-loginHeroku.png)

After clicking on the Heroku button, if not logged in, log in with the Heroku login screen that appears.

![herokuSetting](./../../img/GetStarted/FlowDeployment-herokuSetting.png)

Heroku The Heroku app settings will be displayed.

![appName](./../../img/GetStarted/FlowDeployment-appName.png)

Set the App name.

![userName](./../../img/GetStarted/FlowDeployment-userName.png)

Set the USERNAME and PASSWORD to be used for login after the enebular Node-RED has been created.

![deployApp](./../../img/GetStarted/FlowDeployment-deployApp.png)

After confirming the settings press the "Deploy" button. ¥

After confirming the settings click the "Deploy" button. If you haven't added your credit card information to heroku before, the following modal will show up.
Using the Enebular app is free so one needs to not worry about Enebular charging.

![creditCard](./../../img/GetStarted/FlowDeployment-creditCard.png)

After registering the credit card, heroku will start setting up the app.

![creatingHeroku](./../../img/GetStarted/FlowDeployment-creatingHeroku.png)

The app is being created...

![doneCreated](./../../img/GetStarted/FlowDeployment-doneCreated.png)

Once it has been created click the "View" button to check it.

![agentOnHeroku](./../../img/GetStarted/FlowDeployment-agentOnHeroku.png)

You'll be asked to provide the USERNAME and PASSWORD to log into the enebular Node-RED, so enter those that you set above.

## Deploying {#Deploying}

With the connection saved and Heroku selected as a "Connection Type", a list of the apps on the Heroku account should be displayed. From here, select the Heroku application you just created and press "Deploy".

![appList](./../../img/GetStarted/FlowDeployment-appList.png)

Wait a moment for the "Deploy Added" to be displayed to confirm the app has been deployed.

If you check the Heroku app you will be able to see that the flow has been deployed.

![openApp](./../../img/GetStarted/FlowDeployment-openApp.png)

Check the Heroku app to see if the flow has been deployed.

![confirmDeployed](./../../img/GetStarted/FlowDeployment-confirmDeployed.png)

## Well Done! {#Well Done!}

You can now deploy flows to other services with enebular.