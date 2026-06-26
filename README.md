# Operational Intelligence

### Making safer operational decisions in ERP- and AI-supported environments

Modern ERP systems answer:

> **What happened?**

Modern AI systems answer:

> **What is likely to happen?**

Operational leaders still face a critical question:

> **Should we act?**

This project explores that decision gap through an interactive Operational Intelligence demonstration. Using a vendor-based operational dataset, four analytical lenses evaluate procurement and operational conditions before a governance layer determines whether an AI-supported recommendation should be executed.

---

# Why this project?

Organizations increasingly rely on dashboards, predictive analytics, and AI recommendations to support operational decisions.

While these technologies improve visibility and prediction, they often leave one important question unanswered:

> **Is it operationally safe to execute this recommendation?**

This demonstration proposes one possible approach to that problem by combining multiple analytical perspectives with a structured decision governance layer.

Rather than replacing human judgment, the objective is to support more transparent and defensible operational decision-making.

---

# Interactive Demonstration

The repository contains a browser-based demonstration.

**Features**

* Browser-based (no installation required)
* No login or registration
* No cloud upload
* Data remains on your device during execution
* Supports vendor-based operational datasets across multiple industries
* Includes sample procurement data for evaluation

Industries include:

* Manufacturing
* Construction
* Pharmaceuticals
* Infrastructure
* General Procurement
* Supply Chain Operations

---

# Operational Intelligence Methodology

The demonstration evaluates a single operational dataset through four complementary perspectives.

## CIIP

**Cross-Industry Input Pressure**

Identifies upstream operational and supplier pressure that may influence procurement decisions.

---

## OVIS

**Operational Variability Intelligence Score**

Evaluates operational stability and process variation.

---

## POIS

**Procurement Opportunity Intelligence Score**

Identifies procurement improvement opportunities based on operational performance.

---

## ODEX

**Operational Decision Execution Framework**

Acts as the governance layer.

Rather than asking whether AI confidence is high, ODEX evaluates whether the operational conditions support safe execution of the recommendation.

---

# Repository Structure

```text
operational-intelligence

├── demo/
│     Browser-based interactive demonstration
│
├── docs/
│     The Blind Spot Problem
│
├── images/
│     Screenshots used throughout the project
│
├── video/
│     Demonstration walkthrough
│
├── README.md
│
└── LICENSE
```

---

# Getting Started

1. Download the repository.
2. Open:

```text
demo/index.html
```

3. Upload a vendor-based CSV.

or

Use the included sample dataset.

The demonstration performs all processing locally within your browser.

---

# Supporting Material

This repository includes:

* Interactive Demonstration
* The Blind Spot Problem (research paper)
* Demonstration Video
* Supporting screenshots

---

# Project Status

**Version:** 1.0

This is an independent research demonstration intended to explore Operational Intelligence concepts and decision governance.

Future work includes:

* Validation using enterprise operational datasets
* Multi-industry case studies
* Additional governance scenarios
* Expanded analytical validation

---

# About

Developed by **Aditya V. S. Poduri**

Independent research in:

* Operational Intelligence
* Supply Chain Analytics
* Operational Decision Systems
* AI Governance

The objective of this work is to explore practical approaches for improving enterprise operational decision-making through transparent analytical methodologies.

---

# Feedback

Constructive feedback from operations leaders, supply chain professionals, quality practitioners, researchers, and AI governance experts is welcome.

The goal of this repository is continuous improvement through practical discussion and real-world validation.
