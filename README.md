# typingdna-nuxt-demo
This repository contains two seperate directories, each with a demo project explaining how Multi-factor 
Authentication can be performed with TypingDNA.

## Express.js backend application
The backend application contained in the **typingdna-folder** folder was boostrapped using the [Express-generator]() package, and is built to interface with the [TypingDNA Authentication API](https://www.typingdna.com/clients) for creating Mult-factor authentication for users.

## Quick Installation steps 
- Clone and install dependencies locally using the `yarn install` command
- Start the application using the `yarn start` command and make HTTP requests to port `5000`

## Environment variables
  Note: Create a `.env` file containing the following fields and the respective values;

- TypingDNA Specific: <br>
  **TYPINGDNA_API_KEY**: API key obtained from your TypingDNA Dashboard  <br>
  **TYPINGDNA_API_SECRET**: API secret value obtained from your TypingDNA Dashboard

- MongoDB Specific <br>
  **MONGO_URI** : A MongoDB connection string to connect this application to a running mongodb instance either locally or provisioned on a Atlas Cluster.

- Twilio Specific <br>
  **ACCOUNT_SID**: SID Values obtained after creating a Twilio Verify service.   <br>
  **ACCOUNT_TOKEN**: Secret Token obtained after creating a Twilio Account.
