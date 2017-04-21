# Energy Usage 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-usage-2010-24a67) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/8yq3-m6wp) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/8yq3-m6wp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/8yq3-m6wp/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | 8yq3-m6wp |
| Name | Energy Usage 2010 |
| Attribution | City of Chicago |
| Category | Environment & Sustainable Development |
| Tags | sustainability, energy |
| Created | 2013-04-22T03:34:58Z |
| Publication Date | 2013-08-02T14:59:23Z |

## Description

Displays several units of energy consumption for households, businesses, and industries in the City of Chicago during 2010. Electric  The data was aggregated from ComEd and Peoples Natural Gas by Accenture. Electrical and gas usage data comprises 88 percent of Chicago's buildings in 2010. The electricity data comprises 68 percent of overall electrical usage in the city while gas data comprises 81 percent of all gas consumption in Chicago for 2010.

Census blocks with less than 4 accounts is displayed at the Community Area without further geographic identifiers. This dataset also contains selected variables describing selected characteristics of the Census block population, physical housing, and occupancy.

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                | Data Type | Render Type |
| ======== | ============== | =================================== | =================================== | ========= | =========== |
| Yes      | series tag     | community_area_name                 | COMMUNITY AREA NAME                 | text      | text        |
| Yes      | numeric metric | census_block                        | CENSUS BLOCK                        | number    | number      |
| Yes      | series tag     | building_type                       | BUILDING TYPE                       | text      | text        |
| Yes      | series tag     | building_subtype                    | BUILDING_SUBTYPE                    | text      | text        |
| Yes      | numeric metric | kwh_january_2010                    | KWH JANUARY 2010                    | number    | number      |
| Yes      | numeric metric | kwh_february_2010                   | KWH FEBRUARY 2010                   | number    | number      |
| Yes      | numeric metric | kwh_march_2010                      | KWH MARCH 2010                      | number    | number      |
| Yes      | numeric metric | kwh_april_2010                      | KWH APRIL 2010                      | number    | number      |
| Yes      | numeric metric | kwh_may_2010                        | KWH MAY 2010                        | number    | number      |
| Yes      | numeric metric | kwh_june_2010                       | KWH JUNE 2010                       | number    | number      |
| Yes      | numeric metric | kwh_july_2010                       | KWH JULY 2010                       | number    | number      |
| Yes      | numeric metric | kwh_august_2010                     | KWH AUGUST 2010                     | number    | number      |
| Yes      | numeric metric | kwh_september_2010                  | KWH SEPTEMBER 2010                  | number    | number      |
| Yes      | numeric metric | kwh_october_2010                    | KWH OCTOBER 2010                    | number    | number      |
| Yes      | numeric metric | kwh_november_2010                   | KWH NOVEMBER 2010                   | number    | number      |
| Yes      | numeric metric | kwh_december_2010                   | KWH DECEMBER 2010                   | number    | number      |
| Yes      | numeric metric | total_kwh                           | TOTAL KWH                           | number    | number      |
| Yes      | series tag     | electricity_accounts                | ELECTRICITY ACCOUNTS                | text      | text        |
| Yes      | numeric metric | zero_kwh_accounts                   | ZERO KWH ACCOUNTS                   | number    | number      |
| Yes      | numeric metric | therm_january_2010                  | THERM JANUARY 2010                  | number    | number      |
| Yes      | numeric metric | therm_february_2010                 | THERM FEBRUARY 2010                 | number    | number      |
| Yes      | numeric metric | therm_march_2010                    | THERM MARCH 2010                    | number    | number      |
| Yes      | numeric metric | term_april_2010                     | TERM APRIL 2010                     | number    | number      |
| Yes      | numeric metric | therm_may_2010                      | THERM MAY 2010                      | number    | number      |
| Yes      | numeric metric | therm_june_2010                     | THERM JUNE 2010                     | number    | number      |
| Yes      | numeric metric | therm_july_2010                     | THERM JULY 2010                     | number    | number      |
| Yes      | numeric metric | therm_august_2010                   | THERM AUGUST 2010                   | number    | number      |
| Yes      | numeric metric | therm_september_2010                | THERM SEPTEMBER 2010                | number    | number      |
| Yes      | numeric metric | therm_october_2010                  | THERM OCTOBER 2010                  | number    | number      |
| Yes      | numeric metric | therm_november_2010                 | THERM NOVEMBER 2010                 | number    | number      |
| Yes      | numeric metric | therm_december_2010                 | THERM DECEMBER 2010                 | number    | number      |
| Yes      | numeric metric | total_therms                        | TOTAL THERMS                        | number    | number      |
| Yes      | series tag     | gas_accounts                        | GAS ACCOUNTS                        | text      | text        |
| Yes      | numeric metric | kwh_total_sqft                      | KWH TOTAL SQFT                      | number    | number      |
| Yes      | numeric metric | therms_total_sqft                   | THERMS TOTAL SQFT                   | number    | number      |
| Yes      | numeric metric | kwh_mean_2010                       | KWH MEAN 2010                       | number    | number      |
| Yes      | numeric metric | kwh_standard_deviation_2010         | KWH STANDARD DEVIATION 2010         | number    | number      |
| Yes      | numeric metric | kwh_minimum_2010                    | KWH MINIMUM 2010                    | number    | number      |
| Yes      | numeric metric | kwh_1st_quartile_2010               | KWH 1ST QUARTILE 2010               | number    | number      |
| Yes      | numeric metric | kwh_2nd_quartile_2010               | KWH 2ND QUARTILE 2010               | number    | number      |
| Yes      | numeric metric | kwh_3rd_quartile_2010               | KWH 3RD QUARTILE 2010               | number    | number      |
| Yes      | numeric metric | kwh_maximum_2010                    | KWH MAXIMUM 2010                    | number    | number      |
| Yes      | numeric metric | kwh_sqft_mean_2010                  | KWH SQFT MEAN 2010                  | number    | number      |
| Yes      | numeric metric | kwh_sqft_standard_deviation_2010    | KWH SQFT STANDARD DEVIATION 2010    | number    | number      |
| Yes      | numeric metric | kwh_sqft_minimum_2010               | KWH SQFT MINIMUM 2010               | number    | number      |
| Yes      | numeric metric | kwh_sqft_1st_quartile_2010          | KWH SQFT 1ST QUARTILE 2010          | number    | number      |
| Yes      | numeric metric | kwh_sqft_2nd_quartile_2010          | KWH SQFT 2ND QUARTILE 2010          | number    | number      |
| Yes      | numeric metric | kwh_sqft_3rd_quartile_2010          | KWH SQFT 3RD QUARTILE 2010          | number    | number      |
| Yes      | numeric metric | kwh_sqft_maximum_2010               | KWH SQFT MAXIMUM 2010               | number    | number      |
| Yes      | numeric metric | therm_mean_2010                     | THERM MEAN 2010                     | number    | number      |
| Yes      | numeric metric | therm_standard_deviation_2010       | THERM STANDARD DEVIATION 2010       | number    | number      |
| Yes      | numeric metric | therm_minimum_2010                  | THERM MINIMUM 2010                  | number    | number      |
| Yes      | numeric metric | therm_1st_quartile_2010             | THERM 1ST QUARTILE 2010             | number    | number      |
| Yes      | numeric metric | therm_2nd_quartile_2010             | THERM 2ND QUARTILE 2010             | number    | number      |
| Yes      | numeric metric | therm_3rd_quartile_2010             | THERM 3RD QUARTILE 2010             | number    | number      |
| Yes      | numeric metric | therm_maximum_2010                  | THERM MAXIMUM 2010                  | number    | number      |
| Yes      | numeric metric | therms_sqft_mean_2010               | THERMS SQFT MEAN 2010               | number    | number      |
| Yes      | numeric metric | therms_sqft_standard_deviation_2010 | THERMS SQFT STANDARD DEVIATION 2010 | number    | number      |
| Yes      | numeric metric | therms_sqft_minimum_2010            | THERMS SQFT MINIMUM 2010            | number    | number      |
| Yes      | numeric metric | therms_sqft_1st_quartile_2010       | THERMS SQFT 1ST QUARTILE 2010       | number    | number      |
| Yes      | numeric metric | therms_sqft_2nd_quartile_2010       | THERMS SQFT 2ND QUARTILE 2010       | number    | number      |
| Yes      | numeric metric | therms_sqft_3rd_quartile_2010       | THERMS SQFT 3RD QUARTILE 2010       | number    | number      |
| Yes      | numeric metric | therms_sqft_maximum_2010            | THERMS SQFT MAXIMUM 2010            | number    | number      |
| Yes      | numeric metric | total_population                    | TOTAL POPULATION                    | number    | number      |
| Yes      | numeric metric | total_units                         | TOTAL UNITS                         | number    | number      |
| Yes      | numeric metric | average_stories                     | AVERAGE STORIES                     | number    | number      |
| Yes      | numeric metric | average_building_age                | AVERAGE BUILDING AGE                | number    | number      |
| Yes      | numeric metric | average_housesize                   | AVERAGE HOUSESIZE                   | number    | number      |
| Yes      | numeric metric | occupied_units                      | OCCUPIED UNITS                      | number    | number      |
| Yes      | numeric metric | occupied_units_percentage           | OCCUPIED UNITS PERCENTAGE           | number    | number      |
| Yes      | numeric metric | renter_occupied_housing_units       | RENTER-OCCUPIED HOUSING UNITS       | number    | number      |
| Yes      | numeric metric | renter_occupied_housing_percentage  | RENTER-OCCUPIED HOUSING PERCENTAGE  | number    | number      |
| Yes      | numeric metric | ten_ohu_tot                         | OCCUPIED HOUSING UNITS              | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:8yq3-m6wp d:2010-01-01T00:00:00.000Z t:community_area_name="Archer Heights" t:gas_accounts=11 t:building_type=Residential t:building_subtype="Multi < 7" m:therms_sqft_minimum_2010=1382 m:therm_october_2010=252 m:zero_kwh_accounts=0 m:therms_sqft_1st_quartile_2010=1382 m:therms_sqft_standard_deviation_2010=490.89374275 m:therm_may_2010=502 m:occupied_units_percentage=0.9582 m:therm_march_2010=1400 m:therm_february_2010=2131 m:total_units=24 m:therm_1st_quartile_2010=1334 m:occupied_units=23 m:average_housesize=3.87 m:renter_occupied_housing_units=9 m:therm_3rd_quartile_2010=2306 m:therm_september_2010=197 m:therm_minimum_2010=1061 m:therms_sqft_maximum_2010=2650 m:therms_sqft_3rd_quartile_2010=2162 m:therm_july_2010=222 m:ten_ohu_tot=23 m:term_april_2010=620 m:average_building_age=71.33 m:therms_sqft_2nd_quartile_2010=1779 m:therm_maximum_2010=2487 m:renter_occupied_housing_percentage=0.391 m:therm_mean_2010=1819.5 m:therm_june_2010=224 m:average_stories=2 m:therm_2nd_quartile_2010=1864.5 m:therm_august_2010=187 m:census_block=170315704001006 m:total_therms=10917 m:therms_sqft_mean_2010=1855.67 m:therms_total_sqft=11134 m:total_population=89 m:therm_november_2010=744 m:therm_january_2010=2326 m:therm_standard_deviation_2010=547.64322328 m:therm_december_2010=2112

