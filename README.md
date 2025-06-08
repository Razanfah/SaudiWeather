# 🌟 Saudi Weather Dashboard

## 🌐 Overview

Welcome to the **Saudi Weather Dashboard**! This interactive web application offers a comprehensive view of weather conditions across various cities in Saudi Arabia. Built with **Streamlit**, this dashboard enables users to explore temperature, humidity, wind speed, and dew point, all at their fingertips.

---

## 🎨 Features

- **Interactive Visualizations**: Dive into dynamic maps and heatmaps that showcase real-time weather data.
- **Dynamic Filtering**: Customize your experience by selecting date ranges and specific weather parameters.
- **Weather Extremes**: Instantly view the hottest, coldest, driest, and windiest cities for the most recent month.
- **Personalized Recommendations**: Input your ideal weather preferences and discover the top three matching city/month combinations.

---

## 🛠 Technologies Used

- **Python Libraries**:
  - **Pandas**: For efficient data manipulation and analysis.
  - **Matplotlib & Seaborn**: For crafting beautiful static visualizations.
  - **Streamlit**: To build the interactive web application effortlessly.
  - **Geopandas**: To handle geographic data smoothly.
  - **Plotly**: For stunning interactive plots.
  - **Streamlit-Folium**: To display Folium maps seamlessly.

---

## 🚀 Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Required Packages**:
   ```bash
   pip install pandas matplotlib seaborn streamlit geopandas plotly streamlit-folium
   ```

3. **Download the Dataset**: Ensure you have the `SaudiCitiesWeather.csv` file in your project directory.

---

## 🖥 Usage

1. **Run the Application**:
   ```bash
   streamlit run app.py
   ```

2. **Access the Dashboard**: Open your web browser and navigate to `http://localhost:8501`.

---

## 🔑 Key Functions

- **`load_data(file_path)`**: Loads and prepares weather data from a CSV file.
- **`preprocess_data(df)`**: Cleans and formats the data for analysis.
- **`get_weather_extremes_latest_month(df)`**: Displays the extremes of weather for the most recent month.
- **Visualization Functions**:
  - **`temperature_plot(avg_df)`**
  - **`humidity_plot(avg_df)`**
  - **`wind_plot(avg_df)`**
  - **`dew_point_plot(avg_df)`**
  
- **Recommendation Function**:
  - **`recommend_top3_by_preferences(df, desired_temp, desired_humidity, desired_dew, desired_wind)`**: Suggests the top three city/month combinations based on user-defined weather preferences.

---

## ✨ User Interface

Experience a beautifully designed dashboard that allows you to:
- **Select Cities**: Choose from a variety of cities to view specific weather conditions.
- **Customize Views**: Filter data by date and weather parameters, making it easy to find what you need.
- **Visualize Data**: Switch between different map types and heatmaps to gain insights into the climatic conditions.

---

## Conclusion

The **Saudi Weather Dashboard** is your go-to tool for exploring the weather patterns in Saudi Arabia. With its user-friendly interface and powerful analytical capabilities, you can easily gain insights and discover your ideal weather conditions. Dive in and start exploring today!

## Try the App
If you want to try the app online, you can access it here: Weather Analysis Web App
