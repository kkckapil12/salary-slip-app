# 🧾 Salary Slip Generator (Dockerized)

## 📌 Project Overview

This project is a **Dockerized Flask API** that generates **Salary Slip PDFs** using ReportLab.

---

## 🚀 Features

* Generate salary slip PDF via API
* Dockerized application
* Simple REST API
* Ready for Kubernetes deployment

---

## 🛠️ Tech Stack

* Python
* Flask
* ReportLab
* Docker

---

## 📦 Setup Instructions

### 🔹 Clone Repository

```
git clone https://github.com/YOUR_USERNAME/salary-slip-app.git
cd salary-slip-app
```

### 🔹 Build Docker Image

```
docker build -t salary-slip-app .
```

### 🔹 Run Container

```
docker run -d -p 5000:5000 salary-slip-app
```

---

## 🧪 API Testing

### Endpoint:

POST /generate

### Sample Request:

```
curl -X POST http://localhost:5000/generate \
-H "Content-Type: application/json" \
-d '{
"name": "Kapil",
"basic": 30000,
"hra": 10000,
"allowance": 5000,
"bonus": 3000,
"pf": 2400,
"tax": 3000
}'
```

---

## 📄 Output

Generated PDF stored in:

```
/output/
```

---

## 🧠 Future Improvements

* Kubernetes deployment
* CI/CD pipeline (GitHub Actions)
* Database integration
* UI (React frontend)

---

## 👨‍💻 Author

Kapil Chavan
