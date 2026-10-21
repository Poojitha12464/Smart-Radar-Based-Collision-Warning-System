# Smart Radar-Based Collision Warning System

## 📌 Project Overview

The **Smart Radar-Based Collision Warning System** is a Python-based software simulation designed to demonstrate radar monitoring, moving-object tracking, and collision risk prediction.

The system displays a radar screen with moving objects and predicts potential path conflicts using object positions and velocities. It provides real-time safety alerts to help identify potentially dangerous situations.

This project demonstrates the basic principles of radar visualization, motion analysis, and collision warning systems.

## 🎯 Objectives

- Simulate a radar screen with a rotating radar sweep.
- Track multiple moving objects in real time.
- Calculate the distance between the radar center and tracked objects.
- Predict potential collisions using relative motion.
- Display SAFE, CAUTION, and DANGER warning levels.
- Maintain a history of warning status changes.
- Provide interactive controls to pause, resume, reset, and adjust vehicle speed.

## ✨ Features

- **Live Radar Visualization:** Displays radar circles, cross lines, and a rotating sweep.
- **Moving Object Simulation:** Simulates objects moving with different velocities.
- **Collision Prediction:** Estimates potential path conflicts and time to closest approach.
- **Safety Status Monitoring:** Displays SAFE, CAUTION, or DANGER based on the simulation's predictions.
- **Object Distance Monitoring:** Shows the distance to the nearest object.
- **Safety Statistics:** Displays counts of safe, nearby, and risky objects.
- **Warning History:** Records recent changes in the warning status.
- **Interactive Controls:** Supports Pause, Resume, Reset Simulation, and vehicle speed adjustment.
- **Sound Alerts:** Provides alerts when the warning status changes to CAUTION or DANGER.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **GUI:** Tkinter
- **Mathematics:** Python `math` module
- **Sound Alerts:** Python `winsound` module
- **Time and Warning History:** Python `datetime` module

## ⚙️ How It Works

1. The simulation initializes multiple objects with starting positions and velocities.
2. The objects move according to their assigned velocities.
3. The system calculates each object's distance from the radar center.
4. Relative motion is used to estimate potential path conflicts.
5. The system determines the current warning level.
6. The radar screen displays object positions, distances, predictions, and safety statistics.
7. Warning history and sound alerts respond to changes in the warning status.

## 💻 Requirements

- Windows operating system
- Python 3 installed
- Tkinter (usually included with standard Python installations)
- `winsound` (included with Windows Python installations)

No additional Python packages are normally required.

## 🚀 Installation and Execution

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/smart-radar-collision-warning.git
```

### 2. Open the project folder

```bash
cd smart-radar-collision-warning
```

### 3. Run the program

```bash
python radar.py
```

Alternatively, open `radar.py` in Visual Studio Code and run it using the Python extension.

## 🎮 Controls

| Control | Function |
|---|---|
| Pause | Pauses the simulation |
| Resume | Restarts the simulation |
| Reset Simulation | Resets objects and radar angle |
| Vehicle Speed | Adjusts the simulated vehicle speed |

## 📊 Warning Levels

- **SAFE:** No predicted path conflict is detected by the simulation, and the nearest object is outside the caution distance.
- **CAUTION:** An object is nearby and requires attention.
- **DANGER:** A potential path conflict is predicted.

These warning levels depend on the simulation's configured thresholds and prediction logic.

## 📁 Project Structure

```text
smart-radar-collision-warning/
│
├── radar.py
└── README.md
```

## 🎓 Learning Outcomes

- Python programming and event-driven GUI development.
- Real-time graphical animation using Tkinter.
- Object tracking and distance calculations.
- Relative velocity and collision prediction.
- Conditional logic for safety warnings.
- Interactive simulation controls and status monitoring.

## 🔮 Future Improvements

- Add a detailed object tracking table.
- Introduce more realistic radar detection and sensor noise.
- Display object trajectories and predicted collision points.
- Add data logging and simulation reports.
- Explore integration with real sensors or hardware.

## ⚠️ Limitations

This project is a **software-based radar simulation**. It does not use real radar hardware, and its collision predictions are based on simplified motion assumptions. It is intended for educational and demonstration purposes, not as a real-world vehicle safety system.

## 👩‍💻 Author

**P Poojitha**

## 📄 License

This project is available for educational and learning purposes. Add a license file if you intend to distribute it under a specific open-source license.
