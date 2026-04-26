# Multi-Channel Telematics Server Dashboard

This repository contains an interactive dashboard developed for our Stochastic Processes project on the simulation of a multi-channel telematics server.

The objective of the project is to study how a server with a limited number of channels behaves when incoming calls arrive randomly and service durations are also random. If all channels are occupied, the incoming call is rejected. The dashboard helps visualize this behavior and makes it easier to understand how the system changes when the main parameters are modified.

## Project context

The system is modeled as a loss system with no waiting queue. Each call is assigned to the first available channel. When all channels are busy, the call is blocked.

The main parameters are:

- `N`: number of available channels
- `T`: mean inter-arrival time between calls
- `D`: mean service duration
- simulation horizon: observation period of the simulation

The dashboard allows these parameters to be changed interactively.

## What the dashboard shows

The dashboard includes:

- a visual representation of the multi-channel server
- live scenario controls
- acceptance rate
- blocking probability
- average number of occupied channels
- traffic intensity
- occupied channels over time
- channel utilization
- state distribution
- convergence behavior
- sensitivity to traffic intensity

These visualizations are useful for comparing normal operation, near-saturation, and saturated situations.

## How to use it

Open the dashboard from the GitHub Pages link.

Then adjust the sliders to change the system parameters. You can also use the preset buttons to quickly test different operating regimes:

- Underloaded
- Balanced
- Near saturation
- Saturated

Each change updates the simulation results and the graphs automatically.

## Project files

- `index.html`: the full interactive dashboard

The dashboard is self-contained and can be opened directly in a browser.

## Tools used

The dashboard was built with:

- HTML
- CSS
- JavaScript
- Plotly.js for interactive charts

The simulation logic is implemented directly in JavaScript so that the dashboard can run without installing additional software.

## Authors

Emna Saada  
Souha Hamdani

## Course

Stochastic Processes  
Manouba University — Manouba School Of Engineering

## Instructor

Dr. Fatine Maghrebi

## Academic year

2025–2026
