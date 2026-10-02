# 🏠 Airbnb Global Performance Dashboard

An interactive **Power BI dashboard** built to analyze Airbnb listing
performance across multiple cities. The project focuses on understanding
listing growth, city-level market share, ratings, review behavior,
seasonality, pricing, and host trust indicators.

## 🔗 Live Power BI Dashboard

👉 **[View the Interactive Airbnb Global Performance Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTg3OWU3ZjAtYWU5YS00NDIwLWIzNjMtNzhiZWFiMDk4YmY3IiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)**

## 📊 Dashboard Preview

> Add the exported dashboard screenshots to an `images` folder in your
> GitHub repository using the filenames below.

### 1. New Listings & Growth

![New Listings & Growth](images/01-new-listings.png)

### 2. Market Share, Pricing & Ratings

![Market Share, Pricing & Ratings](images/02-market-share-ratings.png)

### 3. Review Frequency, Seasonality & Host Trust

![Review Frequency, Seasonality & Host
Trust](images/03-reviews-seasonality-trust.png)

### 4. Power BI Data Model

![Power BI Data Model](images/04-data-model.png)

------------------------------------------------------------------------

## 🎯 Project Objective

The objective of this project is to transform Airbnb listing and review
data into an interactive business intelligence solution that helps
answer questions such as:

-   How has Airbnb listing volume changed over time?
-   Which cities contribute the largest share of listings?
-   How do property types differ in average price?
-   Which cities have the highest and lowest ratings?
-   How frequently do customers leave reviews?
-   How does listing activity vary across months?
-   What proportion of hosts have verified identities and profile
    pictures?
-   What patterns can be observed in Airbnb's growth, maturity, decline,
    and COVID-19 period?

------------------------------------------------------------------------

## 📌 Key Dashboard Metrics

  KPI                    Value
  ------------------ ---------
  Total Listings       279,712
  Cities Covered            10
  Hosts                182,024
  Property Types           144
  Listing ID Count      5.373M

*Values shown above are based on the dashboard snapshot.*

------------------------------------------------------------------------

## 🔍 Dashboard Sections

### 1. New Listings & Growth

Analyzes the historical trend of Airbnb listings by property type and
highlights major business periods such as:

-   Initial growth
-   Peak/maturity period
-   Decline
-   Re-invention
-   COVID-19 period

The dashboard compares listing trends across:

-   Entire Place
-   Private Room
-   Shared Room
-   Hotel Room

### 2. Market Share by City

Provides a city-level view of Airbnb's listing distribution using:

-   Superhost vs. non-Superhost listings
-   Cumulative market share
-   City-wise listing volume
-   Average price by property type

Cities included in the dashboard include:

**Paris, New York, Sydney, Rome, Rio de Janeiro, Istanbul, Mexico City,
Bangkok, Cape Town, and Hong Kong.**

### 3. Ratings Analysis

Compares average ratings across cities to identify differences in
customer experience.

The analysis covers cities such as:

-   Mexico City
-   Rio de Janeiro
-   Cape Town
-   New York
-   Rome
-   Sydney
-   Paris
-   Bangkok
-   Istanbul
-   Hong Kong

### 4. Review Frequency

Analyzes how frequently customers leave reviews and shows the cumulative
percentage of reviewers by review count.

This helps understand whether Airbnb customers typically review a
listing once or multiple times.

### 5. Seasonality

Analyzes monthly listing/review patterns across selected cities to
identify seasonal changes in activity.

Cities highlighted include:

-   Mexico City
-   New York
-   Paris
-   Rome
-   Sydney

### 6. Host Trust

Examines host verification and profile-picture availability using a
matrix of:

-   Identity verified / not verified
-   Profile picture available / not available

This provides a simple view of host trust-related characteristics.

------------------------------------------------------------------------

## 🛠️ Tools & Technologies

-   **Power BI**
-   **Power Query**
-   **DAX**
-   **Data Modeling**
-   **Interactive Data Visualization**
-   **Business Intelligence**

### Power BI Concepts Used

-   KPI Cards
-   Line Charts
-   Bar & Column Charts
-   Combo Charts
-   Conditional Formatting
-   Slicers / Filters
-   DAX Measures
-   Relationships
-   Data Modeling
-   Drill-down / Detail-level analysis
-   Dashboard storytelling

------------------------------------------------------------------------

## 🧮 Data Model

The dashboard uses a relational model connecting listing information
with review data.

### Main Tables

**Listings** - listing_id - host_id - city - property type -
accommodates - bedrooms - host acceptance rate - host profile picture -
host identity verification - and other listing attributes

**Reviews** - listing_id - date - review month - month number

A dedicated **measure calculation table** is also used for dashboard
measures.

### Relationship

``` text
Reviews
   │
   │ listing_id
   ▼
Listings

Measure_Calc
   │
   └── DAX Measures
```

------------------------------------------------------------------------

## 💡 Business Insights

The dashboard is designed to communicate several business-level
observations:

-   Listing activity changes significantly across different periods.
-   A relatively small number of major cities account for a substantial
    portion of the listing base.
-   Average prices vary considerably by property type.
-   Customer ratings differ between cities.
-   Review frequency is concentrated among customers who leave a small
    number of reviews.
-   Listing activity shows seasonal patterns across different markets.
-   Host verification and profile-picture availability can be used as
    indicators when analyzing host trust.

------------------------------------------------------------------------

## 📁 Suggested Repository Structure

``` text
Airbnb-Global-Performance-Dashboard/
│
├── README.md
│
├── Airbnb_Global_Performance_Dashboard.pbix
│
├── images/
│   ├── 01-new-listings.png
│   ├── 02-market-share-ratings.png
│   ├── 03-reviews-seasonality-trust.png
│   └── 04-data-model.png
│
└── data/
    └── README.md
```

> If the original dataset cannot be redistributed, do not upload the raw
> data. Instead, mention the dataset source in the repository and
> provide instructions for obtaining it.

------------------------------------------------------------------------

## 🚀 How to Explore the Dashboard

1.  Download the `.pbix` file from this repository.
2.  Open it using **Microsoft Power BI Desktop**.
3.  Review the dashboard pages and interact with filters/visuals.
4.  Explore the data model and DAX measures to understand how the
    analysis was built.

------------------------------------------------------------------------

## 📈 Skills Demonstrated

This project demonstrates practical skills relevant to **Data Analyst /
BI Analyst / Power BI Developer** roles:

-   Data cleaning and transformation
-   Data modeling
-   DAX
-   KPI development
-   Exploratory data analysis
-   Business-oriented visualization
-   Dashboard design
-   Trend analysis
-   Market segmentation
-   Customer behavior analysis
-   Data storytelling

------------------------------------------------------------------------

## 👤 Author

**Shubham Malvankar**

**Aspiring Data Analyst \| Power BI Developer \| SQL Enthusiast \|
Python**

Interested in turning raw data into meaningful business insights using
**Excel, SQL, Power BI, and Python**.

------------------------------------------------------------------------

## ⭐ If You Find This Project Useful

Feel free to explore the dashboard, review the Power BI model, and use
the project as a reference for learning data analytics and business
intelligence.
