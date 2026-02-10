# Tech Advertising Campaigns EDA 📊

A comprehensive **Exploratory Data Analysis (EDA)** on tech advertising campaigns using Python, Pandas, Plotly, and Seaborn to uncover insights about platform performance, creative effectiveness, audience targeting, and campaign profitability.

---

## 🌟 Features

### Core Features
- **Data Cleaning & Preprocessing:** Handling type conversions.
- **Campaign Insights:** Analyze platform concentration, impressions, clicks, conversions, ROAS, and CPA.
- **Creative & Engagement Analysis:** Explore CTR, conversion rate, and creative emotion effectiveness.
- **Audience Targeting & Intent:** Evaluate performance across age groups, purchase intent, and audience interests.
- **Funnel Performance:** Track impressions → clicks → conversions → profitability.
- **Visualization:** Interactive and static plots using Plotly and Seaborn (bar, box, scatter, heatmap, line).

---

## 🗂 Project Structure

The project folder is organized as follows:

```text
Tech_Advertising_Campaigns_EDA/
├── campaigns.csv                      # Dataset of tech advertising campaigns
├── Tech_Advertising_Campaigns_EDA.ipynb  # Jupyter Notebook with full EDA
├── requirements.txt                   # Python dependencies
└── venv/                              # Virtual environment

```

---

## 🏗️ EDA Architecture

```text
+----------------------+  
|      DATA LAYER      |  
|  Raw campaign dataset|  
|  (CSV / Excel)       |  
+----------+-----------+  
           ↓  
+-------------------------+  
|  ANALYSIS LAYER         |  
|  - Data Cleaning        |  
|  - Campaign Insights    |  
|  - Creative Analysis    |  
|  - Audience Analysis    |  
|  - Funnel Performance   |  
+----------+--------------+  
           ↓  
+---------------------------------------+  
| VISUALIZATION LAYER                   |  
|  - Interactive Dashboards (Plotly)    |  
|  - Static Plots (Seaborn & Matplotlib)|  
|  - Scatter, Bar, Boxplots, Heatmaps   |  
+---------------------------------------+  

```

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Data Source:** [Kaggle – YouTube Trending Videos](https://www.kaggle.com/datasets/juniornsa/digital-advertising-campaign-performance-dataset)

---

## 📊 Dataset Overview

- **Rows:** 10,000 campaigns
- **Columns include:** campaign_id, platform, campaign_objective, creative_format, creative_emotion, device_type, target_audience_age, target_audience_gender, budget_tier, impressions, clicks, conversions, ad_spend, revenue, profit, ROAS, CTR, CPA, conversion_rate, start_date, retargeting_flag
  
**Context:**  
This dataset allows analysis of campaign performance across platforms, creative strategies, audience targeting, and time. It is aimed at helping advertisers understand which campaigns perform best and why.

**Acknowledgements:**  
- Data sourced from YouTube via Kaggle.
- Thanks to Kaggle contributors for making this dataset accessible.

**Inspiration:**  
Analyzing trends in YouTube videos can help marketers, content creators, and researchers make data-driven decisions about content creation, marketing strategies, and audience engagement.

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/TejasMJ/Youtube_Trending_Videos_EDA.git
cd Google_Play_Store_EDA
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```
### 3. Activate Virtual Environment
#### Windows:
```bash
.\venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```
### 5. Run Notebook

```bash
jupyter notebook
```

# 📊 App Analysis Project

## Detailed Analysis Scope

### Platform & Market Insights
We examine trends across advertising platforms to understand channel dominance and reach. The number of campaigns, impressions, and average ROAS are analyzed by platform to highlight concentration patterns and profitability differences. ROAS is further evaluated across budget tiers to determine the optimal alignment between platform choice and budget allocation.

### Creative Strategy & Engagement
Campaign creative formats and messaging strategies are analyzed to assess engagement effectiveness. Click-through rates (CTR) are compared across creative formats and emotional tones, and interactions between creative emotion and platform are studied to determine message-platform alignment. Conversion rates are analyzed by creative format and device type to reveal device-aware creative performance.

### Audience Targeting & Intent
The analysis explores who is being targeted and who actually converts. Campaign distribution is reviewed by age group, conversion rate is studied relative to purchase intent score, and ROAS is evaluated across audience interest categories. This reveals which demographic groups and audience segments yield the highest engagement and profitability.

### Funnel Performance & Optimization
Campaign funnels are analyzed from impressions to clicks and conversions. Scatter plots and CPA metrics across budget tiers help identify patterns in campaign efficiency, while highlighting areas where exposure does not translate into conversions. This ensures actionable insights into funnel optimization.

### Budgeting, Profitability & Retargeting
Profitability is assessed across campaigns, campaign objectives, and retargeting strategies. Median and distributional analyses highlight skewed returns and reveal which strategies generate the highest ROI. Grouped analysis of retargeted campaigns demonstrates the additional value of retargeting for bottom-funnel objectives.

### Time & Performance Stability
Monthly ROAS trends are analyzed to identify seasonal patterns and platform-specific performance fluctuations. Monitoring performance over time allows advertisers to make informed budget adjustments, ensuring campaigns remain profitable and stable throughout different periods.


### Visualization
- Interactive dashboards using **Plotly**
- Static plots using **Seaborn** & **Matplotlib**

## 👨‍💻 Author
**Tejas Jadhav**  

- GitHub: [@tejas-jadhav](https://github.com/TejasMJ)  
- LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-m-jadhav/)
