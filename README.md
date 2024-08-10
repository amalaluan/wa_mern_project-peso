# PESO-Lipa.Online

## Table of Contents
1. [Project Description](#project-description)
2. [Technologies Used](#technologies-used)
3. [Installation](#installation)
   - [Backend Installation](#backend-installation)
   - [Frontend Installation](#frontend-installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contact](#contact)

## Project Description
This project involves the development of an automated job portal using the MERN stack (MongoDB, Express.js, React, Node.js). The portal is designed to streamline the job search process by matching candidates with relevant job opportunities based on their profiles, skills, and preferences. The system will integrate a content-based algorithm through an external API, enhancing the matchmaking process by analyzing and comparing job descriptions with candidate profiles to suggest the most suitable job listings. The portal will feature user registration, job listing management, resume submission, and job application tracking functionalities, providing a comprehensive platform for both job seekers and employers.

## Technologies Used

### Backend
![Works with Android](https://img.shields.io/badge/Backend-Node.js-green?style=flat-square)
![Works with Android](https://img.shields.io/badge/Backend-Express-green?style=flat-square)
![Works with Android](https://img.shields.io/badge/Backend-MongoDB-green?style=flat-square)

### Frontend
![Works with Android](https://img.shields.io/badge/Frontend-React.js-blue?style=flat-square)
![Works with Android](https://img.shields.io/badge/Frontend-Tailwind-blue?style=flat-square)

## Installation

### Backend Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/wanderingcoderrr/wa_project-peso.git
    cd wa_project-peso/backend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Set up environment variables:
    - Create a `.env` file in the `backend` directory with the following variables:
    ```plaintext
    PORT=5000
    MONGO_URI=your_mongo_db_connection_string
    ```

4. Start the server:
    ```bash
    npm start
    ```

### Frontend Installation

1. Navigate to the frontend directory:
    ```bash
    cd ../frontend
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm start
    ```

The frontend will run on `http://localhost:3000` by default.

## Usage

1. Start both the backend and frontend servers as described in the installation steps.
2. Open your browser and navigate to `http://localhost:3000`.
3. Click on a building on the map to view the optimal route from your current location.

## Project Structure

```plaintext
university-route-planner/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── .env.example
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .env
└── README.md
```

## Contact
For any questions, feel free to reach out:
- Arvin Malaluan | arvinmalaluan7@gmail.com
