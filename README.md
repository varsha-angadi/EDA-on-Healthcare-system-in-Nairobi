# **Healthcare System Analysis in Nairobi**

## **Objective**
This project applies **Exploratory Data Analysis (EDA)** techniques to understand and analyze the healthcare system in Nairobi. By examining healthcare facilities, their ownership, and operational status, this analysis aims to uncover trends and disparities in healthcare access across different sub-counties. The project also provides actionable recommendations to improve healthcare services.

---

## **Project Structure**
The analysis is divided into the following sections:

### **1. Data Loading and Preprocessing**
- Loaded the dataset and inspected its structure (e.g., for missing values and incorrect formats).
- Cleaned the data by handling missing values and documented the methodology used.
- Encoded categorical variables like `Owner` and `Sub-county`.
- Ensured proper data types, such as converting operational status into boolean values.

### **2. Data Exploration**
- Summary statistics for key numerical features.
- Visualized:
  - Distribution of healthcare facilities by type and ownership.
  - Operational vs. non-operational facilities across regions.
  - Distribution of essential healthcare services (e.g., maternity, blood tests).

### **3. Healthcare Access Analysis**
- Identified sub-counties with the highest number of non-operational facilities.
- Analyzed operational facilities by ownership sector (public, private, NGOs).
- Highlighted regions lacking essential healthcare services.

### **4. Advanced Visualizations**
- Bar chart: Facility ownership distribution by sub-county.
- Heatmap: Operational status of facilities across Nairobi’s sub-counties.
- Pie chart: Proportions of healthcare facility types (e.g., clinics, hospitals).

### **5. Insights and Recommendations**
- Summarized key insights, such as underserved sub-counties and disparities in service access.
- Provided recommendations for improving healthcare access and facility performance.
- Suggested collaborations between public, private, and NGO sectors.

### **6. Documentation and Reporting**
- Well-commented Python code for all tasks in the Jupyter notebook.
- Comprehensive report including visualizations, trends, and actionable recommendations.

---

## **Technologies Used**
- **Python**: For data cleaning, exploration, and analysis.
- **Pandas**: To manage and preprocess the dataset.
- **Matplotlib/Seaborn**: For creating visualizations.
- **Jupyter Notebook**: To document and execute code.

---

## **Outputs**
### **Key Deliverables**
1. **Jupyter Notebook**: Includes all Python code, comments, and outputs.
2. **Visualizations**:
   - Bar charts, pie charts, and heatmaps showing various aspects of healthcare facilities in Nairobi.
3. **Summary Report**: A PDF/Word document with:
   - Findings and insights.
   - Recommendations for improving healthcare services.

---

## **Insights and Recommendations**
### **Key Findings**
- Certain sub-counties have disproportionately high numbers of non-operational facilities.
- The public sector owns the majority of operational facilities, but disparities exist in private and NGO contributions.
- Essential healthcare services like maternity care and blood tests are lacking in specific regions.

### **Recommendations**
1. Allocate more resources to underserved sub-counties.
2. Encourage public-private partnerships to optimize operational capacity.
3. Invest in healthcare infrastructure and essential services in regions with high demand but low supply.
