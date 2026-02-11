<h1 align="center">D2CNet: Towards End-to-End Design to Wafer Contour Prediction for AI Computational Lithography</h1>

<p align="center">
<b>Official PyTorch implementation of the research paper</b>
</p>

<h2 align="center">📌 Overview</h2>

D2CNet is an AI-based proxy model designed to bridge the gap between initial design layouts and final wafer patterns. Unlike traditional multi-stage OPC flows, D2CNet learns to predict the continuous resist image (intensity field) directly from raw layouts. High-fidelity contours are then extracted from this predicted field, providing near-instantaneous feedback for Design-Technology Co-Optimization (DTCO). This approach represents a significant step towards a fully end-to-end design-to-wafer solution.

<h2 align="center">📅 Project Status: Coming Soon</h2>

Note: The code and the PanGen Dataset are currently being cleaned and organized.

[ ] Release inference code and pre-trained models.

[ ] Release the PanGen Dataset (derived from OpenXiangShan layouts).

[ ] Provide training scripts and evaluation tools.


<h2 align="center">📊 Dataset: PanGen</h2>

The PanGen Dataset is a large-scale, industrial-grade benchmark constructed from OpenXiangShan processor layouts using the PanGen computational lithography platform. It captures the cumulative manufacturing effects of full-flow industrial OPC recipes at a calibrated 28nm node.
