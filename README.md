# PressGuard OS - Press Shop Critical Spares Monitoring App

A comprehensive **3-tier role-based monitoring and procurement workflow application** for tracking critical spare parts in heavy-tonnage press shop operations (500T - 2000T mechanical stamping, hydraulic blanking, and transfer presses).

## Features

- **Level 1 - Store Keeper**: Real-time bin stock monitoring, consumption logging, Min/Max safety buffer tracking, critical shortage flagging
- **Level 2 - Supervisor**: Downtime risk evaluation, formal Purchase Indent (Requisition) generation with urgency classification
- **Level 3 - Purchase Manager**: Vendor selection, commercial terms, Purchase Order (PO) issuance against approved Indents

## Critical Spares Tracked

| Part No | Component | Press Line | Unit Cost |
|---------|-----------|-----------|-----------|
| PRS-HYD-SL-9042 | Main Ram Hydraulic Seal Kit (Ø420mm) | 1000T Schuler | $1,250 |
| PRS-CLU-FR-3011 | Clutch & Brake Friction Disc (Ø650mm) | 1200T Komatsu | $840 |
| PRS-SEN-PR-8820 | Die Protection Proximity Sensor (M18) | 800T Aida | $145 |
| PRS-LUB-MK-5510 | Lubrication Metering Block (8-Port) | 600T Clearing | $490 |
| PRS-VLV-DS-4402 | Dual Safety Solenoid Valve (Cat 4 PLe) | 1200T Komatsu | $2,180 |
| PRS-BSH-BR-7218 | Bronze Bolster Bushing (ID 120mm) | 500T Bliss | $320 |

## How to Run

1. Download or clone this repository
2. Open `press_shop_spares_app.html` in any modern browser (Chrome, Edge, Firefox)
3. Switch between the three user roles using the role selector in the header
4. Try raising Indents (as Supervisor) and issuing POs (as Purchase Manager)

## Files

- **press_shop_spares_app.html** - Self-contained interactive app prototype (HTML + Tailwind CSS + JavaScript)
- **press_shop_spares_architecture.md** - Detailed architecture, data schema, and UI/UX specification

## Tech Stack

- HTML5 / CSS3 (Tailwind CSS)
- Vanilla JavaScript
- SVG technical schematics for each spare part
- GitHub REST API for deployment

---

*Built for Stamping & Heavy Forging Division - Bay 4 High-Tonnage Lines*