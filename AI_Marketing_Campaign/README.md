# NOVA Skin — Digital Marketing Campaign Analytics

### Data-driven campaign analysis for a modern skincare brand

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Analytics-150458?style=flat-square&logo=pandas&logoColor=white)
![Marketing Analytics](https://img.shields.io/badge/Marketing-Analytics-6C63FF?style=flat-square)
![GitHub](https://img.shields.io/badge/Portfolio-Project-181717?style=flat-square&logo=github)

---

## Overview

**NOVA Skin Campaign Analytics** is a digital marketing analytics case study built around a simulated skincare campaign.

The project combines **marketing strategy, campaign performance analysis, audience segmentation, content analysis, and ROI measurement** to understand how different campaign activities contribute to business outcomes.

Rather than looking at clicks and impressions alone, the analysis connects campaign activity with:

**Engagement → Conversions → Revenue → Marketing Efficiency**

---

## Campaign Dashboard

<p align="center">
  <img src="dashboard/campaign_dashboard.png" alt="NOVA Skin Marketing Campaign Dashboard" width="100%">
</p>

---

## Business Challenge

A skincare brand is running campaigns across multiple digital channels and needs to understand:

- Which channels are driving revenue?
- Where is advertising spend producing stronger returns?
- Which customer segments are responding to campaigns?
- Which content formats are generating conversions?
- Which campaigns deserve deeper testing and optimization?

The goal is to turn campaign-level data into **clear marketing decisions**.

---

## What I Analyzed

### 01 — Channel Performance

Compared:

- Instagram
- Google Ads
- Email

Metrics analyzed:

**Revenue | Spend | CTR | Conversion Rate | ROAS**

---

### 02 — Audience Performance

Analyzed campaign response across:

- Gen Z
- Young Professionals
- Skincare Seekers
- Existing Customers

This helps evaluate how campaign efficiency changes across customer segments.

---

### 03 — Content Performance

Compared multiple content formats:

- Product Email
- Newsletter
- Search Ad
- Reel
- Carousel
- Story
- Display Ad

The analysis focuses on **conversion performance**, rather than engagement alone.

---

### 04 — Campaign-Level Performance

Individual campaigns were evaluated using:

- Spend
- Revenue
- Conversions
- Conversion Rate
- ROAS

This creates a campaign-level view of marketing efficiency.

---

# Key Performance Snapshot

| Metric | Result |
|---|---:|
| **Total Impressions** | 302,000 |
| **Total Clicks** | 23,306 |
| **Total Conversions** | 1,186 |
| **Total Revenue** | ₹355,800 |
| **Total Spend** | ₹74,600 |
| **Overall ROAS** | 4.77x |

---

# Selected Insights

### Channel Efficiency

The simulated campaign data shows different efficiency patterns across channels.

| Channel | Revenue | ROAS |
|---|---:|---:|
| Instagram | ₹135,900 | 4.30x |
| Google Ads | ₹113,400 | 3.09x |
| Email | ₹106,500 | 16.90x |

Revenue contribution and ROAS are analyzed separately to avoid treating revenue volume as the only measure of campaign efficiency.

---

### Audience Response

The audience analysis shows substantial differences in ROAS across segments.

| Audience | ROAS |
|---|---:|
| Existing Customers | 17.72x |
| Skincare Seekers | 4.01x |
| Young Professionals | 3.65x |
| Gen Z | 3.55x |

This provides a basis for developing different acquisition and retention strategies.

---

### Content Performance

Conversion rates varied across content formats.

| Content Format | Conversion Rate |
|---|---:|
| Product Email | 6.44% |
| Newsletter | 5.72% |
| Search Ad | 5.06% |
| Reel | 4.79% |
| Carousel | 4.72% |
| Story | 4.49% |
| Display Ad | 3.46% |

These results can be used as a starting point for further A/B testing.

---

# Marketing Recommendations

Based on the simulated campaign data, the next optimization cycle could focus on:

### Retention
Develop personalized campaigns for existing customers and test repeat-purchase messaging.

### Content
Experiment with different email subjects, offers, calls-to-action, and creative formats.

### Acquisition
Continue testing paid and social campaigns across different audience segments rather than using a single message for all audiences.

### Budget Optimization
Evaluate future budget allocation using a combination of:

**Revenue + Conversion Rate + ROAS + Audience Response**

### Experimentation
Validate the observed patterns through controlled A/B tests before making long-term budget decisions.

---

# Analysis Workflow

```text
Campaign Data
      │
      ▼
Data Quality Checks
      │
      ▼
KPI Calculation
      │
      ├── CTR
      ├── Conversion Rate
      └── ROAS
      │
      ▼
Performance Analysis
      │
      ├── Channel
      ├── Audience
      ├── Content
      └── Campaign
      │
      ▼
Visualization
      │
      ▼
Marketing Insights
      │
      ▼
Campaign Recommendations
