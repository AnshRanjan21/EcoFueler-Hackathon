# Smart Office Light Automator

Welcome to the **Smart Office Light Automator**, an innovative solution designed to optimize office lighting and reduce electricity usage. This application was developed as part of the **EcoFuelers Hackathon** by a team of three passionate developers: **Sarthak, Ansh, and Akash**. Our goal is to minimize electricity consumption by dynamically controlling office light brightness based on daylight sensor readings.

---

## Overview

This application uses real-time daylight sensor data to:
- Automatically adjust office light brightness for maximum energy efficiency.
- Calculate energy consumption and cost savings.
- Generate a smart lighting schedule using AI for further optimization.

---

## Features

- **Dynamic Brightness Adjustment**: Automatically adjusts light brightness based on `lux` values from daylight sensors.
- **Energy and Cost Calculation**: Provides insights into energy usage and cost savings.
- **AI-Powered Lighting Schedule**: Generates a natural-language schedule for lighting adjustments using the GROQ API.
- **Interactive Dashboard**: Displays key metrics, data overview, and generated schedules in a user-friendly interface.

---

## Input Requirements

The application expects a CSV file with the following columns:
- **`time`**: Time in HH:MM format (e.g., `06:00`, `14:30`).
- **`lux`**: Natural light sensor readings (e.g., `200`, `500`).

---

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
