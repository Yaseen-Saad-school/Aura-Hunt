# Aura Hunt

Welcome to **Aura Hunt**, a thrilling interactive scavenger hunt game designed for the new Grade 10 students of STEM High School for Boys - 6th of October! This adventure will take you through mysteries, challenges, and unforgettable teamwork experiences.

---

## 🌟 Features

- **Dynamic Challenges**: A mix of physical, mental, and creative tasks to engage all participants.
- **Aura System**: Earn or lose aura points based on performance in challenges and tasks.
- **Leaderboard**: 
  - **Public Leaderboard**: Shows the current standings of all teams, updated in real-time for everyone to see [demo](aurahunt.quest/scoreboard).
  - **Organizer Leaderboard**: Exclusive access for organizers to:
    - View every attempt made by every team.
    - See all the questions each team scanned and tried to solve.
    - Update team scores based on performance or manual adjustments.
    - [demo](aurahunt.quest/secretAdminsAuraRoomforEditingScore)

- **Unique Question Types**:
  - **Red Question**: First-to-solve questions with decreasing aura rewards.
  - **Purple Question**: Visual proof required, cannot be submitted via the portal.
  - **Green Question**: Graded at the end of the competition.
  - **Orange Question**: Graded by the aura master in person.
  - **Dark Blue Question**: Repeatable tasks.
- **Mystery Themes**: Explore clues and uncover the secrets of the seven aura layers.
- **Interactive Gameplay**: Engage with your surroundings, teammates, and aura masters.

---

## 🌍 Game Idea

Aura Hunt is inspired by the concept of human energy fields, or auras. The competition encourages participants to unlock their hidden potential by interacting with different layers of their aura:
1. **Physical Layer**: Strength and vitality.
2. **Emotional Layer**: Feelings and emotional intelligence.
3. **Mental Layer**: Logic and reasoning.
4. **Astral Layer**: Dreams, love, and mercy.
5. **Etheric Layer**: Psychic connections.
6. **Celestial Layer**: Creativity and intuition.
7. **Ketheric Layer**: Cosmic connection and enlightenment.

Your mission? Tap into these layers, solve mysteries, complete challenges, and lead your team to victory while building lasting friendships and memories.

---

## 🎮 Demo Challenges

Here are some exciting demos to try out:

