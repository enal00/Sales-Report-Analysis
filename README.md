<img width="800" height="450" alt="ezgif-5b0eb6e89aff5ae8" src="https://github.com/user-attachments/assets/05e19213-c691-4bea-98d1-0fd00851ca92" />

**🔑 Key Learning Points**
1. Applied best‑practice dashboard design principles in Power BI to ensure clarity and executive usability.
2. Structured the dataset with a star schema for scalable and efficient modeling.
3. Established a dedicated measure table with DAX KPIs, enabling consistent calculations across visuals.
4. Implemented time intelligence functions for robust month‑over‑month and year‑over‑year analysis.
5. Leveraged advanced visuals (KPI cards, reference labels, gauge charts, histograms, zoom slider) to highlight performance drivers.
6. Built dynamic trend charts using field parameters for flexible scenario analysis.
7. Applied conditional formatting to tables for immediate performance insights.
8. Designed interactive navigation with bookmarks and slicer panels.
9. Integrated geo‑level tooltips for country breakdowns, enhancing contextual analysis.

**📊 Project Flow**
1. Ingested and modeled the Awesome Chocolates dataset.
2. Defined measures within a star schema to support analytical consistency.
3. Designed wireframes and structured dashboard layout aligned with business objectives.
4. Developed KPI cards, shipment analysis, and product performance visuals.
5. Enhanced interactivity through bookmarks, slicers, and contextual tooltips.
6. Published the dashboard as a portfolio‑ready project.

**🎯 Outcome**

The result is a professional‑grade sales analytics dashboard that demonstrates both technical depth and business acumen. It provides actionable insights across sales, shipment, and profitability dimensions.




# Sales & Shipment Analysis – Executive Summary

## 📊 Boxes–Profit Relationship
<img width="503" height="363" alt="image" src="https://github.com/user-attachments/assets/9a5acb83-9a53-4369-aecf-4187cd988768" />
<img width="359" height="396" alt="image" src="https://github.com/user-attachments/assets/b73729ec-4c70-4a03-92b2-15c0fbafbadf" />

- **Direct correlation**: Higher box volumes often align with higher profit.  
- **Volume trap detected**: UK shows high box shipments but low profit per box ($8.6).  
- **Inverse cases**: Australia demonstrates low shipment but high profit per box ($10.92).  
- **Actionable Insight**:  
  - Optimize logistics in regions with high shipment but low margins.  
  - Maintain premium positioning in geographies with low shipment but high profit.  

### Key Geo Highlights
<img width="465" height="315" alt="image" src="https://github.com/user-attachments/assets/0ddee18e-7e35-4a16-a6e6-e178abcb434a" />
<img width="408" height="331" alt="image" src="https://github.com/user-attachments/assets/106b1c57-ff31-473b-8dc1-589645941723" />
<img width="454" height="360" alt="image" src="https://github.com/user-attachments/assets/0230bea6-bc24-4083-a450-94d54fbe8d1a" />

- **Australia**: Highest profit %, despite requiring campaigns and sample shipments (11%).  
  - Fewest boxes shipped, yet strong profit conversion.  
  - Recommendation: Shift campaign focus from India to Australia.  
- **UK**: High box volume but weak profit.  
  - LBS is low, sales need reinforcement.  
  - Recommendation: Increase marketing via LBS to lift margins.  
- **India**: Excessive LBS (sampling) with poor conversion.  
  - Recommendation: Reassess campaign strategy.  

---

## 📦 Low Box Shipment (LBS) Analysis
- **Definition**: Shipments < 50 boxes → sampling or test campaigns.  
- **High LBS + Low Profit Zones**: India and UK.  
- **Actionable Insight**:  
  - Consolidate shipments to reduce inflated costs.  
  - Introduce minimum order thresholds.  
  - Convert sample-heavy regions into upsell opportunities (bundling, promotions).  

---

## 📈 Profit Trend Analysis
- **Normal trend**: More boxes → more profit (e.g., New Zealand).  
- **Exceptions**: Australia and UK deviate from expected correlation.  
- **Seasonality**:  
  - Lowest profit → Jan–Feb (post-holiday slump).  
  - Highest profit → Jun–Jul and Nov–Dec (promotions & festive season).  
- **Actionable Insight**:  
  - Smooth seasonality with loyalty programs.  
  - Introduce staggered promotions in low-demand months.  

---
## 👥 Sales Team Performance
### Team-Level Insights
<img width="975" height="728" alt="image" src="https://github.com/user-attachments/assets/8a4656bf-4ec5-40b7-ae2d-b4ceec710ea5" />
<img width="975" height="483" alt="image" src="https://github.com/user-attachments/assets/097452d4-9b1a-42eb-8231-31048ed2ab31" />
<img width="865" height="779" alt="image" src="https://github.com/user-attachments/assets/13682986-fd4a-4584-9b01-254fdbcfd415" />
<img width="940" height="688" alt="image" src="https://github.com/user-attachments/assets/b0819476-d0ce-4c0d-ae08-4cc711f03a5e" />
<img width="975" height="562" alt="image" src="https://github.com/user-attachments/assets/ec86eb5d-0069-4af0-ba4f-887fd4f7d0f4" />

