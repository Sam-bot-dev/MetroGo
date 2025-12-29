# 🚇 MetroGo – Gandhinagar & Ahmedabad Metro Navigator

MetroSense is a **map-based metro navigation system** designed to guide passengers across **Gandhinagar & Ahmedabad Metro** stations.  
It provides **nearest metro detection, metro-to-metro routing along real metro paths, search navigation, and live station markers fetched dynamically from OpenStreetMap**.

### 🎯 Core Functionalities
| Feature | Status |
|--------|--------|
| Auto user location detection | ✅
| Fetch all metro stations dynamically from OSM | ✅
| Accurate metro line plotting (manual GIS) | ✅
| Metro-to-metro path routing using line geometry | ✅
| Real routing when typing station name or clicking marker | ✅
| Dynamically show nearest station | ✅
| Chip shortcuts for quick navigation | ✅
| Dark theme UI | 🌙 Default
| Auto location fill into input fields | 🚀 Fast & Optimized
| Works in browser + can be wrapped into APK | 📱 Ready

---

## 🖼 UI Preview
(attach screenshots after hosting)

---

## 🧭 How Navigation Works

MetroSense does not draw random straight routing lines.  
Instead:

1️⃣ User location detected  
2️⃣ Nearest metro is calculated  
3️⃣ Only **valid metro corridor paths** are drawn  
4️⃣ Clicking or typing destination shows **path along metro**  

> **Blue line → full metro corridor**  
> **Yellow line → your route along metro**

---

## 🏗 Tech Stack

| Layer | Technology |
|--------|------------|
| **Frontend** | HTML, Tailwind CSS, JavaScript |
| **Map Rendering** | Leaflet.js |
| **Routing** | Leaflet Routing Machine (only for nearest calculation) |
| **Station Data** | Dynamic OSM Overpass API fetch |
| **Metro Geometry** | Manual geo-coordinates for accuracy |
| **APK Packaging (optional)** | PWA → WebView → Android Studio |

---

## 📦 Setup

Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/MetroSense.git
cd MetroSense
