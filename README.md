# Tic Tac Toe React App

![Tic Tac Toe Screenshot](./screenshot.png)

A modern and interactive **Tic Tac Toe** game built with **React** and **Vite**.  
Developed as part of the Udemy course  
[React – The Complete Guide (incl. Next.js, Redux) 2025](https://www.udemy.com/course/react-the-complete-guide-incl-redux/)  
by Maximilian Schwarzmüller.  
The goal of the project was to apply core React concepts through a hands-on example.

---

## Features

- Player vs Player mode
- Win and draw detection
- Move history log
- Light / Dark mode toggle
- Editable player names
- Game reset and name clearing

---

## Tech Stack

- React (with Vite)
- CSS Modules for scoped styling
- JavaScript (ES6+)
- Modular component-based architecture
- Vite for fast build and development

---

## Project Structure

```
src/
├── assets/
│ └── react.svg
├── components/
│ ├── GameBoard/
│ │ ├── GameBoard.jsx
│ │ └── GameBoard.css
│ ├── GameOver/
│ │ └── GameOver.jsx
│ ├── Log/
│ │ └── Log.jsx
│ └── Player/
│ ├── Player.jsx
│ └── Player.css
├── App.jsx
├── index.jsx
├── utils.js
└── winning-combinations.js

```

---

## Getting Started

Follow these steps to run the project locally:

### 1. Clone the repository

```bash
git clone https://github.com/D-vokic/tic-tac-toe-classic.git
```

### 2. Install dependencies

```bash
cd tic-tac-toe-classic
npm install
```

### 3. Start the development server

```bash
npm run dev
```

---

The application will be available at:
http://localhost:5173

---

## React Concepts Demonstrated

- useState and useEffect hooks

- Prop drilling and component communication

- Conditional rendering

- Handling lists and keys

- Modular logic extraction (winning-combinations.js)

- Theme toggling using state management

---

## UI and UX Highlights

- Clean neon sci-fi design

- Strong contrast and readability

- Responsive layout for all screen sizes

- Smooth animations and hover effects

---

## Future Improvements

- Add AI opponent (Minimax algorithm)

- Add sound effects for moves and victories

- Improve mobile responsiveness

- Add scoreboard and player statistics

## License

This project is open-sourced under the **MIT License** - see the [LICENSE.md](LICENSE.md) file for details.  
© [Duško Vokić](https://duskovokic.com)
