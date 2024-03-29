# gpt-clone
A conversational AI app inspired by OpenAI's GPT-3 language model, built with Create React App.

## Features

- Natural language processing and understanding
- Context-aware responses
- Ability to converse on a variety of topics
- React-based front-end for easy user interaction
- Node.js back-end for communication with the OpenAI API

## Requirements

- Node JS
- npm
- [Create Open AI account](https://beta.openai.com/signup/)

## Setup

1. Install client dependencies

```
cd client
npm install
```

2. Install server dependencies

```
cd server
npm install
```

3. Get your Open AI API key from [Open AI API Key](https://platform.openai.com/account/api-keys)

4. Environment Variable Setup

- Go to server folder and create .env file in root of server folder and create a variable REACT_APP_OPENAI_API_KEY = [ Your Open AI key here ] insise .env file as

```
REACT_APP_OPENAI_API_KEY = [Your Open AI key here]

```
5. Configure Firebase 
- Go to [firbase console](https://console.firebase.google.com/) & click on add project, follow the guidelines to create new firebase project
- Once project is created you'll see the config file generated for you. If you do not find the config file, see the Project Overview section on the left panel. Just click the gear icon     which is at the right of Project Overview, there you'll see the Project Setting. 
- Click on the Project Setting, scroll to the bottom there you'll see "Your apps" section. You need to select web with <mark> </> </mark> symbols. Click on the icon and follow along to add firebase to your web app. Once you'll have your config file update your firebase.config file in the client/src folder. 

## Usage

1. Start the client

```
cd client
npm start
```

2. Start the server

```
cd server
node index.js
```
