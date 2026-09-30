# 🚀 NER Smart Logistics — User & Consignor Portal ("Crazy & Ultimate Ideas")

This repository contains the standalone **User-Friendly Portal** for NER Smart Logistics.

## Features
- **Live Package & Convoy Tracker HUD**: Real-time shipment status (`AS-01-EC-9082`, `AS-01-OX-4011`, `NER-DRONE-01`) with cold-chain temperature telemetry (-182.4°C / 4.1°C).
- **Interactive Route Planner & Voice Guidance**: Terrain maps for Sikkim Nathu La, Arunachal Sela Pass, and Meghalaya Dawki with speech synthesis.
- **AI Instant Cargo Booking**: Real-time delivery rate quote and vehicle recommendation engine.
- **Mountain Pass Weather & Hazard Feed**: Live weather meters and avalanche warnings.
- **Driver Emergency SOS Beacon**: 1-tap SOS trigger with green-wave traffic request.

## How to Deploy Standalone

### Option A: Deploy to Vercel (Recommended)
```bash
cd ner_user_website
npx vercel
```

### Option B: Deploy to Netlify
```bash
cd ner_user_website
npx netlify deploy --prod
```

### Option C: Serve Locally
```bash
cd ner_user_website
npx serve .
```
