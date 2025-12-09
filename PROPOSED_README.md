# CourseVault-Free-Online-Education-Resource-Awesome-List

<p align="center">
  <a href="https://github.com/chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List">
    <img src="https://raw.githubusercontent.com/chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List/main/assets/hero-banner-coursevault.svg" alt="CourseVault Hero Banner" width="800">
  </a>
</p>

### ⭐ Star this Repo! ⭐

<p align="center">
  <a href="https://github.com/chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List">
    <img src="https://img.shields.io/github/stars/chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List.svg?style=flat-square&color=yellow" alt="GitHub stars">
  </a>
  <a href="https://github.com/chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List/blob/main/LICENSE">
    <img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-blue.svg?style=flat-square" alt="License: CC BY-NC 4.0">
  </a>
  <a href="https://github.com/chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List/actions/workflows/ci.yml">
    <img src="https://img.shields.io/badge/Status-Active%20Maintenance-brightgreen?style=flat-square" alt="Status: Active Maintenance">
  </a>
  <a href="#ai-agent-directives--maintenance-protocol">
    <img src="https://img.shields.io/badge/Linter-MarkdownLint%2FLink--Check-7C4DFF?style=flat-square" alt="Linter/Formatter">
  </a>
</p>

---

## 🚀 CourseVault: The Ultimate Free & Discounted Professional Education Resource

**CourseVault** is the definitive, community-driven resource list designed by architects for high-velocity professional development. This list strictly curates the best high-signal, zero-cost, or heavily discounted online courses, learning platforms, and coupon providers, ensuring your technical skill acquisition is efficient and future-proof.

Our mission is to eliminate link rot and guarantee that every resource listed delivers concrete, actionable knowledge in domains ranging from advanced software architecture (Rust, Go, AI) to deep-dive data science and cloud engineering.

## 🏠 Architectural Blueprint & Repository Structure

This repository adheres to the Awesome List Standard, prioritized for resource discovery and maintenance integrity.

tree
CourseVault/
├── .github/                     # Contribution & Template Standards (P0 Integrity)
├── .husky/                      # Pre-commit Hooks (Link Validation)
├── assets/                      # Logos and documentation images
├── categories/                  # Core Resource Folders (e.g., /AI-ML/, /Cloud-DevOps/)
│   ├── Data-Science.md
│   ├── Systems-Programming.md
│   ├── Web-Development.md
├── .awesomeconfig.yml         # List Configuration and Rules
├── CONTRIBUTING.md            # Mandatory guidelines for submissions
├── README.md                  # This document
└── LICENSE


## 🔖 Table of Contents

