# 🛰️ VisionQuant

Can satellite imagery predict stock prices? This project uses Google Earth Engine + YOLOv11 to measure cargo aircraft activity at major U.S. logistics hubs and correlates it with FedEx/UPS stock performance.

**🥇 1st Place — SBU Datathon 2026, Finance & Economics Track**

## Hypothesis

Cargo activity at FedEx Memphis and UPS Louisville hubs — measured via satellite imagery — serves as a 3–4 week leading indicator for freight sector stock prices.

## Key Results

**Correlation:** UPS Louisville hub showed Pearson r = 0.44 (p < 0.001) at 1-week lag. No significant signal found for FedEx Memphis.

**Backtest (2022.01 – 2024.06):** Satellite-derived trading signals targeting UPS outperformed passive benchmarks — SPY returned +18.3%, XTN returned -15.7% over the same period.

**FDX vs UPS divergence:** Despite operating in the same freight sector, FDX returned +22.2% while UPS returned -29.6% — a 47.9% spread that satellite activity patterns helped explain.

## Stack

Google Earth Engine (Sentinel-2) · YOLOv11 · yfinance · scipy · scikit-learn · Plotly