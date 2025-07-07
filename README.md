# 🏨 StayEase – Hostel Management & Billing System


StayEase is a full-featured **Hostel Management and Billing System** built using the **MERN Stack (MongoDB, Express.js, React, Node.js)**. It simplifies hostel administration with features like room allocation, billing, maintenance requests, role-based access, and detailed financial reporting.

---

## 👤 Author

Developed by **Rohan Bhatt** as part of a 4-member team. I contributed extensively to:

- Designing interface layouts and page flows using **Figma**
- Implementing responsive and clean frontend components with **React.js + Tailwind CSS**
- Integrating billing logic and PayPal payment flow
- Working on protected routes, login systems, and user-role handling in the backend


## 🔐 Demo Credentials

| Role     | Email                           | Password   |
|----------|---------------------------------|------------|
| Admin    | `deekadmin@gmail.com`           | `deekadmin` |
| Staff    | `staff@gmail.com`               | `staff`     |
| Resident | `resident1@gmail.com`           | `12345678`  |

> 💳 **Test PayPal Buyer Account**  
`sb-u43cpa35356240@personal.example.com` / `m.)_!Z4S`

---

## 🔑 Key Features

- 🛏️ **Room Allocation & Management**
- 🧾 **Automated Billing with Invoicing**
- 🛠️ **Maintenance Request Handling**
- 👥 **Role-Based Access (Admin, Staff, Resident)**
- 📊 **Financial Reporting with Visual Insights**
- 🔔 **Gmail Notifications for Updates**
- 💳 **Integrated PayPal Payments**
- 🔐 **Secure Auth & User Management**

---

## 🧱 Tech Stack

| Component        | Technology              |
|------------------|--------------------------|
| Frontend         | React.js, Tailwind CSS   |
| Backend          | Node.js, Express.js      |
| Database         | MongoDB                  |
| Payment Gateway  | PayPal Sandbox           |
| Email Services   | NodeMailer (Gmail SMTP)  |

---

# How to Get Started

1. **Clone the Repository**:


```bash
git clone https://github.com/RohanBhattB/stayease_frontend.git
cd stayease_frontend
```
2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Configure Environment Variables**:

   Create a `.env` file in the `backend` directory with the following:

   ```env
   PORT=5000
   MONGODB_URL=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   JWT_EXPIRE=7d
   SMTP_HOST=smtp.gmail.com
   SMTP_PORT=587
   SMTP_USER=your_email@gmail.com
   SMTP_PASS=your_email_app_password
   SMTP_FROM=StayEase <your_email@gmail.com>
   ```

4. **Start Development Server**:

   ```bash
   npm run dev
   ```

5. **Access the System**:
   Navigate to the local development URL to start using the system.
