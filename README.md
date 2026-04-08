Data Cleaning Process
Before performing the analysis, the dataset was cleaned and standardized to ensure accuracy and consistency.
Steps performed:
1.	Removed duplicates
Identified and removed duplicate records to avoid double counting and ensure data integrity.
2.	Standardized text values
Used Find & Replace (Ctrl + H) to correct inconsistent naming:
•	"IT" → "Insta Tag"
•	"Neon" → "Neon Sign"
3.	Formatted text consistency
Applied the =PROPER() function to ensure all text values follow proper capitalization (first letter uppercase).
4.	Corrected spelling errors
Used filters to identify and fix incorrect values such as "Bussines" → "Business".
5.	Removed extra spaces
Applied the =TRIM() function to eliminate leading, trailing, and extra spaces between words.
6.	Adjusted data types
Converted numeric columns from Currency format to Number format for accurate calculations and analysis.
Result:
The dataset became clean, consistent, and ready for further analysis and visualization
<img width="468" height="515" alt="image" src="https://github.com/user-attachments/assets/6aabf3f4-6c7e-4b18-b968-f14e4d287406" />
