<div align="center">

  <img src="assets/future-of-work-3d-globe.gif" width="300" alt="Future of Work Globe Animation" />

  # 🚀 The Future of Work 2030
  ### *AI • Workforce Automation • Salary Dynamics • Emerging Skillsets*

  <p align="center">
    <strong>An end-to-end interactive Tableau analytics project exploring how Artificial Intelligence is reshaping industries, job viability, and tomorrow's talent landscape.</strong>
  </p>

  <p align="center">
    <a href="YOUR_TABLEAU_PUBLIC_LINK" target="_blank">
      <img src="https://img.shields.io/badge/Live_Dashboard-Tableau_Public-E97627?style=for-the-badge&logo=tableau&logoColor=white" alt="Live Demo" />
    </a>
    <a href="#-research--methodology">
      <img src="https://img.shields.io/badge/Methodology-Documentation-7C3AED?style=for-the-badge&logo=gitbook&logoColor=white" alt="Methodology" />
    </a>
    <a href="data/future_of_work.csv">
      <img src="https://img.shields.io/badge/Dataset-500_Records-00B8D9?style=for-the-badge&logo=databricks&logoColor=white" alt="Dataset" />
    </a>
  </p>

  <!-- Metric Badges -->
  <p align="center">
    <img src="https://img.shields.io/badge/Analyzed_Jobs-500-blue?style=flat-square" />
    <img src="https://img.shields.io/badge/Sectors-10_Industries-indigo?style=flat-square" />
    <img src="https://img.shields.io/badge/Remote_Friendly-50.2%25-success?style=flat-square" />
    <img src="https://img.shields.io/badge/Avg_Salary-$91,222-emerald?style=flat-square" />
    <img src="https://img.shields.io/badge/High_Automation_Risk-34%25-critical?style=flat-square" />
  </p>

</div>

---

## 📑 Table of Contents

- [Executive Summary](#-executive-summary)
- [Interactive Dashboard Architecture](#-interactive-dashboard-architecture)
- [Deep Dive Dashboards](#-deep-dive-dashboards)
  - [1. AI & Modern Workforce Landscape](#1-ai--modern-workforce-landscape)
  - [2. Job Automation Risk vs. Industry Growth](#2-job-automation-risk-vs-industry-growth)
  - [3. Compensation & Skillset Economics](#3-compensation--skillset-economics)
  - [4. Strategic Recommendations](#4-strategic-recommendations)
- [Data Pipeline & Methodology](#-data-pipeline--methodology)
- [Key Insights at a Glance](#-key-insights-at-a-glance)
- [Project Architecture & File Tree](#-project-architecture--file-tree)
- [Setup & Exploration](#-setup--exploration)
- [Author & Acknowledgements](#-author--connect)

---

## 🎯 Executive Summary

The transition toward 2030 is defined not by wholesale human replacement, but by **accelerated task automation, talent polarization, and hybrid human-AI workflows**. 

This analytics study demystifies workforce transitions across **500 core roles** and **10 industries**, answering critical questions around:
- *Which sectors face immediate disruption versus those positioned for growth?*
- *What premium skill combinations insulate workers from automation?*
- *How does remote-work viability intersect with high AI integration?*

<br>

<div align="center">
  <table>
    <tr>
      <td align="center" width="25%">
        <h3>💼 500</h3>
        <sub>Benchmarked Job Profiles</sub>
      </td>
      <td align="center" width="25%">
        <h3>🤖 29.4%</h3>
        <sub>High AI Adoption Share</sub>
      </td>
      <td align="center" width="25%">
        <h3>⚠️ 48.7%</h3>
        <sub>Max Disruption (Transportation)</sub>
      </td>
      <td align="center" width="25%">
        <h3>💰 $96,937</h3>
        <sub>Peak Role (Ops Manager)</sub>
      </td>
    </tr>
  </table>
</div>

---

## 📊 Interactive Dashboard Architecture

The reporting suite comprises **four modular analytical views** linked via interactive filters and dynamic KPI parameters:

```text
                           ┌──────────────────────────────┐
                           │   FUTURE OF WORK 2030 SUITE  │
                           └──────────────┬───────────────┘
                                          │
         ┌────────────────────────┬───────┴────────────────────────┬────────────────────────┐
         ▼                        ▼                                ▼                        ▼
┌──────────────────┐    ┌──────────────────┐             ┌──────────────────┐     ┌──────────────────┐
│   01. AI MACRO   │    │ 02. RISK MATRIX  │             │  03. SALARY/SKILL│     │  04. STRATEGIC   │
│     OVERVIEW     │    │    & GROWTH      │             │     DYNAMICS     │     │ RECOMMENDATIONS  │
└────────┬─────────┘    └────────┬─────────┘             └────────┬─────────┘     └────────┬─────────┘
         │                       │                                │                        │
         └───────────────────────┴────────────────┬───────────────┴────────────────────────┘
                                                  ▼
                                       ┌─────────────────────┐
                                       │ ACTIONABLE INSIGHTS │
                                       └─────────────────────┘
