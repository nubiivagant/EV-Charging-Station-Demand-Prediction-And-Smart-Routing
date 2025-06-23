# ⚡ EV Charging Station Optimization & Smart Routing

This project combines **machine learning** and **real-time APIs** to:
- 📍 Predict **demand hotspots** for EV charging stations across cities using clustering.
- 🚗 Provide **inter-city smart routing** for EVs with planned charging stops using range, route, and real-time charger data.

## 🚦 Features

### 🔋 1. Intra-city Clustering
- Cluster charging stations using **KMeans** to detect **high-demand zones** within a city.
- Compute **Silhouette Score** to evaluate clustering performance.
- View clusters on a **Streamlit-based interactive map**.

### 🚗 2. Inter-city EV Smart Route Planning
- Input origin & destination cities.
- Choose EV range (battery limit).
- Automatically calculate route & **charging stops** based on distance thresholds.
- Real-time **nearby charging stations** from MapMyIndia API.
- Visual route planning with **Folium** maps on Streamlit.

# Example Use Case
- User selects Nagpur in clustering app → discovers 3 cluster zones.
- User plans EV trip from Nagpur to Pune with 250 km range.
- System shows route, highlights where to stop, and lists real-time charger availability.

## 🖼️ Demo Screenshots

### 🔋 Clustering Dashboard
Identify high-demand EV station zones in cities based on station density.

![Clustering](clustering.png)

![Output](output.png)

