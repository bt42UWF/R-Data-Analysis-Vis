# Data Analysis and Visualization with R Code

### This R script is an analysis of the HairEyeColor dataset using the tidyverse package in R. 

Here's a breakdown of what each part of the code does:

1. Installation and Loading of Packages:
   - Installs and loads the tidyverse package, which includes several packages for data manipulation and visualization such as dplyr, ggplot2, and purrr.
   - Also installs and loads the dslabs package, which contains the HairEyeColor dataset.

2. Data Loading and Preprocessing:
   - Loads the HairEyeColor dataset.
   - Converts the dataset into a data frame.
   - Displays the first few rows of the dataset.

3. Data Manipulation:
   - Uses the pipe operator %>% to perform data manipulation operations.
   - Groups the data by the columns Sex, Hair, and Eye.
   - Calculates three summary statistics for each group:
     - mean_frequency: Mean of the Freq column within each group.
     - total_frequency: Sum of the Freq column within each group.
     - count: Number of rows within each group.

4. Data Arrangement:
   - Arranges the summarized data based on the values of the Sex, Hair, and Eye columns.

5. Data Visualization:
   - Visualizes the summarized data using ggplot2.
   - Creates a bar plot where:
     - The x-axis represents Eye Color.
     - The y-axis represents Mean Frequency.
     - Bars are colored based on the Hair column.
     - Each bar represents the mean frequency of hair and eye color combinations.
   - Adds a title and axis labels to the plot.
   - Applies a minimal theme to the plot for a clean appearance.
