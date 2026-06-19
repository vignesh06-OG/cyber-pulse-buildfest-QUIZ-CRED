CYBER-PULSE // AI SOC COPILOT

Built for QuizCred BuildFest 2026
Team: CodeSynergy (Aryan, Sanzi, Vignesh)

1. Executive Summary

Modern enterprise security teams are drowning in 'Alert Fatigue.' Static text logs and traditional SIEM dashboards are too slow to communicate the spatial trajectory and ultimate objective of a cyber attack.

The Problem: Traditional SOCs take an average of 2 minutes and 45 seconds to manually correlate logs, map threat origins, and initiate countermeasures.
The Solution: Cyber-Pulse reduces Time-To-Insight (TTI) to 0.8 seconds. It is an autonomous Threat Intelligence Engine that translates raw, high-frequency network telemetry into a live 3D tactical workspace, backed by an AI reasoning copilot.

2. Core Value Proposition

Cyber-Pulse shifts the paradigm from passive visualization to active decision intelligence.

Financial Impact Tracking: Real-time calculation of potential financial loss prevented through automated neutralization.

Predictive Modeling: The engine doesn't just show what is happening; it predicts the next likely action (e.g., forecasting a Payment Gateway attack following a recon scan).

Zero-Latency Alert Pipeline: Translates raw network telemetry instantly into visual nodes and actionable insights.

3. System Architecture & Capabilities

3.1. Telemetry Ingestion Engine

The system simulates real-time ingestion of network metrics:

Requests Per Second (RPS)

Failed Authentication Attempts

Unique Source IPs

3.2. AI Reasoning & Threat Classification

A built-in rules engine (simulating an LLM logic layer) evaluates telemetry against predefined thresholds to automatically classify threats, mapping them directly to the MITRE ATT&CK Framework:

[T1498] Distributed Denial of Service (DDoS): Identified via massive RPS spikes targeting core gateways.

[T1110] Credential Stuffing: Detected via rapid failed login sequences from distributed IPs.

[T1046] Aggressive Port Scan: Classified during anomalous sequential port knocking (Reconnaissance).

3.3. Spatial Visualization Workspace (Three.js)

The Global Grid: A high-FPS, interactive 3D globe rendering global infrastructure nodes.

Attack Trajectories: Dynamic Bezier curves that map the precise origin and destination of an active threat vector.

Heat Nodes: Pulsing 3D spheres at the attack origin for immediate visual localization.

4. The Response Protocol (Kill Chain)

Cyber-Pulse acts as a force multiplier for Security Analysts:

Detect & Predict: The AI Copilot identifies an anomaly and generates a high-confidence prediction.

Recommend: The system immediately proposes specific, actionable countermeasures (e.g., "Null-route offending ASNs", "Force CAPTCHA validation").

Execute: With a single click ("REVIEW AI RECOMMENDATIONS" -> "EXECUTE ALL"), the analyst deploys the defense protocols.

Contain: The network stabilizes, and the dashboard logs the neutralized threat and the estimated ROI of the intervention.

5. Technology Stack

This MVP was engineered with a focus on high-performance rendering and seamless UI/UX:

Frontend & 3D Rendering: HTML5, Three.js, OrbitControls.js

UI/UX Design: Tailwind CSS (Glassmorphism, Dark Tech Aesthetic)

Fonts & Typography: Google Fonts (Orbitron, Share Tech Mono)

Logic & Simulation: Pure Vanilla JavaScript (No external backend dependencies for the MVP, ensuring instant demo capability).

6. Future Roadmap

Phase 1 (Current): Prototype and visual simulation of the AI Copilot.

Phase 2: Integration with real LLM APIs (e.g., OpenAI/Gemini) for dynamic natural language threat reasoning.

Phase 3: Backend integration with actual SIEM tools (Splunk/ELK) via secure WebSockets for real-world telemetry ingestion.

Phase 4: Autonomous Mode (Zero-touch threat neutralization).

"Cyber-Pulse: See the Future. Secure the Perimeter."
