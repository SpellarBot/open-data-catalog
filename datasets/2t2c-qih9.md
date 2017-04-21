# Full-Time And Full-Time Equivalent Staffing Levels

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/full-time-and-full-time-equivalent-staffing-levels) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/2t2c-qih9) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/2t2c-qih9/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/2t2c-qih9/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 2t2c-qih9 |
| Name | Full-Time And Full-Time Equivalent Staffing Levels |
| Attribution | Mayor?s Office of Management & Budget (OMB) |
| Category | City Government |
| Created | 2016-05-03T20:09:51Z |
| Publication Date | 2017-02-08T17:07:07Z |

## Description

This dataset contains estimated fiscal year-end headcount information for full-time and full-time equivalent employees (FTE).  The information is summarized by agency, personnel type and funding.  The amount fields are whole numbers.  The numbers within can be summarized to match pages from the publication ?Full-Time and Full-Time Equivalent Staffing Levels?.

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                                | Data Type | Render Type |
| ======== | ============== | ================================================ | =================================================== | ========= | =========== |
| Yes      | time           | publication_date                                 | Publication Date                                    | text      | text        |
| Yes      | series tag     | agency_number                                    | Agency Number                                       | text      | text        |
| Yes      | series tag     | agency_name                                      | Agency Name                                         | text      | text        |
| No       |                | fiscal_year                                      | Fiscal Year                                         | number    | number      |
| Yes      | series tag     | personnel_type_code                              | Personnel Type Code                                 | text      | text        |
| Yes      | series tag     | personnel_type_name                              | Personnel Type Name                                 | text      | text        |
| Yes      | numeric metric | code_for_full_time_ftes                          | Code for Full-Time & FTEs                           | number    | number      |
| Yes      | series tag     | full_time_full_time_equivalents_ft_fte_positions | Full-Time/Full-Time Equivalents/ FT + FTE Positions | text      | text        |
| Yes      | numeric metric | city_funded_headcount                            | City Funded Headcount                               | number    | number      |
| Yes      | numeric metric | ifa_funded_headcount                             | IFA Funded Headcount                                | number    | number      |
| Yes      | numeric metric | cd_funded_headcount                              | CD Funded Headcount                                 | number    | number      |
| Yes      | numeric metric | other_funded_headcount                           | Other Funded Headcount                              | number    | number      |
| Yes      | numeric metric | total                                            | Total                                               | number    | number      |
```

## Time Field

```ls
Value = publication_date
Format & Zone = yyyyMMdd
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:2t2c-qih9 d:2016-04-26T00:00:00.000Z t:full_time_full_time_equivalents_ft_fte_positions=Full-Time t:personnel_type_code=C t:personnel_type_name=Civilian t:agency_number=101 t:agency_name="Public Advocate" m:total=40 m:other_funded_headcount=0 m:code_for_full_time_ftes=1 m:city_funded_headcount=40 m:ifa_funded_headcount=0 m:cd_funded_headcount=0

series e:2t2c-qih9 d:2016-04-26T00:00:00.000Z t:full_time_full_time_equivalents_ft_fte_positions="Full-Time Equivalent" t:personnel_type_code=C t:personnel_type_name=Civilian t:agency_number=781 t:agency_name="Department of Probation" m:total=0 m:other_funded_headcount=0 m:code_for_full_time_ftes=2 m:city_funded_headcount=0 m:ifa_funded_headcount=0 m:cd_funded_headcount=0

series e:2t2c-qih9 d:2016-06-15T00:00:00.000Z t:full_time_full_time_equivalents_ft_fte_positions=Full-Time t:personnel_type_code=C t:personnel_type_name=Civilian t:agency_number=042 t:agency_name="City University" m:total=1907 m:other_funded_headcount=0 m:code_for_full_time_ftes=1 m:city_funded_headcount=1907 m:ifa_funded_headcount=0 m:cd_funded_headcount=0
```

## Meta Commands

```ls
metric m:code_for_full_time_ftes p:integer l:"Code for Full-Time & FTEs" t:dataTypeName=number

metric m:city_funded_headcount p:integer l:"City Funded Headcount" t:dataTypeName=number

metric m:ifa_funded_headcount p:integer l:"IFA Funded Headcount" t:dataTypeName=number

metric m:cd_funded_headcount p:integer l:"CD Funded Headcount" t:dataTypeName=number

metric m:other_funded_headcount p:integer l:"Other Funded Headcount" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:2t2c-qih9 l:"Full-Time And Full-Time Equivalent Staffing Levels" t:attribution="Mayor?s Office of Management & Budget (OMB)" t:url=https://data.cityofnewyork.us/api/views/2t2c-qih9

property e:2t2c-qih9 t:meta.view v:id=2t2c-qih9 v:category="City Government" v:averageRating=0 v:name="Full-Time And Full-Time Equivalent Staffing Levels" v:attribution="Mayor?s Office of Management & Budget (OMB)"

property e:2t2c-qih9 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:2t2c-qih9 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| publication_date | agency_number | agency_name             | fiscal_year | personnel_type_code | personnel_type_name | code_for_full_time_ftes | full_time_full_time_equivalents_ft_fte_positions | city_funded_headcount | ifa_funded_headcount | cd_funded_headcount | other_funded_headcount | total | 
| ================ | ============= | ======================= | =========== | =================== | =================== | ======================= | ================================================ | ===================== | ==================== | =================== | ====================== | ===== | 
| 20160426         | 101           | Public Advocate         | 2020        | C                   | Civilian            | 1                       | Full-Time                                        | 40                    | 0                    | 0                   | 0                      | 40    | 
| 20160426         | 781           | Department of Probation | 2018        | C                   | Civilian            | 2                       | Full-Time Equivalent                             | 0                     | 0                    | 0                   | 0                      | 0     | 
| 20160615         | 042           | City University         | 2017        | C                   | Civilian            | 1                       | Full-Time                                        | 1907                  | 0                    | 0                   | 0                      | 1907  | 
| 20160426         | 2             | Mayoralty               | 2016        | C                   | Civilian            | 1                       | Full-Time                                        | 860                   | 138                  | 75                  | 59                     | 1132  | 
| 20160426         | 2             | Mayoralty               | 2016        | C                   | Civilian            | 2                       | Full-Time Equivalent                             | 9                     | 1                    | 1                   | 1                      | 12    | 
| 20160426         | 2             | Mayoralty               | 2016        | C                   | Civilian            | 3                       | Full-Time Plus Full-Time Equivalent              | 869                   | 139                  | 76                  | 60                     | 1144  | 
| 20160426         | 2             | Mayoralty               | 2017        | C                   | Civilian            | 1                       | Full-Time                                        | 914                   | 138                  | 65                  | 23                     | 1140  | 
| 20160426         | 2             | Mayoralty               | 2017        | C                   | Civilian            | 2                       | Full-Time Equivalent                             | 9                     | 1                    | 1                   | 0                      | 11    | 
| 20160426         | 2             | Mayoralty               | 2017        | C                   | Civilian            | 3                       | Full-Time Plus Full-Time Equivalent              | 923                   | 139                  | 66                  | 23                     | 1151  | 
| 20160426         | 2             | Mayoralty               | 2018        | C                   | Civilian            | 1                       | Full-Time                                        | 910                   | 138                  | 38                  | 21                     | 1107  | 
```