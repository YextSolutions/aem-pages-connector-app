##### aem-pages-data-connector

# Product Description & Purpose

Adobe Experience Manager (AEM) is a CMS built to power websites with a suite of products. AEM Sites, for example, allows users to publish the content they store in AEM to websites, apps, and more. Create entities by pulling in your AEM Pages to leverage the power of all of our Yext products! 

This app creates the following custom connectors:	

- aemp\_adobeExperienceManagerPagesConnector

This app creates the following custom entity types that correlate to each connector:		

- aemp\_page

This app creates the following custom fields:

- aemp\_jcrName
- aemp\_path
- aemp\_landingTileDescription
- aemp\_landingTitleEyebrow
- aemp\_lastModifiedDate


This app adds the following plugins to your account:

- aemp\_decodeHTML


# Requirements

Ensure that you have completed all prerequisites!
- Cloud SDK copy or be an AEMaaCS client
- Enabled the Querybuilder API
- Deployed the custom exporter using the .model extension

To use this app you will need to have the following handy before you install:
- your AEM environment URL
- your local user AEM credentials, username and password
- the folder file path for your page entities

Follow the step-by-step instructions below to install the Adobe Experience Manager Pages Connector app.

# How to Install

If you are an existing Yext customer, you can install the  Adobe Experience Manager Pages Connector here <https://www.yext.com/s/me/apps/58757>

If you are currently using a Yext sandbox account, you can install the Adobe Experience Manager Pages Connector here <https://sandbox.yext.com/s/me/apps/123432>.

If you are not an existing customer, but interested in learning more, try out a free trial here for a production account, or sign up for Hitchhikers and get started with a sandbox account, here <https://hitchhikers.yext.com/>. 

Install the connector to begin pulling in your Slack data into Yext Content! 


### To install the Adobe Experience Manager Pages Connector:

1. Log in to your Yext account
2. Navigate to the **Apps > Directory** tab in the platform (or use the link provided above).
3. Search for the Adobe Experience Manager Pages Connector app and click **Install**.
4. Accept the following changes to your account by clicking **Next** and authorize Yext APIs.
5. Provide your AEM details, environment URL, username, password and the folder file path of the pages that you want to pull in.
7. Wait for the connector to run and see all of your newly created entities in the **Yext Content** tab in the platform!






