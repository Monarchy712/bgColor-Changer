# 🎨 React Background Color Changer

A simple React application that dynamically changes the background color of the screen using interactive buttons.

---

## 🚀 Features

* 🔁 Dynamic background color updates
* ⚡ Instant UI re-render using React state
* 🎯 Clean and minimal UI with Tailwind CSS
* 🧠 Beginner-friendly project to understand React event handling

---

## 🛠️ Tech Stack

* React
* Vite
* Tailwind CSS

---

## 📸 Preview

The app displays a full-screen background with buttons at the bottom. Clicking a button changes the background color instantly.

---

## 📂 Project Structure

```
├── src
│   ├── assets
│   │   ├── react.svg
│   │   ├── vite.svg
│   │   └── hero.png
│   ├── App.jsx
│   ├── App.css
│   └── main.jsx
├── index.html
├── package.json
└── vite.config.js
```

---

## ⚙️ Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/your-username/react-color-changer.git
```

2. Navigate to the project directory:

```bash
cd react-color-changer
```

3. Install dependencies:

```bash
npm install
```

4. Start the development server:

```bash
npm run dev
```

---

## 🧩 How It Works

* The app uses React's `useState` hook to store the current background color.
* Clicking a button triggers an event handler.
* The handler updates the state using `setColor()`.
* React re-renders the UI with the new background color.

---

## 💡 Key Concept

Event handlers in React require a **function reference**, not a function call.

```jsx
onClick={() => changeColor("red")}
```

This ensures the function runs **only when the button is clicked**, not during render.

---

## 🎯 Future Improvements

* 🎨 Add more color options
* 🌈 Color picker input
* 💾 Save selected color in local storage
* ✨ Smooth transition animations

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

Built as a beginner-friendly project to understand React state and event handling.
