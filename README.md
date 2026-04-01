Data Cleaning Process

Before performing the analysis, the dataset was cleaned and standardized to ensure accuracy and consistency.

Steps performed:

Removed duplicates
Identified and removed duplicate records to avoid double counting and ensure data integrity.

Standardized text values
Used Find & Replace (Ctrl + H) to correct inconsistent naming:

"IT" → "Insta Tag"

"Neon" → "Neon Sign"

Formatted text consistency
Applied the =PROPER() function to ensure all text values follow proper capitalization (first letter uppercase).

Corrected spelling errors
Used filters to identify and fix incorrect values such as "Bussines" → "Business".

Removed extra spaces
Applied the =TRIM() function to eliminate leading, trailing, and extra spaces between words.

Adjusted data types
Converted numeric columns from Currency format to Number format for accurate calculations and analysis.

Result:

The dataset became clean, consistent, and ready for further analysis and visualization.
