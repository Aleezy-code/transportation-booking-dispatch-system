# 🚘 RYDEX — Next-Gen Transportation & Ride Management Platform

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=25&pause=1000&color=38BDF8&center=true&vCenter=true&width=750&lines=SMART+RIDES.+SEAMLESS+JOURNEYS.;BOOK+%E2%80%A2+TRACK+%E2%80%A2+MANAGE+%E2%80%A2+CONNECT;THE+FUTURE+OF+TRANSPORTATION" alt="Animated Rydex heading" />
</p>

<p align="center">
  <b>A modern, full-stack ride-booking and transportation management platform.</b>
  <br/>
  Designed to connect passengers, drivers, and administrators through an intelligent digital mobility experience.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/NEXT.JS-16-black?style=for-the-badge&logo=next.js" />
  <img src="https://img.shields.io/badge/REACT-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/TYPESCRIPT-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/MONGODB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
</p>

<p align="center">
  <a href="https://rydex-demo.vercel.app/"><b>🌐 LIVE DEMO</b></a> •
  <b>🚀 RIDE BOOKING</b> •
  <b>📍 LIVE TRACKING</b> •
  <b>⚡ REAL-TIME SYSTEM</b>
</p>

---

## ✨ 01 — THE VISION

RYDEX is a full-stack transportation and ride-sharing platform built to simplify the way people book, manage, and experience transportation services.

From seamless passenger bookings to driver operations and administrative control, the platform brings essential transportation workflows into one connected ecosystem.

**One platform. Three experiences. Unlimited possibilities.**

## 🌌 02 — EXPLORE THE ECOSYSTEM

<table>
<tr>
<td width="33%" align="center">
<h3>👤 PASSENGER</h3>
<br/>
<b>Book Smarter</b>
<br/><br/>
Search vehicles, book rides, make payments, communicate with drivers, and track journeys.
</td>
<td width="33%" align="center">
<h3>🚗 DRIVER</h3>
<br/>
<b>Drive Smarter</b>
<br/><br/>
Manage bookings, update ride statuses, navigate routes, and monitor earnings.
</td>
<td width="33%" align="center">
<h3>🛡️ ADMIN</h3>
<br/>
<b>Control Everything</b>
<br/><br/>
Manage vehicles, approve partners, oversee bookings, and monitor platform performance.
</td>
</tr>
</table>

## 🚀 03 — CORE FEATURES

| Feature | Description |
|---|---|
| 🚘 Ride Booking | Search available vehicles and book rides |
| 📍 Live Tracking | Real-time location and route tracking |
| 🗺️ Interactive Maps | Map-based transportation experience |
| 👨‍✈️ Driver Management | Driver onboarding and booking management |
| 🚙 Vehicle Management | Vehicle information and approval workflows |
| 💳 Online Payments | Razorpay and Stripe integration |
| 💬 Live Communication | In-ride chat and communication |
| 🔐 OTP Verification | Pickup and drop-off verification |
| 📊 Admin Dashboard | Earnings, statistics, and booking analytics |
| 📈 Driver Analytics | Earnings and active booking insights |
| 🎥 Video KYC | Driver verification functionality |
| ⚡ Real-Time Updates | Socket-based location and communication events |

## 🔄 04 — HOW THE SYSTEM WORKS

<p align="center">
  <b>THE COMPLETE RIDE LIFECYCLE</b>
</p>

```text
       👤 PASSENGER
             |
             ▼
       🔍 SEARCH RIDE
             |
             ▼
       📅 BOOK VEHICLE
             |
             ▼
       💳 PAYMENT
             |
             ▼
       🚗 DRIVER ACCEPTS
             |
             ▼
       📍 LIVE TRACKING
             |
             ▼
       🔐 OTP VERIFICATION
             |
             ▼
       🏁 RIDE COMPLETED
             |
             ▼
       📊 ADMIN ANALYTICS
```

## 🧠 05 — TECHNOLOGY STACK

