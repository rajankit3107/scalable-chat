# Server App

This is the backend server for the Scalable Chat project. It is built with Node.js, TypeScript, and Socket.IO.

## Features

- Real-time WebSocket server using Socket.IO
- Written in TypeScript
- Exposes a single HTTP server for socket connections

## Getting Started

Install dependencies:

```sh
yarn install
```

Build the server:

```sh
yarn build
```

Start the server:

```sh
yarn start
```

## Development

- Main entry: `src/index.ts`
- Socket logic: `src/services/socket.ts`
