# 🚗 AutoDrive Simulator

## Self-Driving Car for Indian Roads

A complete autonomous driving simulator built with Python, PyGame, and OpenCV. The car drives itself on curved Indian roads with cows, auto-rickshaws, traffic lights, and zebra crossings.

---

## 📋 Features

- 🛣️ **Curved Road** with 3 lanes and lane markings
- 🚦 **Traffic Light System** (Red/Yellow/Green with automatic stopping)
- 🐄 **Cow Detection** - Car brakes automatically when cow appears (only 1 cow per game)
- 🚗 **Obstacles** - Cars, Auto-rickshaws, and Cows with bounding boxes
- 🎮 **Auto/Manual Mode** - Toggle between AI driving and manual control
- 🖥️ **Dual View** - Game window + AI camera view with telemetry
- 🧠 **Lane Detection** using Computer Vision (OpenCV)
- 📊 **Real-time Telemetry** - Speed, Action, Crashes, Distance

---

## 🏗️ Project Architecture

┌─────────────────────────────────────────────────────────────┐
│ AUTODRIVE SIMULATOR │
├─────────────────────────────────────────────────────────────┤
│ │
│ MODULE 1 MODULE 2 MODULE 3 MODULE 4 │
│ Environment Perception Decision Integration│
│ │
│ • Road • Lane Detect • Brake Logic • Main Loop │
│ • Traffic Light • Object Detect • Steer Logic • Display │
│ • Obstacles • Bounding Box • Speed Control • Controls │
│ • Car Physics • Traffic Response │
│ │
└─────────────────────────────────────────────────────────────┘
