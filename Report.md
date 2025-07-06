# Dynamic Pricing System for Urban Parking Lots

## Overview

This project implements a **dynamic pricing engine** for urban parking lots using real-time data streams and multiple pricing models. The system is designed to optimize both utilization and revenue across 14 parking locations and 577 spaces, leveraging historical data, demand indicators, and competitive intelligence.

---

## Problem Statement

Traditional static pricing in urban parking lots leads to overcrowding during peak times and underutilization during off-peak hours. This project addresses these inefficiencies by introducing real-time, data-driven dynamic pricing that adapts to demand and competition.

---

## Objectives

- **Optimize space utilization** at all times
- **Maximize revenue** through responsive pricing
- **Reduce queue lengths** and improve customer experience
- **Respond to competitor pricing** in real time

---

## Data Analysis

- **Dataset**: 73 days of data, 18 daily time points, 577 spaces, 14 locations
- **Key fields**: Occupancy, Capacity, QueueLength, Traffic, VehicleType, SpecialDay
- **Insights**:
  - Occupancy varies from 10% to 47% daily
  - Queue lengths and traffic are strong demand signals
  - Vehicle mix (car, truck, bike, cycle) impacts pricing potential

---

## Demand Function

The core demand function combines occupancy, queue, traffic, peak hours, and special days:

