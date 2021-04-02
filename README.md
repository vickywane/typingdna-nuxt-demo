# typingdna-nuxt-demo
This repository contains two seperate directories, each with a demo project explaining how Multi-factor 
Authentication can be performed with TypingDNA.

## Demo Nuxt.js Web Application

This SPA contained in the `nuxt-typingdna-webapp` was boostrapped using [Nuxtjs](https://nuxtjs.or). It serves as a demo application showing how Multi-factor authentication can be implemented in a web application. 

## Intallation steps 
- Clone this repository to your local machine and install the dependencies using the `yarn install` command.

- Start the application using the `yarn start` command and make view in your browser at `https://localhost:3000`

## Usage
To use the web application, setup the demo backend application and have it running on port `5000` (`https://localhost:5000`), before using the account creation and authentication features.

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
