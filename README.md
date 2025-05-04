
# 💻 Nexus PC – Smart Custom PC Builder

**Nexus PC** is an intelligent PC-building assistant that recommends optimal components based on your **budget**, **performance goals**, and **compatibility**. Powered by a **React.js frontend** and a **Python machine learning backend**, it simplifies the process of building your dream PC — whether you're a gamer, creator, or developer.

---

## 👨‍💻 Team Members

| Name              | Roll Number     |
|-------------------|-----------------|
| Kunal Yadav       | 2401730157       |
| I.K Kevin Samuel  | 2401730178       |
| Devesh Kumar      | 2401730150       |
| Vikash Kumar      | 2401730185       |

---

## 📽️ Video Demonstration

📹 **Watch the Demo** → https://drive.google.com/file/d/19xdgmff9oLtlZ2QgTPJGuCYfiAbEll8y/view?usp=sharing

---

## 📄 Project Report

📘 **Download Full Report (PDF)** → https://github.com/KUNALYADAV4258/Kunal_Yadav_CSE-AI-ML--D_NexusPc/blob/main/Mini%20Project%20Report.pdf

---

## 🌐 GitHub Repository

🔗 **Clone or visit the GitHub Repo** → https://github.com/KUNALYADAV4258/Kunal_Yadav_CSE-AI-ML--D_NexusPc

---

## 🛠️ Tech Stack

### 💡 Frontend
- React.js (with Vite)
- HTML, CSS, JavaScript
- Chart.js (for benchmark charts)
- Styled Components

### 🔍 Backend
- Python
- Flask (or FastAPI)
- Scikit-learn
- Pandas, NumPy

---

## 📁 Folder Structure

```
NexusPC/
├── .vscode/                    # VSCode settings (optional)
├── mlbackend/                  # Machine learning backend
│   ├── cpu_model.pkl
│   ├── gpu_model.pkl
│   ├── ram_model.pkl
│   ├── psu_model.pkl
│   ├── motherboard_model.pkl
│   ├── label_encoders.pkl
│   ├── expanded_gpu_recommendation.csv
│   ├── server.py               # API server for ML model
│   └── train_models.py         # Model training script
│
├── my-react-app/               # Frontend React application
│   ├── node_modules/           # Project dependencies
│   ├── public/                 # Public assets
│   ├── src/                    # Source code
│   │   ├── assets/             # Images, icons, etc.
│   │   ├── components/         # React UI components
│   │   ├── App.jsx             # Main app component
│   │   ├── App.css             # Global styles
│   │   ├── index.css           # Base styles
│   │   └── main.jsx            # Entry point
│   ├── index.html
│   ├── package.json
│   ├── vite.config.js
│   └── README.md
```

---

## 🚀 Getting Started

### 📦 Prerequisites
- [Node.js & npm](https://nodejs.org/)
- [Python 3.x](https://www.python.org/)
- [7-Zip](https://www.7-zip.org/) (for archive extraction)

---

### 📥 Step 1: Download and Extract

1. Download these two files:
   - `Minor project.7z.001`
   - `Minor project.7z.002`
2. Place them in the **same folder**.
3. Right-click on `Minor project.7z.001` → Select **Extract Here** (with 7-Zip).
4. Both parts will extract automatically into the full project.

---

### 🧠 Step 2: Run the ML Backend

```bash
cd mlbackend
python -m venv venv
venv\Scripts\activate         # On Windows
# or
source venv/bin/activate      # On Linux/macOS

pip install -r requirements.txt
python server.py
```

> 🧠 Your backend is now live and serving recommendations.

---

### 🌐 Step 3: Run the React Frontend

```bash
cd my-react-app
npm install
npm run dev
```

> Open your browser at [http://localhost:3000](http://localhost:3000)

---

## 🧠 Features

- ✅ **Smart Recommendations** (GPU, CPU, RAM, PSU, Motherboard)
- 💬 **Chatbot Support** to guide beginners
- 🎯 **Performance Tiers**: Budget, Mid-range, High-end
- 📊 **Component Benchmarks** with Chart.js
- ✨ **Responsive UI** with a clean, modern design

---

## 📜 License

This project is part of an academic minor project and is intended for educational purposes only. Feel free to use it for learning, portfolio, or further development.

---

## 🙌 Acknowledgements

Special thanks to our mentors and faculty at **CSE - AI & ML Department** for guiding us through the project and development journey.

---
