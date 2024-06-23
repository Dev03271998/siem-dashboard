# SIEM-Dashboard

A full-stack Security Information and Event Management (SIEM) Dashboard built to monitor, visualize, and analyze system logs and security events in real time. Designed with a modern UI and dark/light mode support, this project was developed as part of a cybersecurity internship to simulate a lightweight Splunk-like system.

---

## Features

- **Dark/Light Mode** - Seamless toggle between light and dark UI for better accessibility and UX.
- **Geo-IP Blocking** - Automatically blocks suspicious IPs based on geolocation data.
- **Vulnerability Detection** - Detects potential system vulnerabilities using pattern matching and custom scripts.
- **Access Log Visualization** - Displays real-time logs, source IPs, actions, and threat levels.
- **Interactive Charts and Dashboard** - Graphs and tables powered by Chart.js for visual security analytics.
- **Secure Salt Authentication** - Login system protected using salted password hashing.

---

## Tech Stack

| Layer          | Technology                     |
|----------------|--------------------------------|
| Frontend       | HTML, CSS, JavaScript, Chart.js |
| Backend        | Python (Flask)                  |
| Visualization  | Chart.js, D3.js (optional)      |
| Database       | SQLite / MongoDB (configurable) |
| Deployment     | GitHub Pages / Heroku / Localhost |

---

## Project Structure

```plaintext
├── static/
│   ├── css/
│   ├── js/
│   └── images/
├── templates/
│   ├── index.html
│   ├── login.html
│   └── dashboard.html
├── scripts/
│   ├── vulnerability_scanner.py
│   └── geo_blocker.py
├── app.py
├── config.py
├── database.db
└── requirements.txt
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Access the Dashboard

1. Run the application - `python app.py`
2. Access the Dashboard - http://127.0.0.1:5000

---

## Screenshots

![Screenshot 2025-06-12 112606](https://github.com/user-attachments/assets/0417c267-7f74-47a2-931c-c77d75bdca02)

![Screenshot 2025-05-29 184040](https://github.com/user-attachments/assets/09bd2fed-6299-4a59-9a4a-acdac80ee22e)

---

## Maintainer

Dev Bhatt maintains this project, bringing experience in data analytics, automated pipelines, controls, and dashboards. His work includes automating risk indicator tracking and reconciliation across large datasets.

- Email: [devbhattwork27@gmail.com](mailto:devbhattwork27@gmail.com)
- LinkedIn: [linkedin.com/in/dev-bhatt27](https://linkedin.com/in/dev-bhatt27)