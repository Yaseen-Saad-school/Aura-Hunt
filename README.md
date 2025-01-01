
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
