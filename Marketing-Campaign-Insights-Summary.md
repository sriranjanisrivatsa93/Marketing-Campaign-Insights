The analysis notebook loads and examines a marketing campaign dataset containing 22,029 records and 16 distinct attributes.

## Dataset Overview & Structure

* **Dimensions:** 22,029 rows and 16 columns with zero missing values across all fields.


* **Primary Columns:** `Campaign_ID`, `Company`, `Campaign_Type`, `Target_Audience`, `Duration`, `Channel_Used`, `Conversion_Rate`, `Acquisition_Cost`, `ROI`, `Location`, `Language`, `Clicks`, `Impressions`, `Engagement_Score`, `Customer_Segment`, and `Date`.


* **Categorical Dimensions:**
* **Companies (5 unique):** Includes TechCorp, Innovate Industries, NexGen Systems, Data Tech Solutions, and Alpha Innovations.


* **Campaign Types (5 types):** Display, Search, Social Media, Email, and Influencer.


* **Channels Used (6 channels):** Facebook, Google Ads, Website, Instagram, YouTube, and Email.


* **Customer Segments (5 segments):** Tech Enthusiasts, Foodies, Fashionistas, Outdoor Adventurers, and Health & Wellness.


* **Locations (10 cities):** Houston, Washington, D.C., Miami, Seattle, Chicago, Los Angeles, Atlanta, Dallas, New York, and San Francisco.





## Statistical Highlights

* **Conversion Rate:** Ranges from 2.02% to 7.47%, with a mean of approximately 4.76% and a standard deviation of 0.96.


* **Acquisition Cost:** Spans from 1,000 to 9,999 units, averaging 5,522.74 units.


* **Return on Investment (ROI):** Averages 182.86 with significant variance (standard deviation of 301.62), ranging from a minimum of -98.30 to a maximum of 3,109.79.


* **Engagement & Traffic:** Average clicks stand at 2,223.81 (max 6,887), average impressions at 50,610.40 (max 99,999), and average engagement scores at 6.58 out of 9.



## Exploratory Data Analysis & Visualization

* **Data Integrity:** Inspection via `df.isnull().sum()` confirms a clean dataset with complete data across all 22,029 rows.


* **Visual Analysis:** The notebook incorporates a Seaborn scatter plot mapping **Acquisition Cost** against **ROI** to evaluate financial efficiency and cost-to-return dynamics across campaigns.