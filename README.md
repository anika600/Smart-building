# 🏢 Smart Building Portal

A modern and responsive web-based **Resident Dashboard & Smart Home Automation Portal**. This frontend application simulates an intuitive control center for apartment residents, allowing them to manage environmental conditions, track real-time energy usage, book building amenities, and coordinate security access through a unified interface.

---

## ✨ Features Checklist & Pages Included

### 📊 1. Main Dashboard (`index.html`)
* **Smart Alert Banner:** Highlights critical, urgent updates such as real-time water leak warnings or active maintenance updates.
* **Quick Actions Block:** Instant control components like toggling living room lights or engaging "Away Mode" with a single click.
* **Energy Snapshot Widget:** Aggregated monthly analytics compared automatically with historical data.
* **Building Announcements Billboard:** Centralized community scroll for pool maintenance schedules, fire drills, and facility updates.

### 🌡️ 2. Environment Control (`environment.html`)
* **Climate (HVAC) Console:** Sliders to regulate indoor temperature settings alongside action buttons for Cooling, Heating, Fan, or **AI Comfort Mode**.
* **Lighting Intensities:** Multi-room overhead sliders coupled with reactive iOS-style binary toggle switches.
* **Blinds & Window Shades:** Position sliders offering variable opacity/aperture configurations from completely open to 100% blacked out.

### 📅 3. Amenity Booking (`amenities.html`)
* **EV Charging Reservation:** Keeps track of live availability statuses for garage vehicle stalls.
* **Fitness Center Cap Tracker:** Real-time capacity monitoring with dedicated booking parameters.
* **Lounge & Conference Space:** Interface to reserve common spaces for private gatherings or collaborative meetings.

### 🛡️ 4. Security & Access Control (`security.html`)
* **Guest Token Generator:** Allows residents to input guest credentials and select temporal duration keys (2h / 8h / 24h).
* **Live Intercom Feed Simulation:** View block container complete with functional action controls to "Talk" or remotely "Unlock" structural gates.
* **Immutable Smart Access Logs:** Historical verification timeline showing resident keystrokes, package notifications, and courier validations.

### ⚡ 5. Energy Dashboard (`energy.html`)
* **Live Usage Telemetry:** Gauges current active load directly in kilowatts (`0.82 kWh`).
* **Financial Projection Model:** Formulates current month's estimated billing liabilities based on consumption patterns.
* **Renewable Offsets Visualization:** Tracks clean power contributions yielded from standard rooftop solar array structures.

### 🔧 6. Support & Maintenance Portal (`support.html`)
* **Structured Ticketing System:** Category dropdown matrix (Plumbing, Electrical, HVAC, Appliances) with photo upload capacity.
* **Historical Request Tracker:** Visual trace matrix utilizing distinct status states (`In Progress` in Warning Amber, `Completed` in Success Green).

---

## 🎨 Design Language & UI Architecture (`style.css`)

The structural interface follows modern design aesthetics utilizing:
* **Typography:** `Inter` variable sans-serif configuration pulled directly from Google Fonts for ultimate readability.
* **Color System:** - Primary Base Accent: `#0A7CFF` (Vibrant San Francisco Blue)
  - Layout Card Backdrops: `#FFFFFF` with muted subtle boundaries (`#E9ECEF`)
  - Universal Canvas Fill: `#F8F9FA` (Soft Neutral Contrast)
* **Custom Interactive Components:** CSS-only toggle animation states, custom slider tracks, floating navigation blocks with persistent sidebar layouts, and smart CSS grid column spans (`grid-col-span-2`) ensuring consistent layout configurations regardless of screen size.

---

## 🛠️ Installation & Getting Started

 **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/Smart-building.git](https://github.com/YOUR_USERNAME/Smart-building.git)