1. **The Hidden Oasis**: Find the hidden oasis within the school—a place where hope exists amidst the desert.
   - **Demo Task**: [https://aurahunt.quest/game/The%20Hidden%20Oasis](https://aurahunt.quest/game/The%20Hidden%20Oasis)

2. **Are You Fast Enough?**: Run 100m in under 15 seconds to "dive into the speed force."
   - **Demo Task**: Delivered via WhatsApp during the competition.

3. **Laughing Challenge**: Make another participant laugh within a time limit.
   - **Demo Task**: Delivered via WhatsApp during the competition.

4. **F.I.R.E.S.T.O.R.M.**: Find the remnants of the firestorm that struck the school in the past.
   - **Demo Task**: [https://aurahunt.quest/game/F.I.R.E.S.T.O.R.M.](https://aurahunt.quest/game/F.I.R.E.S.T.O.R.M.)

5. **Are You Hungry Too?**: Discover one of three hidden codes in the restaurants and earn aura points.
   - **Demo Task**: [https://aurahunt.quest/game/Are%20You%20Hungry%20Too](https://aurahunt.quest/game/Are%20You%20Hungery%20Too)

6. **Decode the Cipher**: Solve a challenging cryptographic puzzle to reveal a hidden message.
   - **Demo Task**: Delivered live on the game day.

7. **Decode the Cipher**: Solve a challenging cryptographic puzzle to reveal a hidden message.
   - **Demo Task**: [https://aurahunt.quest/game/Decode%20the%20Cipher](https://aurahunt.quest/game/Decode%20the%20Cipher)

8. **Shadow Seekers**: Find and capture the shadow lurking in the dark corners of the school.
   - **Demo Task**: Delivered on-site during the hunt.

9. **Aura Relay**: Complete a series of rapid tasks in a relay format with your teammates.
   - **Demo Task**: Delivered live on the game day.

---

## 🎁 Prizes

- **1st Place**: A brand-new **Raspberry Pi 5** from the HC gifts at High Seas!
- **2nd Place**: A **Raspberry Pi Zero**.
- **All Participants**: Stickers and unforgettable memories!

---

## ✨ Notable Quotes

- _"A journey is best measured in friends, rather than miles."_ — Tim Cahill
- _"Aim for the moon. If you miss, you may hit a star."_ — W. Clement Stone
- _"Be both soft and wild. Just like the moon, the storm, or the sea."_ — Victoria Erickson

---

## 📅 Game Schedule

**Date**: Tuesday  
**Time**: 4:00 PM  

Get ready to unlock the mysteries of your aura and embark on an adventure filled with surprises, challenges, and teamwork. Stay tuned for more updates and let the hunt begin!

---

## 🛠️ Technical Expertise

### Backend
- **Node.js**: The game logic and server-side operations are built using Node.js.
- **Express.js**: Powers the RESTful API endpoints for seamless communication between the frontend and backend.
- **Firebase Firestore**: Used for real-time database management to track player progress, aura points, question submissions, and team attempts.

### Frontend
- **EJS (Embedded JavaScript)**: Dynamic templates for rendering the game's user interface with server-side data integration.
- **SASS**: Stylesheets are written in SASS, providing a clean and modular design for the game portal.
- **JavaScript**: Interactive frontend functionalities are managed using vanilla JavaScript.

### Leaderboards
- **Public Leaderboard**:
  - Displays real-time scores and rankings for all teams.
  - Available for all participants and spectators.
- **Organizer Leaderboard**:
  - Detailed tracking of every team's attempts.
  - Allows organizers to see:
    - All questions scanned by each team.
    - Each team’s progress and attempts.
  - Provides options to manually update team scores as needed.

### Hosting and Deployment
- **Vercel**: The application is hosted on Vercel for fast, reliable, and scalable performance.
- **Game Portal URL**: [https://aurahunt.quest](https://aurahunt.quest)

### File Structure
- **Views**: EJS templates for various game screens (e.g., login, challenges, and leaderboard).
- **Public**: Static assets including images, SASS-compiled CSS, and JavaScript files.
- **Routes**: Express routes for handling different endpoints like `/game/:id`, `/leaderboard`, and more.
- **Utils**: Helper functions for calculations, validations, and scoring logic.

### Features
- **Dynamic Scoring**: Real-time scoring and leaderboards updated directly from Firestore.
- **Question Logic**: Unique grading and question types implemented with robust validation.
- **QR Code System**: Players unlock mysteries by scanning QR codes placed in strategic locations.
- **Multi-File Structure**: Clean, modular codebase divided into components for scalability and maintainability.

### Development Tools
- **Postman**: For testing and debugging API endpoints.
- **Git**: Version control for collaborative development.
- **SASS Compiler**: Automated stylesheets for clean and responsive design.

---

## API Documentation

Below you will find a comprehensive guide to the AuraHunt API, which can be used by developers and organizers to interact with the game data, scores, and more.

### Table of Contents
1. [Introduction](#introduction)
2. [API Base URL](#api-base-url)
3. [Authentication](#authentication)
4. [CORS Configuration](#cors-configuration)
5. [Endpoints](#endpoints)
   - [Edit Score](#edit-score)
   - [Toggle Checked Status](#toggle-checked-status)
   - [Toggle Solved Status](#toggle-solved-status)
   - [Correct Question](#correct-question)
   - [Upload File](#upload-file)
   - [Team Login](#team-login)
   - [Generate JSON](#generate-json)
   - [Fetch Team Aura Scores](#fetch-team-aura-scores)
6. [Rate Limiting](#rate-limiting)
7. [Environment Variables](#environment-variables)
8. [Hosting and Deployment](#hosting-and-deployment-1)
9. [Security Considerations](#security-considerations)
10. [Contribution](#contribution)
11. [License](#license)

---

### Introduction

The AuraHunt API allows administrators and teams to manage and interact with the AuraHunt game platform. You can use this API to:
- Edit team scores
- Toggle the status of questions (checked/solved)
- Upload files related to questions
- Retrieve game data and team details
- Securely log in teams and more

### API Base URL

All endpoints in this API are available under the following base URL:

```
https://aurahunt.quest
```

### Authentication

Some endpoints require authentication via a **token** to ensure that only authorized users (admin or teams) can access certain functionality. 

#### Admin Token

- For secure admin operations like editing scores or toggling statuses, the `ADMIN_REQUEST_TOKEN` must be provided in the request body. The token is stored in your environment variables (`.env`).

#### Team Authentication

- Teams must log in with their `teamid` and `password` to obtain a valid `token` for authenticated operations like file uploads and score management.

### CORS Configuration

By default, the API allows requests from a specific origin (`https://aurahunt.quest`). You can change this to allow all domains or configure specific domains for security.

#### Public Access CORS Configuration

To allow all domains to access the API:

```js
app.use((req, res, next) => {
  res.header('Access-Control-Allow-Origin', '*');
  res.header('Access-Control-Allow-Headers', 'Origin, X-Requested-With, Content-Type, Accept');
  next();
});
```

For specific origins:

```js
const allowedOrigins = ['https://example1.com', 'https://example2.com'];

app.use((req, res, next) => {
  const origin = req.headers.origin;
  if (allowedOrigins.includes(origin)) {
    res.header('Access-Control-Allow-Origin', origin);
  }
  res.header('Access-Control-Allow-Headers', 'Origin, X-Requested-With, Content-Type, Accept');
  next();
});
```

### Endpoints

#### 1. Edit Score

**Endpoint**: `POST /editscore`

- **Description**: Allows admins to update the score of a team.
- **Request Body**:
    ```json
    {
      "token": "admin-token",
      "id": "team-id",
      "aura": 50
    }
    ```
- **Response**:
    - Success:
        ```json
        { "message": "Score updated successfully" }
        ```
    - Error:
        ```json
        { "message": "Failed to update scores", "error": "Error message" }
        ```

#### 2. Toggle Checked Status

**Endpoint**: `POST /toggleChecked`

- **Description**: Toggles the checked status of a specific question.
- **Request Body**:
    ```json
    {
      "token": "admin-token",
      "id": "team-id",
      "questionId": "question-id"
    }
    ```
- **Response**:
    - Success:
        ```json
        { "message": "Checked status updated successfully" }
        ```
    - Error:
        ```json
        { "message": "Failed to toggle checked status", "error": "Error message" }
        ```

#### 3. Toggle Solved Status

**Endpoint**: `POST /toggleSolved`

- **Description**: Toggles the solved status of a specific question.
- **Request Body**:
    ```json
    {
      "token": "admin-token",
      "id": "team-id",
      "questionId": "question-id"
    }
    ```
- **Response**:
    - Success:
        ```json
        { "message": "solved status updated successfully" }
        ```
    - Error:
        ```json
        { "message": "Failed to toggle solved status", "error": "Error message" }
        ```

#### 4. Correct Question

**Endpoint**: `POST /correctQuestion`

- **Description**: Marks a question as solved if the answer is correct, or deducts points if incorrect.
- **Request Body**:
    ```json
    {
      "teamId": "team-id",
      "gameId": "game-id",
      "correct": true
    }
    ```
- **Response**:
    - Success:
        ```json
        { "message": "CHECKED" }
        ```
    - Error:
        ```json
        { "message": "Internal server error" }
        ```

#### 5. Upload File

**Endpoint**: `POST /upload`

- **Description**: Allows teams to upload files related to a specific question.
- **Request Body**:
    ```json
    {
      "teamid": "team-id",
      "teamtoken": "team-token",
      "gamename": "game-name",
      "gameId": "game-id"
    }
    ```
- **Response**:
    - Success:
        ```json
        { "message": "File uploaded successfully", "url": "file-url" }
        ```
    - Error:
        ```json
        { "message": "Failed to upload file" }
        ```

#### 6. Team Login

**Endpoint**: `POST /teamlogin`

- **Description**: Allows a team to log in with their credentials.
- **Request Body**:
    ```json
    {
      "team": "team-id",
      "password": "team-password"
    }
    ```
- **Response**:
    - Success:
        ```json
        { "message": "Team logged in successfully", "token": "team-token" }
        ```
    - Error:
        ```json
        { "message": "Wrong password" }
        ```

#### 7. Generate JSON

**Endpoint**: `GET /generate-json`

- **Description**: Generates a JSON containing all teams and their current scores.
- **Response**:
    ```json
    [
      { "id": "team-id", "score": 100 }
    ]
    ```

#### 8. Fetch Team Aura Scores

**Endpoint**: `GET /MyTeamAuraScores/:id`

- **Description**: Fetches the score and questions for a specific team.
- **Response**:
    ```json
    {
      "score": {
        "id": "team-id",
        "score": 200,
        "questions": [
          {
            "id": "question-id",
            "attempts": [],
            "score": 10,
            "deduction": 5,
            "checked": false,
            "solved": true
          }
        ]
      }
    }
    ```

### Rate Limiting

To prevent abuse, a rate-limiting policy is enforced on the API. The limit is set to **100 requests per 15 minutes** per IP address. Exceeding this limit will result in a `429 Too Many Requests` response.

### Environment Variables

The following environment variables need to be set:

- `ADMIN_REQUEST_TOKEN`: Admin token for secure API access.
- `FIREBASE_CREDENTIALS_PATH`: Path to your Firebase credentials file.

**Example `.env` file**:
```plaintext
ADMIN_REQUEST_TOKEN=your-admin-token
FIREBASE_CREDENTIALS_PATH=/path/to/your/firebase/credentials.json
```

### Hosting and Deployment

This API is hosted on vercel app.

### Security Considerations

- **Authentication**: All sensitive endpoints require token-based authentication (admin or team tokens).
- **Environment Variables**: Ensure that sensitive keys (like Firebase credentials and admin tokens) are never exposed in the source code.
- **CORS**: Review and restrict CORS to trusted domains to avoid unauthorized access.

### Contribution

Contributions are welcome! To contribute to this project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

Please ensure that any contributions align with our coding style and pass existing tests.

### License

This project is released under the [MIT License](LICENSE). Feel free to use and modify this software according to the terms in the license.

---

> **Note**: This documentation provides a high-level overview. For more in-depth information on request structures, server responses, and edge cases, refer to the source code and comments within the repository.

Happy hacking!
