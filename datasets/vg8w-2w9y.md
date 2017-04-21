# Performance Metrics - Family & Support Services - Homeless Shelter System Monthly Utilization

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-family-support-services-homeless-shelter-system-monthly-utilization-8d7ff) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/vg8w-2w9y) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/vg8w-2w9y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/vg8w-2w9y/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | vg8w-2w9y |
| Name | Performance Metrics - Family & Support Services - Homeless Shelter System Monthly Utilization |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, human services |
| Created | 2011-08-01T16:16:31Z |
| Publication Date | 2014-09-02T22:06:50Z |

## Description

Homeless Shelter System Monthly Utilization
This metric tracks the number of shelter beds used by individuals and families per month. Overnight shelters provide nightly shelter for individuals for up to 12 consecutive hours and do not serve families with children. Interim shelters house families and individuals for up to 120 days.  DFSS coordinates activities and funding to increase the availability of permanent and supportive housing services in Chicago. DFSS funds community based agencies that provide services to persons and families who are homeless or at imminent risk of homelessness so they can sustain safe and secure housing in the effort to achieve self-sufficiency.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| Yes      | numeric metric | sort                                       | Sort                                       | number    | number      |
| Yes      | series tag     | month                                      | Month                                      | text      | text        |
| Yes      | time           | year                                       | Year                                       | number    | text        |
| Yes      | numeric metric | interim_shelter_beds_used                  | Interim Shelter Beds Used                  | number    | number      |
| Yes      | numeric metric | overnight_shelter_beds_used                | Overnight Shelter Beds Used                | number    | number      |
| Yes      | numeric metric | total_interim_beds                         | Total Interim Beds                         | number    | number      |
| Yes      | numeric metric | total_overnight_beds                       | Total Overnight Beds                       | number    | number      |
| Yes      | numeric metric | percent_of_interim_shelter_beds_utilized   | Percent of Interim Shelter Beds Utilized   | percent   | percent     |
| Yes      | numeric metric | percent_of_shelter_beds_utilized_overnight | Percent of Shelter Beds Utilized Overnight | percent   | percent     |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:vg8w-2w9y d:2011-01-01T00:00:00.000Z t:month=11-Jan m:percent_of_interim_shelter_beds_utilized=91.9 m:sort=1 m:total_interim_beds=2920 m:total_overnight_beds=541 m:overnight_shelter_beds_used=467 m:interim_shelter_beds_used=2684 m:percent_of_shelter_beds_utilized_overnight=86.3

series e:vg8w-2w9y d:2011-01-01T00:00:00.000Z t:month=11-Feb m:percent_of_interim_shelter_beds_utilized=83.7 m:sort=2 m:total_interim_beds=2973 m:total_overnight_beds=541 m:overnight_shelter_beds_used=485 m:interim_shelter_beds_used=2488 m:percent_of_shelter_beds_utilized_overnight=89.6

series e:vg8w-2w9y d:2011-01-01T00:00:00.000Z t:month=11-Mar m:percent_of_interim_shelter_beds_utilized=89.9 m:sort=3 m:total_interim_beds=2973 m:total_overnight_beds=541 m:overnight_shelter_beds_used=465 m:interim_shelter_beds_used=2673 m:percent_of_shelter_beds_utilized_overnight=86
```

## Meta Commands

```ls
metric m:sort p:integer l:Sort t:dataTypeName=number

metric m:interim_shelter_beds_used p:integer l:"Interim Shelter Beds Used" t:dataTypeName=number

metric m:overnight_shelter_beds_used p:integer l:"Overnight Shelter Beds Used" t:dataTypeName=number

metric m:total_interim_beds p:integer l:"Total Interim Beds" t:dataTypeName=number

metric m:total_overnight_beds p:integer l:"Total Overnight Beds" t:dataTypeName=number

metric m:percent_of_interim_shelter_beds_utilized p:float l:"Percent of Interim Shelter Beds Utilized" t:dataTypeName=percent

metric m:percent_of_shelter_beds_utilized_overnight p:float l:"Percent of Shelter Beds Utilized Overnight" t:dataTypeName=percent

entity e:vg8w-2w9y l:"Performance Metrics - Family & Support Services - Homeless Shelter System Monthly Utilization" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/vg8w-2w9y

property e:vg8w-2w9y t:meta.view v:id=vg8w-2w9y v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Family & Support Services - Homeless Shelter System Monthly Utilization" v:attribution="City of Chicago"

property e:vg8w-2w9y t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:vg8w-2w9y t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| sort | month  | year | interim_shelter_beds_used | overnight_shelter_beds_used | total_interim_beds | total_overnight_beds | percent_of_interim_shelter_beds_utilized | percent_of_shelter_beds_utilized_overnight | 
| ==== | ====== | ==== | ========================= | =========================== | ================== | ==================== | ======================================== | ========================================== | 
| 1    | 11-Jan | 2011 | 2684                      | 467                         | 2920               | 541                  | 91.90                                    | 86.30                                      | 
| 2    | 11-Feb | 2011 | 2488                      | 485                         | 2973               | 541                  | 83.70                                    | 89.60                                      | 
| 3    | 11-Mar | 2011 | 2673                      | 465                         | 2973               | 541                  | 89.90                                    | 86.00                                      | 
| 4    | 11-Apr | 2011 | 2584                      | 445                         | 2973               | 541                  | 86.90                                    | 82.30                                      | 
| 5    | 11-May | 2011 | 2564                      | 465                         | 2973               | 541                  | 86.20                                    | 86.00                                      | 
| 6    | 11-Jun | 2011 | 2737                      | 489                         | 2973               | 541                  | 92.10                                    | 90.40                                      | 
| 7    | 11-Jul | 2011 | 2789                      | 451                         | 2973               | 541                  | 93.80                                    | 83.40                                      | 
| 8    | 11-Aug | 2011 | 2831                      | 485                         | 2973               | 541                  | 95.20                                    | 89.70                                      | 
| 9    | 11-Sep | 2011 | 2946                      | 467                         | 2973               | 541                  | 99.10                                    | 86.30                                      | 
| 10   | 11-Oct | 2011 | 2919                      | 495                         | 2973               | 541                  | 98.20                                    | 91.50                                      | 
```