D2CNet: Towards End-to-End Design to Wafer Contour Prediction for AI Computational Lithography

Official implementation of the paper "D2CNet: Towards End-to-End Design to Wafer Contour Prediction for AI Computational Lithography".

📌 Overview

D2CNet is an AI-based proxy model designed to bridge the gap between initial design layouts and final wafer patterns. Unlike traditional multi-stage OPC flows, D2CNet learns to predict the continuous resist image (intensity field) directly from raw layouts. High-fidelity contours are then extracted from this predicted field, providing near-instantaneous feedback for Design-Technology Co-Optimization (DTCO). This approach represents a significant step towards a fully end-to-end design-to-wafer solution.

📅 Project Status: Coming Soon

Note: The code and the PanGen Dataset are currently being cleaned and organized. We are committed to making our research fully reproducible.

[ ] Release inference code and pre-trained models.

[ ] Release the PanGen Dataset (derived from OpenXiangShan layouts).

[ ] Provide training scripts and evaluation tools.

Stay tuned by Starring or Watching this repository!

📊 Dataset: PanGen

The PanGen Dataset is a large-scale, industrial-grade benchmark constructed from OpenXiangShan processor layouts using the PanGen computational lithography platform. It captures the cumulative manufacturing effects of full-flow industrial OPC recipes at a calibrated 28nm node.



📫 Contact

For questions regarding the paper or code, please contact:
Yong Zhao - yzhao@zhejianglab.com
