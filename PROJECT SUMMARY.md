Aviation Risk Analysis

📊 Project Overview
As our company prepares to expand into the aviation sector, understanding the safety and risk profiles of different aircraft is critical to making informed, data-driven investments. This project analyzes aviation accident data from 1962 to 2023—sourced from the National Transportation Safety Board (NTSB)—to identify low-risk aircraft types best suited for commercial and private operations.

Using Python and Tableau, we cleaned and analyzed the data, calculated aircraft-level risk scores, and developed an interactive dashboard to help stakeholders explore accident patterns and evaluate aircraft safety.

🚀 Business Problem
Which aircraft models present the lowest risk to the company as it enters the aviation industry?

To help leadership make confident purchasing decisions, we analyzed historical accident data to:

Identify aircraft types with consistently low accident and fatality rates

Reveal key risk factors such as flight type, location, and severity

Recommend data-driven strategies for aircraft acquisition

🧰 Tools & Technologies
Python (Jupyter Notebook) for data cleaning, analysis, and preprocessing

Pandas, NumPy, Matplotlib, Seaborn for EDA

Tableau for interactive dashboard creation

Git & GitHub for version control and collaboration

📁 Repository Structure
bash
Copy
Edit
📦 aviation-risk-analysis/
├── data/                 # Cleaned dataset used in Tableau
├── notebooks/            # Jupyter notebook with data cleaning & analysis
├── presentation/         # Screenshots or slides from business presentation
├── dashboard/            # Link or embed code for Tableau dashboard
├── README.md             # Project overview and instructions

📈 Key Findings
Aircraft Make X and Model Y had the lowest fatality-to-accident ratio over the last 30 years.

Private flights had higher accident rates compared to commercial operations, especially in rural states.

Accidents due to weather-related factors and pilot error were most common during takeoff and landing phases.

📌 Business Recommendations
Start with Aircraft Models A and B, which demonstrate strong safety records and low historical fatality rates.

Avoid older aircraft and light personal planes, which are overrepresented in fatal accidents.

Focus initial operations in regions with low historical incident rates and strong aviation infrastructure.


📜 Data Source
NTSB Aviation Accident Database (1962–2023)
Contains civil aviation accidents and incidents in the U.S. and international waters.

Actionable Insights and Recommendations for Aircraft Purchase:
------------------------------------------------------------

Key Observations:
- Our analysis ranks aircraft based on actual accident outcomes, prioritizing those with the lowest rates of fatal injuries, overall injuries, and aircraft destruction.
- Several aircraft models demonstrate exceptionally low risk profiles, with zero reported fatalities, serious injuries, or aircraft destruction in the dataset, even across multiple reported incidents.
- Conversely, aircraft with the highest total accident counts often show significant numbers of injuries, particularly fatal ones, as visualized in the injury severity distributions.

Recommendations:
1. Prioritize Aircraft with Proven Low Injury and Damage Rates:
   - Focus acquisition efforts on aircraft models that appear at the top of the 'lowest_risk_aircraft' ranking. These models have a historical record of accidents resulting in minimal or no severe outcomes.
   - Specifically, models with 0 fatal injuries, 0 serious injuries, 0 minor injuries, and 0 destroyed percentages should be strongly considered, provided there is a sufficient number of recorded events to make the data statistically meaningful.
2. Consider Total Accident Count in Context:
   - While a low total accident count might seem desirable, it could also indicate limited data for that aircraft type. Evaluate the low-risk aircraft list in conjunction with their 'total_accidents'. Aircraft with low injury/damage rates across a higher number of accidents may offer more statistically robust evidence of low risk.
3. Be Cautious with High-Accident Aircraft:
   - Aircraft models appearing in the 'Top 20 Aircraft with Highest Accident Counts' list should be approached with caution. While accident rates alone don't tell the whole story, the associated injury severity distributions for these aircraft indicate a higher potential for severe outcomes when accidents do occur.
4. Further Investigate Top Low-Risk Candidates:
   - For the top candidates from the 'lowest_risk_aircraft' list, conduct further due diligence. This could involve looking into the specific circumstances of the minor incidents reported (if any) and considering operational history outside of this dataset.

Caveats and Limitations:
- The analysis is based on the provided historical accident data, which may have limitations in terms of completeness and reporting standards over time.
- The dataset primarily covers accidents reported to the NTSB/FAA, which may not include all incidents or cover all types of aviation operations globally.
- 'Total_Extracted_Injuries' is based on parsing the 'Injury.Severity' string and might not capture all injury information if not explicitly stated in the standard format.
- The definition of 'accident' and reporting requirements may have changed over the years, potentially influencing trends.
- This analysis focuses on accident outcomes. Other factors like maintenance costs, operational efficiency, and acquisition costs are also critical for purchase decisions but are outside the scope of this data.

- ## 📊 Interactive Dashboard

Explore the full interactive Tableau dashboard [here](https://public.tableau.com/views/Book1_17537249048940/Dashboard3?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

<img width="1438" height="749" alt="Dashboard 3" src="https://github.com/user-attachments/assets/5f742f83-09a9-4e66-99bc-b2d8e97a4e10" />


