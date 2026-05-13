# Gestione Lavoratori – Demo Edition

## 🚩 The Problem
In the real company workflow, several issues existed:
- Worker **PDFs and personal files were saved randomly** across Windows folders, making them hard to locate when needed.
- Important **documents expired without anyone noticing**. HR often discovered papers had already ended when they were urgently required.
- **Searching and navigating** through Windows Explorer was slow and confusing, especially with many files scattered across directories.
- No automatic reminders or alerts existed for upcoming deadlines.

## 🎯 The Demo Solution
This repository contains a **demo build** of a desktop application that shows how those problems can be solved.  
⚠️ **Note:** This demo is different from the main application used internally:
- It does **not save data permanently** (no persistent database).
- It does **not auto‑create or manage company data**.
- It has a **simplified interface** compared to the full version.
- It is intended only as a **showcase** of design and functionality.

The demo EXE illustrates:
- A structured interface with tabs for Workers, Documents, and Files.
- Uploading, inspecting, downloading, and deleting files directly from the app.
- Tracking document expiration dates and showing reminders for expiring/expired items.
- Desktop notifications and optional email alerts.
- Search by ID or name, alphabetical filters (A→Z / Z→A), and date sorting (newest/oldest).
- A modern, easy‑to‑use GUI built for non‑technical staff.

## 🛠️ Tech Stack
- **Language:** Python 3.14
- **UI:** Tkinter + ttkbootstrap (modern theme)
- **Extras:**  
  - `tkcalendar` for fast date selection (`yyyy-mm-dd` format)  
  - `win10toast` for Windows desktop notifications  
  - `smtplib` for optional email reminders  
  - `PyInstaller` for packaging into a single `.exe`

## 📦 Current Demo Release
This EXE is the **first demo version** of the project. It already supports:
- Worker CRUD (add, edit, delete)
- Document CRUD with reminders
- File management (upload, inspect, download, delete)
- Dashboard with totals and expiration counts
- Notifications at startup and periodic checks

## 🔮 Roadmap / Upcoming Features
Future updates will add:
- Persistent database saving (SQLite with auto‑creation)
- Multi‑language support (English, French, Italian)
- Export reports to PDF/Excel
- Role‑based access (admin vs. HR staff)
- Cloud sync option (OneDrive/Google Drive)
- Advanced search filters (by company, contract type, etc.)
- Settings tab for easier SMTP/email configuration

## 📸 Screenshots
*(Add screenshots of Workers tab, Documents tab, Files tab, and Notifications here)*

## 🚀 How to Run
1. Download the latest demo release from the **Releases** section.
2. Double‑click `GestioneLavoratori.exe`.
3. Explore the interface and features.  
   ⚠️ Remember: this demo does not save data permanently.

---

> ⚠️ **Note:** This repository contains only a demo binary and documentation. It does not include the company’s source code or internal data, to respect privacy requirements.
