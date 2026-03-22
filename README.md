# Mobile-First Map UI

A mobile-first interactive map application with glassmorphic UI built using **React**, **Tailwind CSS**, and **MapLibre GL JS**.

---

## Features

### 1. Header

* Simple header with a **menu icon** (☰) and **app title**.
* Responsive and glassmorphic style.

### 2. Search Bar

* Glassmorphic search bar at the top of the map.
* **Click anywhere** on the search bar to expand and focus input.
* **Enter** key searches for the location using OpenStreetMap Nominatim API.
* ✖ button closes the search bar.
* Smooth expand/collapse animations.

### 3. Map

* Built with **MapLibre GL JS** using OpenStreetMap tiles.
* **Tilt and rotate** map using native gestures.
* Zoom, pan, rotate, and pitch controlled by gestures or UI buttons.
* Map renders beyond visible boundaries for seamless panning.
* Mobile-first touch gestures supported:

  * **Pan**: 1-finger drag
  * **Zoom**: pinch with 2 fingers
  * **Rotate (bearing)**: twist with 2 fingers
  * **Tilt (pitch)**: 2 fingers drag up/down together

### 4. Custom Map Controls

Bottom-right floating controls include:

* **Zoom In (+)**
* **Zoom Out (-)**
* **Reset North (🧭)**
* **Center on Me (📍)**: flies to user’s current location

### 5. Bottom Navigation

* Five navigation items:

  * Home 🏠
  * Explore 🧭
  * Active ⚡
  * History 🕘
  * Profile 👤
* Glassmorphic, mobile-first layout.

---

## Installation

1. Open `index.html` in a browser.
2. No backend required. Uses **React CDN** and **MapLibre GL JS CDN**.
3. Supports **desktop and mobile devices**.

---

## Usage

1. **Search**: Click anywhere on the top bar → type location → press Enter.
2. **Zoom/Rotate/Tilt**: Use touch gestures or bottom-right controls.
3. **Center on Me**: Click 📍 to fly to current location.
4. **Bottom Nav**: Switch between app sections (currently UI placeholders).

---

## Notes

* Uses **OpenStreetMap tiles** (no API key required).
* Map is **interactive** but doesn’t have 3D objects yet.
* Designed to **feel like a native mobile map app**, but works on desktop too.
* All floating UI elements are **glassmorphic** with smooth transitions.
Do you want me to add that?
