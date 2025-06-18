# Airbnb NYC Data Analysis: Prices & Availability

Analyzing room types, availability, and prices in the NYC Airbnb market.

---

## 🚀 Project Goals
- Explore trends in listings by borough and room type
- Identify pricing strategies
- Visualize availability and seasonal differences

---

## 📦 Dataset
- Source: [Inside Airbnb](http://insideairbnb.com/get-the-data.html) — NYC Listings CSV

---

## 📌 Coding Exercises

### 1. Cleaning & Filtering
- Load and clean the dataset
- Drop listings with missing prices or extreme values (e.g., price > $1000)
- Parse datetime and calculate month from `last_review`

### 2. Aggregation & Grouping
- Group by `neighbourhood_group` and `room_type`
  - Compute: mean price, mean availability, count of listings
- Identify boroughs with the highest median prices
- Create pivot tables of room type vs borough vs price

### 3. Visualization
- Bar plots: average price by borough and room type
- Heatmap of availability by neighborhood
- Plot distribution of prices (use log scale for skewed data)

---

## 🧠 Key Questions
- Which borough is most expensive on average?
- Which room type dominates in Brooklyn?
- Are shared rooms cheaper than private rooms across boroughs?

---
