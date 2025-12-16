# UK Bank Customer Analysis Dashboard (Tableau)

An interactive Tableau story analyzing customer demographics and financial behaviors across UK regions (England, Scotland, and Northern Ireland). This project answers 7 key business questions to help the bank understand customer segments and optimize regional strategies.

---

## 📋 Problem Statement

Analyze UK bank customer data to answer critical business questions:

1. **Top 10 customers** maintaining high balances
2. **Gender ratio** across regions
3. **Number of customers** in age range 30-35 and 40-45
4. **Number of customers** in each region
5. **Number of customers** in each job classification
6. **Pattern and trend** of new customer joining
7. **Customers maintaining balance** in range 10,000-20,000

---

## 🔗 Live Dashboard

**View Interactive Dashboard:** [Tableau Public](https://public.tableau.com/app/profile/satyam.singh7169/viz/UK_Bank_Customer_Analysis_16732999017210/Story1)

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/UK_bank_Customer_Analytics_Tableau/blob/main/imgs/img1.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/UK_bank_Customer_Analytics_Tableau/blob/main/imgs/img2.png" /></a></p>  

<p  align="center"><img width="80%" src="https://github.com/SatyamSingh1299/UK_bank_Customer_Analytics_Tableau/blob/main/imgs/img3.png" /></a></p>
---

## 📊 Dashboard Components

### 1. **Region and Customer Map** (Interactive)
- Geographic visualization of UK regions (England, Scotland, Northern Ireland)
- Color-coded by customer count
- Click regions to filter entire dashboard

### 2. **Gender Ratio** (Icon Chart)
- Male vs. Female distribution
- Visual representation using gender icons
- Updates dynamically by region selection

### 3. **Job Classification Customer-Wise** (Treemap)
- White Collar, Blue Collar, and Other categories
- Proportional sizing by customer count
- Color-coded for easy identification

**Regional Insights:**
- **England:** 69.5% White Collar (dominant), 15.9% Blue Collar, 14.5% Other
- **Scotland:** 48.4% Blue Collar (dominant), 44.1% Other
- **Northern Ireland:** 49.8% Other (dominant), 30.8% White Collar, 19.4% Blue Collar

### 4. **Age Distribution with Range of 5** (Histogram)
- Adjustable age bin parameter (default: 5-year ranges)
- Bar chart showing customer count by age group
- Annotated with key insights

**Age Patterns by Region:**
- **England:** Most customers are middle-aged (30-35) - 567 customers
- **Scotland:** Most customers are elderly (50-55) - 294 customers  
- **Northern Ireland:** Customers are young (25-30) - 56 customers

### 5. **Balance Distribution** (Histogram)
- Customer count by balance ranges (bins)
- Shows concentration of account balances
- Identifies balance range 10,000-20,000

### 6. **Top Customers** (Bar Chart)
- Top 10 customers by account balance
- Horizontal bar chart with customer names
- Balance amounts labeled on bars

**Top Account Holders:**
1. Dorothy Jackson: $183.47K
2. Carl Fraser: $181.68K
3. Sebastian Afino: $161.52K

### 7. **New Customer Pattern** (Line Chart)
- Trend of new customer acquisitions by month (2015)
- Line graph showing joining patterns
- Annotated with observation: "New customers are increasing"

**Monthly Trend:**
- Peak in September/November (~324 new customers)
- Steady growth pattern throughout 2015

---

## 🔍 Key Insights

### Regional Differences:
- **England:** White-collar dominated, middle-aged customers (30-35)
- **Scotland:** Blue-collar dominated, elderly customers (50-55)
- **Northern Ireland:** Service/Other jobs, young customers (25-30), 74% female

### Customer Trends:
- New customer acquisitions increasing in 2015 (peak: September-November)
- Majority of accounts in mid-balance ranges
- Top 10 customers hold balances exceeding $60K-$183K

---

## 📁 Dataset

**Source:** UK bank customer data (2015)  
**Fields:** Customer Name, Region, Gender, Age, Job Classification, Account Balance, Date Joined  
**Grain:** One row per customer account



---





