# Pollution and pH of Soil - Weather Situation 🌱☀️

This project analyzes how **pollution**, **soil pH**, and **weather factors** like **rainfall** and **temperature** influence soil conditions and agricultural performance across different crop types.  
It uses **Python** libraries like **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn** to perform **EDA (Exploratory Data Analysis)** and uncover key insights from the dataset.

---

## 📂 Project Structure

- **Data loading**: Imported and read data from `MD_agric_exam-4313.csv`.
- **EDA (Exploratory Data Analysis)**:
  - Displayed head of the dataset, info, and statistical summary.
  - Analyzed unique crop types and their distributions.
- **Key Insights and Calculations**:
  - Maximum annual yield for *wheat* crop.
  - Total rainfall for crop types with pollution levels above 0.2.
  - Temperature ranges for specific Field IDs.
  - Identified crop type with lowest mean minimum temperature (*rice*).
  - Total plot size where pH < 5.5.
  - Number of fields with *Min Temperature* < -5°C and *Max Temperature* > 30°C.
  - Standard deviation of Rainfall for larger plot sizes.
  - Generated a special concatenated string combining temperature and crop name.
  - Visualized annual yield distribution across different **elevation ranges**.
  - Recursive function to sum lengths of unique crop type names.
  - Statistical test (t-test) to compare **Annual Yield** between *coffee* and *banana* crops (p-value = **0.598**).

---

## 🛠️ Libraries Used

- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib**: For creating plots and graphs.
- **Seaborn**: For advanced visualizations.
- **Scipy**: For statistical testing (t-test).

---

## 📊 Key KPIs Identified

| Metric | Value |
|:------:|:-----:|
| Mean Rainfall | 1197.73 mm |
| Mean Soil pH | 5.60 |
| Mean Pollution Level | 0.223 |
| Mean Plot Size | 3.96 hectares |
| Mean Annual Yield | 2.10 tons |

---

## 📈 Visualization

- **Violin Plot** showing **Annual Yield** distribution based on **Elevation Range** (Low, Medium, High).

---

## 📌 How to Run the Project

1. Clone the repository or download the project files.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
3. Run the Python script to view the outputs and plots.

---

## 📑 Dataset Columns

- `Field_ID`
- `Elevation`
- `Rainfall`
- `Min_temperature_C`
- `Max_temperature_C`
- `pH`
- `Pollution_level`
- `Plot_size`
- `Annual_yield`
- `Crop_type`
- `Elevation_range` (created during analysis)

---

## 📢 Notes

- Elevation was categorized into three ranges: **Low**, **Medium**, and **High**.
- Recursive function was creatively used to sum lengths of crop names.
- A p-value > 0.05 in the t-test suggests **no significant difference** between *coffee* and *banana* yields.

---

## 📸 Project Image

**Preview:**  
(openart-image_-wbOrs37_1709330079784_raw.jpg)
