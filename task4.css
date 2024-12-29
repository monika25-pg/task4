import pandas as pd
import seaborn as sns

# Create a synthetic traffic accident dataset
np.random.seed(42)
data = {
    "Accident_ID": range(1, 501),
    "Road_Condition": np.random.choice(["Dry", "Wet", "Icy", "Snowy"], size=500, p=[0.5, 0.3, 0.1, 0.1]),
    "Weather": np.random.choice(["Clear", "Rainy", "Foggy", "Snowy"], size=500, p=[0.6, 0.2, 0.1, 0.1]),
    "Time_of_Day": np.random.choice(["Morning", "Afternoon", "Evening", "Night"], size=500, p=[0.25, 0.35, 0.25, 0.15]),
    "Latitude": np.random.uniform(40.0, 41.0, size=500),  # Simulated latitudes
    "Longitude": np.random.uniform(-80.0, -79.0, size=500),  # Simulated longitudes
}

accident_data = pd.DataFrame(data)

# Display first few rows of the dataset
accident_data.head()
