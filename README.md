
# Safety-Based Aircraft Investment Analysis

## 📌 Overview
This project analyzes aviation accident data to provide insights and recommendations for making **data-driven, safety-based aircraft investment decisions**. Using Python, the analysis evaluates accident trends, computes risk metrics, and ranks aircraft models to guide strategic investments in the aviation sector.

---

## 👤 Author Information
- **Student Name:** David Munyiri  
- **Student Pace:** Part-time  
- **Instructor:** Fidelis Wanalwenge  
- **Project Review Date:** 27/07/2025  

---

## 📂 Project Structure
- **student.ipynb**: Main Jupyter notebook containing the analysis.
- **data/Aviation_Data.csv**: Aviation dataset used for analysis.
- **outputs/** *(optional)*: Visualizations and processed data files.

---

## 🛠️ Technologies Used
- **Python 3**
- **Libraries:**
  - `pandas` - Data cleaning and manipulation
  - `matplotlib` - Visualization
  - `seaborn` - Advanced plotting

---

## ✅ Analysis Workflow
1. **Data Acquisition**  
   - Import aviation accident data into a pandas DataFrame.

2. **Data Cleaning & Preparation**  
   - Handle missing values  
   - Create combined fields (e.g., `Make_Model`)  

3. **Exploratory Data Analysis (EDA)**  
   - Accident frequency by aircraft model  
   - Severity patterns and contributing factors  
   - Correlation analysis  

4. **Safety Index Computation**  
   Calculate key safety metrics:
   - Fatality Index
   - Injury Index
   - Damage Severity Ind
   Calculate a composite **Risk Score** for each aircraft model.
   Weighted Risk Score: (fatality_index * 0.5) + (damage_severity_index * 0.3) + (injury_index * 0.2)

5. **Investment Recommendations**  
   - Identify aircraft models with **high safety ratings** for investment.

---

## 📊 Key Visualizations
- **Correlation Heatmap of the various indices by Model** (Heat Map)
- **Damage, injury and fatality vs. risk score to validate correlation weighting** (Scatter plot)
- **Safety indices vs aircraft models for further analysis** ( Bar Graph)
- **Safety Score Rankings** (Table/Chart)

---

## ▶️ How to Run
1. Clone this repository or download the files.(https://github.com/dkamash/dsc-phase-1-Aircraft-Investment.git )
2. Install required dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Place `Aviation_Data.csv` in the `data/` directory.
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook student.ipynb
   ```
5. Run all cells to reproduce the analysis and visualizations.

---

## ✅ Deliverables
- Complete aviation safety risk analysis.
- Visual reports supporting investment recommendations.
- Ranked list of safest aircraft models.

---

## 📝 : Tableau Public Visuals:
*https://public.tableau.com/app/profile/david.munyiri/viz/Tableau_17536476127480/Dashboard1?publish=yes*

---

## 📌 License
This project is for **educational purposes only**.

