[Piwigo](https://piwigo.com/) is an open source photo gallery software to manage, organise and publish your digital content. It is a Digital Asset Manager (DAM) helping you centralise all your digital media (photos, logos, videos, documents, etc.) in one web portal. Today, we will explore how you can deploy your own Piwigo photo gallery website using Acorns. 

Acorn is an app platform that simplifies building, sharing and deploying containerized apps. With Acorn, you can encapsulate your entire application and its dependencies in a single file known as an Acornfile. This Acornfile enables to package your application into an OCI container image and deploy on cloud-native environments. 

[Acorn Cloud Platform](https://beta.acorn.io/) lets you run your acorns in free [sandbox environment](https://docs.acorn.io/sandbox). You can also share this nifty artifact with a link, making it a breeze for you to deploy with just a single click into your very own sandbox environment. You can run your Acorns as often as you like for upto 2hrs to evaluate and experiment your application. If you wish to [run your Production workloads](https://docs.acorn.io/aws/overview), upgrade to a teams and enterprise plan to deploy and manage applications in your AWS account.

If you are looking to get started on the Acorn Platform and give the Piwigo application a whirl, just hit that link below and have a peek!

[![Run in Acorn](https://beta.acorn.io/v1-ui/run/badge?image=ghcr.io+infracloudio+piwigo-acorn:v13.8.0-0&ref=aashimodi14)](https://beta.acorn.io/run/ghcr.io/infracloudio/piwigo-acorn:v13.8.0-0?ref=aashimodi14&name=piwigo-sample-app)

To learn how to write your own Acornfile to deploy Piwigo or further customise to integrate in your webiste, follow along:

> _Note: Everything shown in this tutorial can be found in [this repository](https://github.com/infracloudio/piwigo-acorn)._

## Pre-requisites
- [Acorn CLI](https://docs.acorn.io/installation/installing)
- Github account to sign up for the Acorn Platform.

## Acorn Login
Login to the [Acorn Platform](http://beta.acorn.io) using the Github Sign-In option with your Github user.

![acorn-login-screen](https://necessary-creativity-bc071c3082.media.strapiapp.com/login_screen_6fde8a8572.png)

After the installation of Acorn CLI for your OS, you can login to the Acorn platform.

```
acorn login beta.acorn.io
```

## Deploy your Piwigo application
We will be deploying a sample photo gallery application which enables users to organise, manage and share their digital assets such as images, videos, logos and documents  on a website. You can find the source code for the Acorn of this sample application [here](https://github.com/infracloudio/piwigo-acorn). 

There are two ways you can try this sample application.
- Using Acorn platform dashboard.
- Using CLI

The First way is the easiest one where, in just a few clicks you can deploy the Piwigo application to the platform and start using it. However, if you want to customize the application or want to understand how you can run your own flask applications using Acorn, use the second option.

## Running Flaskr application using Dashboard
We can run our application from an existing image from the Acorn Cloud Platform UI by clicking on the _”Create Acorns”_ button. 

Choose the source for deploying your Acorns
![create-acorn-options-screen](https://necessary-creativity-bc071c3082.media.strapiapp.com/create_acorn_options_280ce1aeb1.png)

On the “Create Acorns” page, provide a name such as piwigo-sample-app and keeping Project's default Region, type in the below Pre-built Acorn image or your own Acorn Image and choose Create. 

```
ghcr.io/infracloudio/piwigo-acorn:v13.8.0-0
```

![piwigo-select-image](https://necessary-creativity-bc071c3082.media.strapiapp.com/piwigo_select_image_c1570e4048.png)

Now the sample App is provisioned on Acorn Cloud Platform and is available for 2 hrs. Upgrade to Enterprise account to keep it running longer. 

![piwigo-running-acorn](https://necessary-creativity-bc071c3082.media.strapiapp.com/piwigo_running_acorn_2520fe8797.png)

Once the Acorn is running, you can access it by clicking the Endpoint or the redirect link.



