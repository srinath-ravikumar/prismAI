# Prism: AI-Enabled Online Collaborative Coding Platform

## Description

Prism is a cutting-edge online collaborative coding platform that leverages artificial intelligence to enhance the coding experience. Built on the MERN (MongoDB, Express.js, React.js, Node.js) stack, Prism offers real-time collaboration, code compilation, and AI-powered assistance to developers of all skill levels.

## Features

- **Real-time Collaboration**: Work together with team members in real-time using web sockets
- **Code Compilation**: Compile and run code directly in the browser using Judge0 API integration
- **AI Assistant**: Get intelligent coding suggestions and answers to your questions with Mistral-7B LLM integration
- **Multiple Language Support**: Code in a variety of programming languages
- **User Authentication**: Secure user accounts and project management

## Technology Stack

- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Real-time Communication**: Web Sockets
- **Code Compilation**: Judge0 API
- **AI Language Model**: Mistral-7B
- **Authentication**: JSON Web Tokens (JWT)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/srinath-ravikumar/prismAI
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd client && npm install
   cd ../server && npm install
   ```

3. Create a `.env` file in the server directory and add the following environment variables:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   JUDGE0_API_KEY=your_judge0_api_key
   MISTRAL_API_KEY=your_mistral_api_key
   ```

4. Start the development servers:
   ```bash
   # In the client directory
   npm start
   
   # In the server directory
   npm run dev
   ```

## Usage

1. Register for an account or log in if you already have one.
2. Create a new code space or join an existing one using the project code.
3. Start coding in the collaborative editor.
4. Use the AI assistant by typing in your question in the chat box.
5. Compile and run your code using the "Run" button.

## API Documentation

For detailed API documentation, please refer to the [API Documentation](link-to-api-docs) file.

## Contributing

We welcome contributions to Prism! Please read our [Contributing Guidelines](link-to-contributing-guidelines) for more information on how to get started.

## License

This project is licensed under the MIT License - see the [LICENSE](link-to-license) file for details.

## Acknowledgments

- Judge0 for providing the code compilation API
- Mistral AI for the Mistral-7B language model
- The open-source community for various tools and libraries used in this project
