# Developers in Apigee

In Apigee, developers refer to individuals or entities who register and use APIs provided by an API provider. Developers interact with APIs, access documentation, obtain API keys, and manage their applications.

Apigee provides features and tools to manage developers, such as creating developer accounts, generating API keys, managing access control, and tracking developer analytics. Developers can register themselves or be registered by API providers.

## Adding Developers in Apigee using Jenkins

This repository contains Jenkinsfile which has script for adding developers in Apigee.

For using this template we have to update our Apigee organisation name in jenkinsfile for parameter:

`def orgList = ['YOUR_APIGEE_ORGANISATION_NAME']`

Mention the developer.json file containing developers name inside developers folder.

Create a Jenkins pipeline using this repository and build that pipeline by passing parameters to it.


![jenkins_pipeline](https://i.postimg.cc/x1W0Q08Y/Screenshot-from-2023-06-18-13-52-46.png)


Build the pipeline and it will add a developer in Apigee.

To verify this move to:

Apigee > Publish > Developers
