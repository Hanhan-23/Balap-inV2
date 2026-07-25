# 🚧 BALAP-IN V2

**BALAP-IN (Batam Road Infrastructure Reporting System)** is an integrated road infrastructure reporting platform that connects the citizens of Batam City with government agencies to improve the reporting and management of road infrastructure issues.

The platform consists of a **Mobile Application** for citizens and a **Web Application** for government administrators. By integrating **Artificial Intelligence (AI)**, BALAP-IN helps automate infrastructure damage analysis, improve report validation, and accelerate the report handling process.

---

# ✨ Features

- 📱 Cross-platform mobile application
- 🌐 Web-based government management system
- 📍 GPS-based location reporting
- 📷 Image upload support
- 🤖 AI-powered infrastructure damage detection
- 🗺 Interactive map integration
- 📊 Administrative dashboard
- 📈 Report analytics
- 🔔 Real-time report status updates
- 👥 User management
- 📋 Report history
- ✅ Report verification and validation

---

# 📦 Repository Structure

```text
BALAP-IN/
│
├── web/                  # Government Management System
│   ├── README.md
│   └── ...
│
├── mobile/               # Citizen Mobile Application
│   ├── README.md
│   └── ...
│
└── README.md             # Repository Overview
```

---

# 🌐 Web Application

The **Web Application** is designed for **government agencies and administrators** responsible for managing road infrastructure reports submitted by citizens.

## Main Features

- 📊 Dashboard for monitoring reports
- 📍 Interactive map visualization
- 📋 Report management
- ✅ Verify and validate citizen reports
- 🤖 AI-assisted infrastructure damage analysis
- 🔄 Report status management
- 👥 User and role management
- 📈 Statistics and analytics
- 🛠 Infrastructure data management

The web application serves as the central management portal, allowing authorities to efficiently process reports, monitor infrastructure conditions, and make informed maintenance decisions.

---

# 📱 Mobile Application

The **Mobile Application** is designed for **citizens of Batam City** to easily report road infrastructure issues directly from their smartphones.

## Main Features

- 👤 User registration and authentication
- 📷 Capture and upload road damage photos
- 📍 Automatic GPS location detection
- 🤖 AI-powered infrastructure damage detection
- 🗺 Interactive map integration
- 📡 Submit reports in real time
- 📋 View report history
- 🔔 Receive report status notifications

The mobile application provides a simple, intuitive, and user-friendly experience, encouraging public participation in maintaining safer and better road infrastructure throughout Batam City.

---

# 🤖 Artificial Intelligence

BALAP-IN integrates Artificial Intelligence to improve the efficiency and accuracy of the reporting process.

## AI Capabilities

- Automatic road damage detection from uploaded images
- Infrastructure damage classification
- Intelligent image analysis
- AI-assisted report validation
- Faster report processing

These AI capabilities reduce manual verification efforts while improving the consistency and accuracy of infrastructure assessments.

---

# 🎯 Project Objectives

BALAP-IN aims to:

- Improve public participation in reporting road infrastructure issues.
- Accelerate government response to infrastructure problems.
- Increase transparency throughout the reporting process.
- Support data-driven infrastructure maintenance.
- Utilize Artificial Intelligence to improve reporting accuracy and operational efficiency.

---

# 👥 Target Users

## Citizens

- Report damaged roads and infrastructure
- Track report progress
- Receive report status updates
- Contribute to improving public infrastructure

## Government

- Monitor incoming reports
- Verify and validate reports
- Manage infrastructure maintenance workflows
- Analyze infrastructure data
- Improve decision-making using AI-assisted insights

---

# 🚀 Installation

This repository contains two independent applications. Each application has its own installation guide, dependencies, and environment configuration.

| Application | Description | Installation Guide |
|-------------|-------------|--------------------|
| 🌐 **Web Application** | Government Management System | [`web/README.md`](./web/README.md) |
| 📱 **Mobile Application** | Citizen Mobile Application | [`mobile/README.md`](./mobile/README.md) |

Please navigate to the corresponding project directory and follow the installation instructions before running the application.

---

# 🏛 System Architecture

```text
                        Citizens
                            │
                            ▼
                  Mobile Application
                            │
                            ▼
                     Backend Services
                            │
         ┌──────────────────┴──────────────────┐
         │                                     │
         ▼                                     ▼
 AI Infrastructure Detection          Database & Storage
         │                                     │
         └──────────────────┬──────────────────┘
                            ▼
                     Web Application
                            │
                            ▼
               Government Administrators
```

---

# 🛠 Technology Stack

### Mobile

- Flutter
- Dart

### Web

- Laravel
- PHP
- Blade
- Bootstrap
- JavaScript

### Backend

- REST API
- MySQL

### Artificial Intelligence

- YOLO
- Python
- OpenCV

### Services

- Google Maps API
- Firebase Cloud Messaging *(Optional)*

---

# 👥 Contributors

BALAP-IN was developed through the collaborative efforts of:

- **Farhan Ramadhan**
- **Yulia Pipka Ziliwu**
- **M. Iskandar Dinata**
- **Michael Lee**

We sincerely appreciate the dedication and collaboration of every contributor in designing, developing, and improving the BALAP-IN platform.

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository.
2. Create a new feature branch.

```bash
git checkout -b feature/your-feature-name
```

3. Commit your changes.

```bash
git commit -m "Add your feature"
```

4. Push your branch.

```bash
git push origin feature/your-feature-name
```

5. Open a Pull Request.

---

# 📄 License

This project is licensed under the **MIT License**.

See the [LICENSE](LICENSE) file for more information.

---

# 🌍 Vision

To build a **smart, transparent, and AI-powered road infrastructure reporting ecosystem** that strengthens collaboration between the citizens of Batam City and government authorities in maintaining safe, reliable, and sustainable public infrastructure.