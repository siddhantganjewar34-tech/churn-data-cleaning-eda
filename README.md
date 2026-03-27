# churn-data-cleaning-eda
Cleaning and visualizing a 594k row churn dataset. Fixing the mess before the modeling begins.

# Customer Churn: The Cleanup Phase

Real-world data is never as clean as the tutorials. This part of the project was about getting my hands dirty with 594k rows of raw customer data to make it actually usable for ML.

### What I actually did:
* **The Mess:** Handled missing values in `TotalCharges` and used IQR to boot out outliers that were skewing the data.
* **The Logic:** Scaled numeric features and encoded categories so the models wouldn't choke later.
* **The Visuals:** Built heatmaps and box plots to see why customers were actually leaving.

**Key takeaway:** High monthly charges + short tenure = high risk. No surprise there, but the data confirms it.
