# Healthcare Provider Dashboard

A comprehensive Power BI dashboard for healthcare providers to monitor financial metrics, procedure costs, regional distribution, and departmental performance.

---

## Overview

This Power BI dashboard provides healthcare administrators and financial analysts with a 360-degree view of billing metrics, cost distributions, and operational insights. The dashboard enables data-driven decision making by visualizing key financial indicators across departments, procedures, geographic regions, and service types.

---

## Features

- **Financial KPI Monitoring**: Track top-level metrics including total billing, medication costs, treatment costs, insurance coverage, out-of-pocket expenses, and room charges.
- **Geographic Analysis**: Visualize billing distribution across cities and states/regions with interactive map functionality.
- **Procedure Cost Analysis**: Break down billing amounts by medical procedures including imaging and diagnostic tests.
- **Department Performance**: Monitor billing metrics across specialties including Cardiology, Orthopedics, General Surgery, and more.
- **Service Type Distribution**: Analyze patient service patterns across Emergency, Inpatient, and Outpatient categories.
- **Diagnosis Tracking**: Evaluate billing patterns for common diagnoses including Appendicitis, Asthma, Fracture, and Migraine.

---

## Dashboard Components

### Key Performance Indicators

- **Total Billing:** €3M with average per visit of €521.04
- **Medication Costs:** €546K with average of €100.21
- **Treatment Costs:** €3M with average of €526.09
- **Insurance Coverage:** €2M with average of €365.04
- **Out-of-Pocket Expenses:** €1M with average of €223.76
- **Room Charges:** €180K with average of €35.12

### Visualizations

#### Geographic Distribution

Interactive map showing billing distribution across UK regions including England, Scotland, and Northern Ireland.

#### Procedure Billing Breakdown

Bar chart displaying billing amounts by procedure type:
- **X-Ray:** €1,053,529 (31%)
- **CT Scan:** €805,508 (24%)
- **MRI Scan:** €600,739 (18%)
- **Ultrasound:** €481,347 (14%)
- **Blood Test:** €414,952 (12%)

#### Department Performance

Horizontal bar chart showing billing distribution across medical departments:
- **Cardiology:** €846,925 (25.2%)
- **Orthopedics:** €813,553 (24.2%)
- **General Surgery:** €783,247 (23.3%)
- **Neurology:** €478,200 (14.2%)
- **Pediatrics:** €434,450 (12.9%)

#### Diagnosis & Service Type

Stacked bar chart showing distribution of service types (Emergency, Inpatient, Outpatient) across common diagnoses.

---

## Getting Started

### Prerequisites

- Power BI Desktop (latest version recommended)
- Access to healthcare financial and operational data sources

### Installation

1. **Clone this repository:**
    ```bash
    git clone https://github.com/4256aniket/Healthcare-Provider-Dashboard.git
    ```
2. **Open the .pbix file in Power BI Desktop**
3. **Configure data connections** to match your organization's data sources
4. **Refresh data** to populate visualizations

---

## Data Requirements

This dashboard is designed to work with healthcare financial datasets containing the following elements:

- Billing records with procedure information
- Geographic data (patient/provider locations)
- Department and specialty classifications
- Service type categorization (Emergency/Inpatient/Outpatient)
- Diagnosis codes or descriptions
