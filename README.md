# React Events

## Project Description

React Events is a small full-stack event management application built with React for the frontend and Node.js/Express for the backend. It uses the `@tanstack/react-query` lib to handle the result of HTTP requests and caching data.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Concepts](#concepts)

## Prerequisites
- [Node.js](https://nodejs.org/en/)
- [NPM](https://www.npmjs.com/)

## Installation

1. Clone the repo:
    ```bash
    git clone https://github.com/LucasFdCosta/react-events.git
    ```
2. Navigate into the project directory:
    ```bash
    cd react-events
    ```
3. Install dependencies:
    ```bash
    npm install
    ```
4. Start the development server:
    ```bash
    npm run dev
    ```
5. Navigate into the backend API:
   ```sh
   cd backend
   ```
6. Install dependencies:
   ```sh
   npm install
   ```
7. Start the local server:
   ```sh
   npm start
   ```

## Usage

After starting the development server, open your browser and go to `http://localhost:5173` (or the port specified in your setup). You can create a new event, list all events, edit and delete events. The frontend communicates with the backend API at `http://localhost:3000` which also should be running at the time.

## Features

- Listing events
- Add events
- Edit event
- Delete event

## Concepts
- React
  - State
- React Router
  - Routing
  - `loader()` and `action()`
- Tanstack Query (React Query)
  - `useQuery()`
  - `useMutation()`
  - Caching
  - Optimistic interface
  - Handling error states, loading states
