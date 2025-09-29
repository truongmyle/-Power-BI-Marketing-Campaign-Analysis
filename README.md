# [Power BI] Marketing-Campaign-Analysis
Performance analysis of multi-channel marketing campaigns to optimize budget allocation and improve communication strategy.
## I. Introduction

- The Marketing Campaign dataset contains performance data from multi-channel advertising activities across different regions.
    
    The dataset includes **four main tables**:
    
    - Table 1: **fact_marketing –** Campaign performance data
    - Table 2: **dim_campaign –** Information about each campaign
    - Table 3: **dim_city –** Geographical information
    - Table 4: **dim_date –** Date dimension
- The company is seeking to::
    - **Optimize marketing budget allocation** across regions and platforms.
    - **Identify underperforming campaigns** to refine targeting strategies.
- **Data dictionary:**
  
  <img width="1147" height="627" alt="image" src="https://github.com/user-attachments/assets/752f25f2-0f2a-4111-88ac-51f2691c57cd" />

- **Business Question:**
    - What is the overall performance of marketing campaigns across all channels and regions?
    - How does campaign effectiveness vary by channel and by city?
    - Which efficiency metrics best reflect marketing ROI?
    - How can insights from campaign data support budget optimization?

## II. Design Thinking Method

### Step 1: Empathize
<img width="1852" height="571" alt="image" src="https://github.com/user-attachments/assets/4d9724d7-2897-4ed9-8292-3fef10e68a53" />

### Step 2: Define POV
<img width="1483" height="626" alt="image" src="https://github.com/user-attachments/assets/23bbd2be-d0fe-4008-a12c-615b9f6573b2" />

### Step 3: Ideate
<img width="1838" height="588" alt="image" src="https://github.com/user-attachments/assets/77601213-238a-4031-8ab3-086b03414642" />

### Step 4: Prototype and Review
- This section is shown in Dashboard


## III. Visualization
### 1. Marketing campaign Overview 
<img width="1216" height="713" alt="image" src="https://github.com/user-attachments/assets/86042612-7b66-48c1-8e35-04281528d670" />

### 2. Channal Analysis
<img width="1217" height="709" alt="image" src="https://github.com/user-attachments/assets/8fa75df7-3e8e-449e-af9c-4cd50c1aea66" />

### 3. City Analysis (Drill-through)
<img width="1214" height="711" alt="image" src="https://github.com/user-attachments/assets/e3f64d0e-83fe-455f-98e9-b8fadca808ee" />

## IV. Insights & Recommendation
### 1. Insights
- **By Time (Monthly Trends)**
    - ROI spiked between June–August (~13) but dropped sharply in September (~7.7).
    - Despite higher impressions in September, engagement rate decreased → reach quality declined.
- **By Channel**
    - **Pinterest**: Highest ROI and conversion rate → clear driver of efficiency.
    - **Instagram**: Balanced performance, moderate ROI.
    - **Facebook**: Significant investment but low ROI → weak conversion effectiveness.
- **By City**
    - **Birmingham**: Strong ROI, especially from Pinterest campaigns.
    - **Manchester**: Underperforming ROI despite decent impressions.
    - **London**: High spend but weak ROI → potential inefficiency.
### 2. Recommendations
- **Budget Optimization**
    - Shift budget from **Facebook (low ROI)** to **Pinterest (high ROI & CR)**.
    - Keep limited Facebook budget for awareness only → avoid waste.
    - Test new audience targeting and creatives on Instagram for potential uplift.
- **Communication Strategy**
    - **Pinterest**: Scale further as main conversion channel.
    - **Facebook**: Use as **top-of-funnel (awareness)**, integrate with retargeting on Pinterest/Instagram.
    - **Instagram**: Use for both awareness and conversion experiments.
- **City-level Actions**
    - **Birmingham**: Expand Pinterest campaigns to maximize strong ROI.
    - **Manchester**: Refresh creatives/targeting to improve performance.
    - **London**: Audit conversion funnel → if ROI remains low, reduce budget allocation.
