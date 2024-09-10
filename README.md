
# Airbnb Data Analysis

This project involves analyzing Airbnb data for New York City to uncover trends and insights regarding room listings, host distribution, pricing, reviews, and availability.

## Data

- **Total Listed Rooms**: 38,790
- **Total Hosts**: 9,859
- **Neighborhoods Analyzed**: 218

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : Handled empty cells and errors, and cleaned the data.
- Step 5 : A calculated column was created to show the duration of room listings in months

for creating new column following DAX expression was written;
       
        Age_of_room(in months) = Table1[number_of_reviews]/Table1[reviews_per_month]
- Step 7 : In the report view, under the view tab, theme was selected.
- Step 8 : Began developing charts to uncover valuable insights

## Report Snapshot (Power BI DESKTOP)

![Airbnb powerbi](https://github.com/user-attachments/assets/dbfb6dbb-44ac-4c93-b940-8e5f14b3691d)


## Key Insights

- **Room Distribution**:
  - Highest in Manhattan (16,607) and Brooklyn (16,428).
  - High number of hosts in Bedford-Stuyvesant.

- **Reviews**:
  - Most reviews in Brooklyn (~485,000).
  - Second highest in Manhattan (453,000).

- **Pricing**:
  - Highest average price in Manhattan ($180.10).
  - Lowest in the Bronx ($79.56).
  - Entire home/apartment types are the most expensive($196) while shared rooms are the least ($63.21). Despite higher costs, apartments receive the most reviews, suggesting they are favored by customers.
  

- **Room Availability**:
  - Highest in Staten Island.
  - Lowest in Brooklyn and Manhattan.

- **Room Age**:
  - Number of rooms decreases as they get older.

- **Minimum Stay**:
  - Average minimum nights: 3 for apartments, 2 for private rooms, and 1 for shared rooms.

## Purpose

This analysis aims to provide a comprehensive understanding of the Airbnb market in New York City, focusing on how various factors like room type, location, and pricing influence booking trends and availability.



## Contact

For questions or further information, please contact:
- **Name**: Muhammed Afsal
- **Email**: afsalcpna1999@gmail.com

---

