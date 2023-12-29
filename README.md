# 🚀 Logic App Web App
## Description
Proof of concept that Logic App Standard can be used as web app. 
## Installation
Let's gather our tools:

- Vs Code Extension Logic App Standard 🧙
- Azure Function Core Tools 🖳

Set up local.settings.json
```
{
  "IsEncrypted": false,
  "Values": {
    "AzureWebJobsStorage": "UseDevelopmentStorage=true",
    "APP_KIND": "workflowapp",
    "ProjectDirectoryPath": "C:\\Users\\YourUser\\projectfolder",
    "FUNCTIONS_WORKER_RUNTIME": "node",
    "WORKFLOWS_SUBSCRIPTION_ID": "",
    "API_Key" : "OMDB_API_Key",
    "SEARCH_WORKFLOW_URL" : ""
  }
}

```
## Usage
Run project with the `F5` command.
Right click the home workflow and press `Overview`. Copy the url into the broswer and start searching for movies!🎥