*   [Getting Started & Contribution Standards](#⚙️-getting-started--contribution-standards)
*   [Core Resource Categories](#📚-core-resource-categories)
    *   [Artificial Intelligence & Machine Learning](#artificial-intelligence--machine-learning)
    *   [Cloud, DevOps, & SRE](#cloud-devops--sre)
    *   [Systems Programming (Rust/Go)](#systems-programming-rustgo)
    *   [Frontend Architecture & Web](#frontend-architecture--web)
*   [🤖 AI Agent Directives & Maintenance Protocol](#🤖-ai-agent-directives--maintenance-protocol)
*   [License](#⚖️-license)

---

## 🤖 AI AGENT DIRECTIVES & MAINTENANCE PROTOCOL

<details>
<summary>⚡️ SYSTEM: APEX TECHNICAL AUTHORITY & RESOURCE MANAGEMENT PROTOCOL (December 2025)</summary>

# SYSTEM: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (RESOURCE MANAGEMENT EDITION)

## 1. IDENTITY & PRIME DIRECTIVE
**Role:** Senior Principal Architect, focused on Resource Integrity and Data Quality.
**Context:** Current Date is **December 2025**. Building a robust, Zero-Link-Rot resource list.
**Output Standard:** Maintain absolute data integrity and professional presentation.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof Resource Cataloging."

## 2. PROJECT ARCHITECTURE: THE RESOURCE VAULT
**Core Stack:** Markdown (Primary Data Storage), YAML (Configuration/Metadata).
**Architecture Pattern:** Curated Data Monolith (Emphasis on strict folder organization and schema enforcement).
**Maintenance Toolchain:**
*   **Package Manager:** `uv` (for rapid dependency resolution of maintenance scripts).
*   **Linter/Formatter:** `Pre-commit` framework executing `markdownlint-cli2` and internal link validation scripts.
*   **Configuration:** All resource categorization rules and link exceptions reside in `.awesomeconfig.yml`.

## 3. RESOURCE INTEGRITY MANDATES (ZERO-DEFECT POLICY)
1.  **Link Rot Prevention (P0):** All Pull Requests *must* pass an automated link checker via GitHub Actions (`ci.yml`). HTTP Status Codes 4xx or 5xx are grounds for immediate rejection.
2.  **Signal-to-Noise Ratio (P1):** Resources must genuinely be *Free* or offer discounts of 80%+. No pure paywalls or expired coupons are allowed.
3.  **Categorization:** Every entry must be placed under the most relevant section (`/categories/`). Maintain the **DRY** principle: A resource belongs in only one primary category.
4.  **Schema Enforcement:** Each entry must follow the standardized Markdown format:
    markdown
    * [Course Title](URL) - (Platform/Provider, Duration/Rating) [Tags: #Technology, #Level]
    

## 4. VERIFICATION & MAINTENANCE COMMANDS

Agents should utilize the following commands to validate local changes before submission:

bash
# 1. Install required tools (assuming Python 3.10+ and uv is installed globally)
uv sync

# 2. Run the pre-commit checks (mandatory Markdown linting and formatting)
pre-commit run --all-files

# 3. Custom Deep Link Checker Utility (for testing link health)
python scripts/validate_links.py --mode=deep --timeout=10


</details>

---

## ⚙️ Getting Started & Contribution Standards

We welcome high-quality contributions! Follow these steps to ensure your suggested resources meet our Apex standards:

1.  **Clone the Repository:**
    bash
    git clone https://github.com/chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List.git
    cd CourseVault-Free-Online-Education-Resource-Awesome-List
    
2.  **Setup Pre-commit Hooks:**
    Our resource list uses pre-commit hooks for mandatory Markdown linting (`markdownlint-cli2`) and formatting. This prevents trivial errors.
    bash
    # Install Python dependencies
    uv sync
    # Install the pre-commit hooks locally
    pre-commit install
    
3.  **Add Your Resource:** Navigate to the appropriate `.md` file in the `/categories/` folder and insert your resource following the strict schema defined in the [Agent Directives](#🤖-ai-agent-directives--maintenance-protocol).
4.  **Submit Pull Request:** Ensure all local pre-commit checks pass before pushing.

## 📚 Core Resource Categories

Click on a category to view the complete curated list of courses and platforms.

| Category | Description | Count (Approx) |
| :--- | :--- | :--- |
| **[Artificial Intelligence & Machine Learning](categories/AI-ML.md)** | Deep learning frameworks, foundational math, generative AI, and MLOps platforms. | 45+ |
| **[Cloud, DevOps, & SRE](categories/Cloud-DevOps.md)** | AWS, Azure, GCP certification paths, Kubernetes, Infrastructure-as-Code (IaC), and advanced monitoring. | 60+ |
| **[Systems Programming (Rust/Go)](categories/Systems-Programming.md)** | Low-level optimization, high-performance concurrency, operating systems theory, and embedded development. | 30+ |
| **[Frontend Architecture & Web](categories/Frontend-Web.md)** | TypeScript mastery, React/Vue/Svelte, micro-frontends, WebAssembly, and modern CSS architecture. | 75+ |
| **[Data Science & Analytics](categories/Data-Science.md)** | Python ecosystem (Pandas, NumPy), advanced SQL, data visualization, and data pipeline construction. | 50+ |


## ⚖️ License

This Awesome List is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)**. You are free to share and adapt the content for non-commercial purposes, provided you give appropriate credit to the `chirag127/CourseVault-Free-Online-Education-Resource-Awesome-List` repository.

---
