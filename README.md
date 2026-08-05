<p align="left">
  <img src="https://img.shields.io/badge/Project_Status-Experimental-yellow?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Language-Python_|_HTML_|_CSS_|_JS-blue?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Track-Graph_Theory-brightgreen?style=for-the-badge&logo=neo4j&logoColor=white" />
  <img src="https://img.shields.io/badge/Team-SynergyX-red?style=for-the-badge" />
</p>

# 🛡️ CypherRing: Financial Forensics Engine
### **RIFT 2026 Hackathon | Graph-Based Financial Crime Detection Track**
---
## Live Demo
https://cypherring.onrender.com
---
**CypherRing** is a high-performance forensics engine engineered to expose money muling networks. The application transforms complex transaction data into graph structures to autonomously detect illicit financial patterns.

---

## 👥 The Team: Synergy X
* **Vaibhav Singh** (Team Lead) — *Lead Architect & Graph Logic* 🏗️
* **Antra Priyadarshini** — *UX/UI & Interactive Graph Visualization* 🎨
* **Srishti Maurya** — *Algorithm Optimization & Technical Documentation* 📝

---

## 🧠 Core Detection Methodology
Our engine specifically targets the mandatory forensic patterns required by RIFT 2026:

### 1. Circular Fund Routing (Cycles)
* **Logic**: Identification of closed-loop chains (3 to 5 hops) where funds eventually return to the source account to obscure the trail.


### 2. Smurfing Patterns (Fan-in / Fan-out)
* **Fan-in**: Detection of a single aggregator account receiving funds from 10+ distinct senders.
* **Fan-out**: Identification of a single sender dispersing funds to 10+ distinct receivers.
* **Temporal Analysis**: High-priority flagging for suspicious transactions occurring within a critical 72-hour window.

### 3. Layered Shell Networks
* **Logic**: Exposing intermediate "shell" accounts characterized by low transaction counts (2-3 total) that serve as transit points for layering.

---

## 🛠️ Technical Stack
* **Backend**: Python (Flask)
* **Frontend**: HTML5, CSS3, JavaScript (D3.js for Interactive Graph Visualizations)
* **Graph Engine**: NetworkX for $O(V + E)$ cycle detection efficiency.

---

## 🚀 Submission Checklist & Performance Targets
To ensure eligibility and avoid disqualification, CypherRing meets all mandatory performance metrics:


| **Processing Time** | ≤ 30s for 10K transactions | ✅ Optimized |
| **Precision** | ≥ 70% (Minimizing false positives) | ✅ Target Met |
| **Recall** | ≥ 60% (Catching maximum fraud rings) | ✅ Target Met |
| **JSON Schema** | Exact line-by-line field matching | ✅ Validated |
---
