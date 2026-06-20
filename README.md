# Jaejun Shim

Data Science and Computer Science student at the National University of Singapore, focused on finance-data systems, investment analytics, and data-platform engineering.

I work mainly with Python, SQL, kdb+/q, FastAPI, and data/ML tooling. My strongest interest is building systems that make complex investment, market-data, and analytical workflows more usable, governed, and testable.

## Current focus

- Trading analytics data systems
- kdb+/q APIs and market-data workflows
- SQL/ETL and database migration support
- Databricks / PySpark migration feasibility
- Python-based investment and sustainability analytics
- Finance-oriented simulation and risk-aware optimization

## Selected work

### GIC Trading Analytics — Software Engineering Intern

- Designed and implemented q-side APIs for configurable table retrieval, table listing, and schema description.
- Built validation and control logic for table access, table availability, service limits, date-range limits, symbol limits, and pattern-based configuration expansion across 100+ tables.
- Created Bruno API health-check test cases and fixed shared API-routing edge cases introduced by new API patterns.
- Supported database migration work involving SQL/DSL view definitions, ETL scripts, Flyway table alterations, and dev/pre-production validation.
- Started replicating FX NBBO view-generation logic from kdb+/q into Python/Databricks as part of a migration feasibility POC.

### GIC Investment Insights — Quantitative Strategist Intern

- Built Python-based sustainability analytics pipelines for portfolio-level climate assessment and transition-alignment analysis.
- Rewrote notebook-based methodology into structured, version-controlled Python modules.
- Corrected methodology-code inconsistencies across assessment level, interpolation logic, ID mapping, and intermediate-output joins.
- Migrated climate temperature-alignment analysis from R to Python and adapted it to upstream schema changes.
- Supported Green AUM analysis through fuzzy matching, LLM-assisted candidate verification, manual review, and stakeholder clarification.

## Public projects

### [DCA Simulator](https://github.com/Jaejun02/dca_simulator)

A local FastAPI/React application for comparing future dollar-cost-averaging contribution policies under simulated market scenarios.

Core components:

- Historical price ingestion with `yfinance`
- Daily-to-monthly return conversion
- Robust mean and covariance estimation
- Stationary block bootstrap for short-horizon scenarios
- Adaptive marginals and t-copula scenarios for longer horizons
- CVaR-based optimization with diversification constraints
- Backend tests and frontend build checks

This is a planning and comparison tool, not financial advice or a trading strategy.

### [ESG Data Extraction and Performance Analysis](https://github.com/Jaejun02/esg_analysis)

Course team project for extracting and analyzing ESG information from unstructured reports.

Personal contribution:

- Led a 10-person team.
- Implemented the main OCR extraction component.
- Implemented the LLM engine component.
- Participated in Dockerization.
- Coordinated meetings, implementation direction, blocker resolution, and final report consolidation.

Project-level scope included PDF ingestion, OCR, layout analysis, image/chart-to-text processing, semantic search, LLM-based extraction, ESG scoring workflow, UI/dashboard components, and storage integration.

### [Toxic Comment Classifier](https://github.com/Jaejun02/toxic_comment)

DistilBERT-based multi-label toxic comment classification project.

Key elements:

- DistilBERT architecture
- Optuna hyperparameter tuning
- Stratified k-fold validation
- Mixed-precision training
- Model checkpointing
- Reported best test F1 score: 0.947

## Technical stack

**Languages:** Python, SQL, kdb+/q, R, Java  
**Data / analytics:** Pandas, NumPy, scikit-learn, Matplotlib, CVXPY  
**ML / NLP:** PyTorch, Hugging Face, DistilBERT, Optuna, LLM-based extraction  
**Data engineering / platforms:** Databricks, PySpark, ETL workflows, Flyway, SQLite  
**Backend / tooling:** FastAPI, Docker, Git, Bruno, Selenium  

## Best-fit areas

- Finance data science
- Investment analytics
- Trading analytics software engineering
- Data engineering / data platform engineering
- Backend/API engineering for data-heavy systems
- Quant-adjacent analytics and simulation

## Contact

- LinkedIn: https://www.linkedin.com/in/jaejun-shim-02/
- Email: jaejun.shim@outlook.com
