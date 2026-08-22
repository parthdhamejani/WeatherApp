# 🌤️ WeatherApp

A responsive React weather application built with Tailwind CSS that allows users to look up real-time weather information and forecasts for cities around the globe.

---

## 🚀 Features

- **Live Weather Updates:** Search for any city to fetch real-time temperature, humidity, wind conditions, and weather descriptions.
- **Tailwind CSS Styling:** Modern, mobile-first visual styling configured via PostCSS.
- **Environment API Integration:** Clean environment variable configuration for secure API key management.
- **Responsive Interface:** Adaptive layout optimized across desktop, tablet, and mobile displays.

---

## 🛠️ Tech Stack

- **Framework:** React.js
- **Styling:** Tailwind CSS, PostCSS
- **State & Logic:** React Hooks
- **Data Source:** Weather API (OpenWeatherMap or equivalent)

---

## 📁 Project Structure

```text
WeatherApp/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   ├── logo192.png
│   ├── logo512.png
│   ├── manifest.json
│   └── robots.txt
├── src/
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
├── .env
├── .gitignore
├── package.json
├── package-lock.json
├── postcss.config.js
└── tailwind.config.js
```

---

## ⚙️ Installation & Setup

Follow these steps to set up and run the project locally:

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/parthdhamejani/WeatherApp.git](https://github.com/parthdhamejani/WeatherApp.git)
   ```

2. **Navigate into the project directory:**
   ```bash
   cd WeatherApp
   ```

3. **Install project dependencies:**
   ```bash
   npm install
   ```

4. **Set up environment variables:**
   - Create or update the `.env` file in the root folder.
   - Add your Weather API key:
     ```env
     REACT_APP_WEATHER_API_KEY=your_api_key_here
     ```

5. **Start the development server:**
   ```bash
   npm start
   ```

6. **Open in browser:**
   Navigate to `http://localhost:3000` to view the application.

---

## 📜 Available Scripts

In the project directory, you can run:

- `npm start` — Runs the application in development mode.
- `npm test` — Launches the test runner.
- `npm run build` — Builds the application for production to the `build` folder.
```
