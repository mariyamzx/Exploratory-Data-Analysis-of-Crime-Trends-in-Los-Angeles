# Exploratory-Data-Analysis-of-Crime-Trends-in-Los-Angeles

This project explores crime data from Los Angeles using Python. The goal is to identify useful patterns in criminal activity that can help the LAPD allocate resources more effectively.

## 📁 Dataset
Due to GitHub size limitations, the dataset is not included in this repo.  
You can download the original dataset from:
🔗 [Los Angeles Crime Dataset](https://data.lacity.org/)

Once downloaded, place the `crimes.csv` file in the project root directory.
- **Columns**:
  - `DR_NO`: Unique crime record number
  - `DATE OCC`: Date of occurrence
  - `TIME OCC`: Time of occurrence (24-hour format)
  - `Crm Cd Desc`: Crime description
  - `Vict Age`: Victim's age
  - `Vict Sex`: Victim's gender
  - `Vict Descent`: Victim’s ethnicity
  - Others: Location, Weapon description, Area name, etc.

## 🔧 Key Steps
- **Data Cleaning**: Removed duplicates, handled missing values, converted data types.
- **Feature Engineering**: Extracted hour from time, dropped unused columns.
- **Univariate Analysis**: 
  - Most common crimes
  - Age and gender distribution of victims
- **Bivariate Analysis**:
  - Pairplots between `Vict Age`, `Hour`, and `DR_NO`
  - Heatmaps for correlations
- **Categorical Insights**:
  - Top crimes by victim gender
  - Crime frequency by hour

## 📊 Key Insights
- Theft-related crimes are the most common in LA.
- Crimes peak during specific hours — possibly indicating burglary at night and theft during the day.
- Most common crime for **female** victims: *Theft of identity*.
- Most common crimes for **male** victims: *Battery - Simple Assault* and *Assault with a Deadly Weapon*.
- Stronger correlations observed between victim age and crime count (via `DR_NO`) in certain patterns.

## 🛠️ Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib

## 📌 Author
Mariyam Muzammil  


