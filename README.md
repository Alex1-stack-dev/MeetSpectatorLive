# 🏊 Meet Spectator Live

**A Smart AI-Powered Swim Meet Management & Broadcasting Platform**

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [System Requirements](#system-requirements)
- [Core Features](#core-features)
- [Technical Architecture](#technical-architecture)
- [Installation & Setup](#installation--setup)
- [User Workflows](#user-workflows)
- [Implementation Roadmap](#implementation-roadmap)
- [API Documentation](#api-documentation)
- [Deployment](#deployment)

---

## 🎯 Project Overview

**Meet Spectator Live** is a revolutionary AI-powered website for managing and broadcasting swim meets in real-time. It seamlessly integrates with HY-TEK Swim Meet Manager, automates heat sheet generation, provides live scoreboard overlays, generates performance analytics, and creates professional highlight videos—all in one platform.

### Key Philosophy
- **Simple for Everyone:** Intuitive UI for coaches, swimmers, parents, and volunteers
- **AI-First:** Machine learning handles tedious tasks (heat generation, video analysis, error correction)
- **Offline-First:** Works on any device with any internet quality (including offline mode)
- **Privacy-Focused:** All data remains under user control; post-meet data is downloadable and removable
- **Accessible:** Works on old and new devices, mobile and desktop, in the pool or at home

---

## 🔧 System Requirements

### For Meet Managers/Organizers
- **Computer:** Windows 10+, macOS 10.13+, or Linux
- **Browser:** Chrome, Firefox, Safari, or Edge (latest 2 versions)
- **Internet:** 10 Mbps for live streaming (4 Mbps minimum)
- **HY-TEK Access:** HY-TEK Swim Meet Manager installed and running on same or networked computer

### For Remote Viewers/Swimmers
- **Device:** Any smartphone, tablet, laptop, or desktop
- **Browser:** Modern web browser (2+ years old acceptable)
- **Internet:** 2 Mbps for streaming (LTE acceptable)

### For AI Features
- **GPU (Optional):** NVIDIA GPU recommended for faster video analysis (CPU fallback available)
- **Storage:** 5GB minimum for meet archives per 500 entries

---

## ✨ Core Features

### Tier 1: Essential (Free/Basic)
- [x] User accounts with password protection
- [x] Heat sheet viewing (imported from HY-TEK)
- [x] Live results display (manual input)
- [x] Basic performance tracking (times, places)
- [x] Meet summary statistics
- [x] Offline mode (basic functionality)

### Tier 2: Premium
- [x] **HY-TEK Integration:** Automatic data sync with HY-TEK Swim Meet Manager
- [x] **Live Scoreboard AI:** Auto-detect and display digital/analog scoreboards from video
- [x] **AI Video Analysis:** Upload swimmer videos → get stroke technique analysis
- [x] **Advanced Analytics:** Splits, trends, historical comparisons, projections
- [x] **Highlight Generation:** AI creates best moments from video feed
- [x] **Heat Sheet Auto-Generation:** AI assigns optimal heats based on seed times
- [x] **Live Timeline Updates:** Real-time race start time adjustments
- [x] **Phone Camera Broadcasting:** Stream meet with live scoreboard overlay
- [x] **Post-Meet Data Export:** ZIP file with all meet data, videos, analytics
- [x] **Stroke Comparison:** Compare swimmer's technique against exemplars
- [x] **Historical Archive:** Build 5-year+ performance database

### Tier 3: Enterprise (Custom)
- [x] Multiple meet management
- [x] White-label interface
- [x] Custom integrations
- [x] Priority support
- [x] Team/Club management
- [x] Regional/state competition tracking

---

## 🏗️ Technical Architecture

### Frontend Stack
