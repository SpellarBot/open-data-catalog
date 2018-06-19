# MDOT Performance Dashboard - Quarterly Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/mdot-performance-dashboard-quarterly-data) |
| Metadata | [Link](https://data.maryland.gov/api/views/eicu-xtw4) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/eicu-xtw4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/eicu-xtw4/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | eicu-xtw4 |
| Name | MDOT Performance Dashboard - Quarterly Data |
| Attribution | Maryland Department of Transportation |
| Category | Transportation |
| Created | 2016-07-28T21:35:01Z |
| Publication Date | 2017-01-12T15:32:08Z |

## Description

Contains quarterly performance data regarding average customer wait times at MVA branch offices, traffic fatalities on all roads in Maryland, and average time to certify new MBE Program applicants

## Columns

```ls
| Included | Schema Type    | Field Name                                                 | Name                                                              | Data Type     | Render Type   |
| ======== | ============== | ========================================================== | ================================================================= | ============= | ============= |
| Yes      | time           | date_for_calendar_year_columns                             | Date for Fiscal Year Measure                                      | calendar_date | calendar_date |
| No       |                | year                                                       | Year                                                              | number        | text          |
| No       |                | quarter                                                    | Quarter                                                           | text          | text          |
| No       |                | date_label                                                 | Date Label                                                        | text          | text          |
| Yes      | numeric metric | average_mva_branch_office_customer_wait_time_in_minutes_fy | Average MVA Branch Office Customer Wait Time (in minutes) (FY)    | number        | number        |
| No       |                | date                                                       | Date for Calendar Year Measure                                    | calendar_date | calendar_date |
| Yes      | numeric metric | number_of_traffic_related_fatalities_on_all_roads_in_md_cy | Number of Traffic-Related Fatalities on all Roads in MD (CY)      | number        | number        |
| Yes      | numeric metric | average_time_to_certify_new_mbe_program_applicants_cy      | Average Time to Certify new MBE Program Applicants (in days) (CY) | number        | number        |
```

## Time Field

```ls
Value = date_for_calendar_year_columns
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = quarter,date_label,date,year
```

## Data Commands

```ls
series e:eicu-xtw4 d:2012-03-31T00:00:00.000Z m:average_mva_branch_office_customer_wait_time_in_minutes_fy=20.88 m:number_of_traffic_related_fatalities_on_all_roads_in_md_cy=138

series e:eicu-xtw4 d:2010-09-30T00:00:00.000Z m:average_mva_branch_office_customer_wait_time_in_minutes_fy=30.37 m:number_of_traffic_related_fatalities_on_all_roads_in_md_cy=92

series e:eicu-xtw4 d:2010-12-31T00:00:00.000Z m:average_mva_branch_office_customer_wait_time_in_minutes_fy=21.17 m:number_of_traffic_related_fatalities_on_all_roads_in_md_cy=117
```

## Meta Commands

```ls
metric m:average_mva_branch_office_customer_wait_time_in_minutes_fy p:float l:"Average MVA Branch Office Customer Wait Time (in minutes) (FY)" t:dataTypeName=number

metric m:number_of_traffic_related_fatalities_on_all_roads_in_md_cy p:integer l:"Number of Traffic-Related Fatalities on all Roads in MD (CY)" t:dataTypeName=number

metric m:average_time_to_certify_new_mbe_program_applicants_cy p:integer l:"Average Time to Certify new MBE Program Applicants (in days) (CY)" t:dataTypeName=number

entity e:eicu-xtw4 l:"MDOT Performance Dashboard - Quarterly Data" t:attribution="Maryland Department of Transportation" t:url=https://data.maryland.gov/api/views/eicu-xtw4

property e:eicu-xtw4 t:meta.view v:id=eicu-xtw4 v:category=Transportation v:averageRating=0 v:name="MDOT Performance Dashboard - Quarterly Data" v:attribution="Maryland Department of Transportation"

property e:eicu-xtw4 t:meta.view.license v:name="Public Domain"

property e:eicu-xtw4 t:meta.view.owner v:id=w3wv-wxfw v:screenName="Mike Haley" v:displayName="Mike Haley"

property e:eicu-xtw4 t:meta.view.tableauthor v:id=w3wv-wxfw v:screenName="Mike Haley" v:roleName=editor v:displayName="Mike Haley"
```

## Top Records

```ls
| date_for_calendar_year_columns | year | quarter | date_label | average_mva_branch_office_customer_wait_time_in_minutes_fy | date                | number_of_traffic_related_fatalities_on_all_roads_in_md_cy | average_time_to_certify_new_mbe_program_applicants_cy | 
| ============================== | ==== | ======= | ========== | ========================================================== | =================== | ========================================================== | ===================================================== | 
| 2012-03-31T00:00:00            | 2012 | Q3      | Q3 2012    | 20.88                                                      | 2012-07-01T00:00:00 | 138                                                        |                                                       | 
| 2010-09-30T00:00:00            | 2011 | Q1      | Q1 2011    | 30.37                                                      | 2011-03-31T00:00:00 | 92                                                         |                                                       | 
| 2010-12-31T00:00:00            | 2011 | Q2      | Q2 2011    | 21.17                                                      | 2011-06-30T00:00:00 | 117                                                        |                                                       | 
| 2011-03-31T00:00:00            | 2011 | Q3      | Q3 2011    | 19.66                                                      | 2011-09-30T00:00:00 | 133                                                        |                                                       | 
| 2011-06-30T00:00:00            | 2011 | Q4      | Q4 2011    | 16.95                                                      | 2011-12-31T00:00:00 | 146                                                        |                                                       | 
| 2011-09-30T00:00:00            | 2012 | Q1      | Q1 2012    | 20.41                                                      | 2012-03-31T00:00:00 | 116                                                        |                                                       | 
| 2011-12-31T00:00:00            | 2012 | Q2      | Q2 2012    | 16.62                                                      | 2012-06-30T00:00:00 | 128                                                        |                                                       | 
| 2012-06-30T00:00:00            | 2012 | Q4      | Q4 2012    | 21.52                                                      | 2012-12-31T00:00:00 | 129                                                        |                                                       | 
| 2012-09-30T00:00:00            | 2013 | Q1      | Q1 2013    | 26.25                                                      | 2013-03-31T00:00:00 | 96                                                         |                                                       | 
| 2012-12-31T00:00:00            | 2013 | Q2      | Q2 2013    | 23.19                                                      | 2013-06-30T00:00:00 | 133                                                        |                                                       | 
```