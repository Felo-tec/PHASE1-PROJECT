#  Aviation Accident Data Analysis

##  Project Overview
Safety in the aviation sector is a major issue in the world. Knowledge about the causes, frequency, and effects of aviation accidents can be used to determine the patterns and enhance safety precautions, as well as policy-making. The data in this project ( aviation-accident-data-2023-05-16.csv ) has more than 23,950 records of aviation accidents and incidents in various countries, operators and aircraft type.
We used Python (Pandas, Matplotlib, Seaborn) to clean, analyze, and visualize the dataset.


# Tools & Libraries
- *Python* (3.10+)
- *Pandas* → data cleaning & analysis
- *Matplotlib* & *Seaborn* → visualizations
- *Jupyter Notebook* → interactive analysis


## Dataset
- *File*: aviation-accident-data-2023-05-16.csv  
- *Rows*: ~23,967 records  
- *Columns*:  
  - date – date of the accident  
  - type – aircraft type  
  - operator – airline/operator  
  - fatalities – number of fatalities  
  - location – where the accident occurred  
  - country – country of accident  
  - year – extracted year of accident  

---

## Key Steps
1. *Data Cleaning*
   - Converted year to numeric and removed invalid values (unknown, NaN).
   - Dropped rows with missing or ambiguous entries in critical columns.
   - Standardized column names for consistency.

2. *Exploratory Data Analysis (EDA)*
   - shows fatailites  (histogram).
   - Top 10 countries by accident counts (bar chart).
   - show fatailities over the year (line chart).
   - show fatalities per category(bar chart)
   - show fatalities per operator(bar chart)
3. *Visualization*
   - Simple, clear charts to highlight safety insights.

## Results

### 1. Distribution of Fatalities
- Most accidents involve *0–5 fatalities*, meaning many are small-scale incidents.
- A few high-fatality accidents create long tails.

### 2. Countries with the Most Accidents
- Highest accident counts observed in *USA, Russia, Indonesia, Brazil, and India*.
- Indicates operational and regulatory differences.
- Indicates that there are more flights in *USA, Russia, Indonesia, Brazil, and India*

### 3. Trends Over Time
- Accidents have *decreased significantly since the 1990s*, reflecting better safety regulations and technology improvements.
- Accidents are decreased over time since pilots are trained regularly

## Business Recommendations
1. *Highlight Modern Safety Improvements*  
   Accidents are decreasing over time; new aircraft and regulations make flying safer.  
   Marketing should emphasize these trends.

2. *Focus on Regional Safety Audits*  
   High-incident regions (e.g., Indonesia, Russia) need stricter compliance and training.  
   Entry into such markets should include additional safety protocols.

3. *Prioritize Smaller Aircraft Safety*  
   Most incidents involve smaller planes.  
   Extra investments in *pilot training* and *equipment upgrades* will mitigate risks.


The link to the[tableau dashboard](https://public.tableau.com/views/AviationAccidentDataAnalysis_17593378456050/AVIATIONACCIDENTDATA?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
