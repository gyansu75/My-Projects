# 📊 Gaurav's Analytics Portfolio

# [Project 1: 🏨 Hotel Booking & Cancellation Analysis]()

This is my first project I did for my Analytics Protfolio, where I build a recommendation system for a Hotel Bookings and Cancelations dataset.

## 📌 Project Overview
In recent years,City Hotel and Resort Hotel have seen high cancellation rates. Each hotel is now dealing with a number of issues as a result,including fewer revenues and less than ideal hotel room use.Consequently, lowering cancellation rates is both hotels' primary goal in order to increase their efficiency in generating revenue, and for us to offer thorough business advice to address this problem.
The analysis of hotel booking cancellations as well as other factors that have no bearing on their business and yearly revenue generation are the main topics of this report.

---
## Assumptions
1. No unusual occurences between 2015 and 2017 will have a substantial impact on the data used. 
2. The information is still current and can be used to analyze a hotel's possible plans in an efficient manner.
3. There are no unanticipated negatives to the Hotel employing any advised technique. 
4. The hotels are not currently using any of the suggested solutions. 
5. The biggest factor affecting the effectiveness of earning income is booking cancellations.
6. Cancellations result in vacant rooms for the blocked length of time.
7. Clients make hotel reservations the same year they make cancellations

---

    

## 🎯 Problem Statement
- What are the key factors that lead to hotel booking cancellations?
- How to reduce cancellation rates and promote revenue generation?
- Assistance to hotels in making pricing and marketing decisions?

---

## 📊 Data Identification
**Dataset:** `hotel_bookings.csv`  
**Key Columns Include:**
- Hotel type (`City Hotel`, `Resort Hotel`)
- Lead time
- Booking and arrival dates
- Number of adults, children, babies
- Market segment and distribution channel
- Deposit type and customer type
- Average Daily Rate (ADR)
- Special requests and previous cancellations

---
## Hypothesis

1. Higher prices leads to more cancellations.
2. Customers tend to cancel their booking when there is a longer waiting period for reservation confirmation.
3. The majority of Clients are booking through offline modes which tend to increase the cancellation due to pay on arrival.

## 🧹 Data Exploration & Cleaning
### Steps:
1. **Import and Inspect Data**
   - Check dataset shape, column types, and sample records.
2. **Handle Missing Values**
   - Identify and impute or drop missing data appropriately.
3. **Remove Duplicates & Outliers**
   - Eliminate redundant rows and handle extreme ADR or lead time values.
4. **Feature Formatting**
   - Convert date columns, encode categorical variables, and create derived features if necessary.

---

## 🔍 Data Analysis & Insights
### Exploratory Analysis:
- Booking and cancellation distribution.
- ![Alt Text](images/plot1.png)

- Cancellations by hotel type, month, and lead time.
- Impact of deposit type and market segment.
- Relationship between special requests and cancellations.

### Visualizations:
- Bar plots, pie charts, and histograms.
- Correlation heatmaps.
- Trend lines for booking patterns over time.

---

## 📈 Key Findings
*(You can summarize your main insights here — e.g., higher cancellations for long lead time or no-deposit bookings.)*

---

## 🧠 Conclusion & Recommendations
- Highlight what the hotel management can do to reduce cancellations.
- Suggest data-driven improvements (e.g., incentives for early bookings, flexible pricing, or deposit policies).

---

## 💻 Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Scikit-learn (if predictive modeling is included)

---

## 📁 Project Structure






## ✍️ Author
**Your Name**  
*Data Analytics Portfolio Project*  
📧 [your.email@example.com] | 🔗 [LinkedIn](https://linkedin.com/in/yourprofile)

---





