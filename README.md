# 🌍 Real-Time GPS Location Tracking System

A real-time web application that tracks and visualizes user location on an interactive map using **Node.js**, **Socket.IO**, and **Leaflet.js**.  
Every connected user can share their live GPS position, and all clients will see movements instantly on the map.

---

## 🚀 Features

✅ Live GPS tracking for all connected users  
✅ Real-time updates using WebSockets (Socket.IO)  
✅ Interactive map visualization with Leaflet  
✅ Automatically sets markers for new users  
✅ Removes marker when a user disconnects  
✅ Works on mobile (supports smartphone geolocation)

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| Backend  | Node.js, Express.js, Socket.IO |
| Frontend | JavaScript, Leaflet.js, EJS |
| Styling  | CSS (custom) |
| Communication | WebSockets |
| Map Tiles | OpenStreetMap / Leaflet |

---

## 📁 Folder Structure
```
project-folder/
│── app.js
│── package.json
│
├── public/
│ ├── css/
│ │ └── style.css
│ └── js/
│ └── script.js
│
└── views/
└── index.ejs
```
