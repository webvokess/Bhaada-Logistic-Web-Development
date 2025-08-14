# Bhaada Logistic Web Development

A logistics application suite designed for local businesses, comprising a website, a user app, a driver app, and a fleet management system. The project components are provided as ZIP files.

## Overview

- **Website:** Public-facing interface for customers to place orders and track deliveries.
- **User App:** Mobile app for customers to manage bookings and communicate with drivers.
- **Driver App:** Mobile app enabling drivers to receive delivery tasks, update status, and navigate.
- **Fleet Management System:** Management dashboard for administrators to oversee operations and fleet performance.
- **Backend:** API services powering the apps and website, facilitating authentication, routing, and data management.

## Tech Stack _(example placeholders—update as needed)_

| Component              | Technologies                                                   |
|------------------------|----------------------------------------------------------------|
| Frontend (Website)     | React.js, Next.js, BootstrapTailwind CSS                      |
| Backend                | Node.js, Express.js, MongoDB or PostgreSQL                     |
| User App (Mobile)      | Flutter                                                        |
| Driver App (Mobile)    | Flutter                                                         |.              
| Fleet Management       | Web Dashboard with React/Vue + charts (e.g., Chart.js, Highcharts) |
| Infrastructure         | Dockerized deployment, hosted on AWS/GCP, CI/CD with GitHub Actions |
| Authentication         | JWT tokens, OAuth 2.0                                          |

## Getting Started

1. Extract all ZIP files:
   - `website.zip`
   - `user-app.zip`
   - `driver-app.zip`
   - `fleet-system.zip`
   - `backend.zip`

2. For each component:
   ```bash
   cd <component-folder>
   npm install
   npm run dev  # or appropriate start command
