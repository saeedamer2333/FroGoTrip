# FrogoTrip 🐸✈️ — AI-Powered Travel Itinerary & Smart Booking Platform

> **Your Intelligent Travel Companion**: Automated, budget-optimized day-by-day travel itineraries with seamless hotel, experience, and transit booking.

[![Project Status](https://img.shields.io/badge/status-MVP%20%2F%20Active%20Development-success.svg)](https://github.com/sensayousef)
[![Platform](https://img.shields.io/badge/platforms-iOS%20%7C%20Android%20%7C%20Web-blue.svg)](https://flutter.dev)
[![Backend](https://img.shields.io/badge/backend-NestJS%20%7C%20TypeScript-ea284e.svg)](https://nestjs.com)
[![Affiliate Network](https://img.shields.io/badge/partner%20network-Travelpayouts%20%7C%20Booking.com-ff6900.svg)](https://www.travelpayouts.com)
[![License](https://img.shields.io/badge/license-Proprietary-lightgrey.svg)](#)

---

## 📌 Overview

**FrogoTrip** is an AI-powered travel planning and booking application designed to solve the most exhausting part of travel: the 20+ hours typically spent researching destinations, coordinating multi-day schedules, comparing hotel locations, and balancing budgets.

With FrogoTrip, travelers input their destination, dates, budget tier, travel style, and party size. In seconds, the platform generates a comprehensive, day-by-day itinerary complete with verified attractions, curated restaurants, optimized transit routes, and **direct booking recommendations for accommodations and activities**.

FrogoTrip bridges the gap between **inspiration, planning, and booking** by integrating trusted affiliate inventory (powered by **Travelpayouts**, including **Booking.com**, **Viator**, and **GetYourGuide**) directly into the traveler's itinerary journey.

---

## 🧭 The Problem & Our Solution

| The Traditional Booking Dilemma | The FrogoTrip Solution |
|---|---|
| **Fragmented Research:** Travelers juggle 10+ tabs across Google Maps, TripAdvisor, Reddit, and booking sites. | **All-in-One Engine:** Day-by-day itinerary, interactive route map, budget breakdown, and direct booking links in a single unified flow. |
| **Location Mismatch:** Booking a hotel that turns out to be far from daily activities, wasting hours in transit. | **Geographic Clustering:** Accommodations are suggested based on the geographic center of the traveler's planned activities. |
| **Budget Surprises:** Travelers frequently overspend by 20–30% due to unexpected transit and activity costs. | **Deterministic Budget Optimization:** 40/30/20/10 budget allocation (Lodging, Food, Activities, Transit) with live tracking. |
| **Low-Intent Window Shopping:** Standard travel blogs suffer from low conversion because readers are only browsing. | **High-Intent In-Itinerary Handoff:** Users book accommodations and activities directly tailored to their confirmed trip dates. |

---

## 💼 Travelpayouts & Affiliate Partnership Model

FrogoTrip is built to provide high-converting, contextual booking touchpoints rather than generic banner ads. Every affiliate recommendation serves a specific functional purpose in the traveler's journey:

```
[ Traveler Inputs Preferences ]
            │
            ▼
[ AI Generates Multi-Day Itinerary ]
            │
            ├─► 🏨 1. Where to Stay (Booking.com via Travelpayouts)
            │      - Curated hotel cards matching daily activity clusters
            │      - Transparent "Book on Booking.com" handoff sheet
            │
            ├─► 🎟️ 2. Tours & Activities (Viator / GetYourGuide / Klook)
            │      - Direct ticket reservation for key landmarks & museums
            │      - Guided day-trip booking links
            │
            ├─► 🚗 3. Transit & Getting Around (DiscoverCars / 12Go / Flights)
            │      - Airport transfer recommendations & inter-city routes
            │      - Car rental comparison for regional legs
            │
            ▼
[ Seamless Handoff to Official Partner Checkout ]
```

### 1. Accommodations (Booking.com via Travelpayouts)
- **Contextual Hotel Cards**: As soon as an itinerary is generated, FrogoTrip calculates the optimal neighborhood based on the activities planned and presents 3 curated hotel options (Budget, Balanced, Premium).
- **"Compare Prices & Book" Sheet**: Travelers view live pricing, ratings, and amenity highlights, then tap a direct button that opens Booking.com with the traveler's exact dates and destination pre-filled using affiliate tracking parameters.

### 2. Tours, Activities & Attractions (Viator, GetYourGuide, Klook via Travelpayouts)
- **In-Itinerary Activity Handoff**: When a schedule includes high-demand sights (e.g., teamLab Tokyo, Eiffel Tower, Batu Caves tour, Island hopping in Phuket), a **"Reserve Ticket / Book Tour"** button is integrated right on the activity card.
- **Guaranteed Conversion Intent**: Users are guided to secure their tickets in advance, preventing sold-out disappointments.

### 3. Transportation, Flights & Transfers (Aviasales, DiscoverCars, 12Go)
- **Transit Cost Estimates**: The app calculates realistic transit legs (ride-hailing, train, rental car) and offers direct partner booking links for rental cars and regional transit tickets.

---

## 👥 Audience & Market Reach

- **Core User Demographic:** Independent travelers, couples, digital nomads, and young families aged 22–45.
- **Commercial Intent:** **High purchase intent.** Users generate itineraries with explicit start dates, durations, and headcount. They are ready to book.
- **Key Target Geographies:**
  - **Southeast Asia:** Malaysia, Thailand, Singapore, Indonesia, Vietnam
  - **East Asia:** Japan, South Korea
  - **Middle East:** UAE, Saudi Arabia, Qatar
  - **Europe:** UK, France, Italy, Germany, Spain
- **Distribution Channels:**
  - Native iOS & Android App Store distribution (organic ASO).
  - Web itinerary sharing (shareable web links and interactive PDF exports with clickable affiliate booking links).
  - Community "Discover" hub featuring creator-curated trips with integrated affiliate booking tags.

---

## ✨ Core Features & User Experience

- 🤖 **AI-Driven 3-Alternative Generation**: Offers Budget, Balanced, and Premium itinerary plans matching the traveler's stated spend.
- 🗺️ **Interactive Geographic Route Map**: Real-time map with numbered pins, daily travel routes, and distance estimates.
- 🏨 **Integrated "Stay Finder"**: Instant lodging suggestions placed near the day's highlights.
- 👛 **Live Trip Wallet & Cost Breakdown**: Tracks actual spend against the planned budget across stays, meals, activities, and transit.
- 🧳 **Traveler's Essentials Kit**: Localized weather forecast, foreign exchange converter, emergency contacts, customs etiquette, and cultural phrasebook.
- 📤 **Shareable Itineraries & PDF Export**: Travelers can share view-only web links or export branded PDFs that retain affiliate booking links.

---

## 🛡️ Affiliate Disclosure & Compliance Policy

FrogoTrip adheres strictly to ethical affiliate marketing practices, search engine guidelines, and partner network terms of service:

1. **Clear Affiliate Disclosure:** FrogoTrip prominently notifies users that booking links are affiliate partnerships:
   > *"FrogoTrip partners with trusted travel providers including Booking.com and Travelpayouts. When you book a stay or activity through our links, we may earn an affiliate commission at no additional cost to you. We only recommend accommodations and experiences that fit your itinerary criteria."*
2. **Transparent Pricing:** We never inflate prices or add hidden booking fees. Travelers receive the exact same rates (or partner discounts) available directly on Booking.com.
3. **Secure Official Checkout:** All financial transactions, card processing, booking confirmations, and customer service requests occur directly on the certified partner platform (e.g., Booking.com). FrogoTrip never stores traveler payment card details.
4. **Data Privacy & GDPR / PDPA Compliance:** FrogoTrip respects user privacy. No personal identifying information (PII) is shared with affiliate networks beyond standard anonymous click tracking identifiers (`tripId`/`clickId`).

---

## 🛠️ Technology Stack

| Layer | Technologies | Purpose |
|---|---|---|
| **Frontend** | **Flutter (Dart)** | High-performance, cross-platform native app for iOS, Android, and Web |
| **Backend API** | **NestJS (TypeScript)** | Scalable microservice-ready backend architecture |
| **Databases** | **PostgreSQL + Prisma ORM** | Secure transactional user data, saved itineraries, and click tracking |
| **Caching & Queue** | **Redis** | High-speed cache for places, routes, and rate-limiting |
| **AI Planning Engine** | **OpenAI GPT-4 & Google Places API** | Intelligent itinerary generation with verified real-world places and coordinates |
| **Affiliate Engine** | **Travelpayouts Deep-Linking API** | Dynamic tracking URL generation, partner attribution, and click reconciliation |

---

## 📱 Product Preview & Screenshots

```
+-----------------------------------+     +-----------------------------------+
|  FrogoTrip — Day 2 in Tokyo       |     |  🏨 Recommended Stay              |
|  [ Map View ]   [ Timeline View ] |     |  Shinjuku Granbell Hotel          |
|                                   |     |  ⭐ 4.5/5 (2,410 reviews)         |
|  09:00 AM — Meiji Jingu Shrine    |     |  📍 0.8 km from your Day 2 stops  |
|  11:30 AM — Harajuku Takeshita    |     |  💵 $110 / night                  |
|  01:00 PM — Afuri Ramen (Lunch)   |     |                                   |
|  03:00 PM — Shibuya Sky           |     |  [ Compare Prices on Booking.com ]|
|  [ 🎟️ Reserve Shibuya Sky Ticket ] |     |  (Opens official Booking.com app) |
+-----------------------------------+     +-----------------------------------+
```

---

## 📞 Partnership & Contact Information

We actively welcome affiliate networks, hotel chains, OTA partners, and tourism boards.

- **Platform Name:** FrogoTrip
- **Project Lead & Architecture:** Yousef Abu Al Atta (`sensayousef`)
- **Backend & Integrations:** Saeed Alameri
- **Business Development & Partnerships:** Zayed Fahad
- **Partnership Inquiries:** [saeedamerz200@gmail.com](mailto:saeedamerz200@gmail.com)
- **Development Status:** Private Development (Beta Launch Q4 2026)

---

<p align="center">
  <b>FrogoTrip 🐸 — Smart itineraries. Seamless bookings. Unforgettable journeys.</b><br>
  © 2026 FrogoTrip Team. All rights reserved.
</p>
