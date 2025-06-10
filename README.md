# GDP Data Analysis and Visualization

This repository features a Google Colab notebook that demonstrates comprehensive data analysis and visualization techniques using Python's Pandas, Matplotlib, and Seaborn libraries. The analysis is based on the `GDP (nominal) per Capita.csv` dataset, which contains GDP per capita figures for various countries and territories.

---

## 📁 Files in this Repository

- **Copy_of_Pandas_Practice_Notebook.ipynb**  
  The Google Colab notebook containing all the Python code for data loading, analysis, and visualization.

- **GDP (nominal) per Capita.csv**  
  The dataset used in the notebook, containing GDP per capita (nominal) figures for various countries and territories.

---

## 🚀 How to Use

1. **Open in Google Colab:**
   - Navigate to the `Copy_of_Pandas_Practice_Notebook.ipynb` file in this GitHub repository.
   - Click on the "Open in Colab" badge (if available) or copy the URL of the notebook.
   - Alternatively, go to [Google Colab](https://colab.research.google.com/), click "File" → "Open notebook" → "GitHub", and paste the repository URL.

2. **Upload the Dataset:**
   - Once the notebook is open in Colab, upload the `GDP (nominal) per Capita.csv` file.
   - In the notebook, run the cell containing:
     ```
     from google.colab import files
     uploaded = files.upload()
     ```
   - Use the prompt to select and upload the CSV file from your local machine.

3. **Run the Notebook:**
   - Execute each cell in order by clicking the "Play" button or pressing `Shift + Enter`.
   - Review the outputs, including data tables and generated plots, to understand the analysis and visualizations.

---

## 📊 Key Concepts Covered

The notebook provides practical, hands-on examples of:

### **Data Loading and Inspection (Pandas)**
- Loading CSV data into a DataFrame (`pd.read_csv()`).
- Viewing data samples (`df.head()`, `df.tail()`, `df.sample()`).
- Checking DataFrame dimensions (`df.shape`).
- Inspecting data types and missing values (`df.info()`).
- Generating descriptive statistics (`df.describe()`).
- Identifying unique values and their counts (`.value_counts()`).

### **Data Manipulation and Transformation (Pandas)**
- Filtering data based on conditions (e.g., by region or country).
- Grouping and aggregating data (`df.groupby().mean()`, `df.groupby().median()`).
- Sorting data by specific columns (`df.sort_values()`).
- Selecting top/bottom N records (`df.nlargest()`, `df.nsmallest()`).

### **Data Visualization (Matplotlib & Seaborn)**

![image](https://github.com/user-attachments/assets/74b8ba77-3dfa-4f12-af0f-35642934874c)

![image](https://github.com/user-attachments/assets/5a242cb0-3484-417d-bc87-ca7e5abf4310)

![image](https://github.com/user-attachments/assets/de343cec-7717-4d32-a1f6-fafa14271bbd)

- Creating bar charts and line plots to compare GDP per capita across regions or over time.
- Visualizing distributions of GDP estimates.
- Using scatter plots to explore relationships between economic indicators.
- Generating heatmaps or other statistical plots to identify patterns.

---

**Explore the notebook to gain practical skills in data analysis and visualization using real-world economic data!**
