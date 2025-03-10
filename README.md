# Chemical Kinetics - Organizational Culture Analysis

## Project Overview
This project analyzes the relationship between organizational culture and task performance within **Chemical Kinetics**, a company specializing in chemical and technical services. The analysis is based on survey data collected from employees and is visualized using Python, Pandas, Matplotlib, and Seaborn in a Jupyter Notebook.

The key focus areas include:
- Examining **organizational culture dimensions**: Community & Collaboration, Innovation & Agility, Competitive Drive, and Structure & Control.
- Understanding their impact on **task performance**.
- Identifying correlations, outliers, and data trends through **visualization and statistical analysis**.

---

## Data Description
The dataset used in this analysis is sourced from an **Organizational Culture Assessment Test (OCAT) survey** taken from "Mindbyte Analytics Tests". It includes responses from employees regarding their perceptions of organizational culture and self-assessed task performance.


### **Key Variables in the Dataset**
- `age`: Employee age
- `experience_with_current_organization_(in_years)`: Work experience in the company
- `community_and_collaboration`: Rating of teamwork and support
- `innovation_and_agility`: Perception of adaptability and innovation
- `competitive_drive`: Employee drive to meet goals
- `structure_and_control`: Level of structured policies and control
- `task_performance`: Self-rated task performance score

---

## Analysis and Visualizations
### **1. Data Cleaning & Processing**
- Loaded the dataset using **Pandas**.
- Renamed columns for consistency.
- Converted necessary columns to **numeric format** and handled missing values.

### **2. Statistical & Correlation Analysis**
- Computed the **correlation matrix** to examine relationships between cultural dimensions and task performance.
- Generated a **heatmap** of correlations to visualize trends.
- Created **pairwise scatter plots** to explore potential linear relationships.

### **3. Task Performance Analysis**
- **Boxplots** of task performance based on employee **designation**.
- **Scatter plot** of task performance vs **experience**.
- **Histogram** of task performance distribution.
- **Outlier detection** using boxplots.

### **4. Cultural Dimensions Analysis**
- **Box plots** comparing different cultural dimensions.
- **Bar chart** showing the average scores for organizational culture aspects.

---

## Installation & Setup
### **Prerequisites**
Ensure you have **Python 3.x** installed along with Jupyter Notebook.

### **Required Libraries**
Install the necessary Python libraries using pip:
```bash
pip install pandas matplotlib seaborn notebook
```

### **Running the Jupyter Notebook**
1. Clone this repository:

2. Navigate to the project folder:
   ```bash
   cd Chemical-Kinetics-Analysis
   ```
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open **Chemical_Kinetics_Visualizations.ipynb** and run the cells.

---

## Contact
For questions or suggestions, reach out via LinkedIn
