# AidLink – Donation Platform

AidLink is an event-centered donation platform that connects donors with individuals and organizations in need during disasters and community crises. It emphasizes transparency, accountability, and role-based dashboards to ensure donations reach the right people.

## Features

* User authentication with role-based access (Admin, Donor, Receiver)
* Organization registration and admin verification
* Event creation and need listing by verified organizations
* Donation flow with real-time funding progress
* Role-specific dashboards for donors, organizations, and admins
* Image and document upload via Cloudinary

## Tech Stack

### Frontend
* React + Vite
* Tailwind CSS

### Backend
* Spring Boot
* JWT for authentication
* MongoDB for data storage
* Cloudinary for file storage

### Deployment

* Frontend: Firebase
* Backend: Render

## Installation

### Prerequisites
* Java 17+
* Node.js & npm
* MongoDB (local or hosted)
* Cloudinary account

### Backend

```
cd backend
mvn spring-boot:run
```

### Frontend

```
cd frontend
npm install
npm run dev
```

## Contributors

* Multazam Mahmud – Backend, donor and organization workflows, API integration
* Tahsan Ferdous Lihan – Authentication UI, user dashboards, deployment
* Subarno Neel – Admin workflows and dashboard navigation, documentation

## Feedback & Support

If you’d like to contribute or report an issue, feel free to open a GitHub Issue or reach out!
