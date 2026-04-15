# 🏭 Production Downtime Analysis & Optimisation
## 📊 SQL + Power BI Project

## 📌 Overview

This project analyses production downtime in a mid-sized manufacturing company (**GreenTech Manufacturing**) to identify root causes of inefficiencies and provide data-driven recommendations to optimise production scheduling and reduce operational losses.

GreenTech specialises in eco-friendly consumer products and has experienced rapid growth, but increasing demand exposed inefficiencies in production planning and downtime management.

## 🌱 Business Context

GreenTech Manufacturing produces:

- Eco-cleaning supplies
- Recyclable packaging
- Energy-efficient appliances

As production scaled, maintaining efficient scheduling and minimising downtime became critical to:

- Meeting customer demand
- Reducing operational costs
- Sustaining profitability

## ⚠️ Problem Statement

The business faced recurring production downtime caused by:

- Machine failures
- Raw material shortages
- Inefficient scheduling
- Manual planning processes
- Limited visibility into operational bottlenecks

### 💥 Business Impact

- ~$1.5M annual loss
- Delayed order fulfilment
- Reduced operational efficiency
- Resource wastage

## 🎯 Project Objectives

- Identify root causes of downtime
- Analyse production performance across products and operators
- Evaluate scheduling efficiency
- Improve operational visibility through dashboards
- Provide actionable recommendations to reduce downtime

## 🛠️ Tools & Technologies

- **SQL** → Data extraction, transformation, and analysis
- **Power BI** → Data modelling, visualisation, and dashboarding

## 📊 Key Metrics

- **Total Batches:** 645
- **Delayed Batches:** 363 (~56%)
- **Downtime Incidents:** 885
- **Total Time Lost:** ~22 days
- **Downtime Factors Identified:** 13

## 🔍 Key Insights

### 1️⃣ Downtime is primarily process-driven

- ~69% of downtime was caused by non-operator factors

**Major contributors:**
- Cleaning / sanitation
- Scheduling / coordination
- Raw material shortages

👉 Indicates inefficiencies in **process design and planning**, not just workforce performance.

### 2️⃣ Cleaning & scheduling are major bottlenecks

Cleaning processes and scheduling inefficiencies were the top contributors to downtime.

👉 Suggests:
- Poor production sequencing
- Excessive changeovers
- Weak coordination between teams

### 3️⃣ Product-level inefficiency

**GreenFoam Hand Soap** recorded the highest downtime frequency and delay duration.

👉 Indicates:
- Higher production complexity
- Or process-specific inefficiencies

### 4️⃣ Unrealistic production planning

Actual production times consistently exceeded planned times across all products.

👉 Indicates:
- Ineffective scheduling assumptions
- Delays embedded into the system

### 5️⃣ Operator performance requires context

- High downtime volume ≠ poor performance

**Variations likely influenced by:**
- Workload
- Product complexity
- Scheduling conditions

### 6️⃣ Downtime is persistent

Downtime remained consistently high across multiple months.

👉 Indicates a **systemic issue**, not a temporary disruption.

## 💡 Recommendations

### 🔴 Immediate Actions

- Optimise cleaning and sanitation processes
- Redesign production scheduling to minimise overlaps and changeovers
- Implement pre-production material readiness checks

### 🟠 Medium-Term Improvements

- Introduce preventive maintenance for high-risk equipment
- Use data to balance operator workload and improve allocation

### 🟢 Long-Term Strategy

- Implement automated scheduling systems
- Develop real-time inventory tracking and alerts
- Build dashboards for proactive downtime monitoring

## 🔮 Future Work

- Develop predictive models to identify high-risk production runs
- Automate anomaly detection for downtime events
- Integrate production, inventory, and scheduling systems for real-time optimisation

## 🧠 Key Takeaway

> Downtime is not just an operational issue — it is a **data visibility problem**.

By improving visibility into production processes and decision-making, organisations can move from reactive problem-solving to proactive optimisation.

## 📸 Dashboard Preview

![Production Factors Overview](./screenshots/production_overview.png)<img width="1458" height="730" alt="Dashboard1" src="https://github.com/user-attachments/assets/3f1138ec-c690-4874-989a-bb4dddf5b049" />


## 📁 Project Structure

```text
/data
/sql
/powerbi
/screenshots
README.md
