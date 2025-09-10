Project Title: ABCONS Technology – Smart River & Nala Management
Team ID: TH2025-ABCONS

1. Overview:
ABCONS Technology is a nature-based, patent-backed water treatment system that uses diatoms, floating bio-islands, UV disinfection, and IoT-based monitoring to restore river and nala water quality. Designed for Simhasth 2028, it ensures safe, clean, and sustainable water for millions of pilgrims while lowering O&M costs and reducing carbon footprint.

2. Problem & Solution
• Problem Statement:
Rivers and nalas around Ujjain face heavy pollution due to untreated sewage, solid waste inflow, and lack of real-time monitoring, creating severe health, sanitation, and ecological risks during Simhasth.

• Solution:
ABCONS Technology integrates modular phycoremediation units, IoT-based SCADA monitoring, floating bio-islands, and decentralized UV disinfection channels to treat sewage at source, rejuvenate water bodies, and provide continuous monitoring dashboards for authorities and citizens.

3. Logic & Workflow
• Data Collection: Real-time sensors for flow rate, BOD, COD, pH, DO, and turbidity.
• Processing: AI-enabled decision engine + diatom-based phycoremediation + aeration + bio-island treatment.
• Output: Treated water with improved clarity, safe for religious, ecological, and recreational purposes.
• User Side: Pilgrims and citizens access a public dashboard showing real-time water quality.
• Admin Side: Municipal bodies get a control panel with SCADA + IoT integration for monitoring and alerts.

4. Tech Stack
Frontend: React.js + Tailwind CSS
Backend: Node.js + Express
Database: MongoDB / PostgreSQL
AI/Processing: Python (for diatom growth, water quality predictions)
IoT/Monitoring: Arduino/Raspberry Pi + SCADA sensors
APIs: Google Maps API, ThingSpeak/IoT Cloud
Hosting: Firebase / AWS

5. Future Scope
- AI-powered predictive maintenance for water treatment.
- Mobile app integration for public awareness and citizen reporting.
- Multi-city scalability across river stretches and nalas.
- Blockchain-based water quality transparency.
- Integration with national Clean Ganga Mission.

6. Code Repository Link
Public Repository:
https://github.com/abconsinfrallp-arch/Simhasth-Hackathon-ABCONS

Instructions to Run Prototype:
1. Clone the Repository
   git clone https://github.com/abconsinfrallp-arch/Simhasth-Hackathon-ABCONS.git
   cd Simhasth-Hackathon-ABCONS

2. Frontend
   cd frontend
   npm install
   npm start
   - Access the dashboard at http://localhost:3000

3. Backend
   cd backend
   npm install
   npm start
   - Connects IoT sensor data and handles API requests

4. IoT & Data Simulation
- Simulated sensor data is included in /iot-simulator for demonstration purposes.
- Real sensors can be connected via Arduino/Raspberry Pi + SCADA interface.

5. Dashboard Access
- Real-time water quality parameters: pH, DO, BOD, COD, turbidity, flow rate.
- Admin panel credentials:
  - Username: admin
  - Password: admin123
