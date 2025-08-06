# 📱 Geotech Logging App

A mobile-first logging tool designed for field technicians to capture and manage geotechnical test data in real-time — even offline.

---

## 🛠 Built With

- **React Native + Expo**
- **SQLite** for offline data storage
- **Expo Location** for GPS tagging
- **Dark/Light Mode** via context toggle
- **Reusable components** with modular architecture

---

## 🎯 Key Features

### ✅ Job Management
- Create/edit geotechnical jobs
- Stores project metadata: client, contractor, engineer, location
- Local-only (offline) storage via SQLite

### ✅ Geotechnical Test Logging
Each job supports these test types:

| Test Type   | Description |
|-------------|-------------|
| **CPT**     | Cone Penetration Testing — with zero checks, tolerance validation, GPS |
| **SCPT**    | Seismic CPT — with arrival times, polarity, Vs calculations |
| **Dissipation** | Pore pressure calculation at t10, t50, t90, t100 |
| **DPSH**    | Dynamic probing with depth and blow count rows |
| **DMT/SDMT** | Coming soon... |

### ✅ Offline-First Design
- Works fully without mobile signal
- GPS captured automatically
- Plans for sync-to-cloud (e.g. M-Files) in future

---

## 🔒 Planned Features

- Cloud sync with M-Files or Firebase
- Export to CSV and JSON for reporting
- Add calibration + prestart safety forms
- Cross-device login support

---

## 🚀 Getting Started

### 📦 Clone & Install
```bash
git clone https://github.com/CassJah/geotech-log-app.git
cd geotech-log-app
npm install
npx expo start
