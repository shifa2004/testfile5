# 🚑 Ambulance Drone Doctor Monitoring System

This project is a **real-time emergency response system** that connects drones with doctors for faster medical assistance.  
It includes a **Drone Simulator** and a **Doctor Interface**, with **real-time GPS, video streaming, and monitoring features**.

---

## 📂 Project Structure
- `index.html` → Landing page (home, links to Drone & Doctor panels)
- `drone.html` → Drone interface (GPS + video feed + controls)
- `doctor.html` → Doctor interface (live monitoring, map & video)
- `server.js` → Node.js + Express + Socket.IO backend
- `package.json` → Project dependencies
- `package-lock.json` → Dependency lock file
- `images/` → Images used (team, UI, etc.)

---

## 🚀 Features
- Real-time GPS synchronization between drone and doctor  
- Two-way video call (doctor ↔ drone)  
- Drone simulation with Leaflet map integration  
- Doctor panel to monitor patients in emergencies  
- Socket.IO for live communication  

---

## 🛠️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>

2. Install Dependencies
npm install

3. Run the Server
npm start


By default, the server runs at http://localhost:8003

Open 👉 http://localhost:8003/drone.html
 → Drone view

Open 👉 http://localhost:8003/doctor.html
 → Doctor view
