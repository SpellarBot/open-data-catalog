# EMS - Communications Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ems-communications-measures) |
| Metadata | [Link](https://data.austintexas.gov/api/views/hjne-yn95) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/hjne-yn95/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/hjne-yn95/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | hjne-yn95 |
| Name | EMS - Communications Measures |
| Attribution | Austin-Travis County EMS |
| Category | Public Safety |
| Tags | atcems, communications, ems, 911, workload, performance, 911 calls, mpds compliance, call processing, grade of service |
| Created | 2016-03-04T16:05:02Z |
| Publication Date | 2016-04-01T15:41:59Z |

## Description

Data contained in this table documents Austin-Travis County EMS (ATCEMS) Communications Center workload and performance.  

Data contained in this table comes from several sources:  
?	911 Call Count and Grade of Service are obtained from the ECaTS reporting system provided by the Capital Area Council of Governments (CAPCOG).
?	Call Processing Interval is calculated using data from the department Computer-Aided Dispatch (CAD) data warehouse.
?	MPDS Compliance is calculated by the Advanced Quality Assurance (AQUA) system used by Communications Center personnel to assess center performance.
?	Performance targets are determined by ATCEMS management.

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                            | Data Type     | Render Type   |
| ======== | ============== | ======================================== | =============================== | ============= | ============= |
| Yes      | numeric metric | month_key                                | Month Key                       | number        | number        |
| Yes      | time           | month_start_date                         | Month-Year                      | calendar_date | calendar_date |
| Yes      | numeric metric | count_calls_911                          | 911 Call Count                  | number        | number        |
| Yes      | numeric metric | percent_gos                              | Grade of Service                | percent       | percent       |
| Yes      | numeric metric | percent_gos_target                       | Grade of Service Target         | percent       | percent       |
| Yes      | numeric metric | average_call_processing_interval_seconds | Call Processing Interval        | number        | number        |
| Yes      | numeric metric | average_call_processing_interval_target  | Call Processing Interval Target | number        | number        |
| Yes      | numeric metric | percent_triage_compliance_mpds           | MPDS Triage Compliance          | percent       | percent       |
| Yes      | numeric metric | percent_triage_compliance_mpds_target    | MPDS Triage Compliance Target   | percent       | percent       |
```

## Time Field

```ls
Value = month_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:hjne-yn95 d:2013-10-01T00:00:00.000Z m:percent_triage_compliance_mpds=99.15 m:percent_triage_compliance_mpds_target=90 m:average_call_processing_interval_target=75 m:percent_gos_target=90 m:count_calls_911=10946 m:average_call_processing_interval_seconds=62.83 m:month_key=201310 m:percent_gos=94.34

series e:hjne-yn95 d:2013-11-01T00:00:00.000Z m:percent_triage_compliance_mpds=99.58 m:percent_triage_compliance_mpds_target=90 m:average_call_processing_interval_target=75 m:percent_gos_target=90 m:count_calls_911=9785 m:average_call_processing_interval_seconds=64.14 m:month_key=201311 m:percent_gos=90.97

series e:hjne-yn95 d:2013-12-01T00:00:00.000Z m:percent_triage_compliance_mpds=99.65 m:percent_triage_compliance_mpds_target=90 m:average_call_processing_interval_target=75 m:percent_gos_target=90 m:count_calls_911=9766 m:average_call_processing_interval_seconds=68.05 m:month_key=201312 m:percent_gos=90.55
```

## Meta Commands

```ls
metric m:month_key p:integer l:"Month Key" d:"Year and month for record in <yyyymm> format (e.g. 201407). This format is useful for sorting records." t:dataTypeName=number

metric m:count_calls_911 p:integer l:"911 Call Count" d:"Count of phone calls received through 911 system." t:dataTypeName=number

metric m:percent_gos p:float l:"Grade of Service" d:"Percent of 911 calls answered within 10 seconds of initial ring." t:dataTypeName=percent

metric m:percent_gos_target p:integer l:"Grade of Service Target" d:"Performance target for percent of 911 calls answered within 10 seconds of initial ring." t:dataTypeName=percent

metric m:average_call_processing_interval_seconds p:float l:"Call Processing Interval" d:"Average amount of time required to dispatch the first unit to an incident, measured from the time that the 911 call is answered. This value is reported in seconds." t:dataTypeName=number

metric m:average_call_processing_interval_target p:integer l:"Call Processing Interval Target" d:"Performance target for Call Processing Interval. This value is reported in seconds." t:dataTypeName=number

metric m:percent_triage_compliance_mpds p:float l:"MPDS Triage Compliance" d:"Communications Center compliance with Medical Priority Dispatch System (MPDS) standards." t:dataTypeName=percent

metric m:percent_triage_compliance_mpds_target p:integer l:"MPDS Triage Compliance Target" d:"Performance target for compliance with Medical Priority Dispatch System (MPDS) standards." t:dataTypeName=percent

entity e:hjne-yn95 l:"EMS - Communications Measures" t:attribution="Austin-Travis County EMS" t:url=https://data.austintexas.gov/api/views/hjne-yn95

property e:hjne-yn95 t:meta.view v:id=hjne-yn95 v:category="Public Safety" v:averageRating=0 v:name="EMS - Communications Measures" v:attribution="Austin-Travis County EMS"

property e:hjne-yn95 t:meta.view.owner v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:displayName="Austin-Travis County EMS"

property e:hjne-yn95 t:meta.view.tableauthor v:id=4zcf-8die v:profileImageUrlMedium=/api/users/4zcf-8die/profile_images/THUMB v:profileImageUrlLarge=/api/users/4zcf-8die/profile_images/LARGE v:screenName="Austin-Travis County EMS" v:profileImageUrlSmall=/api/users/4zcf-8die/profile_images/TINY v:roleName=publisher_stories v:displayName="Austin-Travis County EMS"
```

## Top Records

```ls
| month_key | month_start_date    | count_calls_911 | percent_gos | percent_gos_target | average_call_processing_interval_seconds | average_call_processing_interval_target | percent_triage_compliance_mpds | percent_triage_compliance_mpds_target | 
| ========= | =================== | =============== | =========== | ================== | ======================================== | ======================================= | ============================== | ===================================== | 
| 201310    | 2013-10-01T00:00:00 | 10946           | 94.34       | 90                 | 62.83                                    | 75                                      | 99.15                          | 90                                    | 
| 201311    | 2013-11-01T00:00:00 | 9785            | 90.97       | 90                 | 64.14                                    | 75                                      | 99.58                          | 90                                    | 
| 201312    | 2013-12-01T00:00:00 | 9766            | 90.55       | 90                 | 68.05                                    | 75                                      | 99.65                          | 90                                    | 
| 201401    | 2014-01-01T00:00:00 | 9914            | 91.15       | 90                 | 68.85                                    | 75                                      | 99.89                          | 90                                    | 
| 201402    | 2014-02-01T00:00:00 | 9073            | 92.36       | 90                 | 65.85                                    | 75                                      | 99.06                          | 90                                    | 
| 201403    | 2014-03-01T00:00:00 | 10602           | 92.94       | 90                 | 66.57                                    | 75                                      | 99.80                          | 90                                    | 
| 201404    | 2014-04-01T00:00:00 | 10198           | 93.22       | 90                 | 72.23                                    | 75                                      | 98.94                          | 90                                    | 
| 201405    | 2014-05-01T00:00:00 | 11489           | 98.46       | 90                 | 67.22                                    | 75                                      | 99.09                          | 90                                    | 
| 201406    | 2014-06-01T00:00:00 | 11308           | 99.67       | 90                 | 67.51                                    | 75                                      | 98.90                          | 90                                    | 
| 201407    | 2014-07-01T00:00:00 | 11436           | 99.60       | 90                 | 70.35                                    | 75                                      | 99.00                          | 90                                    | 
```