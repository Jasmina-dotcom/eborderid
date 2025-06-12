# eBorderID

**eBorderID** is a full-stack border control and identity verification system designed to simulate modern electronic passport and biometric border management. It incorporates key technologies such as RFID, biometric authentication, PKI, and secure document issuance aligned with ICAO and ISO standards.

---

## 🚀 Project Overview

This project is intended as a mid-size demonstration of a real-world system used in border control, passport scanning, and identity verification. It aims to reflect key components found in actual e-Gate or border management solutions.

---

## 🧰 Technologies Used

### Backend
- Java 21 (Spring Boot)
- RESTful APIs
- Spring Security (JWT-based)
- Hibernate / JPA
- PostgreSQL

### Frontend
- Angular 17+
- Angular Material / Bootstrap
- RxJS and Reactive Forms

### Additional
- RFID simulation
- Biometric placeholder API (facial/fingerprint matching)
- PKI (X.509 certificate simulation)
- Docker (for deployment, optional)
- GitHub Actions (CI/CD, optional)

---

## 📐 System Architecture

- Microservice-style Spring Boot backend
- Angular frontend served separately
- Secure API communication (JWT)
- Mocked biometric and RFID modules
- PostgreSQL database for identity, passport, and border logs

![System Architecture](docs/architecture.png)

---

## 📦 Features

- Biometric ID verification
- RFID-based passport scanning
- Encrypted passport data storage
- Certificate-based signature verification (PKI)
- Admin and officer login roles
- Border crossing logs and session monitoring
- Internationalization-ready UI

---

## 🛠️ Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/Jasmina-dotcom/eborderid.git
   cd eborderid

2. Start the backend (Spring Boot)

cd backend
./mvnw spring-boot:run

Or, if you have Maven installed:

mvn spring-boot:run

3. Start the frontend (Angular)

cd frontend
npm install
ng serve

The Angular app will be available at http://localhost:4200/

👩‍💻 Use Case Scenario
An immigration officer uses the system to:

Scan an RFID-enabled passport

Capture biometric input

Verify the identity via PKI and biometric match

Log the border crossing with time/location metadata

🌍 Standards Referenced
ICAO Doc 9303 (ePassports)

ISO/IEC 19794 (biometric data)

X.509 (digital certificates)

📄 License
This project is for demonstration and educational purposes only.

✈️ Author
Made with 💻 by Jasmina Zoric
