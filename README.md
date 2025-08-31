# 🏨 Hotel Booking Analysis Project  

## 📌 Project Overview  
This project is part of my personal upskilling journey in **Data Analysis using Python**.  
I worked with a hotel booking dataset containing records from **2015 to 2017** for two types of hotels: **🏙️ City Hotel** and **🏖️ Resort Hotel**.  

The dataset includes booking details such as:  
- Hotel type, year, and booking date  
- Stay duration and cancellation status  
- Number of guests (including children)  
- Special requests and meal preferences  
- Booking sources (agents, companies, online TA/TO)  
- Guest origin countries  

🎯 **Main Goals:**  
1. Understand guest booking patterns.  
2. Compare performance between City Hotel and Resort Hotel.  
3. Find business insights related to **revenue, cancellations, guest behavior, and seasonality**.  
4. Suggest strategies to improve hotel operations and growth.  

---

## 🔎 Steps Followed  

### 1️⃣ Knowing the Data  
- Imported the dataset and performed initial exploration.  
- Identified the structure, size, and major attributes.  

### 2️⃣ Understanding the Variables  
- Studied variables such as: hotel type, booking status, lead time, stay nights, ADR (Average Daily Rate), etc.  
- Understood categorical vs. numerical features.  

### 3️⃣ Data Wrangling  
- Handled missing values (e.g., `agent`, `company`).  
- Removed duplicate records.  
- Converted data types where needed (e.g., date columns).  

### 4️⃣ Data Visualization & Storytelling  
- Used Matplotlib and Seaborn for creating visual insights.  
- Experimented with multiple chart types to understand relationships between variables.  

---

## 📊 Charts Created  

1. Hotel Type Preference – City vs Resort Hotels.  
2. Yearly Bookings Trend – 2015–2017 comparison.  
3. ADR Comparison – City vs Resort.  
4. Parking Space Requirement – Guest demand analysis.  
5. Booking Cancellations – Cancelled vs successful bookings.  
6. Monthly Booking Trends – Peak booking months.  
7. Top Agents – Agents with maximum bookings.  
8. Country-wise Guests – Top 10 guest origins.  
9. Correlation Heatmap – Relationships between variables.  
10. Room Type Preference – Most booked room categories.  
11. Meal Type Preference – BB vs others.  
12. Repeat Guests – % of repeated customers.  
13. Average Length of Stay – Guest stay duration.  
14. Booking Channels – Online TA/TO vs Offline TA/TO.  
15. Waiting Time Analysis – Average waiting days.  
16. ADR vs Total Guests – Effect of guest count on ADR.  

---

## ✅ Conclusion (Insights)  

1. 61.07% preferred City Hotel, 38.93% preferred Resort Hotel.  
2. City Hotel had more bookings in 2016 & 2017, while Resort Hotel declined in 2017.  
3. City Hotels generated higher ADR (revenue) than Resort Hotels.  
4. 91.6% of guests did not require parking; only 8.3% needed one space.  
5. City Hotel bookings had a higher waiting time.  
6. 27% of bookings were cancelled across both hotel types.  
7. July & August saw peak bookings, likely due to summer vacations.  
8. Agents 9 & 240 made the highest bookings; Agents 1 & 6 the least.  
9. Top guest origins: Portugal, UK, France, and Spain.  
10. Maximum bookings came via Online TA & Offline TA/TO.  
11. Room Types A & D were the most booked.  
12. Very few repeat customers despite large clientele.  
13. Average stay length was 7 days for both hotels.  
14. Bed & Breakfast (BB) was the most popular meal type.  
15. arrival_date_year & week_number = negative correlation (-0.51), while stays_in_week_nights & total_stay = strong positive correlation (0.95).  
16. ADR increases with guest count → directly proportional relationship.  

---

## 💡 Suggestions to Achieve Business Objectives  

### Boost Resort Hotel Bookings  
- Launch seasonal packages, holiday offers, and discounts.  
- Partner with travel agencies & OTAs for better visibility.  

### Diversify Meal Options  
- Add Half Board, Full Board, and local cuisine packages.  
- Upsell meal combos to increase ADR.  

### Expand International Reach  
- Digital marketing for underrepresented countries.  
- Localized packages & language support for international guests.  

### Optimize Facilities  
- Reduce spending on underused parking.  
- Invest in wellness, entertainment & family-friendly facilities.  

### Reduce Booking Cancellations  
- Flexible cancellation & rebooking policies.  
- Loyalty discounts for confirmed-booking customers.  

### Increase Average Length of Stay (LOS)  
- Offers like “Stay 3 Nights, Pay for 2”.  
- Perks like free spa, late checkout, complimentary meals.  

### Improve ADR & Revenue  
- Dynamic pricing models by demand/season.  
- Retain customers via loyalty programs & personalized offers.  

---

## 🚀 Key Learnings  
- Hands-on experience in data cleaning, wrangling, visualization.  
- Learned to extract business insights from raw data.  
- Improved storytelling with charts for decision-making.  

---

## 🛠️ Tools & Libraries Used  
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
