# Chat-GPT-Clone
Welcome to Chat-GPT-Clone, a Multi-Functional MERN project powered by OpenAI API!

## Project Overview
Chat-GPT-Clone is a versatile application that incorporates various AI-driven functionalities such as text summarization, paragraph generation, chatbot interactions, JavaScript code conversion, and sci-fi image generation. This project serves as an excellent showcase of the capabilities of the OpenAI API.

## Folder Structure
The project follows the following folder structure:

backend/ // Backend server implementation client/ // Frontend client implementation

The backend/ folder contains the server-side implementation, built with Node.js and Express.js. It handles API requests, interacts with the OpenAI API, and communicates with the database.
The client/ folder contains the client-side implementation, built with React.js. It provides the user interface for interacting with the various functionalities of the application.
## Prerequisites
Before running the application, make sure you have the following prerequisites installed on your system:
Node.js
MongoDB
## Installation
Clone the repository:
git clone <github_repo_url>

Navigate to the project root directory:
cd Chat-Gpt-Clone

Install dependencies for both the backend and client:
cd backend
npm install
cd ../client
npm install

## Configuration
To configure the application, create a .env file in the backend/ directory and add the following environment variables:

OPENAI_API_KEY=
MONGO_URI=
JWT_ACCESS_SECRET=
JWT_REFRESH_TOKEN=

## Add proxy
To connect frontend with the backend add proxy: cd client
go to packege.json
add "proxy":"http://localhost:8000"

Make sure to replace the placeholders with your own values.

## Usage
Start the backend server:
cd backend
npm start

Start the client:
cd client
npm start

Access the application by opening your browser and visiting http://localhost:3000.

<img width="960" alt="page 1" src="https://user-images.githubusercontent.com/88341691/227281760-cae8fff9-798e-44a8-9e07-76b066fb1139.png">
<img width="960" alt="page 2" src="https://user-images.githubusercontent.com/88341691/227281800-194943ab-96a1-4a2b-87e1-2c93c7186433.png">
<img width="960" alt="page 3" src="https://user-images.githubusercontent.com/88341691/227281838-c214f61d-5f52-416a-a305-0f69323f7974.png">
<img width="960" alt="page 4" src="https://user-images.githubusercontent.com/88341691/227282947-49268627-51a3-4c15-b63d-f5180549977a.png">
<img width="960" alt="page 5" src="https://user-images.githubusercontent.com/88341691/227282978-dbcfeecf-737b-42dd-9c06-49e6db3cf3c0.png">
