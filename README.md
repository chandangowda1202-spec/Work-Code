# Pravidham

## **Overview**

**Pranveda** is a modern full-stack healthcare management application that bridges the gap between traditional care and modern technology. It offers personalized care, senior citizen support, teleconsultation, real-time monitoring, and a secure platform to manage patient health records.

The name "Pranveda" signifies **“life-knowledge”**, emphasizing a holistic approach to healthcare and well-being.

---

## **Key Features**

### **For Patients / Senior Citizens**

* **Intuitive Dashboard:** Large fonts, simple navigation, and real-time vitals.
* **Tele-consultation:** Book online appointments with doctors easily.
* **Emergency SOS:** One-touch alerts to family and hospitals.
* **Medication Reminders:** Automated notifications for timely medication.
* **Health Vault:** Secure storage for prescriptions, reports, and medical history.
* **Companion Services:** Connect with caregivers and community support.

### **For Doctors**

* **Patient Summaries:** Organized reports before consultations.
* **Remote Monitoring:** Live access to patient vitals like heart rate and glucose.
* **E-Prescriptions:** Digital prescriptions sent directly to patients.
* **Collaboration Tools:** Consult with specialists on complex cases.

### **System-Wide Impact**

* Reduces hospital burdens with early detection.
* Provides data-driven insights for accurate diagnoses.
* Bridges rural-urban healthcare gaps.
* Streamlines workflow between patients, doctors, and pharmacies.

---

## **Tech Stack**

* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **PDF Generation:** jsPDF (for prescriptions)
* **Authentication:** JWT & Role-Based Access
* **Deployment:** Vercel / Heroku (optional)

---

## **Project Structure**

```
Pranveda/
├─ client/                 # React.js frontend
│  ├─ src/
│  │  ├─ App.jsx
│  │  ├─ main.jsx
│  │  ├─ components/
│  │  │  ├─ Dashboard.jsx
│  │  │  ├─ Booking.jsx
│  │  │  └─ History.jsx
│  │  └─ styles/
│  │     └─ main.css
├─ server/                 # Node.js backend
│  ├─ index.js
│  ├─ routes/
│  ├─ controllers/
│  └─ models/
├─ package.json
└─ README.md
```

---

## **Installation & Setup**

### **1. Clone the repository**

```bash
git clone https://github.com/chandangowda1202-spec/senior-connect-kannada.git
cd senior-connect-kannada
```

### **2. Setup Backend**

```bash
cd server
npm install
npm start      # Starts backend server on default port 5000
```

### **3. Setup Frontend**

```bash
cd ../client
npm install
npm start      # Runs React app on localhost:3000
```

### **4. Environment Variables**

Create a `.env` file in the `server` folder and add:

```
MONGO_URI=<Your MongoDB Connection String>
JWT_SECRET=<Your JWT Secret Key>
PORT=5000
```

---

## **Usage**

* Open your browser at `http://localhost:3000`
* Register as **Patient** or **Doctor**
* Explore dashboard, book appointments, and manage health records
* Senior citizens can access simplified interfaces and SOS alerts

---

## **NPM Commands Recap**

| Command         | Description                               |
| --------------- | ----------------------------------------- |
| `npm install`   | Install dependencies for frontend/backend |
| `npm start`     | Start the React frontend or Node backend  |
| `npm run build` | Build production-ready React app          |

---
