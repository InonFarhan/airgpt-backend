AirGPT Backend
This repository contains the backend code for AirGPT, a natural language processing application built with OpenAI's GPT-3.5 model. AirGPT allows users to interact with the model via a RESTful API.

Table of Contents
Introduction
Installation
Usage
API Endpoints
Contributing
License
Introduction
AirGPT Backend is the server-side component of the AirGPT application. It provides a bridge between the frontend client and the OpenAI GPT-3.5 model, allowing users to make requests and receive responses.

Installation
To set up the AirGPT Backend, follow these steps:

Clone the repository:

shell
Copy code
git clone https://github.com/omerBNB/airgpt-backend.git
Navigate to the project directory:

shell
Copy code
cd airgpt-backend
Install the required dependencies using npm:

shell
Copy code
npm install
Set up the environment variables by creating a .env file and providing the necessary values. You can use the provided .env.example file as a template.

Start the server:

shell
Copy code
npm start
The server should now be running at http://localhost:3000. You can configure the port in the .env file.

Usage
To use the AirGPT Backend, you need to have the frontend client set up. The client can be found at AirGPT Frontend.

Once both the backend and frontend are running, you can access the AirGPT application in your browser.

API Endpoints
The AirGPT Backend provides the following API endpoints:

POST /api/completions: Sends a request to the GPT-3.5 model for text completion. The request payload should include the prompt and maxTokens fields.
For detailed information on how to use these endpoints, refer to the API documentation provided in the repository.

Contributing
Contributions to the AirGPT Backend are welcome! If you find any bugs or want to suggest improvements, please open an issue or submit a pull request. Make sure to follow the existing coding style and guidelines.

License
This project is licensed under the MIT License. Feel free to modify and distribute this code as needed.
