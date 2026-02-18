# TuneWorks Growth Strategy: End-to-End SQL Analysis 🎵

> **Role:** Data Analyst | **Team:** 6 Members
> **Tech Stack:** SQL (PostgreSQL), Advanced Excel, GenAI (Gemini)

## 📖 Project Overview
Designed and executed an **end-to-end data analysis solution** for TuneWorks, an entertainment booking agency facing revenue stagnation. Our team analyzed the complete data lifecycle—from cleaning raw booking logs to delivering strategic revenue optimization plans.

## 🎯 Key Objectives
* **Data Quality Audit:** Conducted rigorous data cleaning to ensure integrity across customer, agent, and engagement tables.
* **Revenue Optimization:** Identified high-value booking segments to restructure commission incentives.
* **Human vs. AI Benchmarking:** Pitched human-derived insights against AI (Gemini) analysis to evaluate the depth and accuracy of automated analytics.

## 📊 Key Findings & Strategic Impact (Resume Highlights)
* **Band vs. Solo (The High-Value Pivot):**
    * While solo acts had higher booking *frequency*, our SQL analysis revealed that **multi-member Bands generated significantly higher revenue per engagement**.
    * *Strategic Shift:* Recommended shifting agent incentives to prioritize Band bookings, projecting a potential **$100k+ revenue surplus** by reallocating resources from low-margin solo gigs.
* **Human Intelligence > AI Surface-Level Analysis:**
    * When benchmarking against AI (Gemini), we found that AI tools successfully summarized surface-level trends (e.g., "Top 3 Agents").
    * However, **AI failed to detect complex structural anomalies**, such as specific commission inefficiencies for top-tier talent. Our manual SQL deep-dives were required to uncover these actionable profit leaks that AI missed.
* **Resource Misallocation:**
    * Identified a mismatch in resource allocation where top-performing agents (generating ~$15k+ revenue) were under-supported, while operational focus was disproportionately skewed towards lower-margin activities.

## 🛠️ Technical Approach (End-to-End)
1.  **Data Ingestion & Cleaning:**
    * Utilized Regex in SQL to identify inconsistent zip codes, phone numbers, and email formats.
    * Verified referential integrity across 8+ relational tables.
2.  **Analysis & Modeling:**
    * Employed complex queries (`JOINs`, `CTEs`, `Window Functions`) to calculate agent revenue performance.
    * Performed hypothesis testing on customer preferences vs. actual purchasing behavior.
3.  **Strategy Formulation:**
    * Synthesized quantitative findings into a coherent business strategy for the executive board.

## 👥 Team Contribution
This was a collaborative group project. My specific contributions included:
* **Univariate Analysis:** Led the breakdown of single-variable trends.
* **Strategy Integration:** Synthesized the final executive presentation based on our "Human vs. AI" findings.
* **Code Review:** Collaborated on SQL logic validation.

## 📂 Files Included
* `TuneWorks_Strategy_Deck.pdf`: Executive presentation of findings and recommendations.
* `SQL_Analysis_Process.pdf`: Detailed documentation of SQL queries and data checks.
* `analysis_queries.sql`: Raw SQL scripts used for the project.

## 📄 License
This project is for educational purposes.
