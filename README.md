# 🎟️ District Live Entertainment & Dining: Venue Operations & Box Office Telemetry Analytics

### Partner Venue Operations | Entry SLA Diagnostics | Inventory Health
**District by Eternal | Delhi NCR Market**

[![Python](https://img.shields.io/badge/Python-Pandas%20%7C%20NumPy-yellow)](https://www.python.org/)
[![SQL](https://img.shields.io/badge/SQL-SQLite%20%7C%20PostgreSQL-blue)](https://www.sqlite.org/)
[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)](https://powerbi.microsoft.com/)
[![Analytics](https://img.shields.io/badge/Analytics-Operations%20Analytics-green)](https://en.wikipedia.org/wiki/Business_analytics)
[![GitHub](https://img.shields.io/badge/Version%20Control-GitHub-black)](https://github.com/)

---

## 📌 1. Project Overview

An end-to-end Operations and Product Analytics framework simulating live event ticketing, venue check-ins, and premium partner dining operations for **District (by Eternal)** across Delhi NCR.

The project focuses on analyzing end-to-end commercial fulfillment, diagnosing on-ground operational bottlenecks, monitoring partner venue inventory health, and delivering executive-ready business intelligence.

The analytical framework is structured around four major operational pillars:

### 🎯 Primary Business Objectives

- **Ticketing & Reservation Performance:** Analyze Gross Booking Value (GBV), booking conversion, and payment method distribution.
- **Turnstile & Entry SLA Diagnostics:** Monitor venue check-in velocity, gate scan times, and peak-hour queue breach rates.
- **Tiered Inventory Health:** Evaluate live inventory allocation, reserved VIP capacity, and partner table reconciliation.
- **Executive Strategic KPIs:** Assess regional market penetration across Gurugram, Delhi, and other NCR corridors.

---

## 🎥 2. Dashboard Walkthrough

**[▶️ Watch Interactive Dashboard Walkthrough](PASTE_YOUR_VIDEO_LINK_HERE)**

*Replace the placeholder with your dashboard walkthrough video link.*

---

## 🛠️ 3. Data Infrastructure & Technology Stack

| Technology | Purpose |
|---|---|
| Python (Pandas, NumPy, Faker) | Synthetic generation of 5,000+ transactional and gate-scan telemetry records |
| SQLite / PostgreSQL | Relational database architecture, data normalization, and indexing |
| SQL | CTEs, conditional aggregations, window functions, and SLA diagnostics |
| Power BI Desktop | Interactive operational dashboards and executive reporting |
| DAX | Dynamic KPIs, operational measures, and performance calculations |
| Git & GitHub | Version control and structured project repository |

---

## 🔄 4. Analytics Workflow & Schema Architecture

### End-to-End Analytics Pipeline

Business Requirements Gathering → Relational Schema Design → Synthetic Telemetry Generation (Python) → SQL Data Modeling → Power BI Intelligence → Operational Recommendations

### Database Schema Structure

The project uses a normalized relational database architecture consisting of six primary tables:

| Table | Description |
|---|---|
| `Bookings` | Core transaction metadata, including Customer ID, Venue ID, booking status, timestamps, and payment mode |
| `Booking_Items` | Granular ticket/table items, booking quantities, and convenience surcharges |
| `Experiences_Catalog` | Experience categories such as Concerts, Nightlife, Dining, Comedy, and Pop-ups |
| `Inventory_Allocation` | System capacity, physical venue allocations, and reserved inventory |
| `Gate_Personnel` | On-ground check-in and entry-scan staff telemetry |
| `Venues` | Partner venue details, geographical corridors, and capacity limits |

---

## 📊 5. Executive Dashboards & Operational Views

The Power BI solution is structured into four executive-facing dashboards.

### 1. Venue Operations & Entry Dashboard

**Primary KPIs:**
- Total Revenue: ₹7.0M
- Total Bookings: 5,000
- Average Order Value (AOV): ₹1,400
- Average Check-in Time: 16.06 minutes
- Entry SLA Breach Rate: 47.14%
- Active Customers

**Visual Diagnostics:**
- Hourly Booking Trajectory
- Revenue by Experience Category
- Payment Gateway Distribution
- Check-in Latency by NCR Cluster

### 2. Experience & Tiered Inventory Health Dashboard

**Primary KPIs:**
- Total Active SKUs / Experiences
- Average Platform-Allocated Capacity
- Physical Venue Capacity
- Reserved VIP Inventory
- Disputed / Overbooked Capacity

**Visual Diagnostics:**
- Inventory Distribution by Vertical
- System Capacity vs Actual Venue Capacity
- Allocation Variance across Premium Corridors

### 3. Box Office & Gate Staff Productivity Dashboard

**Primary KPIs:**
- Total Active Turnstile Scanners
- Check-in Scans per Gate
- Gate Latency per Attendee
- SLA Compliance Percentage

**Visual Diagnostics:**
- Volume Scanned per Turnstile
- Gate Queue Latency Trends
- Shift-wise Peak Flow Dynamics

### 4. Executive Business Summary

**Strategic Perspectives:**
- Revenue by Geographic Corridor (Gurugram vs Delhi vs Peripheral NCR)
- Category Contribution Breakdown
- Booking Fulfillment vs Cancellation Dynamics
- Regional Commercial Performance

---

## 🔍 6. Critical Business Insights

### 1. Revenue & Spend Velocity

- Generated **₹7.0 Million in Gross Booking Value (GBV)** across 5,000 completed bookings.
- Documented an **Average Order Value of ₹1,400**, indicating strong spending potential across curated weekend dining and live entertainment experiences.

### 2. Geographic Market Concentration

- **Gurugram emerged as the dominant commercial hub**, contributing approximately ₹2.3M–₹2.5M, representing around 35% of total platform GBV.
- DLF CyberHub and Golf Course Road were the primary commercial corridors.
- Delhi followed as the second-largest market, contributing approximately ₹1.8M–₹2.0M.
- Noida, Faridabad, and Ghaziabad represented emerging markets with opportunities for localized partner acquisition.

### 3. Turnstile SLA & Gate Congestion Bottleneck

- Average attendee check-in duration: **16.06 minutes**.
- Entry SLA Breach Rate: **47.14%**.
- Nearly one out of every two attendees experienced entry delays beyond the defined operational SLA during peak 8 PM–10 PM weekend arrival windows.

This identified venue check-in congestion as a major operational friction point.

### 4. Category Diversification

Bookings were distributed across five core experience verticals:

- Live Concerts & Festivals
- Nightlife & Clubs
- Curated Dining & Table Reservations
- Stand-up Comedy & Theatre
- Lifestyle Pop-ups & Experiences

A diversified category mix helps reduce dependence on individual event categories and seasonal concert demand.

### 5. Fulfillment & Drop-off Integrity

- **93.6% Successful Fulfillment:** 4,680 out of 5,000 bookings were successfully redeemed at partner venues.
- **6.4% Cancellation / No-show Rate:** 320 bookings resulted in cancellations or unredeemed reservations.

This highlights opportunities to improve booking fulfillment through better entry management and partner coordination.

---

## 🚀 7. Actionable Strategic Recommendations

### 1. Staggered Entry & Dynamic Turnstile Fast-Tracks

Introduce tiered entry time slots, such as 15-minute priority arrival windows, along with dedicated fast-track lanes for eligible District Priority Pass and loyalty customers.

**Expected Impact:** Reduced gate congestion and improved SLA compliance.

### 2. Real-time Inventory & Table Auditing

Synchronize POS and box-office capacity feeds through automated inventory reconciliation to identify discrepancies between digital platform allocations and actual venue capacity.

**Expected Impact:** Reduced overbooking and improved partner coordination.

### 3. Strategic Merchant Expansion

Leverage Gurugram's approximately ₹2.5M GBV contribution by expanding exclusive ticketing and dining partnerships across high-density commercial corridors.

**Expected Impact
