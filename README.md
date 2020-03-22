This repository holds a node.js application providing a simple frontend & Interface for an IBM Watson Assistent. The Assistant should be configured by yourself inside the IBM Cloud Portal.

## Configure the Chatbot: IBM Watson Assistant

1. Go to https://cloud.ibm.com/
2. Set up an IBM Watson Assistant (https://cloud.ibm.com/docs/assistant?topic=assistant-getting-started)
3. Note its API credentials for the application

## Configuring the application

1. In the application folder, create a file called ".env"

2. Add API credentials as environment variables

    ```
    # Environment variables
    ASSISTANT_ID=

    #IAM API key and URL
    ASSISTANT_IAM_APIKEY=
    ASSISTANT_URL=
    ```

## Running locally

1. Install the dependencies

    ```
    npm install
    ```

1. Run the application

    ```
    npm start
    ```

1. View the application in a browser at `localhost:3000`


