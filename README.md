# 🗽 NYC Airbnb Analysis Dashboard

This Qlik Sense project presents an interactive dashboard built to explore and analyze Airbnb listings in New York City. The data is based on the publicly available [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) from Kaggle.

🔗 **Live Dashboard**: [View on Qlik Sense](https://jupidigital.us.qlikcloud.com/sense/app/d0a92468-57f2-4310-af5e-badea4b0cafb/sheet/hejPC/state/analysis/hubUrl/%2Fanalytics%2Fhome)

---

## 📊 Project Objectives

- Understand the distribution and pricing of Airbnb listings across NYC.
- Identify trends by neighborhood, room type, and availability.
- Provide insights for travelers, hosts, and policy makers.

---

## 📁 Dataset Overview

- **Source**: [Kaggle - NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **Size**: ~49,000 listings
- **Features Include**:
  - `name`, `host_id`, `neighbourhood_group`, `neighbourhood`
  - `room_type`, `price`, `minimum_nights`, `number_of_reviews`
  - `availability_365`, `last_review`, `latitude`, `longitude`

---

## 📌 Key Features of the Dashboard

- **Interactive Filters**: Quickly explore by borough, neighborhood, room type, or price range.
- **KPI Overview**: Total listings, average price, total reviews, and availability summary.
- **Maps**: Geospatial distribution of listings with price and room-type segmentation.
- **Top Hosts**: Identify the most active and popular Airbnb hosts.
- **Pricing Insights**: Average price per borough and room type.
- **Availability Trends**: Listings available throughout the year.

---

## 🔍 Key Insights

### 📍 Neighborhood & Room Type

- **Manhattan** has the highest number of listings and the highest average prices.
- **Private rooms** are most common in the Bronx and Queens, while **entire homes/apartments** dominate in Manhattan and Brooklyn.

### 💵 Price Distribution

- Average price in NYC: ~$150 per night.
- **Outliers**: Some luxury listings significantly inflate borough averages.
- **Staten Island** offers the most affordable stays on average.

### 📈 Availability & Reviews

- Listings with 365-day availability are common in Brooklyn and Manhattan.
- Most listings receive fewer than 50 reviews, indicating moderate engagement.
- Many high-priced listings have low availability, possibly indicating exclusive or seasonal use.

### 🧭 Geographic Trends

- High-density clusters of listings near:
  - **Central Park**
  - **Downtown Brooklyn**
  - **Harlem**
  - **Williamsburg**
- These areas combine accessibility, tourism demand, and unique lodging options.

---

## 🛠️ Tools & Technologies

- **Qlik Sense SaaS** (Cloud Edition)
- **Kaggle** (for data source)
- **Geo-mapping** features in Qlik Sense
- Data cleaning and transformation done within Qlik load editor

---

## 🚀 How to Reproduce

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data).
2. Upload it to your Qlik Sense workspace.
3. Follow the same sheet and visualization structure:
   - KPIs, bar charts, maps, filters
   - Create master items for key dimensions and measures
4. Use map visualizations to show listing density and price hotspots.

---

## 📌 License & Credits

- **Data**: [Kaggle - Public Dataset](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **Dashboard**: Built by Octavio Alvarez
- **Tools**: Qlik Sense (Cloud)

---

## 📬 Contact

For questions or collaborations:

**GitHub**: https://github.com/OctavioAlvarez1
**LinkedIn**: https://www.linkedin.com/in/octavio-alvarez-6a229b223/

---

