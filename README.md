# QuickTalk

A full stack, real-time chat application.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

QuickTalk is a real-time chat application built using a full stack JavaScript approach. It enables users to communicate instantly and efficiently, leveraging modern web development technologies for both the frontend and backend.

## Features

- Real-time messaging
- User authentication
- Responsive UI
- Scalable backend and frontend separation

## Tech Stack

- **Frontend:** JavaScript, HTML, CSS (located in the `frontend` directory)
- **Backend:** JavaScript (Node.js/Express, located in the `backend` directory)
- **Other:** Uses NPM for package management

## Project Structure

```
QuickTalk/
│
├── .gitignore
├── backend/       # Backend server code
├── frontend/      # Frontend client code
├── package.json   # Project metadata and dependencies
├── package-lock.json
```

## Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- NPM

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ayushh8/QuickTalk.git
   cd QuickTalk
   ```

2. Install dependencies for both frontend and backend:
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. Start the backend server:
   ```bash
   cd ../backend
   npm start
   ```

4. Start the frontend client:
   ```bash
   cd ../frontend
   npm start
   ```

## Usage

- Access the frontend via your browser (typically at http://localhost:3000).
- Register or log in to start chatting in real time.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for improvements or bug fixes.

## License

This project is licensed under the MIT License.
