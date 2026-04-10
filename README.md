Emergency Corridor — AI-Powered Dhaka Simulator
An interactive, high-fidelity simulation designed to visualize and analyze emergency vehicle movement through the dense traffic of Dhaka, Bangladesh. The project leverages AI-driven path clearing and real-time impact metrics to demonstrate how intelligent traffic management can save lives.

✦ Core Features
Real-Time Traffic Simulation: Simulates a dynamic environment with up to 800 individual drivers on a route through key Dhaka locations like Banani, Mohakhali, and Kawran Bazar.

AI Corridor Analysis: Utilizes a simulated integration of Claude-4 to perform live analysis of the corridor, providing localized insights and priority clearing strategies.

Emergency Mode: Activating the emergency siren triggers a visual "priority ring" and forces surrounding drivers to transition into different states: "Normal," "Pulling Aside," "Transitioning," or "All Clear".

Impact Dashboard: A live metrics suite tracking:

Time Saved: Cumulative seconds gained through efficient clearing.

Corridor Clearance: Percentage of the emergency zone currently cleared.

Lives at Risk: A critical status indicator based on simulation performance.

Automated Violation System: A "Violations" panel tracks and logs license plates of drivers who fail to yield to the emergency vehicle.

Route Planner: Allows users to calculate paths between major Dhaka medical facilities, including Dhaka Medical College, Square Hospital, and Apollo Hospitals.

🛠 Technology Stack
Frontend: HTML5, CSS3 (Custom "Space Mono" and "Barlow Condensed" typography).

Mapping: Leaflet.js for interactive map rendering and coordinate handling.

Map Tiles: CARTO Dark Matter for a high-contrast, professional aesthetic.

Animations: Custom CSS keyframes for siren pulses, AI "cognition" effects, and skeleton loaders.

🚦 Interactive Controls
Emergency Toggle: Activate/Deactivate the ambulance siren and AI analysis.

Simulation Speed: Adjust the time scale from 1× to 6×.

Traffic Volume: Dynamically change the number of vehicles on the road (50 to 800).

Manual Reset: Instantly reset the simulation state and vehicle position to the Banani starting point.

📍 Key Locations Supported
The simulator includes pre-defined coordinates for major Dhaka hospitals:

Dhaka Medical College Hospital

Square Hospital

United Hospital

Labaid Hospital

Ibn Sina Hospital Dhanmondi

Bangabandhu Sheikh Mujib Medical University (BSMMU)
