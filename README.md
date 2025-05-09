# 🚦 Traffic Light Control System Based on Vehicle Density
📌 Project Description
This JavaFX-based simulation models a smart traffic light system that dynamically adjusts green light durations based on real-time vehicle density at a four-way intersection. It aims to reduce congestion caused by static signal timings by applying adaptive signal logic.

🎯 Key Features
✅ Four-directional intersection (North, South, East, West)

✅ Dynamic green light timing proportional to vehicle count

✅ Constant yellow light duration (e.g., 3 seconds)

✅ Real-time animated traffic flow with no collisions

✅ GUI-based input: manual or random vehicle density

✅ Signal timers and car movements synchronized to phase logic

✅ Fully MVC-compliant architecture with OOP principles

🧠 Signal Timing Logic
Total cycle time: 120 seconds

Green time range: 10–60 seconds, based on density

Example distribution:

Direction	Vehicles	Share (%)	Green Time
North	40	50%	60 sec
South	20	25%	30 sec
East	10	12.5%	15 sec
West	10	12.5%	15 sec

🖥️ GUI Components
🛣️ Central intersection visualization with signals

🧮 Vehicle density inputs or random generator

⏱️ Countdown timers for each signal phase

🚗 Animated car logic:

Waits at red

Proceeds on green

Disappears post-intersection

🎮 Controls: Start, Pause, Reset

⚙️ Technologies Used
Language: Java (SE)

GUI: JavaFX

Architecture: MVC

Libraries: Java Collections (No third-party dependencies)

📂 Project Structure
css
Kopyala
Düzenle
src/
├── controller/
├── model/
├── view/
└── Main.java
🚀 Running the Project
Compile with a Java 8+ environment.

Launch the application from Main.java.

Use GUI to configure vehicle density and start simulation.

📎 Deliverables
✅ Java source files

✅ README file

✅ Project report with diagrams

🎥 (Optional) Simulation video or GIF
