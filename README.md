## 💰 Expense-Tracking-System
A full-stack Python application for managing and visualizing personal expenses
Frontend: 🎨 Streamlit | Backend: ⚡ FastAPI | Testing: ✅ Pytest

###📌 Overview
The Expense-Tracking-System is a simple yet powerful tool to help users log, categorize, and analyze their spending. With a clean Streamlit interface and a fast FastAPI backend, it offers a seamless and responsive experience for everyday financial tracking.

##✨ Key Features
📝 Add & categorize expenses with date and description.
📊 Visualize spending trends using bar charts, line graphs, and pie charts.
⚡ Fast, scalable backend with interactive API docs (Swagger UI).
🗂 Modular architecture for easy maintenance and scaling:
🎨 frontend/ — Streamlit app for user interaction.
⚙️ backend/ — FastAPI services and endpoints.
🧪 tests/ — Pytest for automated unit & integration tests.
🛡 Robust test coverage to ensure reliability.

##🚀 Why This Project Stands Out
✅ Demonstrates end-to-end development: UI, API, and testing.
📈 Data-driven insights with real-world utility.
🛠 Built with modern Python frameworks and best practices.

##🛠 Installation & Setup
1️⃣ Clone the Repository
```bash
git clone https://github.com/AquasaAziz247/Expense-Tracking-System.git
cd Expense-Tracking-System
```
2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
3️⃣ Run the Backend
```bash
uvicorn backend.server:app --reload
```
4️⃣ Launch the Frontend
```bash
streamlit run frontend/app.py
💡 This opens the app in your browser for interactive expense tracking.
```
🧪 Running Tests
```bash
pytest tests/
Ensures all components remain robust & error-free.
```

## Project Structure

Expense-Tracking-System/
├─ backend/       ⚡ FastAPI endpoints & logic
├─ frontend/      🎨 Streamlit app UI
├─ tests/         🧪 Unit & integration tests
├─ requirements.txt 📦 Dependencies
└─ README.md       📄 Project documentation

##🛠 Tech Stack
⚡ FastAPI — High-performance API framework with automatic docs.
🎨 Streamlit — Rapid UI development for data apps.
✅ Pytest — Simple, powerful testing framework.
