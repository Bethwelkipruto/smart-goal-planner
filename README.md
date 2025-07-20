# Smart Goal Planner

A professional and user-friendly Smart Goal Planner built with React and JSON Server. This app helps users set, track, update, and delete their financial savings goals.

---

## Features

* Create new SMART financial goals
* View and manage all goals
* Edit existing goals
* Delete completed or outdated goals
* Data persistence using JSON Server
* Responsive design for mobile and desktop

---

## Technologies Used

* React (with Vite)
* JavaScript (ES6+)
* CSS3
* JSON Server
* React Router DOM

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/smart-goal-planner.git
cd smart-goal-planner
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Start the JSON Server

```bash
npx json-server --watch db.json --port 3001
```

> `db.json` should be in the root folder with your goal data or an empty array `[]`.

### 4. Start the React App

```bash
npm run dev
```

> Vite will start the app on `http://localhost:5173`

---

## Folder Structure

```bash
src/
├── components/
│   ├── GoalList.jsx
│   ├── GoalForm.jsx
│   └── Overview.jsx
├── api/
│   └── goalAPI.js
├── App.jsx
├── main.js
├── index.css / App.css
db.json
```

---

## License

MIT License

---

## Built By

Bethwel.kc

email:[bethwel.c7@gmail.com](mailto:bethwel.c7@gmail.com)

github: Bethwelkipruto
