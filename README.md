# 🛰️ VisionQuant

Can satellite imagery predict stock prices? This project uses Google Earth Engine + YOLOv11 to measure cargo aircraft activity at major U.S. logistics hubs and correlates it with FedEx/UPS stock performance.

**🥇 1st Place — Stony Brook University Datathon 2026, Finance & Economics Track**

## Hypothesis

Cargo activity at FedEx Memphis and UPS Louisville hubs — measured via satellite imagery — serves as a 3–4 week leading indicator for freight sector stock prices.

## Key Result

UPS Louisville hub: Pearson r = 0.44, p < 0.001 at 1-week lag. No significant signal found for FedEx Memphis.

## Stack

Google Earth Engine (Sentinel-2) · YOLOv11 · yfinance · scipy · scikit-learn · Plotly
