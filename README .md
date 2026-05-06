# 🚀 Arju's Developer Portfolio

A clean, responsive portfolio website built with **HTML**, **CSS**, and **JavaScript** — showcasing my projects and skills as a frontend developer.

---

## 🔗 Live Demo

👉 [View Live on GitHub Pages](https://arju109.github.io/portfolio)



---

## ✨ Features

- **Responsive design** — works on all screen sizes (mobile, tablet, desktop)
- **Dark / Light mode** toggle with preference saved to `localStorage`
- **Smooth scroll** and **scroll-reveal animations** using `IntersectionObserver`
- **Typed text effect** on the hero section
- **Active nav link** highlighting based on scroll position
- **Contact form** with real-time validation
- **3 sub-projects** included (Weather App, Quiz App, To-Do App)

---

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Main portfolio page
├── style.css           # Main stylesheet
├── script.js           # Main JavaScript
├── README.md           # This file
├── .gitignore          # Git ignore rules
│
├── weather-app/
│   ├── index.html      # Weather App (OpenWeatherMap API)
│   └── style.css
│
├── Quiz-app/
│   ├── index.html      # Quiz App (10 web dev questions)
│   └── style.css
│
└── todo/
    ├── index.html      # To-Do App (localStorage persistence)
    └── style.css
```

---

## 🛠️ Built With

| Technology | Purpose |
|-----------|---------|
| HTML5 | Semantic structure |
| CSS3 | Styling, animations, responsive layout |
| JavaScript (ES6+) | Interactivity, DOM manipulation, APIs |
| Font Awesome 6 | Icons |
| Google Fonts | Typography (Syne + DM Sans) |
| OpenWeatherMap API | Weather App data |

---

## 🗂️ Sub-Projects

### ✅ To-Do App
- Add, complete, and delete tasks
- Filter by All / Active / Done
- Tasks persist after page refresh using `localStorage`

### 🌤️ Weather App
- Search weather by city name
- Displays temperature, humidity, wind speed, and feels-like
- Full error handling (invalid city, network error, bad API key)
- Uses [OpenWeatherMap API](https://openweathermap.org/)

### ❓ Quiz App
- 10 web development questions
- Real-time answer feedback (correct/wrong highlighting)
- Score tracking and final results screen
- Play again functionality

---

## ⚙️ Setup & Running Locally

1. **Clone the repo:**
   ```bash
   git clone https://github.com/your-username/portfolio.git
   cd portfolio
   ```

2. **Open in browser:**
   ```bash
   # Just open index.html in any browser — no server needed
   # Or use Live Server extension in VS Code
   ```

3. **Add your Weather API key:**
   - Get a free key at [openweathermap.org](https://openweathermap.org/api)
   - Open `weather-app/index.html`
   - Replace `YOUR_API_KEY_HERE` with your real key

---

## 🚀 Deploying to GitHub Pages

1. Push your code to a GitHub repository
2. Go to **Settings → Pages**
3. Set Source to **Deploy from a branch → main → / (root)**
4. Your site will be live at `https://your-username.github.io/portfolio`

---

## 🙋 About Me

**Arju** — B.Tech student in Materials Engineering at **IIT Gandhinagar**  
Passionate about frontend development and building things for the web.  
Currently looking for **internship opportunities**.

📧 arju.arju@iitgn.ac.in  
🐙 [GitHub](https://github.com/arju109)

---

## 📄 License

This project is open source and free to use for learning purposes.