<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,typescript,tailwind,nodejs,mongodb,redux,git,github&perline=5" />
</p>

| Category | Technologies |
|---|---|
| Frontend | Next.js 16, React 19 |
| Language | TypeScript |
| Styling | Tailwind CSS 4 |
| State Management | Redux Toolkit |
| Backend | Next.js API Routes, Node.js |
| Database | MongoDB, Mongoose |
| Authentication | NextAuth |
| Real-Time | Socket.IO |
| Maps | React Leaflet |
| Payments | Razorpay, Stripe |
| Charts | Recharts |
| Animations | Framer Motion |
| Media | Cloudinary |
| Email | Nodemailer |
| Deployment | Netlify |

## 🏗️ 06 — PROJECT ARCHITECTURE

```text
RYDEX/
│
├── rydex/
│   ├── app/
│   │   ├── api/             # Backend API routes
│   │   ├── admin/           # Admin dashboard
│   │   ├── partner/         # Driver dashboard
│   │   ├── book/            # Ride booking
│   │   └── search/          # Vehicle search
│   │
│   ├── components/          # Reusable UI components
│   ├── lib/                 # Database and integrations
│   ├── models/              # Database models
│   └── redux/               # State management
│
└── socketServer/            # Real-time Socket.IO server
```

## ⚙️ 07 — INSTALLATION & SETUP

### Prerequisites

- Node.js 20+
- MongoDB database
- npm
- Required third-party service credentials

### Step 1 — Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/transportation-booking-dispatch-system.git
```

### Step 2 — Navigate to the project

```bash
cd transportation-booking-dispatch-system/rydex
```

### Step 3 — Install dependencies

```bash
npm install
```

### Step 4 — Configure environment variables

Create a `.env.local` file and configure the required credentials:

```env
MONGODB_URL=your_mongodb_connection_string

NEXTAUTH_SECRET=your_secret
NEXTAUTH_URL=http://localhost:3000

RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret

STRIPE_SECRET_KEY=your_stripe_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Configure other service credentials required by the project as well.

### Step 5 — Start the application

```bash
npm run dev
```

### Step 6 — Open in your browser

```text
http://localhost:3000
```

### Optional — Start the Socket.IO server

Open another terminal:

```bash
cd socketServer
npm install
node index.js
```

## 🌐 08 — DEPLOYMENT

The application can be deployed using a supported hosting provider.

General deployment workflow:

1. Push the project to GitHub.
2. Connect the repository to Netlify.
3. Configure the required environment variables.
4. Set up MongoDB connectivity.
5. Configure external service credentials.
6. Build and deploy the application.

## 🔮 09 — FUTURE ENHANCEMENTS

Potential improvements for future development:

- AI-powered ride recommendations.
- Automated booking confirmations and reminders.
- Advanced driver scheduling.
- Fleet performance analytics.
- Intelligent dispatch allocation.
- Customer support automation.
- Enhanced operational reporting.

## 👩‍💻 10 — DEVELOPER

**Project Repository:** `transportation-booking-dispatch-system`

Developed and customized as a transportation technology project.

**GitHub:** [YOUR-GITHUB-PROFILE](https://github.com/YOUR-USERNAME)

## 🤝 11 — ORIGINAL PROJECT & CREDITS

This repository is based on the open-source Rydex project by its original developer.

- **Original Developer:** [sujalrajapure](https://github.com/sujalrajapure)
- **Original Repository:** [Rydex-Demo](https://github.com/sujalrajapure/Rydex-Demo)
- **Original Demo:** [rydex-demo.vercel.app](https://rydex-demo.vercel.app)

Original project attribution and applicable MIT license terms are retained. Additional modifications should be documented separately.

---

<p align="center">
  <b>🚘 RYDEX — REDEFINING THE WAY WE MOVE.</b>
  <br/><br/>
  <i>Smart Transportation. Connected Experiences. Better Journeys.</i>
  <br/><br/>
  ⭐ If you find this project interesting, consider starring the repository.
</p>
