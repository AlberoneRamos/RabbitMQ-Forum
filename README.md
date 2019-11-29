This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## About

This is the Frontend for the RabbitMQ C# Forum.

## How to run it

### Frontend

Since the frontend was made in React, you should have `npm` and `node` installed. If you don't have those, Install them [Here](https://nodejs.org/en/download/).
After installing npm and node, at the root directory:

```zsh
cd Frontend
npm install
npm start
```

### Consumer

To run the backend, you'll need to install .NET. After that, you should run the following commands from the **root directory**:

```zsh
cd Backend
dotnet run
```

## Motivation

This project was done for the Distributed Systems subject, taught by Hugo de Paula to the Software Engineering course at PUC Minas. It aims to teach the students about message brokers and its concepts.
