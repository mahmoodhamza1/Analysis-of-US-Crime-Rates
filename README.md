# Analysis of US Crime Rates (1960–2014)

This project analyzes **crime trends in the United States between 1960 and 2014** using official statistics.  
The study investigates how crime patterns evolved over five decades, identifying **periods of rapid growth, decline, and structural shifts** across crime categories.  

The analysis uses **data visualization and exploratory analysis** in R to uncover key drivers of crime and highlight correlations with population dynamics:contentReference[oaicite:0]{index=0}.  

---

## 📄 Project Overview

Crime is a critical issue that impacts communities, economies, and policy decisions.  
In the U.S., crime rates surged from the 1960s through the early 1990s, then steadily declined.  
This project explores:

- **Long-term crime trends** over five decades.  
- The contrast between **violent** and **property crimes**.  
- The **relative share** of different crime categories.  
- The **relationship between population growth, property crimes, and larceny theft**.  

---

## ⚙️ Methodology

### 1. Dataset
- **Source:** `US_Crime_Rates_1960_2014.csv`  
- **Period:** 1960–2014  
- **Variables:**  
  - **Demographic:** Population  
  - **Aggregate:** Total crimes, Violent crimes, Property crimes  
  - **Disaggregated Violent crimes:** Murder, Forcible Rape, Robbery, Aggravated Assault  
  - **Disaggregated Property crimes:** Burglary, Larceny Theft, Vehicle Theft  

### 2. Tools
- **Language:** R (R Markdown workflow)  
- **Libraries:**  
  - `tidyverse` for wrangling and summarization  
  - `ggplot2` for advanced plotting and visualization  

### 3. Analytical Steps
1. **Trend analysis**  
   - Line plots to show changes in **total crime rates** year-over-year.  
   - Identified structural breakpoints (early 1990s peak).  

2. **Crime type breakdown**  
   - Trellis plots for each crime category to capture different trajectories.  
   - Compared property vs. violent crimes over time.  

3. **Distribution analysis**  
   - Treemap visualization to show the **relative share of each crime type** in total crime.  
   - Highlighted property crime dominance.  

4. **Correlation analysis**  
   - Scatterplots of **population vs. property crimes**, colored by larceny theft levels.  
   - Measured whether crime growth tracked population or diverged due to other factors.  

5. **Interpretation**  
   - Linked results to **socio-economic drivers** (urbanization, poverty, policing reforms, demographic shifts).  

---

## 📊 Results & Insights

### 1. Overall Trends
- **Sharp rise (1960–1990s):**  
  - Total crimes increased from ~3M in 1960 to ~14.5M in the early 1990s.  
  - Causes: rapid urbanization, poverty, changes in drug laws, limited law enforcement capacity.  
- **Decline (post-1990s):**  
  - Fell to ~9M by 2014.  
  - Causes: community policing, better policing technology (CompStat, hot spot policing), stronger economies, demographic changes (aging population).  

### 2. Crime Type Dynamics
- **Property crimes** were the dominant contributor to overall crime levels:  
  - **Larceny Theft** was the largest single sub-category.  
  - Burglary and Vehicle Theft also contributed significantly.  
- **Violent crimes** (murder, rape, robbery, assault) followed the same rise-and-decline trend but remained **lower in absolute numbers**.  
- All categories showed synchronized trends: **increase until early 1990s, followed by steady decline**.  

### 3. Distribution of Crimes
- Treemap confirmed:  
  - **Property crimes accounted for the majority of U.S. crime.**  
  - **Violent crimes were proportionally small**, but high in social and political impact.  

### 4. Correlation Findings
- **Population vs. Property Crimes:**  
  - Positive correlation up to ~1990 → more people, more property crime.  
  - After 1990 → property crime declined despite continued population growth.  
  - Insight: **population growth alone does not drive crime** — socio-economic and policy shifts matter.  
- **Larceny Theft:**  
  - Strongly correlated with property crimes, confirming its role as the **key driver** of crime rates.  

### 🔑 Key Insight
The U.S. experienced a **crime wave (1960s–1990s)** followed by a **historic decline**.  
- **Property crimes, especially larceny theft, were the central driver** of overall trends.  
- Crime is **not linearly linked to population growth** — policy reforms, economic improvements, and demographic shifts explain much of the decline.  
- This underscores the need for **targeted crime prevention strategies** (e.g., addressing theft-related crimes) alongside broader **social and economic policies** to sustain public safety. 
