 🖥️ Infra Monitoring Suite

A comprehensive dashboard solution for real-time and historical system performance monitoring using Bash scripts, Python visualizations, and a Flask-based web interface.

---

## 📊 Project Overview

**Infra Monitoring Suite** enables users to collect, analyze, and visualize essential system metrics such as CPU usage, memory consumption, disk utilization, and network traffic. It combines lightweight data collectors in Bash with rich dashboards powered by Python (Matplotlib & Plotly) to deliver actionable insights.

---

 🎯 Features

- 📡 Real-time system performance tracking
- 📁 Bash-based data collection with Cron job automation
- 📊 Visual analytics via Python (Matplotlib, Plotly)
- 🌐 Flask-powered interactive dashboard
- 🧠 Historical trend analysis
- 📦 Pre-packaged builds for Linux & macOS systems

---

 ⚙️ Tech Stack

- **Backend Scripts:** Bash, Cron
- **Visualization & Logic:** Python 3, Matplotlib, Plotly
- **Web Interface:** Flask
- **Packaging & Docs:** Shell, Markdown

---

 🗂️ Directory Structure

  ## 📁 Project Structure – Infra Monitoring Suite

Here's a breakdown of the core directories and files in this project:

- `.venv/` — Virtual environment directory for Python dependencies (excluded from version control).
- `data/` — Raw performance metrics collected periodically (CSV, TXT).
- `json_datalog/` — Stores structured system data in JSON format for dashboards and historical analysis.
- `scripts/` — Bash scripts used to gather metrics (CPU, Memory, Disk, Network). Includes `setup_cron.sh` for scheduling.
- `visualizations/` — Python scripts to generate visual reports using Matplotlib and Plotly.
- `dashboard/` — Flask-based web application that presents the dashboard UI for real-time and historical monitoring.
- `smd_package_linux/` — Pre-built installable package for Linux systems (includes binaries and install instructions).
- `smd_package_macos/` — Equivalent package directory for macOS users.
- `webpage/` — Static HTML files for hosting a download page for the packages.
- `docs/` — Project documentation including:
  - `initial_documentaion.md` — Project planning and architecture notes.
  - `sprint_1_documentation.md` — Goals and features from Sprint 1.
  - `sprint_2_documentation.md` — Sprint 2 tasks and changes.
  - `sprint_3_documentation.md` — Final documentation phase and refinements.
- `README.md` — This file. Contains the project overview, usage guide, and setup instructions.
- `requirements.txt` — Python dependencies required to run the dashboard and visualizations.
- `LICENSE` — MIT License for legal usage, reuse, and contribution.


 
---

🚀 Getting Started

 🔧 Prerequisites

- Python 3.12+
- Bash (Linux/macOS)
- Browser (for dashboard UI)
- Optional: `virtualenv`

---

 📥 Installation

Clone the repository:

```bash
git clone https://github.com/Lavanyaraju19/infra-monitoring-suite.git
cd infra-monitoring-suite

Create and activate a virtual environment (optional but recommended):
python3 -m venv venv
source venv/bin/activate

Install dependencies:
pip install -r requirements.txt

📈 Usage
Start System Monitoring
cd scripts
./setup_cron.sh

Launch Dashboard
cd dashboard
python app.py
Visit http://localhost:5000 in your browser to explore system insights.

🤝 Contributing
Have ideas or improvements? Fork the repo and open a pull request! Contributions are appreciated.

📄 License
Licensed under the MIT License.

👤 Author
Lavanya J
📧 lavanyaj365@gmail.com
🔗 LinkedIn | GitHub

🙌 Acknowledgements
Python + Bash scripting community

Matplotlib and Plotly for powerful visualizations

Flask for building the interactive dashboard


