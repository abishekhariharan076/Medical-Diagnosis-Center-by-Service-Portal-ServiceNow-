# 🏥 Medical Diagnosis Center – ServiceNow

A **ServiceNow-based Medical Diagnosis Center Service Portal** designed to digitize diagnostic center operations. The system enables patients to book tests, manage appointments, access reports, and receive automated notifications through a user-friendly portal.

## 🎯 Objectives

* Digitize patient and diagnostic service management
* Simplify test booking and appointment scheduling
* Prevent duplicate and overlapping bookings
* Automate appointment and report workflows
* Provide secure digital access to medical reports
* Improve coordination between patients, lab staff, and administrators
* Provide dashboards for operational monitoring

## ⚙️ Key Features

### 📝 Test Booking

* Browse available diagnostic tests
* Select date and time slots
* Real-time slot availability validation
* Booking and cancellation management
* Patient profile management

### 🔄 Automated Workflow

```text
Requested → Pending Approval → Confirmed
→ Sample Collected → Processing
→ Completed → Report Available
```

* Optional manager approval
* Automated status updates
* Delayed report escalation

### 📄 Report Management

* Track report processing status
* Notify patients when reports are available
* Digital report viewing and downloading

### 💳 Payment

**Phase-based feature**

* Automatic fee calculation
* Payment status tracking
* Digital invoice and receipt generation
* Transaction history

### 🔔 Notifications

Automated notifications for:

* Booking confirmation
* Approval / rejection
* Payment confirmation
* Report availability
* Cancellation
* Delayed processing

## 👥 Stakeholders

| Stakeholder       | Responsibilities                               |
| ----------------- | ---------------------------------------------- |
| **Patients**      | Book tests, track appointments, access reports |
| **Lab Staff**     | Manage samples, tests, and reports             |
| **Management**    | Approvals, monitoring, dashboards              |
| **Administrator** | Configuration, security, workflows             |

## 🏗️ ServiceNow Components

* **Service Portal** – Patient-facing interface
* **Flow Designer** – Workflow automation
* **Business Rules** – Booking and validation logic
* **ACLs** – Role-based security
* **Custom Tables** – Patients, bookings, reports, payments
* **Notifications** – Automated email alerts
* **JavaScript** – Client/server-side scripting

## 🚀 Implementation Roadmap

* [x] Requirement analysis
* [x] Business objectives and scope
* [x] Stakeholder mapping
* [ ] Service Portal development
* [ ] Custom table configuration
* [ ] Booking validation
* [ ] Workflow implementation
* [ ] Notifications
* [ ] Report management
* [ ] Payment integration
* [ ] UAT
* [ ] Production deployment

## 🛠️ Technology Stack

**ServiceNow · Service Portal · Flow Designer · JavaScript · Business Rules · ACLs · Notifications**

## 📌 Project Status

🚧 **In Development**

The project demonstrates **ServiceNow Service Portal development, workflow automation, healthcare service management, and role-based access control.**
