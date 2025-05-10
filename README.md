# Eye Training Animation App

This is a browser-based eye training animation app built with **HTML** and **JavaScript**. It guides users through various eye movements using animated visuals and (planned) voice prompts.

---

## 🚀 Features (Current)

- Animated visual eye movement guidance.
- All logic and markup are currently inside a single `index.html` file.
- Built using the [p5.js](https://p5js.org/) JavaScript library.

---

## 🛠️ Getting Started Locally (Using Node.js)

This project can be run locally using a simple Node.js static server. Follow the steps below:

### 1. Install Node.js

Download and install Node.js from: [https://nodejs.org](https://nodejs.org)
To check installation, run:

```bash
node -v
npm -v
```

---

### 2. Install `http-server`

Install the `http-server` package globally:

```bash
npm install -g http-server
```

---

### 3. Run the Project

Navigate to the project directory (where `index.html` is located):

```bash
cd path/to/eye-training-app
http-server
```

You’ll see output like this:

```
Starting up http-server, serving ./
Available on:
  [http://127.0.0.1:8080](http://127.0.0.1:8080)
```

Open the provided local URL in your browser to view the app.

---

## 🧠 Code Overview

Currently, the application includes:

* `index.html` — contains both HTML structure and embedded JavaScript.
* Uses the `p5.js` library for animations.
* Animations guide the user to follow specific eye movement patterns (e.g., left-right, up-down, circular paths).
* Voice prompts are planned for future integration to enhance interactivity.

---

## 📦 Roadmap / Improvements

* ✅ **Step 1:** Build prototype with all code in `index.html`. *(done)*
* 🔜 **Step 2:** Refactor code by separating:
    * HTML (`index.html`)
    * JavaScript (`script.js`)
    * CSS (if needed)
    * Media assets (voice/audio, images)
* 🔜 **Step 3:** Add voice prompt functionality.
* 🔜 **Step 4:** Expand to different eye exercises or user customization.

---

## 🤝 Contributing

When contributing:

* Please keep code modular and readable.
* Use separate files for HTML, JS, and assets moving forward.
* Add comments for clarity.
* Update this README with any new dependencies or features.

---

## 📁 Project Structure (Future Layout)

```
eye-training-app/
├── index.html      # HTML markup only
├── script.js       # JavaScript logic (to be moved from index.html)
├── style.css       # (optional) styling
├── assets/         # images, sounds, etc.
└── README.md
```
