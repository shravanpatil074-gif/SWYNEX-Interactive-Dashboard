# Power BI setup

1. Open Power BI Desktop.
2. Home -> Get Data -> Text/CSV.
3. Import `data/cleaned_titanic_dashboard.csv`.
4. In Power Query/Data view confirm numeric types:
   - PassengerId: Whole number
   - Survived: Whole number
   - Pclass: Whole number
   - Age: Decimal number
   - SibSp: Whole number
   - Parch: Whole number
   - Fare: Decimal number
   - Family_Size: Whole number
   - Age_Group: Text
5. Create the DAX measures from `DAX_Measures.txt`.
6. Build the page using `DASHBOARD_LAYOUT.md`.
7. Add slicers and verify they cross-filter all visuals.
8. Save as `SWYNEX_Interactive_Dashboard.pbix`.
