# Acorn for a Piwigo App

[Piwigo](https://piwigo.org/) is an open source photo management software to manage, organize and share your photos easily on the web.


## Deploy the Piwigo App 

You can deploy the Piwigo app on the Acorn SaaS Platform with following simple steps.

1. Login into the [Acorn SaaS Platform](https://beta.acorn.io/) using the Github Sign-In option with your Github user.
2. Select the "Create Acorn" option.
3. Choose the source for deploying your Acorns
  * Select "From Acorn Image" to deploy the sample Flask Application and select its Image
  * Provide any random name such as `piwigo-app` and keeping Project's default Region, type in the below Acorn image and choose Create 
    ```bash
    ghcr.io/infracloudio/piwigo-acorn:v#.#.#-#
    ```
4. Now the sample App is provisioned on Acorn SaaS Platform and is available for 2hrs. Upgrade to pro account to keep it running longer.
5. Once the Acorn is running, you can access it by clicking the Endpoint or the redirect link.

## One-Time Piwigo Installation

Once the Piwigo application is deployed and running, we need to perform a one-time installation of the app by providing the MySql DB credentials.
Fill in the below details :

host : db
user : piwigo
password : secret-password
db_name : piwigo

Note : user, password and db_name are configurable and can be provided as arguments while running the Acornfile.

Fill in the Administrative Details as per your preference.

## Acorn Piwigo App Details

The Acorn Dashboard is integrated with multiple features such as Events, Logs, Details and accessing the Shell of the Application. Details include the CPU, Memory, Network, Latency, Requests and Errors for the Application.

Explore various available options by clicking the Menu option on your Acorn App.

For more details on using the Acorn Dashboard, check this link - [https://beta-docs.acorn.io/getting-started#exploring-the-acorn-dashboard](https://beta-docs.acorn.io/getting-started#exploring-the-acorn-dashboard) 

## What next?
After deploying you can edit the Acorn Application or remove it if no longer needed.

1. Click the Edit option to edit your Acorn's Image. Toggle the Advanced Options switch for additional edit options.
2. Remove the Acorn by selecting the Remove option from your Acorn dashboard.