series e:8yq3-m6wp d:2010-01-01T00:00:00.000Z t:community_area_name=Ashburn t:electricity_accounts=8 t:building_type=Residential t:building_subtype="Multi 7+" m:zero_kwh_accounts=3 m:kwh_1st_quartile_2010=8886 m:kwh_january_2010=7334 m:kwh_february_2010=7741 m:kwh_april_2010=4284 m:kwh_sqft_3rd_quartile_2010=10892 m:kwh_sqft_maximum_2010=10892 m:occupied_units_percentage=0.9254 m:total_units=67 m:average_housesize=1.81 m:kwh_december_2010=19676 m:occupied_units=62 m:renter_occupied_housing_units=50 m:kwh_march_2010=4214 m:kwh_3rd_quartile_2010=51815 m:kwh_mean_2010=27354.67 m:kwh_2nd_quartile_2010=21363 m:kwh_sqft_2nd_quartile_2010=10892 m:ten_ohu_tot=62 m:kwh_sqft_minimum_2010=10892 m:average_building_age=41 m:renter_occupied_housing_percentage=0.8059 m:kwh_september_2010=3357 m:kwh_june_2010=4273 m:kwh_sqft_mean_2010=10892 m:kwh_maximum_2010=51815 m:kwh_total_sqft=10892 m:kwh_october_2010=5540 m:kwh_standard_deviation_2010=22082.794487 m:kwh_sqft_1st_quartile_2010=10892 m:average_stories=2 m:census_block=170317005014004 m:total_kwh=82064 m:total_population=112 m:kwh_november_2010=15774 m:kwh_may_2010=2518 m:kwh_july_2010=4566 m:kwh_minimum_2010=8886 m:kwh_august_2010=2787