- **Best-performing team**: Jucies (≈6.6x revenue vs Tempo).  
- **Underperforming team**: Tempo, consistently low volume across all geographies.  
- **Capability gap**: Jucies has stronger salespeople, but productivity variance among members is modest (1.25x).  
- **Marney O’Breen (UK)**: LBS has exceeded the 10% threshold, reaching 16.7%. However, profit remains below the 60% target, currently at 32.1%, particularly within the *Bites* category. This indicates strong sampling activity but insufficient conversion to profit, requiring targeted sales and marketing intervention.
  

### Product-Level Insights
<img width="405" height="247" alt="image" src="https://github.com/user-attachments/assets/16c54842-5b1f-4221-aeed-411cdfd9ebd1" />
<img width="975" height="197" alt="image" src="https://github.com/user-attachments/assets/58a138b2-258e-41fd-8918-1b7efdf9c6ba" />
<img width="975" height="203" alt="image" src="https://github.com/user-attachments/assets/72bbb8d7-cfa8-4f03-b0ad-b42b51dd2aa0" />


- **Bars**: Drive sales volume.  
- **Bites**: Drive profit.  
- **Strategic Shift**: Prioritize Bars and Bites in inventory and marketing.  
- **High-value product**: Peanut Butter Cubes (USA, Tempo team).  
- **Phase-out candidate**: Baker’s Choco Chips (UK, Jucies team).  

### Executive Actions
- **For Jucies**: Document best practices, replicate across teams.  
- **For Tempo**: Conduct root cause analysis, coaching, and territory review.  
- **Salespeople**: Retain top performers, create mentoring programs.  

---

## 🌍 Regional & Product Portfolio
- **Fastest growth**: Australia (May 2023, +63.32% MoM).  
- **Optimal ROI market**: New Zealand (balanced profit and box volume).  
- **Strategic allocation**:  
  - Increase box volume in Australia & New Zealand.  
  - Reposition Peanut Butter Cubes from USA to APAC.  
  - Maintain marketing in New Zealand for sustained ROI.  

---

## 🎯 Strategic Recommendations
1. **Optimize shipment strategy**: Reduce LBS inefficiencies via consolidation.  
2. **Focus on premium categories**: Leverage high-margin products in profitable regions.  
3. **Seasonality management**: Loyalty programs and staggered promotions.  
4. **Sales team development**: Coaching and mentoring to uplift underperformers.  
5. **Cost control**: Enforce minimum shipment thresholds to reduce per-unit logistics costs.  

---

## 📌 Executive Takeaway
This analysis highlights **where profit is generated vs. where volume is concentrated**, exposing inefficiencies and opportunities.  
- **Australia & New Zealand** → Growth engines.  
- **UK & India** → Require strategic intervention.  
- **Bars & Bites** → Core product focus.  
- **Sales team gap** → Address Tempo’s underperformance, replicate Jucies’ strengths.  

## 📊 Forecasting – Revenue Trend Analysis
<img width="975" height="602" alt="image" src="https://github.com/user-attachments/assets/0f5fee10-3cff-46a2-b626-6206dd061ccc" />
<img width="935" height="216" alt="image" src="https://github.com/user-attachments/assets/b0e1dad2-3769-4fbe-8c47-97f7a87026e1" />

- **What will revenue look like next quarter?**  
  Projected decline of **–6.27%** compared to the current quarter.

- **What risks threaten future growth?**  
  - **Seasonality effects**: Post holiday demand slump and uneven promotional cycles.  
  - **High LBS inefficiencies**: Excessive sample shipments in regions like India and UK erode margins.  
  - **Volume traps**: UK shows high shipment but low profit per box, indicating structural inefficiency.  
  - **Product portfolio imbalance**: Over reliance on Bars for volume while Bites drive profit; risk of stockouts in high margin products (e.g., Peanut Butter Cubes).  
  - **Sales team performance gap**: Tempo team underperformance reduces overall competitiveness.  
  - **Geographic dependency**: Heavy reliance on APAC growth (Australia, New Zealand); exposure if campaigns fail or demand shifts.  
  - **Cost pressures**: Rising logistics costs for small shipments and potential inflationary impacts.  

### 🎯 Executive Action
- Smoothen seasonality with loyalty programs and staggered promotions.  
- Consolidate shipments to reduce LBS inefficiencies.  
- Rebalance product portfolio by prioritizing high margin items and avoiding stockouts.  
- Strengthen underperforming sales teams through coaching and mentoring.  
- Diversify geographic focus to reduce dependency on single region growth.
The dashboard and insights provide a **clear roadmap for resource allocation, marketing strategy, and team development** to maximize ROI.
