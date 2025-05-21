# 📒 Notes App - Back-End Fundamentals

A simple note-taking application built with a **separated front-end and back-end architecture** using **Node.js** and **npm**.

## 📁 Project Structure

This project contains two main directories:

```
notes-app/
📄 notes-app-frontend/   # Front-End (User Interface)
📄 notes-app-backend/    # Back-End (Server Logic)
```

> Make sure you execute the commands inside the correct directory.

---

## ✅ Prerequisites

* [Node.js](https://nodejs.org/) v16.x or later (npm included)

---

## 🔧 Installation

### 1. Back-End Setup

```bash
cd notes-app-backend
npm install
```

### 2. Front-End Setup

```bash
cd ../notes-app-frontend
npm install
```

---

## 🚀 Running the Project

### 1. Start Back-End Server

```bash
cd notes-app-backend
npm run start
```

The back-end server will run at: `http://localhost:5000`

### 2. Build & Run Front-End (Production)

```bash
cd ../notes-app-frontend
npm run build
```

To serve the front-end build folder, you can use [`serve`](https://www.npmjs.com/package/serve):

```bash
npm install -g serve
serve -s build
```

The front-end will be available at: `http://localhost:3000` (or the port used by `serve`)

---

## 📆 Available NPM Scripts

### In `notes-app-backend/`:

| Command         | Description                                            |
| --------------- | ------------------------------------------------------ |
| `npm install`   | Install dependencies                                   |
| `npm run start` | Start the back-end server                              |
| `npm run dev`   | *(optional)* Start in dev mode (e.g., using `nodemon`) |

### In `notes-app-frontend/`:

| Command         | Description                                                 |
| --------------- | ----------------------------------------------------------- |
| `npm install`   | Install dependencies                                        |
| `npm run build` | Build the app for production                                |
| `npm run start` | Start production server (if configured)                     |
| `npm run dev`   | *(optional)* Start front-end in dev mode (e.g., Vite/React) |

---

## 🔗 Customization

* Change ports or URLs based on your local environment or deployment server.
* Update the API endpoint inside the front-end if the back-end is hosted separately (e.g., using a domain or different port).
* You can also use environment variables or `.env` files to manage configuration more cleanly.

---

## 📬 License

This project is for learning purposes. Feel free to fork and modify.

---
