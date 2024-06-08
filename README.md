# Emergency Department Burden Dataset

This dataset provides the ratio of Emergency Department (ED) encounters to treatment stations to represent the ED burden. Smaller ratios indicate fewer ED visits per available treatment station, signifying less burden. Conversely, larger ratios indicate a greater burden, with more ED visits per available treatment station.

The dataset breaks down encounters by various health-related conditions, including Active COVID-19, Asthma, Cancer, Cardiac, COPD, COVID-19 History, Diabetes, Homelessness, Hypertension, Mental Health
Obesity
Pneumonia
Respiratory Issues
Sepsis
Stroke
Substance Abuse

### Source: Data.gov
(https://catalog.data.gov/dataset/emergency-department-volume-and-capacity)

### Data Dictionary
| Field Title                | Field Name                   | Data Type | Description                                                                          |
|----------------------------|------------------------------|-----------|--------------------------------------------------------------------------------------|
| OSHPD_ID                   | oshpd_id                     | Number    | OSHPD ID for the facility                                                            |
| Facility Name              | FacilityName2                | Plain Text| Name of the facility                                                                 |
| County Name                | CountyName                   | Plain Text| County the facility is located in                                                    |
| System                     | system                       | Plain Text| Hospital system the facility is a part of (if applicable)                            |
| Licensed Bed Size          | LICENSED_BED_SIZE            | Plain Text| Category(range) of ED treatment stations                                             |
| Hospital Ownership         | HospitalOwnership            | Plain Text| Facility ownership category                                                          |
| Urban Rural Designation    | UrbanRuralDesi               | Plain text| The area designation for the location of the facility                                |
| Teaching Designation       | TEACHINGDesignation          | Plain Text| Indicates if a facility is a teaching or non-teaching facility                       |
| Category                   | Category                     | Plain Text| Health-related condition                                                             |
| ED Encounters              | Tot_ED_NmbVsts               | Number    | Total number of ED Encounters for the facility                                       |
| ED Stations                | EDStations                   | Number    | Number of ED treatment stations                                                      |
| ED Burden                  | EDDXCount                    | Number    | Number of ED visits for the specific category (health-related condition)             |
| Latitude                   | LATITUDE                     | Number    | Facility latitude                                                                    |
| Longitude                  | LONGITUDE                    | Number    | Facility longitude                                                                   |
| HPSA - Primary Care        | PrimaryCareShortageArea      | Plain Text| Indicates if a facility is in a Health Professional Shortage Area - Primary Care      |
| HPSA - Mental Health       | MentalHealthShortageArea     | Plain Text| Indicates if a facility is in a Health Professional Shortage Area - Mental Health     |

### Summary


#### Total Number of ED Visits by County
The bar chart represents the total number of Emergency Department (ED) visits for the top 10 counties in California. Los Angeles County has the highest number of ED visits with 3,468,109 visits, followed by Orange County with 1,108,283 visits, and San Diego County with 947,565 visits. The numbers of ED visits decrease progressively among the remaining counties, with Contra Costa County having the fewest visits among the top 10 with 487,899 visits.

![output (2)](https://github.com/madhulathachavali/Emergency-Department-Burden-Dataset/assets/71414635/cd77da5b-eead-4232-9e98-7384d1e2f779)


#### ED Visits by Health Condition
The graph illustrates the number of emergency department (ED) visits by health condition. Active COVID-19 had the highest number of visits. Conditions are displayed in descending order based on the total number of ED visits.

1. Active COVID-19: 8,932,253 visits
2. Hypertension: 1,711,200 visits
3. Substance Abuse: 1,091,496 visits
4. Mental Health: 920,816 visits
5. Diabetes: 899,382 visits

Total ED Visits: 13,626,808 visits



<img width="654" alt="image" src="https://github.com/madhulathachavali/EDburdendata/assets/71414635/bbd75044-76fd-46cf-b3cd-eae27d98e335">

### Alameda County 

#### Hospital Ownership: Facility Ownership Category

| HospitalOwnership | Frequency | Percent |
|-------------------|-----------|---------|
| Government        | 51        | 30.00%  |
| Nonprofit         | 119       | 70.00%  |

#### Licensed Bed Size: Category (Range) of ED Treatment Stations

| LICENSED_BED_SIZE | Frequency | Percent |
|-------------------|-----------|---------|
| 100-149           | 51        | 30.00%  |
| 150-199           | 17        | 10.00%  |
| 200-299           | 34        | 20.00%  |
| 300-499           | 68        | 40.00%  |

#### Urban Rural Designation: The Area Designation For The Location Of The Facility

| UrbanRuralDesi | Frequency | Percent |
|----------------|-----------|---------|
| Urban          | 170       | 100.00% |

#### Teaching Designation: Indicates If a Facility Is Teaching or not

| TEACHINGDesignation | Frequency | Percent |
|---------------------|-----------|---------|
| Non-Teaching        | 153       | 90.00%  |
| Teaching            | 17        | 10.00%  |

#### System: Hospital System The Facility Is a Part Of (if applicable)

| system                 | Frequency | Percent |
|------------------------|-----------|---------|
| Alameda Health System  | 34        | 20.00%  |
| Kaiser Foundation Hos  | 51        | 30.00%  |
| N/A                    | 34        | 20.00%  |
| Sutter Health          | 51        | 30.00%  |

#### Primary Care Shortage Area

| PrimaryCareShortageArea | Frequency | Percent |
|-------------------------|-----------|---------|
| No                      | 170       | 100.00% |

#### Mental Health Shortage Area

| MentalHealthShortageArea | Frequency | Percent |
|--------------------------|-----------|---------|
| No                       | 170       | 100.00% |


#### Summary Statistics for Number of ED Visits by Primary Care Shortage Area and Mental Health Shortage Area for each System in Alameda County

**EDDXCount: Number of ED visits for the specific category (health-related condition)**

- **Alameda Health System**: The total number of ED visits in areas without primary care and mental health shortages is 135,779.
- **Sutter Health**: The total number of ED visits is 574,899 in areas without shortages, 137,826 in areas with only mental health shortages, 32,135 in areas with only primary care shortages, and 75,244 in regions with both shortages.
- **Kaiser Foundation Hospital**: The total number of ED visits is 2,696,826 in areas without shortages, 530,968 in areas with only mental health shortages, and 412,944 in areas with only primary care shortages.
- **N/A**: The total number of ED visits is 1,484,796 in areas without shortages, 931,605 in areas with only mental health shortages, 387,830 in areas with only primary care shortages, and 824,578 in areas with both shortages.

#### Summary Statistics for EDDXCount by Various Designations in Alameda Health System

#### Alameda Health System

**Analysis Variable: EDDXCount**

| HospitalOwnership | UrbanRuralDesi | TEACHINGDesignation | PrimaryCareShortageArea | MentalHealthShortageArea | N Obs | Sum        |
|-------------------|----------------|---------------------|-------------------------|--------------------------|-------|------------|
| Government        | Urban          | Non-Teaching        | No                      | No                       | 34    | 135,779.00 |

#### Sutter Health

**Analysis Variable: EDDXCount**

| HospitalOwnership | UrbanRuralDesi | TEACHINGDesignation | PrimaryCareShortageArea | MentalHealthShortageArea | N Obs | Sum        |
|-------------------|----------------|---------------------|-------------------------|--------------------------|-------|------------|
| Nonprofit         | Rural          | Non-Teaching        | Ye                      | No                       | 17    | 32,135.00  |
|                   |                |                     |                         | Ye                       | 51    | 75,244.00  |
|                   | Urban          | Non-Teaching        | No                      | No                       | 187   | 574,899.00 |
|                   |                |                     |                         | Ye                       | 68    | 137,826.00 |

#### Kaiser Foundation Hospital

**Analysis Variable: EDDXCount**

| HospitalOwnership | UrbanRuralDesi | TEACHINGDesignation | PrimaryCareShortageArea | MentalHealthShortageArea | N Obs | Sum        |
|-------------------|----------------|---------------------|-------------------------|--------------------------|-------|------------|
| Nonprofit         | Urban          | Non-Teaching        | No                      | No                       | 357   | 2,644,196.00|
|                   |                |                     |                         | Ye                       | 68    | 437,844.00 |
|                   |                |                     | Ye                      | No                       | 34    | 326,348.00 |
|                   |                | Teaching            | No                      | No                       | 17    | 52,630.00  |
|                   |                |                     |                         | Ye                       | 17    | 93,124.00  |
|                   |                |                     | Ye                      | No                       | 17    | 86,596.00  |

#### N/A

**Analysis Variable: EDDXCount**

| HospitalOwnership | UrbanRuralDesi | TEACHINGDesignation | PrimaryCareShortageArea | MentalHealthShortageArea | N Obs | Sum        |
|-------------------|----------------|---------------------|-------------------------|--------------------------|-------|------------|
| Government        | Front          | Non-Teaching        | Ye                      | No                       | 16    | 2,301.00   |
|                   |                |                     |                         | Ye                       | 102   | 35,312.00  |
|                   | Rural          | Non-Teaching        | No                      | No                       | 17    | 10,758.00  |
|                   |                |                     |                         | Ye                       | 17    | 31,590.00  |
|                   |                |                     | Ye                      | No                       | 34    | 54,827.00  |
|                   |                |                     |                         | Ye                       | 102   | 107,346.00 |
|                   | Urban          | Non-Teaching        | No                      | No                       | 85    | 279,772.00 |
|                   |                |                     |                         | Ye                       | 34    | 226,215.00 |
|                   |                |                     | Ye                      | No                       | 17    | 9,978.00   |
|                   |                |                     |                         | Ye                       | 51    | 243,142.00 |
|                   |                | Teaching            | No                      | No                       | 17    | 97,530.00  |
|                   |                |                     |                         | Ye                       | 34    | 210,157.00 |
| Investor O        | Front          | Non-Teaching        | Ye                      | Ye                       | 17    | 7,398.00   |
|                   | Rural          | Non-Teaching        | Ye                      | Ye                       | 34    | 48,189.00  |
|                   | Urban          | Non-Teaching        | No                      | No                       | 51    | 136,282.00 |
|                   |                |                     |                         | Ye                       | 34    | 76,350.00  |
|                   |                |                     | Ye                      | No                       | 34    | 47,596.00  |
| Nonprofit         | Front          | Non-Teaching        | Ye                      | Ye                       | 17    | 5,794.00   |
|                   | Rural          | Non-Teaching        | No                      | No                       | 34    | 46,998.00  |
|                   |                |                     |                         | Ye                       | 34    | 34,371.00  |
|                   |                |                     | Ye                      | Ye                       | 153   | 321,894.00 |
|                   | Urban          | Non-Teaching        | No                      | No                       | 220   | 876,532.00 |
|                   |                |                     |                         | Ye                       | 85    | 352,922.00 |
|                   |                |                     | Ye                      | No                       | 34    | 75,735.00  |
|                   |                |                     |                         | Ye                       | 17    | 55,503.00  |
|                   |                | Teaching            | No                      | No                       | 17    | 36,924.00  |
|                   |                |                     | Ye                      | No                       | 34    | 197,393.00 |



#### Conclusion
Based on the analysis of the Emergency Department Burden Dataset, several key insights can be drawn:

1. Total ED Visits by County:

Los Angeles County has the highest number of ED visits with 3,468,109 visits.
Other counties with significant ED visits include Orange County (1,108,283), San Diego (947,565), Riverside (889,722), and San Bernardino (841,649).
Counties such as Alameda (777,934) and Sacramento (723,933) also show a substantial number of ED visits.
Smaller counties like Glenn and Modoc have the fewest ED visits, indicating less burden in these regions.

2. ED Visits by Health Condition:
Active COVID-19 is the leading health condition, accounting for the highest number of ED visits (8,932,253 visits).
Hypertension (1,711,200 visits) and Substance Abuse (1,091,496 visits) are also major contributors to ED visits.
Mental Health issues (920,816 visits) and Diabetes (899,382 visits) are prevalent health conditions leading to significant ED usage.

#### Alameda County Analysis:
4. Hospital Ownership:
Most facilities in Alameda County are non-profit (70.00%), with the remaining being government-owned (30.00%).
5. Licensed Bed Size:
Most facilities fall in the 300-499 range (40.00%), followed by 100-149 (30.00%).
6. Urban Rural Designation:
All facilities in Alameda County are located in urban areas (100.00%).
7. Teaching Designation:
Most facilities are non-teaching (90.00%), with only 10.00% being teaching hospitals.
8. System Affiliation:
Facilities are distributed among Alameda Health System, Kaiser Foundation, and Sutter Health, with each system having a significant presence.
9. Summary Statistics for EDDXCount by System and Category:
a. Alameda Health System: The total number of ED visits is substantial in areas without primary care and mental health shortages.
b. Sutter Health: Shows variability in ED visits across different shortage areas, with a notable number in regions with both primary care and mental health shortages.
c. Kaiser Foundation Hospital: Displays the highest number of ED visits in areas without shortages, but also significant numbers in areas with primary care and mental health shortages.
d.  N/A: Indicates a broad distribution of ED visits across various shortage designations, highlighting the diverse healthcare needs within the county.
10. Facility Designations and ED Burden:
The data indicates that government-owned facilities, non-profit hospitals, and both teaching and non-teaching hospitals are managing significant ED visits.
The urban designation of facilities underscores the higher healthcare demand in urban areas compared to rural regions.
