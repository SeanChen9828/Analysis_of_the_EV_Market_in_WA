<p align="center">
  <img src="1-Data Resources/EV-background.jpg" width="100%" height = "200" alt="Excel Background Visual"/>
</p>

## 🚗 Electric Vehicle Population Analysis: Washington State

---

### 🔍 Analysis Overview
This project analyzes Washington State's electric vehicle (EV) registration data to understand market trends, technology adoption, and policy impacts. Using Python for data processing and visualization, key insights about EV distribution, brand performance, and eligibility for clean energy incentives are extracted.

---

### 📂 Dataset Description
- **📍 Publisher:** [data.wa.gov](https://data.wa.gov)  
- **🔗 Source:** Washington State Department of Licensing (DOL) [View Dataset on Data.gov](https://catalog.data.gov/dataset/electric-vehicle-population-data)
- **🗓️ Metadata Updated:** May 17, 2025
- **✨ Key fields:** County, Make, Model, Electric Vehicle Type, Clean Alternative Fuel Vehicle (CAFV) Eligibility, Electric Range
- **📌 Size:** ~250,000 vehicle records
---

### 🛠️ Analytical Approach
1. **Data Processing** (Python):
   - 🧾 **Step 1: Data Collection / Loading**
     > Importing basic Lib resources used in this data analysis, like pandas,numpy,matplotlib and seaborn
     > Loading data from Electric_Vehicle_Population_Data.CSV using pandas

   - 🔍 **Step 2: Data Inspection**
     -  Using .head(), .info(), .describe() to understand data shape, types, and basic stats
     -  Describing the columns filled in value

   - 🧹 **Step 3: Data Cleansing**
     -  Identifying and handling missing or null values
     -  Coping with 0 values by replacing them with NaN or statistic values

   - 📊 **Step 4: Exploratory Data Analysis (EDA)**
     - Visualizing distributions, trends, and relationships using matplotlib, seaborn,plotly

   - 💡 **Step 5: Reporting & Interpretation**
     - Concluding the key findings with charts and graphs

   - 📤 **Step 6: Export Results**
     - Saving cleaned datasets as '.csv'

2. **Analysis Dimensions**:
   - **🗺️ Market Overview:** Showcase the overall distribution of electric vehicles in Washington State, highlighting hotspots
   - **🏁 Brand Competition:** Analyze the market share of each brand and identify market leaders and emerging competitors
   - **⚙️ Technological Evolution:** Showcase the progressive trends in the range of electric vehicles and compare the performance of different types of vehicles
   - **🏛️ Policy Impact:** Explore the influence of policy incentives (such as CAFV qualifications) on the popularization of electric vehicles
   - **👥 Consumer Insights:** Revealing consumer preference patterns to provide a basis for marketing
   - **🔮 Future Outlook:** Predict the future development direction based on the current trend and put forward suggestions

3. **Visualization**:
   - Created bar/line/pie charts using Matplotlib/Seaborn/Plotly

---

### 🔑 Key Findings
1. **Market Overview: EV Distribution in Washington State**
   - **Top Counties by EV Population:** **King County** leads with the highest number of EVs, followed by **Pierce**, **Thurston**, and **Kitsap** counties. These areas represent the primary hotspots for EV adoption in Washington State.
   - **Implication:** Urban and densely populated regions are driving EV adoption, likely due to better infrastructure and higher awareness.
<p align="center">
  <img src="Pic_Inserted/EMSI_JobChange_UK Dashboard.png" width="400" alt="EMSI Job Change Dashboard"/>
</p>

2. **Brand Competition: Market Share and Leaders**
   - **Dominant Brands:** **Tesla** is the clear market leader with the highest number of registered EVs, significantly outpacing competitors like **Chevrolet**, **Nissan**, and **Ford**.
   - **Emerging Competitors:** **Rivian** and **Jeep**, though smaller in volume, are notable entrants in the EV market.
   - **Implication:** Tesla’s strong presence underscores its brand dominance, while traditional automakers like Chevrolet and Ford are also key players.
<p align="center">
  <img src="Pic_Inserted/EMSI_JobChange_UK Dashboard.png" width="400" alt="EMSI Job Change Dashboard"/>
</p>

3. **Technological Evolution: Electric Range Trends**
   - **Range Improvement:** The electric range of EVs has shown a **progressive increase** over the years (2010–2025), with brands like Tesla, Audi, and Porsche offering some of the highest ranges.
   - **Brand Comparison:** **Tesla** consistently leads in range performance, while brands like **Nissan** and **Hyundai** show competitive but lower ranges.
   - **Vehicle Types:** Battery Electric Vehicles (BEVs) dominate the market (**79.3%**), far exceeding Plug-in Hybrid Electric Vehicles (PHEVs) (**20.7%**).
   - **Implication:** Consumers prefer BEVs, possibly due to advancements in battery technology and longer ranges.
<p align="center">
  <img src="Pic_Inserted/EMSI_JobChange_UK Dashboard.png" width="400" alt="EMSI Job Change Dashboard"/>
</p>

4. **Policy Impact: CAFV Eligibility**
   - **Eligibility Distribution:** Approximately **30.5%** of EVs qualify as Clean Alternative Fuel Vehicle (CAFV) eligible, while **9.6%** are not eligible due to low battery range. A large percentage (**60%**) have unknown eligibility.
   - **Implication:** Policy incentives like CAFV eligibility are likely influencing consumer choices, with nearly a third of EVs meeting the criteria for benefits.
<p align="center">
  <img src="Pic_Inserted/EMSI_JobChange_UK Dashboard.png" width="400" alt="EMSI Job Change Dashboard"/>
</p>

5. **Consumer Insights: Preference Patterns**
   - **Brand Preference:** Tesla’s dominance suggests strong consumer trust and preference for its technology and brand reputation, and Tesla's **Model 3** and **Model Y** are the most popular vehicle models.
   - **Range Preference:** The trend toward higher electric ranges indicates that consumers prioritize vehicles with longer driving capabilities.
   - **Implication:** Marketing strategies should emphasize range and brand reliability to attract potential buyers.
<p align="center">
  <img src="Pic_Inserted/EMSI_JobChange_UK Dashboard.png" width="400" alt="EMSI Job Change Dashboard"/>
</p>

6. **Future Outlook: Predictions and Suggestions**
   - **Growth Areas:** Continued growth in urban counties like **King** and **Pierce** is expected, with potential expansion into suburban areas as infrastructure improves.
   - **Technological Advancements:** Brands investing in **longer-range batteries and faster charging** will likely gain a competitive edge.
   - **Policy Recommendations:** Expanding CAFV eligibility criteria and incentives could further boost EV adoption, especially for emerging brands and models with lower ranges.
   - **Consumer Education:** Increasing awareness about PHEVs and their benefits could help balance the market distribution between BEVs and PHEVs.

---

### 📝 Summary
The data highlights **Tesla’s market dominance**, the preference for **BEVs with longer ranges**, and the significant role of **policy incentives** in driving EV adoption. Urban centers are the primary adoption hubs, while technological advancements and policy adjustments will shape future trends. Strategic focus on **infrastructure**, **consumer education**, and **competitive offerings** will be key to sustaining growth in the EV market.

