# How to use Postman Collections
The easiest way to get started using the Apply with Linkedin APIs is to use our Postman collections. <br>Postman is a free-to-download tool for making HTTP requests. You can find more details about Postman [here](https://www.postman.com).<br>
The following steps outline the necessary actions in order to install Postman and gain certainty that everything is working as it should be.
<br>If you prefer, you can explore our API with other tools like curl.

## Install Postman
Visit www.getpostman.com and download the version of Postman required for your platform and complete Postman installation.

## Import Postman Collection

- Open Postman
- Click `Import` button, click `Choose Files` button and locate the required collection json file to import. An import success message appears for each collection imported and then you can see the collection in `Collections` tab.
- After a collection is successfully imported into postman, Click `...` icon next to an imported collection and click on `Edit` button to setup variables.
- Please set the value for the variables and click on `Update` button. 
- You have successfully setup and ready to make API calls.

## Apply with LinkedIn Postman Collection Variables

|Variable Name|Description|
|---|---|
|partner_app_client_id|Client id of Partner's Application. It will be used to get access token to be able to call `Provision Customer Application` APIs|
|partner_app_client_secret|Client secret of Partners Application. It will be used to get access token to be able to call `Provision Customer Application` APIs|
|customer_app_client_id|Client id of Customer's Application. It will be used to get access token to be able to call `Configure Customer Middleware Integrations` APIs|
|customer_app_client_secret|Client secret of Customer's Application. It will be used to get access token to be able to call `Configure Customer Middleware Integrations` APIs|
|integration_context|The value for `integration_context` is obtained when customer has requested for `Apply with LinkedIn` integration using `ATS Integration Configuration Plugin`|
|unique_foreign_id|A unique ID that represents the child application being created, as seen from the parent/calling application. This value must be unique across all child applications that belong to the parent application|