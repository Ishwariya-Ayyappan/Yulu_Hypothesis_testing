# 🚲 Yulu Bike Rentals: Hypothesis Testing & Data Analysis with Python & Pandas

This project provides a comprehensive statistical analysis of the Yulu bike rental dataset using Python and pandas.  
We conduct hypothesis testing and exploratory data analysis to uncover key factors influencing bike rental demand, seasonal trends, and actionable recommendations for Yulu’s operational and marketing strategies.

---

## 📈 Key Insights

### 1. Data Overview
- **Dataset Size:** 10,886 hourly records of bike rentals in 2011–2012.
- **Features:** Includes timestamp, season, holiday, working day, weather, temperature, humidity, windspeed, and rental counts (casual, registered, total).

### 2. Demand Patterns
- **Seasonality:** Rentals peak in **fall** and **summer**, with winter showing the lowest demand.
- **Working Days:** ~68% of rentals occur on working days, indicating commuter usage.
- **Weather Impact:** Clear weather dominates (66%), with rentals dropping sharply during rain.

### 3. Hypothesis Testing Results
- **Working Day vs. Holiday:** Rentals are significantly higher on working days compared to holidays.
- **Seasonal Differences:** Statistically significant differences in average rentals across seasons, with fall and summer outperforming spring and winter.
- **Weather Effect:** Clear weather significantly boosts rentals compared to rainy conditions.
- **Temperature & Humidity:** Higher temperatures (up to a point) and moderate humidity levels are associated with increased rentals.

---

## 💡 Underrated Insights

- **Holiday Potential:** Holidays account for only ~2.8% of records, suggesting untapped potential for leisure-focused promotions.
- **Night-time Rentals:** Off-peak hours (late night/early morning) see minimal usage, indicating opportunities for targeted discounts or alternative services.
- **Extreme Weather:** Even light rain causes a notable drop in demand; heavy rain almost eliminates rentals.
- **Registered vs. Casual Users:** Registered users consistently outnumber casual riders, highlighting the value of loyalty and membership programs.

---

## 📝 Strategic Recommendations

1. **Seasonal Campaigns**
   - Launch marketing and pricing campaigns during fall and summer to maximise revenue.
   - Offer off-season incentives (e.g., in winter) to smooth demand fluctuations.

2. **Weather-Responsive Operations**
   - Adjust fleet deployment and maintenance schedules based on weather forecasts.
   - Provide real-time weather alerts and safety tips within the Yulu app.

3. **Holiday & Weekend Promotions**
   - Develop special offers and family/group packages for holidays and weekends to boost non-commuter usage.

4. **Membership & Loyalty Programs**
   - Encourage casual users to become registered members through targeted onboarding and rewards.

5. **Data-Driven Expansion**
   - Use analytics to identify under-served time slots and locations for potential service expansion.

6. **Continuous Monitoring**
   - Build dashboards to track demand by season, weather, and user type, enabling agile business decisions.

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
For major changes, please open an issue first.

---

> **Data-driven insights power smarter, greener urban mobility.**

---

## 📂 File Structure

- `yulu_hypothesis_testing-1.ipynb`: Main Jupyter notebook with data analysis, visualizations, and hypothesis testing code.

---

## 📊 Data Dictionary (Key Columns)

| Column      | Description                                 |
|-------------|---------------------------------------------|
| datetime    | Timestamp (hourly)                          |
| season      | 1: Spring, 2: Summer, 3: Fall, 4: Winter    |
| holiday     | 0: No, 1: Yes                               |
| workingday  | 0: No, 1: Yes                               |
| weather     | 1: Clear, 2: Cloudy, 3: Light Rain, 4: Heavy Rain |
| temp        | Temperature (Celsius)                       |
| atemp       | Feels-like temperature (Celsius)            |
| humidity    | Relative humidity (%)                       |
| windspeed   | Windspeed                                   |
| casual      | Count of casual users                       |
| registered  | Count of registered users                   |
| count       | Total rentals (casual + registered)         |

---

## 🛠️ Requirements

- Python 3.x
- pandas
- numpy
- scipy
- matplotlib / seaborn (for visualizations)
- Jupyter Notebook

---

## 🚀 Getting Started

1. Clone this repository.
2. Install dependencies:  
   `pip install pandas numpy scipy matplotlib seaborn`
3. Open `yulu_hypothesis_testing-1.ipynb` in Jupyter Notebook.
4. Run the notebook cells to reproduce the analysis and visualizations.

---

## 🤝 Contributing

Pull requests and suggestions are welcome!  
For major changes, please open an issue first.

---

> **Data-driven insights shape the future of global streaming.**
