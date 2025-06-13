# 🎧 ADSIFT - Static FM Web App (with Ads)

This is a **frontend-only React web application** that serves as a mock FM radio interface. It simulates an FM station dashboard and audio player **without any backend integration or advertisement detection logic**.

> ✅ No API or ML model is connected in this version.  
> ❌ Does not skip or detect advertisements.

---

## 🌐 Live Demo

🔗 [View on GitHub Pages](https://kavin-antony.github.io/ADSIFT-WEB_APP_REACT_WITH_AD/)

---

## 📁 Project Structure

```markdown
ADSIFT-WEB_APP_REACT_WITH_AD
├── public/                  # Static files (images, station logos)
├── src/
│   ├── assets/              # React logo SVGs and images
│   ├── components/          # UI Components (AudioPlayer, Sidebar, etc.)
│   ├── styles/              # CSS for each component
│   ├── App.jsx              # App layout and logic
│   └── main.jsx             # App entry point
├── .github/workflows/       # GitHub Actions for deployment
├── index.html               # Base HTML file
├── package.json             # Dependencies and scripts
├── vite.config.js           # Vite configuration
└── README.md                # You’re reading it!
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/Kavin-Antony/ADSIFT-WEB_APP_REACT_WITH_AD.git
cd ADSIFT-WEB_APP_REACT_WITH_AD
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the App Locally
```bash
npm run dev
```

### 💡 Features
	•	📻 FM radio station list UI
	•	🎵 Audio player to simulate streaming
	•	🖼️ Station logos and UI components
	•	💻 Fully static React app — no server required

### 📌 Limitations
	•	No backend or API calls
	•	Does not detect or skip ads
	•	Audio sources are static or stream URLs

