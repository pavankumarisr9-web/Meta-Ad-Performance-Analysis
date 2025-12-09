Meta Ad Performance Analysis – Project Overview

This project delivers a comprehensive analysis of advertising performance across Facebook and Instagram, using an integrated Power BI dashboard. It evaluates user engagement, audience demographics, and campaign efficiency to support data-driven marketing decisions.

**Objective**

To build an interactive dashboard that helps marketers analyze:

- Ad reach and impressions

- Engagement behavior (likes, shares, comments)

- Click-through and conversion performance

- Budget utilization and ROI

- Audience demographics and geographic distribution

- Cross-platform comparison (Facebook vs. Instagram)

The dashboard enables quick insights and optimization of ad targeting and spending.

**Data Model & Sources**

The solution uses four key datasets:

**1. ad_events (Fact Table)**

Captures user interactions with ads, including:

- Views / Impressions

- Clicks

- Shares, Likes, Comments

- Timestamp, day of week, time of day

**2. ads (Dimension)**

Contains metadata such as:

- Ad ID

- Target gender & age group

- Platform (Facebook/Instagram)

**3. campaigns (Dimension)**

Includes campaign-level information:

- Campaign name

- Total budget

- Start & end dates

- Linked ad IDs

**4. users (Dimension)**

Provides demographic attributes:

- Gender

- Age group

- Country / Location

- Interests

**Data Model Structure**

A clean **star schema**, with ad_events as the central fact table:

users      ads         campaigns
   \        |           /
    \       | ad_id    /
     \      |         /
      ---- ad_events ----

**KPIs Featured in the Dashboard**

**Performance Metrics**

- Total Impressions

- Total Clicks

- Total Shares

- Total Comments

- Total Purchases

- Total Engagements

**Efficiency Metrics**

- CTR (Click-Through Rate)

- Engagement Rate

- Conversion Rate

- Purchase Rate

- Total Budget

- Average Budget per Campaign

These KPIs provide a fast, high-level understanding of ad performance.

**Visualizations & Their Purpose**

**1. KPI Tiles**

Show core metrics in a clean, color-coded layout for easy comparison.

**2. Donut Chart – Gender Performance**

Breaks down impressions by gender to reveal the most engaged audience segment.

**3. Country Performance (Treemap or Bar Chart Alternative to Map)**

Shows which countries contribute the highest reach or engagement.
Visual emphasizes size or intensity based on the selected metric.

**4. Dynamic Metric Selector**

Allows switching between KPIs such as:

- Impressions

- Clicks

- Purchases

- Engagement

This makes the dashboard adaptive and user-driven.

**5. Filters & Slicers**

Segment data by:

- Platform (Facebook / Instagram)

- Country

- Gender

- Campaign

Enhances drill-down capability for deeper insights.

**Insights Enabled by the Dashboard**

Identify which platform drives higher reach and engagement.

Assess demographic performance across gender and age groups.

Determine which countries contribute the strongest results.

Analyze time-of-day and day-of-week engagement patterns.

Evaluate campaign ROI by comparing budget vs outcomes.

Monitor user behavior trends and ad effectiveness.

**Business Value**

This solution empowers marketing teams to:

Optimize targeting strategies

Improve creative and audience alignment

Allocate budget more efficiently

Track campaign health in real time

Make informed decisions based on measurable performance

The dashboard serves as a central analytics tool for continuous improvement of Meta ad campaigns.
