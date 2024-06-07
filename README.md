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
Los Angeles, Orange County, San Diego, Riverside, and San Bernardino are the top counties with the highest ED Visits.

   
 
| Obs | CountyName      | Total_ED_Visits |
|-----|-----------------|-----------------|
| 1   | Los Angeles     | 3,468,109       |
| 2   | Orange County   | 1,108,283       |
| 3   | San Diego       | 947,565         |
| 4   | Riverside       | 889,722         |
| 5   | San Bernardino  | 841,649         |
| 6   | Alameda         | 777,934         |
| 7   | Sacramento      | 723,933         |
| 8   | Santa Clara     | 636,471         |
| 9   | San Joaquin     | 582,963         |
| 10  | Contra Costa    | 487,899         |
| 11  | Fresno          | 468,757         |
| 12  | Kern            | 387,285         |
| 13  | San Francisco   | 339,309         |
| 14  | Placer          | 332,690         |
| 15  | Solano          | 331,934         |
| 16  | Stanislaus      | 305,065         |
| 17  | Ventura         | 290,721         |
| 18  | Santa Barbara   | 227,091         |
| 19  | San Mateo       | 178,875         |
| 20  | Monterey        | 162,903         |
| 21  | Tulare          | 142,292         |
| 22  | San Luis Obispo | 140,519         |
| 23  | Madera          | 136,296         |
| 24  | Shasta          | 134,708         |
| 25  | Merced          | 124,882         |
| 26  | Kings           | 123,847         |
| 27  | Butte           | 120,396         |
| 28  | Marin           | 104,077         |
| 29  | Sonoma          | 103,102         |
| 30  | Yuba            | 94,088          |
| 31  | Mendocino       | 83,689          |
| 32  | Yolo            | 78,260          |
| 33  | Lake            | 61,073          |
| 34  | El Dorado       | 59,864          |
| 35  | Nevada          | 54,660          |
| 36  | Napa            | 51,280          |
| 37  | Tuolumne        | 50,361          |
| 38  | Tehama          | 49,082          |
| 39  | Imperial        | 43,623          |
| 40  | San Benito      | 32,468          |
| 41  | Amador          | 32,135          |
| 42  | Humboldt        | 25,489          |
| 43  | Del Norte       | 19,797          |
| 44  | Calaveras       | 18,628          |
| 45  | Siskiyou        | 16,496          |
| 46  | Lassen          | 16,180          |
| 47  | Inyo            | 13,059          |
| 48  | Mariposa        | 7,994           |
| 49  | Plumas          | 7,685           |
| 50  | Modoc           | 7,650           |
| 51  | Glenn           | 7,398           |


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

### Alameda Health System

**The MEANS Procedure**

**Analysis Variable: EDDXCount**

| PrimaryCareShortageArea | MentalHealthShortageArea | Sum      |
|-------------------------|--------------------------|----------|
| No                      | No                       | 135,779  |

### Sutter Health

**The MEANS Procedure**

**Analysis Variable: EDDXCount**

| PrimaryCareShortageArea | MentalHealthShortageArea | Sum      |
|-------------------------|--------------------------|----------|
| No                      | No                       | 574,899  |
|                         | Yes                      | 137,826  |
| Yes                     | No                       | 32,135   |
|                         | Yes                      | 75,244   |

### Kaiser Foundation Hospital

**The MEANS Procedure**

**Analysis Variable: EDDXCount**

| PrimaryCareShortageArea | MentalHealthShortageArea | Sum      |
|-------------------------|--------------------------|----------|
| No                      | No                       | 2,696,826|
|                         | Yes                      | 530,968  |
| Yes                     | No                       | 412,944  |

### N/A

**The MEANS Procedure**

**Analysis Variable: EDDXCount**

| PrimaryCareShortageArea | MentalHealthShortageArea | Sum      |
|-------------------------|--------------------------|----------|
| No                      | No                       | 1,484,796|
|                         | Yes                      | 931,605  |
| Yes                     | No                       | 387,830  |
|                         | Yes                      | 824,578  |











