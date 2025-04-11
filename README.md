# EDA OF SALARY BASED ON DEMOGRAPHICS
### PROJECT OVERVIEW
# EDA-Project

The provided code segment represents an Exploratory Data Analysis (EDA) conducted on a dataset concerning salary variations based on demographic factors. The analysis is performed using Python within a Jupyter Notebook environment. Here's a concise overview of the code:

1. **Data Import and Libraries:**
   - The code starts by importing necessary libraries, including pandas, matplotlib, seaborn, and numpy.
   - Warnings are filtered to be ignored.

2. **Data Loading and Preprocessing:**
   - The dataset is loaded from a specified path using pandas.
   - Initial checks are carried out, including displaying the first few rows of the dataset and checking its shape.

3. **Data Transformation:**
   - The 'Unnamed: 0' column, presumed to be an index column, is removed.
   - A custom function is applied to the 'Job Title' column to categorize job titles into broader roles.
   - Another function is applied to the 'Education Level' column to categorize education levels consistently.

4. **Descriptive Statistics:**
   - Descriptive statistics, such as mean, standard deviation, and quartiles, are computed for 'Age', 'Years of Experience', and 'Salary'.

5. **Exploratory Data Analysis (EDA) Visualizations:**
   - A series of visualizations are generated to provide insights into the dataset's characteristics.

   - Pie Chart: Displays the distribution of genders within the dataset.
   - Histogram: Shows the distribution of ages, including a kernel density estimate.
   - Countplot: Illustrates the distribution of education levels.
   - Countplot: Represents the distribution of various job titles.
   - Histogram: Depicts the distribution of years of experience, including kernel density.
   - Countplot: Presents the distribution of individuals across different countries.
   - Countplot: Displays the distribution of different races.
   - Scatter Plot: Shows the relationship between salary and age.
   - Box Plot and Violin Plot: Depict the relationship between gender and salary.
   - Box Plot and Violin Plot: Illustrates the connection between education level and salary.
   - Bar Plot: Displays the average salary for different job titles.
   - Scatter Plot: Represents the relationship between years of experience and salary.
   - Box Plot and Violin Plot: Depict the relationship between country and salary.
   - Box Plot and Violin Plot: Illustrates the relationship between race and salary.
   - Heatmap: Displays the correlation matrix between numerical columns.
   - Pair Plot: Shows scatter plots for pairwise numerical relationships.

In summary, the code showcases a comprehensive EDA process aimed at gaining insights into salary variations based on demographic attributes. The visualizations provide a better understanding of distribution patterns, relationships, and potential trends within the dataset.
### TOOLS
#NUMPY
#PANDAS
#MATPLOTLIB
#SEABORN
#JUPITOR NOTEBOOK
