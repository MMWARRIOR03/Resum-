# Mrinal Mohit

+91 9693937893 | mrinal0307mohit@gmail.com | Bhopal, Madhya Pradesh | [LinkedIn](https://www.linkedin.com/in/mrinal-mohit-647778289/) | [GitHub](https://github.com/MMWARRIOR03)

---

## Technical Skills

- **Languages**: Golang, Java, C++, Python, SQL, JavaScript, Dart
- **Backend & Frameworks**: Spring Boot, React, Flask, Flutter
- **Databases & Cloud**: PostgreSQL, MongoDB, AWS, Docker, RabbitMQ
- **Developer Tools**: GitHub, Maven
- **Hardware/IoT**: ESP32, GPS Module, Sensors, Arduino
- **Systems Programming**: Linux System Programming, Multithreading, Memory Management

---

## Projects

### High-Concurrency Transaction Engine  
**Tech Stack:** Golang | PostgreSQL | Docker | AWS Lambda | WebSockets  

-  Architected a crypto transaction simulator replicating **UTXO-style** wallet behavior — supporting deposits, withdrawals, and peer-to-peer transfers with **ledger persistence in PostgreSQL.**
-  Implemented real-time transaction ingestion using **WebSockets** and **Goroutines**, enabling parallel processing with **46% faster throughput** compared to sequential execution.
-  Designed a **Merkle-tree** based hashing workflow to generate **immutable transaction fingerprints**, ensuring auditability and preventing tampering.
-  Containerized **microservices** using **Docker** and deployed validation + reconciliation functions via **AWS Lambda**, reducing compute costs by **30%**.
-  Added fraud detection rules (double-spend check, negative-balance prevention, nonce replay filtering) ensuring **100% ledger consistency** across sessions.

---

### GPS-Based Dynamic Toll Collection System  
**Tech Stack:** Spring Boot | Embedded C | PostgreSQL | Redis | RabbitMQ | Docker | Kubernetes  

-  Engineered **Embedded C** firmware for **ESP32-WROOM-32** with **NEO-6M GPS** and **SIM800L GSM** modules; implemented **MQTT** client with QoS 1 for reliable telemetry transmission, achieving **3m GPS accuracy** and **99%** message delivery rate
-  Built **Spring Boot application** processing real-time GPS data from **ESP32** devices; implemented **PostGIS geofencing** and dynamic pricing with traffic/weather-based multipliers.
-  Engineered **JWT authentication**, **Redis**-based rate limiting, and fraud detection achieving **95% accuracy**; deployed event-driven architecture using **RabbitMQ** for async processing.
-  Containerized with **Docker/Kubernetes** achieving **98% uptime** and <**200ms** response time; integrated **Grafana** monitoring with zero-downtime deployments.

---

### Web & API Automated Validation Framework  
**Tech Stack:** Java — Burp Suite Extender API — OWASP ZAP — Docker — JWT  

-  Developed a **Java**-based security testing framework using **Burp Suite Extender API** and **OWASP ZAP** for automated detection of **OWASP Top 10** vulnerabilities across **Web and REST APIs**.
-  Implemented exploit modules for **SQLi, XSS, SSRF, CSRF, host header injection**, parameter pollution, prototype pollution, and insecure deserialization.
-  Created PoCs for **JWT tampering** (weak key brute force, `alg=none` abuse), **session fixation**, and **Broken Access Control via IDOR and privilege-escalation fuzzing**.

---

### Real-Time Market Data Stream Analyzer  
**Tech Stack:** Python | RabbitMQ | AWS Lambda | PostgreSQL | Redis | Flask | Plotly  

-  Built event-driven pipeline with **RabbitMQ** processing **10K+ ticks/sec**; implemented **Pandas/NumPy** anomaly detection with Z-score and Bollinger Bands for volatility analysis
-  Deployed **AWS Lambda** with **Redis** caching achieving **sub-500ms** latency and **99.9%** availability; optimized for **50+ concurrent** streams with auto-scaling and **SQS** integration
-  Developed **Flask** API with **Plotly Dash** dashboards and **WebSocket** live feeds; integrated **PostgreSQL/TimescaleDB** reducing storage **60%** with <**100ms** queries

---

### TEDx Pass Generator – Full-Stack Cloud Application  
**Tech Stack:** Java | Spring Boot | MongoDB Atlas | GCP App Engine | Maven  

-  Built enterprise **REST API** with **Spring Boot** using layered architecture, DTO pattern, and centralized exception handling for event pass lifecycle management.
-  Engineered automated pass generation with **ZXing (QR codes)** and **iText (PDF)**.
-  Implemented secure **MongoDB Atlas**, supporting cloud **deployment on GCP**.
-  Deployed on GCP App Engine achieving **99.9% uptime** with **auto-scaling**.

---

## Experience

### Software Developer Intern  
**Know Your Trips, Dublin**  
Mar 2025 --- Apr 2025  

-  Led a **team of 5 developers**, conducted **15+ code reviews**, and **mentored** team members to deliver **scalable mobile features**, improving sprint velocity by **15%**.
-  Integrated **JWT authentication** and **Firebase Cloud Messaging**, strengthening **system reliability** by **30%**.
-  **Automated** deployments through **CI/CD**, reducing release cycles by **20%**.
-  Contributed to **QA testing** and debugging, enhancing app stability by **25%**.
- **Tech Stack:** Flutter, Dart, GetX, MongoDB, AWS, and Firebase.

---

## Certifications

- • AWS Certified Solutions Architect - Associate
- • Oracle Certified Java Professional (Java SE-17)
- • IBM Introduction to Cloud

---

## Education

**Vellore Institute of Technology Bhopal**  
Bhopal, India  
B.Tech in Computer Science and Engineering  
Expected Sept 2027  

- **CGPA:** 7.97/10

---

## Leadership and Impact

### Technical Head | Mozilla Firefox Club VIT Bhopal  
Feb 2025 --- Jul 2025  
VIT Bhopal University  

-  Led 20+ member tech division, mentoring peers in open-source, web, and automation development.
-  Conducted coding bootcamps and hackathons impacting **150+ students**.
-  Enhanced cross-team collaboration and project execution using agile practices.

---

## Co-Curricular Activities

-  Max. rated 1030+ on CodeForces.
-  Participated in hackathons focusing on fintech automation and cloud-based scalability.