series e:8yq3-m6wp d:2010-01-01T00:00:00.000Z t:community_area_name="Auburn Gresham" t:gas_accounts=4 t:building_type=Commercial t:building_subtype="Multi < 7" m:therms_sqft_minimum_2010=7347 m:zero_kwh_accounts=7 m:therms_sqft_1st_quartile_2010=7347 m:therm_may_2010=486 m:occupied_units_percentage=0.7082 m:therm_march_2010=1507 m:therm_february_2010=1388 m:total_units=48 m:occupied_units=34 m:therm_1st_quartile_2010=94 m:average_housesize=3 m:renter_occupied_housing_units=23 m:therm_3rd_quartile_2010=5963 m:therm_minimum_2010=94 m:therms_sqft_maximum_2010=7347 m:therms_sqft_3rd_quartile_2010=7347 m:therm_july_2010=18 m:ten_ohu_tot=34 m:term_april_2010=701 m:average_building_age=86 m:therms_sqft_2nd_quartile_2010=7347 m:therm_maximum_2010=5963 m:renter_occupied_housing_percentage=0.6759 m:therm_mean_2010=3028.5 m:therm_june_2010=380 m:average_stories=3 m:therm_2nd_quartile_2010=3028.5 m:therm_august_2010=16 m:census_block=170317105001006 m:total_therms=6057 m:therms_sqft_mean_2010=7347 m:therms_total_sqft=7347 m:total_population=102 m:therm_january_2010=1561 m:therm_standard_deviation_2010=4150.0096988
```

## Meta Commands

```ls
metric m:census_block p:long l:"CENSUS BLOCK" d:"Census Block number obtained in the address matching/geocoding algorithms. Blank Census Blocks correspond to data that was aggregated to the Community Area due to privacy issues." t:dataTypeName=number

