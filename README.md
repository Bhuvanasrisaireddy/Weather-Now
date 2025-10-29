# 🌤 Weather Now

## 👤 User Personal
**Name:** Jamie  
**Occupation:** Outdoor Enthusiast  
**Need:** Jamie wants to check the current weather conditions quickly for any city.

---

## 🧠 Project Overview
**Weather Now** is a simple and fast React web app that allows users to search for any city and instantly view the current temperature, wind speed, and update time.  

The application uses **OpenStreetMap (Nominatim)** to convert city names into coordinates and the **Open-Meteo API** to fetch real-time weather data — both are completely free and require no authentication.

This project was developed as part of a UI challenge to demonstrate:
- Understanding of user requirements  
- Building with React.js and CSS  
- Clean UI and responsive design  
- API integration and state management  

---

## ⚙️ Tech Stack
- ⚛️ **React (Vite)** — Front-end framework  
- 🎨 **CSS** — Styling  
- 🌍 **OpenStreetMap Nominatim API** — For geocoding city names  
- ☁️ **Open-Meteo API** — For current weather data  
- 🖥️ **StackBlitz** — For hosting and live demo  

---

## 🚀 Features
✅ Search for any city around the world  
🌡 Shows current temperature (°C)  
💨 Displays wind speed and updated time  
🧭 Uses free public APIs (no key needed)  
📱 Responsive and clean UI  
⚙️ Built with modern React hooks (useState)  

---

## 🧩 File Structure
```

project/
├── public/
│   └── vite.svg
├── src/
│   ├── App.tsx
│   ├── App.css
│   ├── main.tsx
│   └── ...
├── index.html
├── package.json
├── README.md
└── vite.config.ts

```

---

## 📦 APIs Used

### 1️⃣ OpenStreetMap (Nominatim)
Used to fetch city coordinates (latitude and longitude)
```

[https://nominatim.openstreetmap.org/search?city={CITY}&format=json](https://nominatim.openstreetmap.org/search?city={CITY}&format=json)

```

### 2️⃣ Open-Meteo
Used to fetch current weather details
```

[https://api.open-meteo.com/v1/forecast?latitude={LAT}&longitude={LON}&current_weather=true](https://api.open-meteo.com/v1/forecast?latitude={LAT}&longitude={LON}&current_weather=true)

````

---

## 🧪 How to Run Locally

1. **Clone or download** this repository  
2. **Install dependencies**
   ```bash
   npm install
````

3. **Start development server**

   ```bash
   npm run dev
   ```
4. **Open your browser** at:

   ```
   http://localhost:5173/
   ```

---

## 🌍 Live Demo

**Hosted on StackBlitz:**
👉 [https://your-project-name.stackblitz.io](https://your-project-name.stackblitz.io)
*(Replace this link with your actual StackBlitz public URL)*

---

## 🧾 Submission Levels

| Level             | Description                    | Status                 |
| ----------------- | ------------------------------ | ---------------------- |
| **Level 1 (50%)** | Shared ChatGPT discussion link | ✅ Included             |
| **Level 2 (30%)** | Working hosted app             | ✅ StackBlitz live link |
| **Level 3 (20%)** | Source code with README        | ✅ This file            |

---

## 🧠 Approach

1. **Requirement Understanding:**

   * The user (Jamie) wants a quick weather lookup for any city.
   * Must use React and a free, no-auth API.

2. **Design Choices:**

   * Minimal UI with centered layout and instant feedback.
   * Responsive design using basic CSS (no external libraries).

3. **Implementation Steps:**

   * Fetch coordinates using Nominatim API.
   * Use latitude/longitude to fetch weather data from Open-Meteo.
   * Handle loading, errors, and empty responses gracefully.

4. **Testing:**

   * Tested with multiple city names (Delhi, London, Tokyo, Paris).
   * Verified data accuracy and response times.

---

## ⚠️ Challenges & Learnings

* **Challenge:** Open-Meteo requires lat/lon, so needed a second API (Nominatim) to convert city names.
* **Solution:** Implemented async API chaining with error handling.
* **Learning:** Gained hands-on experience with real-world API integration, state management, and minimal deployment setup.

---

## 🙌 Credits

Developed by **Bhuvana**
Guided through **ChatGPT (AI-assisted development)**
APIs courtesy of **Open-Meteo** and **OpenStreetMap**
Hosted on **StackBlitz**

---

## 🏁 Summary

This project demonstrates practical React.js skills — handling user input, API integration, state management, and deploying on a free cloud platform — all focused on delivering a clean, functional experience for the end user (Jamie).

---

```

---
```
