# Airport Analysis

## 📌 Project Overview
This project explores airport operations and performance using real-world aviation data. The goal is to extract insights about airport traffic, performance, and trends by cleaning raw data, preparing it for analysis, and building interactive visualizations in Tableau.

## 🗂️ Data Source
- **Source:** Kaggle
- **Format:** (e.g., CSV / Excel) raw datasets
- **Location:** `Raw Data/`

## 🧹 Data Cleaning (Power Query Editor)
Data cleaning and transformation were performed using **Power Query Editor** to ensure the dataset is analysis-ready. Key steps include:
1. Inspecting and removing duplicates
2. Handling missing values (imputing or removing as appropriate)
3. Standardizing column names and formats (dates, times, numeric types)
4. Creating calculated fields (e.g., delay minutes, on-time performance)
5. Filtering out irrelevant records (e.g., test flights, incomplete rows)

## 📊 Analysis (Tableau)
The core analysis was built in **Tableau** and includes the following dashboards and insights:
- **Airport traffic overview:** passenger counts, flight counts, peak hours
- **Delay analysis:** causes, airlines, and airports with the most delays
- **Route & connectivity analysis:** busiest routes, origin/destination trends
- **Performance metrics:** on-time performance, cancellation rates, seasonal patterns

## 🗂️ Project Structure
- `Raw Data/` — Original downloaded data (Kaggle)
- `Clean Data/` — Processed datasets after Power Query transformations
- `Result/` — Tableau workbook(s) and output

### 📌 Dashboard structure
- **Longest Routes:** Identifies destinations with the highest flight distance from SFO.
- **Day-wise Flight Count:** Tracks daily flight volume over the month.
- **Nearest Routes:** Lists closest destinations and their flight frequencies.
- **Overall Flight Count:** Provides a top-level view of the busiest destination routes.

## 🔍 Key Findings (SFO – March 2020)
These findings are based on the Tableau dashboard analyzing flight operations from **San Francisco International Airport (SFO)** for **March 2020**.

### 🔎 Key Insights
- **Longest routes:** The longest flights from SFO were to international hubs such as **BLR (Bangalore)**, **SIN (Singapore)**, **DXB (Dubai)**, and **MEL (Melbourne)**. These long-haul routes recorded between ~1K to 3K flights, with BLR and SIN slightly leading.
- **Daily volume trend:** Flight counts were relatively stable from **March 4–14** (~3.0K–3.2K flights/day), then declined sharply starting **March 19**, reaching ~2.7K by March 24 and dropping further toward month-end.
- **Nearest routes:** The closest destinations were domestic airports including **MNH**, **RNO**, and **SBP**, with distances generally under 350 miles. **MNH** had the highest count at **17,153 flights**.
- **Top destination routes:** **LAX** was the most frequent destination from SFO, with **7,968 flights**. Other high-volume routes included **JFK**, **SEA**, **LAS**, **ORD**, **SAN**, **PDX**, **EWR**, **SLC**, and **BOS**, each ranging from ~2.2K to ~8K flights.

---