metric m:kwh_january_2010 p:integer l:"KWH JANUARY 2010" d:"Kilowatt hours (kWh) for January 2010" t:dataTypeName=number

metric m:kwh_february_2010 p:integer l:"KWH FEBRUARY 2010" d:"Kilowatt hours (kWh) for February 2010" t:dataTypeName=number

metric m:kwh_march_2010 p:integer l:"KWH MARCH 2010" d:"Kilowatt hours (kWh) for March 2010" t:dataTypeName=number

metric m:kwh_april_2010 p:integer l:"KWH APRIL 2010" d:"Kilowatt hours (kWh) for April 2010" t:dataTypeName=number

metric m:kwh_may_2010 p:integer l:"KWH MAY 2010" d:"Kilowatt hours (kWh) for June 2010" t:dataTypeName=number

metric m:kwh_june_2010 p:integer l:"KWH JUNE 2010" t:dataTypeName=number

metric m:kwh_july_2010 p:integer l:"KWH JULY 2010" d:"Kilowatt hours (kWh) for July 2010" t:dataTypeName=number

metric m:kwh_august_2010 p:integer l:"KWH AUGUST 2010" d:"Kilowatt hours (kWh) for August 2010" t:dataTypeName=number

metric m:kwh_september_2010 p:integer l:"KWH SEPTEMBER 2010" d:"Kilowatt hours (kWh) for September 2010" t:dataTypeName=number

metric m:kwh_october_2010 p:integer l:"KWH OCTOBER 2010" d:"Kilowatt hours (kWh) for October 2010" t:dataTypeName=number

metric m:kwh_november_2010 p:integer l:"KWH NOVEMBER 2010" d:"Kilowatt hours (kWh) for November 2010" t:dataTypeName=number

metric m:kwh_december_2010 p:integer l:"KWH DECEMBER 2010" d:"Kilowatt hours (kWh) for December 2010" t:dataTypeName=number

metric m:total_kwh p:integer l:"TOTAL KWH" d:"Total 2010 kWh from ComEd accounts." t:dataTypeName=number

metric m:zero_kwh_accounts p:integer l:"ZERO KWH ACCOUNTS" d:"Number of accounts with 0 kilowatt hours amounts for 12 months in 2010 from ComEd." t:dataTypeName=number

metric m:therm_january_2010 p:integer l:"THERM JANUARY 2010" d:"Therm consumption for January 2010." t:dataTypeName=number

metric m:therm_february_2010 p:integer l:"THERM FEBRUARY 2010" d:"Therm consumption for February 2010." t:dataTypeName=number

metric m:therm_march_2010 p:integer l:"THERM MARCH 2010" d:"Therm consumption for March 2010." t:dataTypeName=number

metric m:term_april_2010 p:integer l:"TERM APRIL 2010" d:"Therm consumption for April 2010." t:dataTypeName=number

metric m:therm_may_2010 p:integer l:"THERM MAY 2010" d:"Therm consumption for May 2010." t:dataTypeName=number

metric m:therm_june_2010 p:integer l:"THERM JUNE 2010" d:"Therm consumption for June 2010." t:dataTypeName=number

metric m:therm_july_2010 p:integer l:"THERM JULY 2010" d:"Therm consumption for July 2010." t:dataTypeName=number

metric m:therm_august_2010 p:integer l:"THERM AUGUST 2010" d:"Therm consumption for August 2010." t:dataTypeName=number

metric m:therm_september_2010 p:integer l:"THERM SEPTEMBER 2010" d:"Therm consumption for September 2010." t:dataTypeName=number

