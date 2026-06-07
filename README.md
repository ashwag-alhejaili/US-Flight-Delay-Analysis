# ✈️ US Flight Delay Analytics (30M Records)

## 📌 Overview
An enterprise Power BI dashboard analyzing over **30 million US flight records**. The project focuses on strategic data preparation to handle Big Data efficiently and deliver clean operational insights.

## 🛠️ Data Preparation & RAM Optimization
* **Column Reduction:** Dropped redundant separate columns (Years, Months, Days) to minimize table width.
* **Data Type Optimization:** Converted flight dates strictly to **Date** data type, and transformed high-precision decimal numbers into lightweight **Whole Numbers (Integers)** to drastically reduce RAM consumption.

## 📊 Key Metrics (KPIs)
* **Total Flights:** 30M+ | **On-Time:** 24M (79%) | **Delayed:** 6M (21%)

## 🗂️ Architecture
1. **Overview:** High-level operational view tracking top cities and airlines market share.
2. ![Overview Page](<img width="2083" height="1753" alt="overview (2)" src="https://github.com/user-attachments/assets/183a1db0-8ea8-4ddf-a882-9ddaa4513a7b" />)
3. **Data Analysis:** Root cause analysis (Late Aircraft and Carrier issues drive >73% of delays).
4. ![Data Analysis Page](<img width="2098" height="1752" alt="Data Analysis" src="https://github.com/user-attachments/assets/d621d7e3-25d8-409e-94aa-1e057bf6f96c" />/)
   
5. **Performance Trend:** Visual timeline showing weekly patterns (Fridays peak at 24% delay rate).
6. ![Performance Trend Page](<<img width="2099" height="1752" alt="Performance Trend" src="https://github.com/user-attachments/assets/5de3684f-e3a0-4846-81ea-be84f1d79fb2" />
/>)

## 💡 Key Skills Demonstrated
* **Big Data Optimization:** Preparing and compressing 30M+ rows inside Power Query.
* **UI/UX Engineering:** Seamless native navigation using Power BI Bookmarks & Actions.
