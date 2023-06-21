# ChatGPT

ChatGPT is an application that utilizes OpenAI GPT-3.5 to provide a chat-based conversational experience. This repository consists of two folders: `client` and `server`. 
The server-side handles requests and responses from OpenAI, while the client-side calls the API to showcase the responses on the frontend.

## Installation

To set up ChatGPT locally, follow the instructions below:

1. Clone this repository to your local machine using the following command:

   ```bash
   git clone https://github.com/ItsRoy69/ChatGPT.git
   ```

2. Navigate to the cloned repository:

   ```bash
   cd ChatGPT
   ```

### Server Setup

3. Go to the server directory:

   ```bash
   cd server
   ```

4. Install the server-side dependencies:

   ```bash
   npm install
   ```

5. Set up environment variables by creating a `.env` file and adding your OpenAI API key. You can use the `.env.example` file as a template:

 Replace `YOUR_OPENAI_API_KEY` with your actual OpenAI API key.

### Client Setup

6. Go to the client directory:

   ```bash
   cd client
   ```

7. Install the client-side dependencies:

   ```bash
   npm install
   ```

## Usage

To run ChatGPT, follow the instructions below:

### Server

1. Make sure you are in the `server` directory.

2. Start the server:

   ```bash
   nodemon server
   ```

   The server will run on `http://localhost:8000`.

### Client

1. Make sure you are in the `client` directory.

2. Start the client:

   ```bash
   npm start
   ```

   The client will be accessible at `http://localhost:5173`.

