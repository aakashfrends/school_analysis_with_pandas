# school_marks_analysis_with_pandas
“This project uses Pandas to clean, filter, and analyze a dataset of student marks. Includes visualization with Matplotlib/Seaborn/ to show trends and insights.”

**Project Description**
This project contains a Jupyter Notebook (school_analysis.ipynb) for performing Exploratory Data Analysis (EDA) and data cleaning on a dataset of school student records.

The primary goals of this analysis include:

Loading and inspecting the raw student data.

Identifying and handling missing values.

Preparing numerical columns (like marks and admission year) for analysis.

Performing basic data querying, filtering, and aggregation to gain insights into student demographics and performance.

**✨ Key Features and Analysis Steps**
<br>
The school_analysis.ipynb notebook demonstrates the following operations on the student dataset:

**Data Loading:** Reading the student data from a schoolr.csv file using pandas.

**Data Inspection:** Displaying the first few rows, checking data types, and summarizing non-null counts (df.info()).

**Missing Value Handling:** Identifying and summing null values for all columns, followed by removing rows with any missing data (df.dropna()).

**Data Type Conversion:** Casting multiple columns (including 'Admission Year', 'Hindi Marks', 'English Marks', etc.) from float to integer type for cleaner analysis.

**Data Slicing and Querying:** Demonstrating how to select specific column values (df.loc) and slices of the DataFrame (df.iloc).

**Conditional Aggregation:** Filtering student records based on conditions (e.g., students named 'Anjali' or 'Suman' with a 'Percentage' > 70) and counting the results.

**🛠️ Requirements**
<br>
To run this notebook locally, you need a Python environment with the following libraries installed:

pandas (for data manipulation)

numpy (for numerical operations)

matplotlib (for plotting/visualization)

seaborn (for statistical visualizations)

You can install them using pip
pip install pandas numpy seaborn matplotlib

**📂 Data**
<br>
The analysis uses data loaded from a file named schoolr.csv.
The data contains columns such as:

Serial Number, Roll Number, Name, Father Name

Admission Year, Category, Gender, Grade, City, Standard

Subject Marks: Hindi Marks, English Marks, Science Marks, Maths Marks, Drawing Marks

Calculated fields: Total Marks, Percentage.
