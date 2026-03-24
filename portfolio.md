# Aditya Singh Rajput

📧 adityarajsir162@gmail.com  
🐙 [github.com/adityasingh03rajput](https://github.com/adityasingh03rajput)

---

## About Me

I'm a self-driven full-stack developer who builds across the entire stack — web, mobile, desktop, and AI. I've shipped production-grade billing software, anonymous social platforms, attendance apps, developer tooling, ML-powered Android apps, and multiplayer games. I pick up whatever tech the problem needs and get it done.

---

## Tech Stack

**Frontend:** React 18, TypeScript, Vite, Tailwind CSS, Radix UI, Three.js, HTML5/CSS3  
**Backend:** Node.js, Express.js, Socket.io, REST APIs  
**Mobile:** React Native (Server-Driven UI), Android (Kotlin), Capacitor, Flutter  
**Database:** MongoDB, Supabase, SQLite  
**AI/ML:** PyTorch, Random Forest, MediaPipe, MobileNet V3, EfficientDet, facial recognition  
**Tools:** JWT, WebRTC, bcrypt, Electron, Twilio, Cloudinary, jsPDF, Recharts, Git

---

## Projects

### BillVyapar — Full-Stack Business Management & Billing Platform
[github.com/adityasingh03rajput/BillVyapar](https://github.com/adityasingh03rajput/BillVyapar)

A complete billing ecosystem for small and medium businesses in India. Runs as a web app, Android APK (Capacitor), and desktop app (Electron) — one account, every platform.

**Core Features:**
- All document types: Invoice, Quotation, Purchase Order, Challan, Proforma, Credit Note — with PDF export and 8 professional templates
- Auto GST calculation (CGST/SGST/IGST), GSTIN lookup via RapidAPI, GST reports ready for filing
- Customer & Supplier management with full party ledger and outstanding balance tracking
- Vyapar Khata — digital udhar bahi (debit/credit ledger per party)
- POS mode for fast counter billing
- Real-time analytics dashboard — revenue trends, top items, invoice conversion rate
- Automatic payment reminders via Twilio SMS — detects overdue invoices, notifies customers automatically
- Employee attendance tracking with GPS map view
- Bank account management with UPI QR code support
- Extra expense tracking, project management, roles & permissions
- Subscription system — 7-day free trial, license key activation, graceful feature lock on expiry
- Master Admin console — manage all subscribers, generate license keys, plans, audit logs, revenue analytics
- Offline support via IndexedDB caching, lazy-loaded pages, gzip compression (~70% payload reduction)
- 6 UI themes (Light, Dark, Warm, Ocean, Emerald, Rosewood) + built-in guided walkthrough tour

**Tech:** React 18, TypeScript, Tailwind CSS, Radix UI, Recharts, jsPDF, html2canvas, Node.js, Express, MongoDB, JWT, bcrypt, Twilio, Cloudinary, Nodemailer, Capacitor (Android), Electron, Vite


---

### INTROVERT — Anonymous Social Platform
[github.com/adityasingh03rajput/adioncode](https://github.com/adityasingh03rajput/adioncode) · Live: https://google-8j5x.onrender.com

A full-stack anonymous social platform — not just a chat app. Built with a complete social graph, AI features, and real-time everything.

**Core Features:**
- JWT auth with bcrypt, session persistence, auto-login after registration
- Real-time messaging via Socket.IO — typing indicators, message history, room-based chat
- Posts system — create posts with image upload (Multer + Sharp), feed with pagination, likes, comments, delete
- Follow system — follow/unfollow, follow requests, accept/reject, followers/following lists
- Random matching — gender preference, online-only matching, enhanced retry algorithm
- Face recognition search — upload a photo, get top 5 user matches with confidence scores
- Notifications — real-time push via Socket.IO, types: like, comment, follow, badge
- Badge system — Bronze (25 follows), Silver (50), Gold (100) — auto-awarded
- Watch parties — sync YouTube videos across all users in a room via Socket.IO
- Collaborative canvas — real-time drawing with HTML5 Canvas, 5 colors, coordinate sync
- WebRTC voice & video calls — RTCPeerConnection, STUN server, full signaling via Socket.IO
- AI translation — 7 languages, translates last message on demand
- AI smart replies — conversation suggestions
- Profile management — bio, interests, username, profile picture (300x300 processed)
- Content moderation, rate limiting, XSS protection, Helmet.js security headers

**Tech:** Node.js, Express, Socket.IO, JWT, bcrypt, Multer, Sharp, WebRTC, HTML5/CSS3/JS

---

### LetsBunk / Native-Bunk — Smart Attendance Tracking System
[github.com/adityasingh03rajput/native-bunk](https://github.com/adityasingh03rajput/native-bunk) · ⭐ 1

A hybrid attendance system combining a React Native mobile app, Node.js + MongoDB backend, and an Electron admin desktop panel. The standout feature: Server-Driven UI — the server controls the entire UI layout, enabling dynamic updates without releasing a new app version.

**Mobile App Features:**
- Face verification — biometric attendance marking
- WiFi BSSID validation — confirms student is physically in the classroom
- Real-time circular timer — tracks presence duration per lecture
- Teacher dashboard — manage students, view attendance
- Random ring system — surprise checks to verify student presence
- Timetable and calendar screens
- Offline support — works without internet

**Backend Features:**
- RESTful API for all mobile operations
- Socket.IO for real-time data sync
- MongoDB for attendance, students, teachers data
- Azure deployment, rate limiting

**Admin Panel (Electron):**
- Student management — add, edit, bulk import, attendance history
- Teacher management — accounts, permissions, class assignments
- Attendance reports — generate and export
- WiFi BSSID mapping configuration

**Tech:** React Native, JavaScript, Node.js, Express, Socket.IO, MongoDB, Electron, Python (face verification), Azure


---

### Chilly Chills — Food Ordering Platform
[github.com/adityasingh03rajput/Chillychills](https://github.com/adityasingh03rajput/Chillychills)

A full-stack food ordering system built for a college canteen — with separate interfaces for students, staff, and managers, plus a real-time backend and an Electron admin desktop app.

**Student App Features:**
- Browse menu by category, add to cart, place orders
- UPI checkout modal with QR code payment
- Wallet/credit top-up system
- Selfie broadcast — live selfie feed feature
- Order tracking with real-time status updates via Socket.IO

**Manager Dashboard:**
- Full menu management — add, edit, delete items, category management
- Branch announcements and branch-level menu control
- Staff management — add/remove staff, assign roles
- Analytics dashboard — real-time stats, sales trends, employee performance, customer behavior, popular items
- Finance dashboard — monthly balance sheet, revenue by category, 12-month summary, export to Excel/PDF
- PDF downloader for reports

**Staff Dashboard:**
- View and manage incoming orders
- Update order status in real-time

**Backend (Node.js + MongoDB):**
- REST API with Socket.IO events for live order/menu updates
- 50–300ms avg response time, <50ms real-time latency
- Balance sheet and analytics endpoints
- Deployed on Railway

**Tech:** React Native, TypeScript, Node.js, Express, MongoDB, Socket.IO, Electron, Supabase, Tailwind CSS

---

### EquityEdge — Stock Trading Web App
[github.com/adityasingh03rajput/BillVyapar](https://github.com/adityasingh03rajput/BillVyapar)

A modern stock trading platform with a full dashboard, portfolio management, and admin panel.

**Features:**
- Dashboard — portfolio value, balance, total invested, profit/loss, P&L %, live market indices, watchlist
- Buy/sell trade modal — execute trades directly from the dashboard
- Stock market page — browse all stocks with price change badges
- Stock details page — individual stock view with charts
- Portfolio page — holdings overview with performance metrics
- Watchlist — track favourite stocks
- Transactions page — full trade history
- Admin page — platform management
- JWT auth, protected routes, theme support (next-themes)
- Recharts for all data visualizations, Netlify deployment

**Tech:** React 18, TypeScript, Vite, Tailwind CSS, Recharts, React Router, JWT, Netlify


---

### NodeCity 3D — Interactive Code Visualization Platform
[github.com/adityasingh03rajput/nodecity](https://github.com/adityasingh03rajput/nodecity) · Live: https://adityasingh03rajput.github.io/nodecity

Transform any codebase into an interactive 3D city you can walk through. Each file is a building, each directory is a district. No installation needed — just open the HTML file in a browser and upload your project folder.

**41+ Features including:**
- 3D city rendering with Three.js — smart file categorization (controllers, services, components, utilities)
- 6 visualization modes: Normal, File Size, Complexity, Change Frequency, Test Coverage, Team Ownership
- Heat maps, security scanner (4 severity levels), code smell detector (7+ types), test coverage overlay
- Dependency graph — see connections, detect circular dependencies, path finder between any two files
- Multi-user collaboration — see other devs as avatars, team color-coding (Frontend/Backend/DevOps)
- Time machine — scrub through git history, compare versions side-by-side
- Weather system — visual code health indicators, day/night cycle
- Achievements/gamification, API playground, export system (screenshots, diagrams, metrics)
- Controls: WASD movement, mouse look, fly up/down, zoom, inspect buildings, right-click context menu

**Tech:** Three.js, HTML, JavaScript, Git integration — zero dependencies to run

---

### Photo-Lelo 3.0 — Face Enrollment & Verification App
Android app for face-based enrollment and identity verification with liveness detection.

**Features:**
- Camera activity with real-time face detection
- Liveness detector — prevents photo spoofing
- Face embedding extraction using MobileNet-based model
- Face embedding helper for feature vector generation
- REST API integration — enrollments stored in MongoDB with face embeddings
- Verify enrollment by matching face embedding against stored data
- Node.js backend with full CRUD for enrollment records

**Tech:** Android (Kotlin), MediaPipe, MobileNet, Node.js, Express, MongoDB

---

### Ucab — Cab Booking Application
[github.com/adityasingh03rajput](https://github.com/adityasingh03rajput)

A full MERN stack cab booking app with real-time ride tracking and driver matching.

**Features:**
- JWT auth — secure login/signup
- Ride booking — select pickup/drop, choose cab type
- Nearby cab detection — shows available drivers on map
- Fare calculation — based on distance and time
- Real-time ride tracking via Socket.IO
- Automatic payments with saved methods
- Ride history, promo codes, donation options, in-ride refreshment purchase
- Layered architecture: Client → API → Service → Data Access (Mongoose)

**Tech:** React, TypeScript, Node.js, Express, MongoDB, Socket.IO, JWT, Vite


---

### AdionAI — AI-Powered Ink Formulation System

Two separate AI systems built to generate and optimize ink formulations — replicating the methodology used in a Nature-published Hokkaido University research paper.

**System 1 — Text Generation AI (Transformer)**
- Character-level Transformer (nanoGPT architecture) trained on historical ink recipes
- 6-layer Transformer, 8 attention heads, 256-dim embeddings
- Generates complete ink recipes: ingredients, quantities, preparation steps, color descriptions, pH levels
- Supports Iron Gall, India, Walnut, Sepia, and custom ink types
- Adjustable temperature for creativity control (0.5 conservative → 1.5 creative)
- Training: ~5–10 min on GPU, ~30–60 min on CPU

**System 2 — Chemical Optimization AI (Random Forest)**
- 4 Random Forest ML models trained on chemical property relationships
- Generates 500 candidate formulations, optimizes across 2000 candidates
- Outputs top 5 formulations meeting all specs: erasability, permanence, waterproofing, cost
- Best result: 9.97/10 overall score, ₹0.059/unit cost (target <₹1.29), 10/10 permanence
- Replicates Hokkaido University's adhesive protein optimization methodology

**Also engineered:** Phase-change polymerization ink formula with ternary solvent buffer for climate stability, silica ball-bearing matrix to prevent smudging, and hermetic sandwich design for 18+ month shelf life.

**Tech:** Python, PyTorch, scikit-learn (Random Forest), character-level Transformer

---

### Janubabu — Anonymous Chat Matching App

A minimal anonymous chat app where users pick a gender, get assigned a random name, and are matched with a stranger for a real-time conversation.

**Features:**
- Gender selector → random name generation → 3-second matching animation → live chat
- Sticker picker with emoji/sticker support
- Text and sticker message types
- Partner disconnect/reconnect flow
- Supabase backend for real-time data

**Tech:** React, TypeScript, Supabase, Tailwind CSS, Vite

---

### Lost Person Finder — Facial Recognition Missing Persons System
[github.com/adityasingh03rajput/lost-person-finder](https://github.com/adityasingh03rajput/lost-person-finder)

A web-based platform for reporting and finding missing persons using facial recognition. Users submit reports with photos and the system matches them against a database of missing persons using face comparison algorithms.

**Tech:** HTML, JavaScript, facial recognition

---

### Wall Chess & Wall Path Duels — Multiplayer Browser Games
[wall-chess](https://github.com/adityasingh03rajput/wall-chess) · [wall-path-duels](https://github.com/adityasingh03rajput/wall-path-duels)

Two multiplayer browser games — a full chess implementation and a strategy path-dueling game. Both have been forked by other developers.

**Tech:** JavaScript (Wall Chess), TypeScript (Wall Path Duels)

---

### Dermy Buddy — Skin Disease Classification
[github.com/adityasingh03rajput/dermy-buddy](https://github.com/adityasingh03rajput/dermy-buddy)

ML model for classifying skin diseases from images, based on the derm-ai architecture. Built for accessible dermatology screening.

**Tech:** Python, Machine Learning

---

### Weighment Software — Desktop Utility
A minimal Flutter Windows desktop app for weighment/measurement operations. Packaged as a standalone `.exe` installer with a clean UI.

**Tech:** Flutter, Windows desktop

---

## Contact

📧 adityarajsir162@gmail.com  
🐙 [github.com/adityasingh03rajput](https://github.com/adityasingh03rajput)
