# 🗺️ Geofence Eligibility Checker

This Python project determines whether a user is eligible for a location-based offer by checking if their ZIP code falls within a specified radius of a store. It combines geolocation, distance calculation, and data visualization.

---

## 📌 Project Overview

- **Store Location:** Hardcoded latitude and longitude
- **User Input:** ZIP code
- **Functionality:**
  - Converts ZIP code to geographic coordinates
  - Calculates geodesic distance to store
  - Checks if user is within a geofence radius
  - Generates a personalized offer if eligible
  - Visualizes store and user locations on a map

---

## 🧰 Technologies Used

| Tool/Library | Purpose |
|--------------|---------|
| `pgeocode`   | ZIP code to latitude/longitude conversion |
| `geopy`      | Geodesic distance calculation |
| `matplotlib` | Map visualization |
| `pandas`     | Data summarization and export |
| `streamlit` _(optional)_ | Web interface for user input and output |

---

## 🛠️ Future Enhancements
- Batch processing from CSV
- Database integration for storing results
- Interactive map
- Role-based access and user authentication
- Deployment to cloud

## Project Description
This project was made to for a case competition to solve the problem statement "Using the dataset, suggest ways to use AI to analyze people's spending habits and offer custom rewards or deals in real time while theyre shopping" in the 2 hour time span, I took the approach to use the location of the user to generate if they are close enough to a location to be alerted they have a coupon avalable to shop at that store.
With my group we used Google Colab to create Python code using the pandas, matplotlib, and pgeocode libraries to analyze and visualize our results.
Challenges arose in the checkproximity function when finding the distance from the store to the user. In the future I would like to use AI to predict user engagement, optimize the geofence radius for better customer targeting and also for anomaly detection in location data.