metric m:therm_october_2010 p:integer l:"THERM OCTOBER 2010" d:"Therm consumption for October 2010." t:dataTypeName=number

metric m:therm_november_2010 p:integer l:"THERM NOVEMBER 2010" d:"Therm consumption for November 2010." t:dataTypeName=number

metric m:therm_december_2010 p:integer l:"THERM DECEMBER 2010" d:"Therm consumption for December 2010." t:dataTypeName=number

metric m:total_therms p:integer l:"TOTAL THERMS" d:"Total 2010 Therms from Peoples accounts." t:dataTypeName=number

metric m:kwh_total_sqft p:integer l:"KWH TOTAL SQFT" d:"Total square footage associated with the electric energy usage in 2010 according to Cook County Assessor Records." t:dataTypeName=number

metric m:therms_total_sqft p:integer l:"THERMS TOTAL SQFT" d:"Total square footage associated with the natural gas energy usage for Kilowatt Hours in 2010 according to Cook County Assessor Records." t:dataTypeName=number

metric m:kwh_mean_2010 p:double l:"KWH MEAN 2010" d:"Average Total KWHs for 2010." t:dataTypeName=number

metric m:kwh_standard_deviation_2010 p:double l:"KWH STANDARD DEVIATION 2010" t:dataTypeName=number

metric m:kwh_minimum_2010 p:integer l:"KWH MINIMUM 2010" t:dataTypeName=number

metric m:kwh_1st_quartile_2010 p:double l:"KWH 1ST QUARTILE 2010" t:dataTypeName=number

metric m:kwh_2nd_quartile_2010 p:double l:"KWH 2ND QUARTILE 2010" t:dataTypeName=number

metric m:kwh_3rd_quartile_2010 p:double l:"KWH 3RD QUARTILE 2010" t:dataTypeName=number

metric m:kwh_maximum_2010 p:integer l:"KWH MAXIMUM 2010" t:dataTypeName=number

metric m:kwh_sqft_mean_2010 p:double l:"KWH SQFT MEAN 2010" d:"Average kWh per square foot in 2010." t:dataTypeName=number

metric m:kwh_sqft_standard_deviation_2010 p:double l:"KWH SQFT STANDARD DEVIATION 2010" t:dataTypeName=number

metric m:kwh_sqft_minimum_2010 p:integer l:"KWH SQFT MINIMUM 2010" t:dataTypeName=number

metric m:kwh_sqft_1st_quartile_2010 p:integer l:"KWH SQFT 1ST QUARTILE 2010" t:dataTypeName=number

metric m:kwh_sqft_2nd_quartile_2010 p:double l:"KWH SQFT 2ND QUARTILE 2010" t:dataTypeName=number

metric m:kwh_sqft_3rd_quartile_2010 p:integer l:"KWH SQFT 3RD QUARTILE 2010" t:dataTypeName=number

metric m:kwh_sqft_maximum_2010 p:integer l:"KWH SQFT MAXIMUM 2010" t:dataTypeName=number

metric m:therm_mean_2010 p:double l:"THERM MEAN 2010" d:"Average Total Therms for 2010." t:dataTypeName=number

metric m:therm_standard_deviation_2010 p:double l:"THERM STANDARD DEVIATION 2010" t:dataTypeName=number

metric m:therm_minimum_2010 p:integer l:"THERM MINIMUM 2010" t:dataTypeName=number

metric m:therm_1st_quartile_2010 p:double l:"THERM 1ST QUARTILE 2010" t:dataTypeName=number

metric m:therm_2nd_quartile_2010 p:double l:"THERM 2ND QUARTILE 2010" t:dataTypeName=number

metric m:therm_3rd_quartile_2010 p:double l:"THERM 3RD QUARTILE 2010" t:dataTypeName=number

metric m:therm_maximum_2010 p:integer l:"THERM MAXIMUM 2010" t:dataTypeName=number

metric m:therms_sqft_mean_2010 p:double l:"THERMS SQFT MEAN 2010" d:"Average Therms per square foot in 2010." t:dataTypeName=number

metric m:therms_sqft_standard_deviation_2010 p:double l:"THERMS SQFT STANDARD DEVIATION 2010" t:dataTypeName=number

metric m:therms_sqft_minimum_2010 p:integer l:"THERMS SQFT MINIMUM 2010" t:dataTypeName=number

metric m:therms_sqft_1st_quartile_2010 p:integer l:"THERMS SQFT 1ST QUARTILE 2010" t:dataTypeName=number

metric m:therms_sqft_2nd_quartile_2010 p:double l:"THERMS SQFT 2ND QUARTILE 2010" t:dataTypeName=number

