COVID-19 Data Exploration Project:

Objective: Conducted comprehensive analysis of COVID-19 data to derive insights into infection rates, mortality rates, and vaccination progress.
Skills Utilized: Leveraged advanced SQL techniques including joins, Common Table Expressions (CTEs), Temp Tables, Window Functions, and Aggregate Functions. Created Views to store intermediate results for visualization and further analysis.
Key Analyses:
Calculated mortality rates and infection rates for various countries and continents.
Identified countries with the highest infection rates relative to their population.
Analyzed vaccination progress by calculating the percentage of the population vaccinated over time.
Generated global COVID-19 statistics including total cases, total deaths, and death percentages.
Data Sources: Utilized COVID-19 datasets stored in the PortfolioProject database, encompassing information on cases, deaths, population, and vaccinations.
Outcome: Provided valuable insights into the impact of COVID-19 across different regions, aiding in understanding disease dynamics and informing public health interventions.

Nashville Housing Project:
This SQL script is designed to clean and standardize data from the "NashvilleHousing" table within the "PortfolioProject" database. Here's a breakdown of the main tasks performed:

Standardize Date Format: Converts the "SaleDate" column to a standardized date format.
Populate Property Address Data: Fills in missing "PropertyAddress" values by matching parcel IDs and updating accordingly.
Break Out Address into Individual Columns: Splits the "PropertyAddress" column into separate columns for address, city, and state.
Parse Owner Address: Extracts address, city, and state from the "OwnerAddress" column and separates them into individual columns.
Change Yes/No to Y/N in "SoldAsVacant" Field: Converts "Y" and "N" values in the "SoldAsVacant" column to "Yes" and "No" respectively.
Remove Duplicates: Identifies and removes duplicate rows based on specific columns while preserving one instance of each unique row.
Delete Unused Columns: Removes columns "OwnerAddress", "TaxDistrict", "PropertyAddress", and "SaleDate" from the table.
Additionally, there's a commented section providing an alternative method for importing data using OPENROWSET and BULK INSERT, which allows data to be imported from external sources like CSV files.

This script aims to enhance data quality and consistency within the database by standardizing formats, filling missing values, and removing duplicates.






