<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1f14,40:15803d,100:16a34a&height=220&section=header&text=People%20Analytics%20Guide&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Formulas%20%E2%80%A2%20KPIs%20%E2%80%A2%20Benchmarks%20%E2%80%A2%20DAX%20%E2%80%A2%20SQL%20%E2%80%A2%20Python&descAlignY=60&descColor=86efac"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2500&pause=900&color=16a34a&center=true&vCenter=true&width=720&lines=10+validated+KPIs+for+HR+leaders;Excel+%7C+DAX+%7C+SQL+%7C+Python+%7C+Power+BI;Benchmarks%3A+SHRM+%C2%B7+AIHR+%C2%B7+LinkedIn+%C2%B7+Michael+Page;Open+guide+%E2%80%94+PT+%F0%9F%87%A7%F0%9F%87%B7+%26+EN+%F0%9F%87%BA%F0%9F%87%B8+available"/>

<br/>

[![Open PT](https://img.shields.io/badge/🇧🇷%20Abrir%20em%20Português-16a34a?style=for-the-badge)](https://fernandotrecruiter.github.io/people-analytics-guide/)&nbsp;
[![Open EN](https://img.shields.io/badge/🇺🇸%20Open%20in%20English-2563eb?style=for-the-badge)](https://fernandotrecruiter.github.io/people-analytics-guide/index-en.html)&nbsp;
[![Stars](https://img.shields.io/github/stars/fernandotrecruiter/people-analytics-guide?style=for-the-badge&color=f59e0b&label=⭐%20Stars)]()

<br/>

</div>

---

## 🎯 What is this?

A **complete, interactive People Analytics guide** built for HR and TA professionals who want to go beyond spreadsheets.

Every formula is validated against real-world benchmarks from **SHRM, AIHR, LinkedIn Talent Trends, Michael Page and ABRHF** — covering 4 environments in a single click: Excel, DAX (Power BI), SQL, and Python.

> **No fluff. Just the formulas your CEO will actually ask about.**

---

## 📊 10 KPIs Covered

| # | KPI | Formula | Benchmark |
|:-:|-----|---------|-----------|
| 1 | **Turnover Rate** | Exits ÷ Avg HC × 100 | 10–15% (SHRM) |
| 2 | **Retention Rate** | 100 − Turnover Rate | ≥ 85% |
| 3 | **eNPS** | (Promoters − Detractors) ÷ Total × 100 | 20–40 (AIHR) |
| 4 | **Absenteeism** | Absent days ÷ (HC × Work days) × 100 | ≤ 3.5% (AIHR) |
| 5 | **Time to Fill** | Req open → Offer accepted (days) | 30–45 days (SHRM) |
| 6 | **Offer Acceptance Rate** | Offers accepted ÷ Offers extended × 100 | ≥ 85% (LinkedIn) |
| 7 | **Cost per Hire** | (Internal + External costs) ÷ Hires | ~USD 4,700 (SHRM) |
| 8 | **Quality of Hire** | (Performance Score + Retention Score) ÷ 2 | ≥ 70 |
| 9 | **Voluntary Turnover** | Voluntary exits ÷ Avg HC × 100 | ≤ 10% (SHRM) |
| 10 | **Time to Hire** | Application → Offer accepted (days) | 15–30 days |

---

## 🛠️ Formulas available in

<p align="center">
  <img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/DAX%20%7C%20Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
  &nbsp;
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  &nbsp;
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
</p>

---

## ✨ Guide Features

<table>
<tr>
<td width="50%">

**📚 Content**
- 10 fully worked KPI sections with formula derivation
- 8 Business Q&A — real questions CEOs ask
- STAR framework for storytelling with data
- Flight Risk Score model (Python)
- 12-month implementation roadmap

</td>
<td width="50%">

**🎨 UX**
- Hover tooltips on every technical term
- Accordion sections (click to expand)
- 4-tab formula switcher per KPI
- PT 🇧🇷 green / EN 🇺🇸 blue themes
- Sidebar navigation with source links
- Fully responsive layout

</td>
</tr>
</table>

---

## 🗄️ Data Model (Star Schema)

```
dim_Colaboradores ──┐
dim_Vagas ──────────┤──► fato_Historico ──────► dim_dCalendario
                    └──► fato_Avaliacoes ─────► dim_dCalendario
```

5 tables • Power BI ready • Compatible with Azure Synapse, BigQuery, Databricks

---

## 🚀 Open the Guide

<div align="center">

| | Language | Link | Color theme |
|:---:|:---:|:---:|:---:|
| 🇧🇷 | Português | [**→ Abrir Guia PT**](https://fernandotrecruiter.github.io/people-analytics-guide/) | 🟢 Emerald green |
| 🇺🇸 | English | [**→ Open EN Guide**](https://fernandotrecruiter.github.io/people-analytics-guide/index-en.html) | 🔵 Royal blue |

</div>

---

## 📚 References & Benchmarks

| Source | Used for |
|--------|----------|
| [SHRM](https://www.shrm.org) | Turnover Rate, Time to Fill, Voluntary Turnover, Cost per Hire |
| [AIHR](https://www.aihr.com) | eNPS, Absenteeism, Quality of Hire, Retention Rate |
| [LinkedIn Talent Trends](https://business.linkedin.com/talent-solutions/global-talent-trends) | Offer Acceptance Rate, Time to Hire |
| [Michael Page BR](https://www.michaelpage.com.br) | Brazil market salary & hiring benchmarks |
| [ABRHF](https://www.abrhf.org.br) | Brazilian HR standards and practices |

---

## 🗺️ Implementation Roadmap

```
Q1 · Data Foundation     → HRIS audit · star schema · headcount dashboard
Q2 · Operational KPIs    → All 10 KPIs · ATS integration · scheduled reports
Q3 · Predictive          → Flight Risk Score · correlation analysis · stay interviews
Q4 · Strategy & ROI      → Board report · ROI calc · next-year workforce planning
```

---

<div align="center">

Built by [**Fernando L. Paoli**](https://github.com/FernandoTRecruiter) — Tech Recruiter & People Analytics Enthusiast · São Paulo, BR · 2026

<sub>🔗 Also check: [Interactive HR Dashboard](https://fernandotrecruiter.github.io/FernandoTRecruiter.2/) · [LinkedIn](https://www.linkedin.com/in/fernandopaoli)</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16a34a,100:0d1f14&height=120&section=footer"/>