metric m:therms_sqft_3rd_quartile_2010 p:integer l:"THERMS SQFT 3RD QUARTILE 2010" t:dataTypeName=number

metric m:therms_sqft_maximum_2010 p:integer l:"THERMS SQFT MAXIMUM 2010" t:dataTypeName=number

metric m:total_population p:integer l:"TOTAL POPULATION" d:"Total population from Census 2010 report (QT-P6) Race alone or in combination and Hispanic or Latino 2010." t:dataTypeName=number

metric m:total_units p:integer l:"TOTAL UNITS" d:"Total number of housing units from census 2010 report (H1) Occupancy Status." t:dataTypeName=number

metric m:average_stories p:float l:"AVERAGE STORIES" d:"Average number of stories based on data from Cook County Assessor's Office." t:dataTypeName=number

metric m:average_building_age p:float l:"AVERAGE BUILDING AGE" d:"Average Age of the buildings based on data from Cook County Assessor's Office." t:dataTypeName=number

metric m:average_housesize p:float l:"AVERAGE HOUSESIZE" d:"Average household size from Census 2010 report QT-P11 Households and Families." t:dataTypeName=number

metric m:occupied_units p:integer l:"OCCUPIED UNITS" d:"Number of housing units that are occupied from census 2010 report (H1) Occupancy Status." t:dataTypeName=number

metric m:occupied_units_percentage p:float l:"OCCUPIED UNITS PERCENTAGE" t:dataTypeName=number

metric m:renter_occupied_housing_units p:integer l:"RENTER-OCCUPIED HOUSING UNITS" d:"Number of housing units that are renter occupied from Census 2010 report (QT-H2) Tenure, Household Size and Age of Householder." t:dataTypeName=number

metric m:renter_occupied_housing_percentage p:float l:"RENTER-OCCUPIED HOUSING PERCENTAGE" d:"Percentage of occupied housing units that are renters from Census report (QT-H2) Tenure, Household Size and Age of Householder" t:dataTypeName=number

metric m:ten_ohu_tot p:integer l:"OCCUPIED HOUSING UNITS" d:"Number of occupied housing units from Census 2010 report (QT-H2) Tenure, Household Size and Age of Householder." t:dataTypeName=number

entity e:8yq3-m6wp l:"Energy Usage 2010" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/8yq3-m6wp

property e:8yq3-m6wp t:meta.view v:id=8yq3-m6wp v:category="Environment & Sustainable Development" v:attributionLink=http://www.cityofchicago.org v:averageRating=100 v:name="Energy Usage 2010" v:attribution="City of Chicago"

property e:8yq3-m6wp t:meta.view.owner v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"

