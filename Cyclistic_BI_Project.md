# **Cyclistic Business Intelligence Project 🚴‍♂️📊**

## **📌 Stakeholder Requirements Document**

**BI Professional:** U Dekontee Kun  
**Client/Sponsor:** Jamal Harris, Director, Customer Data

### **Business Problem**

Cyclistic wants to optimize its bike-share operations and grow its customer base. The business problem is to understand customer behavior, station demand, and peak usage patterns to make data-driven decisions on station placement, marketing strategies, and operational improvements.

**Primary Question:** How can customer usage insights be applied to inform station expansion and marketing strategies?

### **Stakeholders**

* **Sara Romero**, VP, Marketing  
* **Ernest Cox**, VP, Product Development  
* **Jamal Harris**, Director, Customer Data  
* **Nina Locklear**, Director, Procurement

### **Stakeholder Usage Details**

* **Marketing Team:** Uses insights to target promotions and encourage casual users to become subscribers.  
* **Product Development:** Leverages station usage and peak-hour data to improve bike availability and maintenance schedules.  
* **Customer Data Team:** Analyzes usage trends to enhance user experience and operational efficiency.  
* **Procurement Team:** Uses demand analysis to determine optimal station placements and bike distribution.

### **Primary Requirements**

* A **map visualization** showing the most used starting and ending stations.  
* A **trend analysis** of bike usage during peak and off-peak hours.  
* A **year-over-year comparison** of bike trip growth.  
* A **gender-based breakdown** of bike trips to identify key demographics.  
* Insights into **weather impact on bike demand**.  
* A **heatmap of congestion at stations** to optimize bike distribution.


## **📌 Project Requirements Document**

**BI Analyst:** U Dekontee Kun  
**Client/Sponsor:** Jamal Harris, Director, Customer Data

### **Purpose**

The project aims to enhance Cyclistic’s decision-making by providing a business intelligence (BI) tool that analyzes customer demand, trip behavior, and operational efficiencies. This tool will help stakeholders plan station expansions, optimize marketing campaigns, and improve service availability.

### **Key Dependencies**

* **Data Source:** NYC\_BIKE\_2013 dataset and Cyclistic Zip Code dataset.  
* **Primary Contacts:** Adhira Patel (Data Compliance), Megan Pirato (Marketing), Rick Andersson (Operations), Tessa Blackwell (Procurement).  
* **Deliverables:** BI dashboard with interactive visualizations for trip analysis, station demand, and demographic insights.

### **Stakeholder Requirements**

| Requirement Description | Priority |
| ----- | ----- |
| A map of starting and ending stations | R |
| A visualization of popular destinations based on trip duration | R |
| Year-over-year trip growth analysis | R |
| A heatmap of station congestion | N |
| Insights into time-of-day and seasonal variations | R |
| A breakdown of user types (subscribers vs. casual riders) | R |

### **Success Criteria**

✅ **Specific:** BI insights must identify specific characteristics of a successful product by analyzing **customer behavior, trip patterns, and demand trends across different station locations**. The analysis must show how **bike usage varies across different neighborhoods** and which factors influence demand.

✅ **Measurable:** Key performance indicators (KPIs) will evaluate **trip start and end locations, trip duration, usage variations by time of day, seasonality, and weather impact.** The analysis will differentiate between **subscribers and casual users** to determine their distinct behaviors.

✅ **Actionable:** Data insights must **prove or disprove** the impact of **location, time, season, and weather on bike-share demand.** This will help the Cyclistic team **refine station expansion plans, optimize bike rebalancing, and create targeted marketing strategies** to improve conversion rates from casual users to subscribers.

✅ **Relevant:** All collected metrics and insights must directly support **Cyclistic’s strategic goal of increasing ridership and improving station availability to enhance the overall user experience.**

✅ **Time-bound:** The analysis will cover **at least one year** to ensure that **seasonal trends and fluctuations are captured.** The data must include multiple months to highlight **peaks and valleys in demand**, ensuring that insights are relevant year-round.

### **User Journeys**

* **Current Experience:** Customers use Cyclistic bikes without insight into availability or demand fluctuations.  
* **Ideal Experience:** Improved bike availability through data-driven station expansion and optimized rebalancing of bikes.

### **Assumptions**

* The dataset includes GPS coordinates but does not identify neighborhoods; zip code data will supplement this information.  
* Weather impact on trip behavior assumes any precipitation affects demand, though the timing may vary.

### **Compliance and Privacy**

* No personally identifiable information (PII) is included in the dataset.  
* All user data will be anonymized to prevent bias and privacy violations.

### **Accessibility**

* Reports should include text alternatives for visualizations and support screen-reader compatibility.

### **Roll-out Plan**

| Phase | Timeline | Deliverables |
| :---- | :---- | :---- |
| **Week 1** | Data preparation | Validate fields and structure for analysis. |
| **Weeks 2-3** | SQL & ETL development | Data transformation and validation. |
| **Weeks 3-4** | Dashboard design | Initial draft and stakeholder review. |
| **Weeks 5-6** | Final development | Testing and deployment. |

---

## **📌 Strategy Document**

### **Sign-off Matrix**

| Name | Team / Role | Date |
| :---- | :---- | :---- |

### **Proposer: U Dekontee Kun**

### **Status: \[Draft\] \> Under review \> Implemented | Not implemented (Highlight current status)**

### **Primary Dataset: NYC\_BIKE\_2013**

### **Secondary Dataset: Cyclistic Zip Code Data**

### **User Profiles**

* **Marketing Team:** Uses insights to design customer engagement strategies.  
* **Operations Team:** Monitors congestion and bike availability for efficiency.  
* **Leadership Team:** Evaluates year-over-year growth for business planning.

### **Dashboard Functionality**

| Dashboard Feature | Your Request |
| :---- | :---- |
| Interactive Station Map | Display top start/end stations |
| Peak Usage Graph | Show hourly trip distribution |
| Subscriber vs. Casual User Trends | Breakdown of customer types |
| Weather Impact Analysis | Compare trip volume on rainy vs. clear days |

### **Metrics and Charts**

| Chart Feature | Your Request |
| :---- | :---- |
| **Top Stations** | Bar chart of busiest stations |
| **Peak Usage Hours** | Line graph of hourly trends |
| **Subscriber vs. Casual Users** | Pie chart of user breakdown |
| **Weather Impact** | Comparative bar chart of trip counts by weather conditions |

✅ **This document now fully aligns with Cyclistic’s BI project goals and deliverables.**

