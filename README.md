# ⚡ VoltPath — Smart EV Trip Planner

An industry-level EV monitoring and trip planning web application.

## 🚀 Setup Instructions (Step by Step)

### Step 1: Install Node.js
1. Go to https://nodejs.org
2. Download **LTS version** (the green button)
3. Install it (just click Next → Next → Install)
4. To verify: open Terminal/Command Prompt and type: `node --version`

### Step 2: Install VS Code (if not installed)
1. Go to https://code.visualstudio.com
2. Download and install

### Step 3: Get the Project
If you downloaded the zip:
- Extract the folder somewhere (e.g., Desktop)

If cloning from GitHub:
```bash
git clone https://github.com/YOUR_USERNAME/ev-trip-planner.git
```

### Step 4: Open in VS Code
1. Open VS Code
2. File → Open Folder → select `ev-trip-planner` folder

### Step 5: Install Dependencies
Open the **Terminal** in VS Code (View → Terminal) and type:
```bash
npm install
```
Wait for it to finish (takes 1-2 minutes).

### Step 6: Run the Website
```bash
npm start
```
The website will open at: **http://localhost:3000**

### Login Credentials
- Email: `demo@voltpath.com`
- Password: `demo123`
- (Any email + password also works)

---

## 🌐 Deploy to Netlify (Share with Anyone via URL)

### Step 1: Build the Project
```bash
npm run build
```

### Step 2: Deploy to Netlify (Free)
1. Go to https://www.netlify.com → Sign Up (free)
2. Click **"Add new site"** → **"Deploy manually"**
3. Drag and drop the **`build`** folder into the Netlify window
4. Your site is LIVE! You'll get a URL like: `https://amazing-app-123.netlify.app`

Share this URL with anyone — no VS Code needed!

---

## 📤 Upload to GitHub

### Step 1: Install Git
- Download from https://git-scm.com → install

### Step 2: Create GitHub Account
- Go to https://github.com → Sign Up

### Step 3: Create Repository
1. Click the **+** button → New repository
2. Name it: `ev-trip-planner`
3. Click **Create repository**

### Step 4: Push Code
In VS Code terminal:
```bash
git init
git add .
git commit -m "Initial commit - VoltPath EV Trip Planner"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ev-trip-planner.git
git push -u origin main
```

---

## 📁 Project Structure
```
ev-trip-planner/
├── public/
│   └── index.html          ← Main HTML file
├── src/
│   ├── components/
│   │   └── Sidebar.js      ← Navigation sidebar
│   ├── pages/
│   │   ├── Login.js        ← Login page
│   │   ├── Dashboard.js    ← Main dashboard
│   │   ├── TripPlanner.js  ← Route planning
│   │   ├── ChargingStations.js ← EV chargers
│   │   ├── Analytics.js    ← Charts & data
│   │   └── Alerts.js       ← Fault alerts
│   ├── App.js              ← Main app
│   ├── index.js            ← Entry point
│   └── index.css           ← Global styles
└── package.json
```

## 🎯 Features
- ✅ Login page with authentication
- ✅ Real-time dashboard with live battery simulation
- ✅ Trip planner with charging stop calculation
- ✅ Charging station locator with live status
- ✅ Analytics with charts (battery, range, efficiency)
- ✅ Smart alerts (low battery, overheating, tyre pressure)
- ✅ Google Maps integration
- ✅ Industry-level dark UI design
