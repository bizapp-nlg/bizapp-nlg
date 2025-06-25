# 📦 bizapp-nlg

**`bizapp-nlg`** is the central repository for developing and managing API services for the BizApp ecosystem of **Nam Long Group (NLG)**. This platform integrates essential business modules such as Booking, eWallet FnB, IMS (Incentive Management System), and CRM — supporting internal operations, partner collaboration, and digital transformation.

---

## 🔧 Modules Included

### 🧾 Booking & Reservation API
- Manage appointment scheduling, booking confirmations, and customer transaction flows.

### 🍽️ eWallet FnB API
- Internal digital wallet system for Food & Beverage programs.
- Supports employee benefits, voucher redemption, and promotional campaigns.

### 💰 IMS (Incentive Management System)
- Automates commission calculation, reconciliation, and payout.
- Designed for real estate brokerage and sales partner networks.

### 🧑‍💼 CRM API
- Centralizes customer data and interactions.
- Enables lead tracking, care journeys, and marketing automation.

---

## 🎯 Project Objectives

- ✅ Establish a unified, RESTful API architecture across business domains.
- ✅ Improve integration efficiency between internal systems and external partners.
- ✅ Accelerate delivery of digital services and product features.
- ✅ Ensure security, version control, and scalability of all modules.

---

## 💼 Business Value

- 🚀 **Faster service deployment** across departments and to market.
- 🔄 **Operational efficiency** through standardized APIs and process automation.
- 🤝 **Seamless integration** with third-party and internal platforms.
- 🧱 **Digital infrastructure** that supports NLG's strategic business transformation.

---

## 📁 Folder Structure

bash
bizapp-nlg/
├── booking/            # Booking and reservation APIs
├── ewallet/            # FnB Wallet APIs
├── ims/                # Commission and incentive system APIs
├── crm/                # Customer relationship management APIs
├── shared/             # Common libraries and configurations
└── docs/               # API documentation and workflow guides

🚀 Getting Started

Prerequisites
	•	.NET 6 SDK
	•	SQL Server / PostgreSQL (depending on module)
	•	Redis (if using caching)

Installation
# Clone the repository
git clone https://github.com/your-org/bizapp-nlg.git
cd bizapp-nlg

# Restore dependencies
dotnet restore

# Run the application (example: Booking API)
cd booking
dotnet run

📌 API Documentation

Each module includes its own Swagger/OpenAPI documentation. After running a module:
	•	Visit http://localhost:{port}/swagger to explore the API.
	•	Auth headers and token handling are described in each module’s README.

⸻

👥 Contribution Guidelines

We welcome internal collaboration. Please follow our development guide and use pull requests for changes. Naming conventions and coding standards are defined in the /docs folder.

⸻

🔐 Security & Access
	•	Environment variables for secrets (DB, Redis, JWT) are required.
	•	OAuth2 token-based authentication is supported where applicable.
	•	Please refer to the /docs/security.md for more information.

⸻

🏢 About Nam Long Group

Nam Long Group is one of Vietnam’s leading real estate developers, with a vision to build complete townships and sustainable communities. The BizApp ecosystem supports this vision by digitalizing the company’s internal operations, customer journey, and partner engagement models.

⸻

📫 Contact

For internal usage, please contact the BizApp platform team:
📧 bizapp.nlg@namlongvn.com

⸻

📝 License

This repository is intended for internal use. Contact the repository admin for license inquiries.
