# Customer Financial Performance & Strategic Segmentation Model
A financial intelligence solution that analyzes customer profitability, cost-to-serve, and risk exposure — helping leadership identify high-value customers, cost inefficiencies, and strategic opportunities.

## 📌 Business Problem
- Most companies focus only on revenue. Reality is harsher:
- Some customers generate massive profits
- Some consume heavy service resources
- Some look “big” but silently destroy margins
- Some are profitable but risky

Leadership needs clear visibility on:
- Which customers truly create financial value?
- Which customers dilute profitability?
- Where is economic risk concentrated?
- How should strategy, pricing, and focus change?

This project answers exactly that.

## 🎯 What This Solution Does

This financial intelligence framework:

- Builds a complete customer-level financial model
- Computes Net Revenue, Cost-to-Serve, Contribution & Profitability
- Segments customers into strategic value groups:
1. Strategic Gold 
2. Hidden Gems   
3. Margin Diluters  
4. Value Destroyers

 
- Evaluates customer financial risk
- Quantifies economic loss from unprofitable segments
- Enables data-driven FP&A and BI decision making

## 📂 Dataset

- Synthetic but business-realistic dataset created with:
- 250+ customers
- Industry, region, user base
- Cost drivers (service hours, infra usage, tickets, platform load)
- Financial assumptions (discounts, retention probability, transactions)

The objective: Simulate enterprise financial reality as closely as possible.


## 📐 Financial & Segmentation Logic
- Profitability Logic: Net Revenue = Subscription Revenue − Discounts
- Direct Cost-To-Serve computed using: I. Support Costs  II. Service Costs  III. Infra Cost and IV. Transaction Cost
- Customer Profit = Net Revenue − (Direct Cost + Overhead Allocation)
- Profit Margin% derived from profit proportion

Revenue vs Profitability Segmentation: 
1. High Revenue & High Profit - Strategic Gold
2. High Revenue & Low Profit - Margin Diluters
3. Low Revenue & High Profit - Hidden Gems 
4. Low Revenue & Low Profit - Value Destoyers


Cost-To-Serve Classification
1. Low Cost → < 40%
2. Medium Cost → 40% to 70%
3. High Cost → > 70%


Risk Model
- Weighted Risk Score = 0.4 × Late Payment Score + 0.3 × Discount Dependency + 0.3 × Retention Risk
Where:
Late Payment Score is normalized;
Discount Score = Discount %;
Retention Risk = (1 − Retention Probability)

Risk Classes:
- Low Risk: < 0.35
- Medium Risk: 0.35 – 0.65
- High Risk: > 0.65 (High Risk class was found to be nil; demonstrated in the model)

# 📊 Dashboard Highlights

## ⭐ Executive KPI Layer
- Total Net Revenue
- Total Profit
- % Profitable Customers
- Average Profit Margin %
- Economic Loss from Value Destroyers

## 📈 Strategic Visuals
- Profitability vs Revenue Quadrant: Identifies value creators vs destroyers
- Cost-To-Serve vs Profitability: Reveals operational efficiency impact
- Risk Distribution: Shows customer stability
- Profit Contribution by Risk Class: Links profit to risk exposure
- Interactive Segmentation Table: Deep dive customer analytics explorer

## 📌 Key Business Insights

- 90% customers profitable
- Majority revenue contribution comes from low-risk customers
- Value Destroyers generate economic losses — strong case for repricing or exit strategy
- Hidden Gems indicate untapped expansion potential

## 🛠️ Tools & Skills
- Power BI
- Excel Financial Modeling
- Data Modeling
- Analytics Storytelling
- FP&A Thinking
- Segmentation Strategy


## 🚀 Why This Project Matters
This project demonstrates ability to:
- Think like FP&A leadership
- Build decision-driving analytics
- Convert raw data → financial strategy
- Blend finance, analytics, and business intelligence meaningfully

## 📷 Dashboard Preview

<img width="968" height="766" alt="Screenshot 2025-12-31 225038" src="https://github.com/user-attachments/assets/7854935b-2c10-488d-8157-17caacee34d0" />
<img width="1325" height="681" alt="Screenshot 2025-12-31 225117" src="https://github.com/user-attachments/assets/6408ff66-f744-44dd-bb68-183a882819a5" />


## 🤝 Let’s Connect
Open to discussions, opportunities, and conversations in:
1. FP&A
2. Business Intelligence
3. Financial Analytics
4. Strategy Analytics
