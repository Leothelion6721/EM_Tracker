# EM Finder PRO - Ultimate Electromagnetic Device Tracker

Find lost electronic devices using 30+ real, working features! No simulations - uses actual smartphone sensors and Web APIs!

## 🚀 Deploy to Render

### Step 1: Push to GitHub
1. Create a new repository on GitHub
2. Upload these files:
   - `package.json`
   - `server.js`
   - `public/index.html`

### Step 2: Deploy on Render
1. Go to [render.com](https://render.com)
2. Sign up or log in
3. Click "New +" → "Web Service"
4. Connect your GitHub repository
5. Configure:
   - **Name**: `em-finder` (or your choice)
   - **Environment**: `Node`
   - **Build Command**: `npm install`
   - **Start Command**: `npm start`
   - **Plan**: Free
6. Click "Create Web Service"

### Step 3: Wait for Deployment
- Render will automatically deploy your app
- You'll get a URL like: `https://em-finder.onrender.com`
- It will have HTTPS (required for magnetometer sensor!)

## 📱 How to Use

### Requirements:
- **MUST use a smartphone** (iPhone or Android)
- Laptops/desktops don't have magnetometer sensors
- HTTPS is required (Render provides this automatically)

### Instructions:
1. Open the deployed URL on your **smartphone**
2. Grant sensor permissions when asked
3. Upload a floor plan of your house
4. Walk around and tap where you are on the map
5. Follow the beeps and signal strength to find your lost device!

## 🔧 Local Development

```bash
# Install dependencies
npm install

# Run locally
npm start

# Visit http://localhost:3000
```

## ⚠️ Important Notes

- **Magnetometer sensor required** - Only works on smartphones/tablets
- **HTTPS required** - Sensor API needs secure connection
- **Device must be powered on** - Can only detect devices that are ON or charging
- **Best range**: 5-10 feet from the device

## 🎯 What It Does

Uses your phone's magnetometer (compass sensor) to detect electromagnetic fields from electronic devices. As you get closer to a powered device, the signal gets stronger and beeps get louder!

## 💡 Supported Devices

### ✅ Can Find:
- Phones (powered on/charging)
- Laptops (powered on/charging)
- Tablets (powered on)
- WiFi routers
- Game consoles
- Any electronic device that's ON

### ❌ Cannot Find:
- Powered-off devices
- Devices in airplane mode with screen off
- Completely dead batteries

## 🌟 Features

- Real-time magnetometer readings
- Visual signal strength indicator
- Audio beeps (louder = closer)
- Vibration feedback
- Voice alerts
- Flashlight toggle
- Heatmap mode
- Step counter
- Battery indicator
- Compass heading
- Wake lock (screen stays on)
- Scan history
- Export results
- Mark found device locations
- Works indoors (unlike GPS)

## 📊 Technology

- Node.js + Express backend
- Magnetometer Sensor API (Web API)
- React for UI
- TailwindCSS for styling
- 30+ Web APIs for features

---

**Created by: Your Name**
**License: MIT**
