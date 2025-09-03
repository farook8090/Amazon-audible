📊 Audible Dataset Cleaning — Excel Case Study
📌 Project Overview

This case study demonstrates how to utilize Power Query Editor in Excel to clean and standardize an Audible dataset. The objective is to ensure data consistency, accuracy, and readiness for analysis by applying various data transformation techniques.

📝 Case Study Description

The dataset required multiple cleaning and formatting tasks to prepare it for meaningful analysis. Using Power Query, the following steps were performed:

🔹 Data Cleaning & Transformation Tasks

Name Standardization

Converted all entries in the name column to consistent title case.

Author Column Split

Separated combined names in the author column into individual authors.

Release Date Formatting

Ensured all entries in the releasedate column follow a DD-MM-YYYY format.

Duration Conversion

Converted the time column from text to a recognized duration format.

Price Column Standardization

Ensured the price column is numeric.

Identified and handled non-numeric values.

Applied consistent currency formatting with two decimal places.

Ratings Transformation

Converted text-based ratings in the stars column into numeric values.

Narrators Column Split

Split the narratedby column into multiple columns when multiple narrators are listed.

Release Info Column Creation

Merged releasedate and language columns into a new column:

releaseinfo → "DD-MM-YYYY, Language"

🛠️ Tools Used

Microsoft Excel

Power Query Editor

🚀 Outcome

By cleaning and standardizing the Audible dataset, the data is now:

Consistent and error-free.

Properly formatted for analysis.

Ready to be used for reporting and visualization.
