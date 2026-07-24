# queue-simulation
Web-based simulation of queueing and waiting time for MM1 model
# 🎬 M/M/1 Queue Animation Simulation

This project is a **visual simulation of a queueing system (M/M/1)** using HTML5 Canvas and JavaScript.

It demonstrates how customers arrive, wait in a queue, get served, and leave — with real-time animation.

---

## 📌 Features

- 🎯 Simulates **M/M/1 queue**
- 👤 Animated customers (dots moving)
- 📦 Queue visualization
- 🟩 Server processing
- ⚡ Real-time stochastic behavior
- 🎛 Adjustable parameters:
  - λ (arrival rate)
  - μ (service rate)

---

## 🧠 Concept

This simulation is based on:

- **Arrival process**: Poisson (rate λ)
- **Service time**: Exponential (rate μ)
- **Single server**

---

## 📊 System Behavior

| Condition | Behavior |
|----------|--------|
| λ < μ | Stable system |
| λ ≈ μ | Fluctuating queue |
| λ > μ | Queue grows (congestion) |

---

## 🎮 Demo

Customers move through 3 states:

1. 🟢 Arriving
2. 🔵 Waiting in queue
3. 🔴 Being served
4. ➡️ Leaving system

---

## 🚀 How to Run

### Option 1: Run locally

```bash
# Just open the file
index.html
