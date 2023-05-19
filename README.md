# MercorTalks - Real Time Chat App
This is a real-time chat application built with Node.js, Firebase, and Google Cloud. It allows users to sign in with their Google account, initiate chats with other users, send messages, and view previous chat history.

## Features
- User authentication with Google Sign-In
- Real-time chat functionality
- Initiate chats with other users based on their registration email
- Send messages to other users
- View previous chat history

## Tech Stack

- Node.js
- Express.js
- Firebase Authentication
- Google Cloud SQL
- HTML/CSS/JavaScript

## Deployment
To deploy the application to Google Cloud:
* Setup a free Google Cloud account.
* Create a Cloud SQL instance for your MySQL database.
* Update the .env file with the appropriate database connection details provided by Google Cloud.
* Deploy the application to a hosting platform like Firebase Hosting.



## Installation
1. Clone the repository `git clone https://github.com/aritro66/Talkito.git`
2. Install dependencies in both the client and server directories 
    * `cd Talkito/client`
    * `npm install`
    * `cd ../server`
    * `npm install`
3. Set environment variables
4. Start the server 
    * `cd ../server`
    * `npm start`
5. Start the client 
    * `cd ../client`
    * `npm run dev`

## Usage
To use Talkito, follow these steps:

* Visit the deployed application URL or http://localhost:3000 if running locally.
* Click on the "Sign in with Google" button to authenticate.
* Once signed in, you can initiate chats with other users by entering their registration email.
* Send messages to other users by typing in the chat input box and pressing Enter.
* View previous chat history by navigating to the chat conversation.

## Contribution
We welcome contributions from everyone. If you would like to contribute to this project, please fork the repository and submit a pull request.

