# 🚀 EventHub – College Event Management System

## 📚 Project Introduction
**EventHub** is a comprehensive full-stack **MERN** (MongoDB, Express.js, React.js, Node.js) application designed to revolutionize how college events are discovered, registered for, and tracked.

It serves as a one-stop platform for students, event organizers, and administrators to manage and participate in academic and technical events across India. The platform provides features like personalized dashboards, event registration, QR code ticket generation, and achievement tracking. 🎉

---

## 🛑 Problem Statement
College event management often lacks centralization, making it difficult for students to find and register for relevant events, track their participation, or showcase their achievements.

Event organizers face challenges in promoting events, managing registrations, and engaging participants.

There is no centralized platform allowing students to maintain a structured record of their event participation and achievements. 🤔

---

## 💡 Proposed Solution
**EventHub** offers a unified platform where students, event organizers, and administrators can interact seamlessly.

Key features include:

- Discover and register for events across multiple categories (hackathons, symposiums, tech summits, meetups, conferences, etc.).
- QR code generation for event entry and easy check-ins.
- Leaderboards and point systems to encourage participation and recognize top performers.
- Real-time notifications and reminders to keep participants engaged and informed.
- User dashboards to track achievements, points, and event participation. 🏆

---

## 🔑 Features Overview

### 1. 👤 User Management
- Role-based Authentication (Student, Organizer, Admin) 🔐
- Registration via Email, Google, or Microsoft OAuth
- Manage profiles with achievements, points, and events joined 🏅

### 2. 🎉 Events Registration
- Browse and filter events by category, location, and mode (online/offline)
- RSVP/Registration with seat limits and QR code generation 🎟️
- Email reminders for event updates and participation

### 3. 👨‍💻 Admin & Organizer Panel
- Create/Edit/Delete events
- View RSVP lists
- Event analytics and participant management 📊

### 4. 🏆 Leaderboard & Points System
- Event-specific leaderboards and badges 🏅
- College-wide and department-wise leaderboards 🏆

### 5. 🔔 Notification System
- In-app and email notifications for event reminders, winner announcements, and updates 📧

### 6. 💬 Chat & Announcements
- Real-time chat groups for event discussions using **Socket.IO** 💬
- Organizer-wide announcements 📢

### 7. 📸 Media & Gallery Module
- Upload and view event photos
- Tag winners and maintain a dynamic event gallery 📸

### 8. 💳 Payment Gateway
- **Razorpay** integration for event registration payments (UPI, cards, wallets) 💳

### 9. 💻 User Dashboard
- Public portfolio link for students to showcase their achievements and track events 🌟

---

## 💻 Tech Stack

**Frontend:**
- React.js
- React Bootstrap
- Material UI
- Framer Motion
- Bootstrap Icons

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB, Mongoose

**Authentication:**
- JWT (Email, Google, Microsoft OAuth)

**State Management:**
- Redux Toolkit

**Other Integrations:**
- QR Code Handling: `react-qr-code`, `react-qr-reader`
- Media Storage: Cloudinary / Firebase
- Notifications: Firebase Cloud Messaging / NodeMailer / SendGrid
- Payment Gateway: Razorpay API 💳

---

## 🔐 Security Measures

- **JWT Authentication:** Secure token-based authentication for user login and role management 🔒
- **OAuth Integration:** Secure Google and Microsoft OAuth for seamless third-party login
- **Data Encryption:** Sensitive user and event data encrypted both in transit and at rest
- **Role-based Access Control (RBAC):** Ensures only authorized users can create, edit, or manage events
- **Payment Verification:** Razorpay payment integration with secure signature validation to prevent fraud
- **Input Validation:** Comprehensive validation for user inputs and event registration forms to prevent vulnerabilities 🛡️

---

## 🛠 How It Works

### 1. User Registration
- Students register via Email, Google, or Microsoft OAuth.
- Default "Student" role assigned; students can apply to become event organizers.

### 2. Event Discovery & Registration
- Browse/filter events based on category, location, and mode (online/offline).
- Upon registration:
  - A QR code ticket is generated.
  - Email with QR code ticket is sent.
  - QR code is also available in the dashboard.

### 3. Payment Processing
- For paid events:
  - Users pay securely using Razorpay.
  - Payment confirmation triggers QR code generation and email notification.

### 4. Event Check-In
- Participants show their QR code ticket at the venue.
- Coordinators scan QR codes via the Organizer Portal/App.

### 5. Admin & Organizer Management
- Admins manage approvals, user roles, payments, reports.
- Organizers create/edit events, manage participants, scan QR codes.

### 6. Leaderboard & Badges
- Students earn points and badges for participation and wins.
- Leaderboards are available at college-wide and department-specific levels.
- Achievements are shown on public profiles.

### 7. Notifications
- In-app and email notifications for:
  - Registration confirmations
  - Event reminders and updates
  - Announcements

---

## 🌟 Impact & Benefits

**Students**
- Centralized access to events
- Easy registration and portfolio building 📑

**Event Organizers**
- Efficient event management
- Real-time analytics and engagement 📈

**Administrators**
- Simplified user and event management
- Secure payments and detailed reporting 📊

**Employers**
- View students' event participation and achievements
- Better recruitment insights 👥

---

## 🔮 Future Enhancements

- Mobile App: Android/iOS version 📱
- Advanced Analytics: Deeper insights into event performances 📊
- Integrated Chat: Real-time event discussions 💬
- AI Recommendations: Smart event suggestions based on interests 🤖
- Institutional Collaborations: Partner with colleges for wider outreach 🌍

---

## 👩‍💻👨‍💻 Learnings & Team Contribution

- **Frontend Development:** Built responsive dashboards, focused on UI/UX 🖥️
- **Backend Development:** Implemented secure authentication, event APIs, and payment flows 💻
- **Database Management:** Designed optimized MongoDB schemas 🗄️
- **Security Practices:** Applied JWT, OAuth, encryption, and form validations 🔐
- **Teamwork:** Collaborated effectively using GitHub and project management tools 📅

---

## 🎉 Thank You for exploring **EventHub**!