property e:8yq3-m6wp t:meta.view.tableauthor v:id=3qqc-w7ag v:profileImageUrlMedium=/api/users/3qqc-w7ag/profile_images/THUMB v:profileImageUrlLarge=/api/users/3qqc-w7ag/profile_images/LARGE v:screenName="Tom Schenk Jr" v:profileImageUrlSmall=/api/users/3qqc-w7ag/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491330280 v:displayName="Tom Schenk Jr"
```

## Top Records

```ls
| community_area_name | census_block    | building_type | building_subtype | kwh_january_2010 | kwh_february_2010 | kwh_march_2010 | kwh_april_2010 | kwh_may_2010 | kwh_june_2010 | kwh_july_2010 | kwh_august_2010 | kwh_september_2010 | kwh_october_2010 | kwh_november_2010 | kwh_december_2010 | total_kwh | electricity_accounts | zero_kwh_accounts | therm_january_2010 | therm_february_2010 | therm_march_2010 | term_april_2010 | therm_may_2010 | therm_june_2010 | therm_july_2010 | therm_august_2010 | therm_september_2010 | therm_october_2010 | therm_november_2010 | therm_december_2010 | total_therms | gas_accounts | kwh_total_sqft | therms_total_sqft | kwh_mean_2010 | kwh_standard_deviation_2010 | kwh_minimum_2010 | kwh_1st_quartile_2010 | kwh_2nd_quartile_2010 | kwh_3rd_quartile_2010 | kwh_maximum_2010 | kwh_sqft_mean_2010 | kwh_sqft_standard_deviation_2010 | kwh_sqft_minimum_2010 | kwh_sqft_1st_quartile_2010 | kwh_sqft_2nd_quartile_2010 | kwh_sqft_3rd_quartile_2010 | kwh_sqft_maximum_2010 | therm_mean_2010 | therm_standard_deviation_2010 | therm_minimum_2010 | therm_1st_quartile_2010 | therm_2nd_quartile_2010 | therm_3rd_quartile_2010 | therm_maximum_2010 | therms_sqft_mean_2010 | therms_sqft_standard_deviation_2010 | therms_sqft_minimum_2010 | therms_sqft_1st_quartile_2010 | therms_sqft_2nd_quartile_2010 | therms_sqft_3rd_quartile_2010 | therms_sqft_maximum_2010 | total_population | total_units | average_stories | average_building_age | average_housesize | occupied_units | occupied_units_percentage | renter_occupied_housing_units | renter_occupied_housing_percentage | ten_ohu_tot | 
| =================== | =============== | ============= | ================ | ================ | ================= | ============== | ============== | ============ | ============= | ============= | =============== | ================== | ================ | ================= | ================= | ========= | ==================== | ================= | ================== | =================== | ================ | =============== | ============== | =============== | =============== | ================= | ==================== | ================== | =================== | =================== | ============ | ============ | ============== | ================= | ============= | =========================== | ================ | ===================== | ===================== | ===================== | ================ | ================== | ================================ | ===================== | ========================== | ========================== | ========================== | ===================== | =============== | ============================= | ================== | ======================= | ======================= | ======================= | ================== | ===================== | =================================== | ======================== | ============================= | ============================= | ============================= | ======================== | ================ | =========== | =============== | ==================== | ================= | ============== | ========================= | ============================= | ================================== | =========== | 
| Archer Heights      | 170315704001006 | Residential   | Multi < 7        |                  |                   |                |                |              |               |               |                 |                    |                  |                   |                   |           |                      | 0                 | 2326               | 2131                | 1400             | 620             | 502            | 224             | 222             | 187               | 197                  | 252                | 744                 | 2112                | 10917        | 11           |                | 11134             |               |                             |                  |                       |                       |                       |                  |                    |                                  |                       |                            |                            |                            |                       | 1819.5          | 547.64322328                  | 1061               | 1334                    | 1864.5                  | 2306                    | 2487               | 1855.67               | 490.89374275                        | 1382                     | 1382                          | 1779                          | 2162                          | 2650                     | 89               | 24          | 2.0             | 71.33                | 3.87              | 23             | 0.9582                    | 9                             | 0.391                              | 23          | 
| Ashburn             | 170317005014004 | Residential   | Multi 7+         | 7334             | 7741              | 4214           | 4284           | 2518         | 4273          | 4566          | 2787            | 3357               | 5540             | 15774             | 19676             | 82064     | 8                    | 3                 |                    |                     |                  |                 |                |                 |                 |                   |                      |                    |                     |                     |              |              | 10892          |                   | 27354.67      | 22082.794487                | 8886             | 8886                  | 21363                 | 51815                 | 51815            | 10892.0            |                                  | 10892                 | 10892                      | 10892                      | 10892                      | 10892                 |                 |                               |                    |                         |                         |                         |                    |                       |                                     |                          |                               |                               |                               |                          | 112              | 67          | 2.0             | 41.0                 | 1.81              | 62             | 0.9254                    | 50                            | 0.8059                             | 62          | 
| Auburn Gresham      | 170317105001006 | Commercial    | Multi < 7        |                  |                   |                |                |              |               |               |                 |                    |                  |                   |                   |           |                      | 7                 | 1561               | 1388                | 1507             | 701             | 486            | 380             | 18              | 16                |                      |                    |                     |                     | 6057         | 4            |                | 7347              |               |                             |                  |                       |                       |                       |                  |                    |                                  |                       |                            |                            |                            |                       | 3028.5          | 4150.0096988                  | 94                 | 94                      | 3028.5                  | 5963                    | 5963               | 7347.0                |                                     | 7347                     | 7347                          | 7347                          | 7347                          | 7347                     | 102              | 48          | 3.0             | 86.0                 | 3                 | 34             | 0.7082                    | 23                            | 0.6759                             | 34          | 
| Austin              | 170312503003003 | Commercial    | Multi < 7        |                  |                   |                |                |              |               |               |                 |                    |                  |                   |                   |           |                      | 2                 |                    |                     |                  |                 |                |                 |                 |                   |                      |                    | 9                   | 391                 | 400          | Less than 4  |                | 2146              |               |                             |                  |                       |                       |                       |                  |                    |                                  |                       |                            |                            |                            |                       | 400.0           |                               | 400                | 400                     | 400                     | 400                     | 400                | 2146.0                |                                     | 2146                     | 2146                          | 2146                          | 2146                          | 2146                     | 121              | 56          | 2.0             | 84.0                 | 2.95              | 41             | 0.7321                    | 32                            | 0.78                               | 41          | 
| Austin              | 170312504002008 | Commercial    | Multi < 7        |                  |                   |                |                |              |               |               |                 |                    |                  |                   |                   |           |                      | 3                 | 310                | 268                 | 163              | 77              | 57             | 23              | 19              | 8                 | 14                   | 10                 |                     |                     | 949          | Less than 4  |                | 2146              |               |                             |                  |                       |                       |                       |                  |                    |                                  |                       |                            |                            |                            |                       | 949.0           |                               | 949                | 949                     | 949                     | 949                     | 949                | 2146.0                |                                     | 2146                     | 2146                          | 2146                          | 2146                          | 2146                     | 62               | 23          | 2.0             | 85.0                 | 3.26              | 19             | 0.8261                    | 11                            | 0.579                              | 19          | 
| Austin              | 170312517001044 | Commercial    | Commercial       | 0                | 0                 | 0              | 0              | 0            | 0             | 0             | 819             | 619                | 416              | 138               | 2                 | 1994      | Less than 4          | 1                 |                    |                     |                  |                 |                |                 |                 |                   |                      |                    |                     |                     |              |              | 1512           |                   | 1994.0        |                             | 1994             | 1994                  | 1994                  | 1994                  | 1994             | 1512.0             |                                  | 1512                  | 1512                       | 1512                       | 1512                       | 1512                  |                 |                               |                    |                         |                         |                         |                    |                       |                                     |                          |                               |                               |                               |                          | 54               | 18          | 2.0             | 131.0                | 3                 | 18             | 1.0                       | 10                            | 0.556                              | 18          | 
| Austin              | 170312518003009 | Commercial    | Commercial       |                  |                   |                |                |              |               |               |                 |                    |                  |                   |                   |           |                      | 0                 | 3041               | 2680                | 1151             | 373             | 124            | 26              | 29              | 25                | 49                   | 177                | 670                 | 3895                | 12240        | Less than 4  |                | 69800             |               |                             |                  |                       |                       |                       |                  |                    |                                  |                       |                            |                            |                            |                       | 6120.0          | 3505.8354211                  | 3641               | 3641                    | 6120                    | 8599                    | 8599               | 34900.0               | 32244.069222                        | 12100                    | 12100                         | 34900                         | 57700                         | 57700                    | 0                | 0           | 1.0             | 54.0                 | 0                 | 0              |                           | 0                             |                                    | 0           | 
| Austin              | 170312520004000 | Commercial    | Multi < 7        | 1470             | 1325              | 294            | 391            | 366          | 2204          | 2345          | 2032            | 920                | 586              | 705               | 785               | 13423     | Less than 4          | 3                 |                    |                     |                  |                 |                |                 |                 |                   |                      |                    |                     |                     |              |              | 1988           |                   | 13423.0       |                             | 13423            | 13423                 | 13423                 | 13423                 | 13423            | 1988.0             |                                  | 1988                  | 1988                       | 1988                       | 1988                       | 1988                  |                 |                               |                    |                         |                         |                         |                    |                       |                                     |                          |                               |                               |                               |                          | 64               | 63          | 2.0             | 131.0                | 1.02              | 59             | 0.9365                    | 59                            | 1.0                                | 59          | 
| Austin              | 170312521011000 | Residential   | Multi 7+         | 2461             | 4888              | 2893           | 2737           | 2350         | 3037          | 3874          | 4861            | 5180               | 2984             | 2635              | 3597              | 41497     | 6                    | 0                 |                    |                     |                  |                 |                |                 |                 |                   |                      |                    |                     |                     |              |              | 4500           |                   | 41497.0       |                             | 41497            | 41497                 | 41497                 | 41497                 | 41497            | 4500.0             |                                  | 4500                  | 4500                       | 4500                       | 4500                       | 4500                  |                 |                               |                    |                         |                         |                         |                    |                       |                                     |                          |                               |                               |                               |                          | 79               | 31          | 3.0             | 99.0                 | 2.93              | 27             | 0.871                     | 27                            | 1.0                                | 27          | 
| Austin              | 170312521011008 | Residential   | Multi 7+         | 0                | 0                 | 0              | 0              | 0            | 511           | 904           | 1818            | 1968               | 738              | 450               | 2207              | 8596      | Less than 4          | 0                 |                    |                     |                  |                 |                |                 |                 |                   |                      |                    |                     |                     |              |              | 4500           |                   | 8596.0        |                             | 8596             | 8596                  | 8596                  | 8596                  | 8596             | 4500.0             |                                  | 4500                  | 4500                       | 4500                       | 4500                       | 4500                  |                 |                               |                    |                         |                         |                         |                    |                       |                                     |                          |                               |                               |                               |                          | 84               | 33          | 3.0             | 99.0                 | 3.82              | 22             | 0.6667                    | 16                            | 0.727                              | 22          | 
```