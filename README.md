# respiratory-virus-data-analysis
#### This dataset includes weekly respiratory disease hospital admissions for Influenza, RSV, and COVID-19 into San Francisco hospitals. The data are reported by week. The data used here are from 2024-10-13 to 2025-11-02.
#### This dataset is obtained from https://catalog.data.gov/dataset/respiratory-virus-hospital-admissions-over-time
#### The dataset contains the following columns:
#### - week_start_date: First day inclusive of reporting period
#### - week_end_date: Last day inclusive of reporting period
#### - epi_week: Ordinal count of week periods for the year. Weeks last from Sunday through Saturday and usually range from 1 to 52. Week 1 is the first week of the year that has at least four days in the calendar year.
#### - respiratory_virus: Type of respiratory virus (Influenza, RSV, COVID-19)
#### - new_admissions: Count of disease specific hospital admissions to San Francisco Hospitals reported 
#### - admission_rate_per_100k: The rate of disease specific hospital admissions per 100,000 is calculated by multiplying the count of admissions each week by 100,000 and dividing by the San Francisco population estimate 
#### - sf_population: 2019-2023 5-year American Community Survey (ACS) population estimate
#### - date_as_of: A date and time when the most recent data was made available to San Francisco 
#### - data_loaded_at: Timestamp the data was uploaded to the open data portal