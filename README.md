# Read data file
data = pd.read_csv("crash_data.csv")
if "Round" not in data.columns:
    data.columns = ["Round", "Value"]  # Ensure consistent column names