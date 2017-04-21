# COA Key Indicators Pilot

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/coa-key-indicators-pilot) |
| Metadata | [Link](https://data.austintexas.gov/api/views/pzmf-qcv7) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/pzmf-qcv7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/pzmf-qcv7/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | pzmf-qcv7 |
| Name | COA Key Indicators Pilot |
| Created | 2015-10-22T18:04:02Z |
| Publication Date | 2015-10-22T18:06:25Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type     | Render Type   |
| ======== | ============== | ===================== | ===================== | ============= | ============= |
| Yes      | series tag     | measure_id            | MEASURE_ID            | text          | number        |
| Yes      | series tag     | measure_name          | MEASURE_NAME          | text          | text          |
| Yes      | series tag     | frequency_name        | FREQUENCY_NAME        | text          | text          |
| No       |                | fy                    | FY                    | number        | number        |
| Yes      | numeric metric | data_value            | DATA_VALUE            | number        | number        |
| Yes      | time           | data_date             | DATA_DATE             | calendar_date | calendar_date |
| Yes      | series tag     | data_type             | DATA_TYPE             | text          | text          |
| Yes      | numeric metric | dashboard_ind         | DASHBOARD_IND         | number        | number        |
| Yes      | series tag     | dashboard_ind_value   | DASHBOARD_IND_VALUE   | text          | text          |
| Yes      | numeric metric | key_performance       | KEY_PERFORMANCE       | number        | number        |
| Yes      | series tag     | key_performance_value | KEY_PERFORMANCE_VALUE | text          | text          |
| Yes      | numeric metric | active                | ACTIVE                | number        | number        |
| Yes      | series tag     | active_value          | ACTIVE_VALUE          | text          | text          |
| Yes      | series tag     | dept_cd               | DEPT_CD               | text          | text          |
| Yes      | series tag     | dept_name             | DEPT_NAME             | text          | text          |
```

## Time Field

```ls
Value = data_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy
```

## Data Commands

```ls
series e:pzmf-qcv7 d:2010-10-01T00:00:00.000Z t:dept_cd=EGRS t:measure_id=1337 t:data_type=Annual t:frequency_name=Annual t:key_performance_value=Yes t:dashboard_ind_value=No t:dept_name="Economic Development" t:active_value=Yes t:measure_name="Number of new jobs created through all economic development efforts" m:active=1 m:data_value=1550 m:key_performance=1 m:dashboard_ind=0

series e:pzmf-qcv7 d:2011-10-01T00:00:00.000Z t:dept_cd=EGRS t:measure_id=1337 t:data_type=Annual t:frequency_name=Annual t:key_performance_value=Yes t:dashboard_ind_value=Yes t:dept_name="Economic Development" t:active_value=Yes t:measure_name="Number of new jobs created through all economic development efforts" m:active=1 m:data_value=1689 m:key_performance=1 m:dashboard_ind=1

series e:pzmf-qcv7 d:2012-10-01T00:00:00.000Z t:dept_cd=EGRS t:measure_id=1337 t:data_type=Annual t:frequency_name=Annual t:key_performance_value=Yes t:dashboard_ind_value=Yes t:dept_name="Economic Development" t:active_value=Yes t:measure_name="Number of new jobs created through all economic development efforts" m:active=1 m:data_value=4139 m:key_performance=1 m:dashboard_ind=1
```

## Meta Commands

```ls
metric m:data_value p:double l:DATA_VALUE t:dataTypeName=number

metric m:dashboard_ind p:integer l:DASHBOARD_IND t:dataTypeName=number

metric m:key_performance p:integer l:KEY_PERFORMANCE t:dataTypeName=number

metric m:active p:integer l:ACTIVE t:dataTypeName=number

entity e:pzmf-qcv7 l:"COA Key Indicators Pilot" t:url=https://data.austintexas.gov/api/views/pzmf-qcv7

property e:pzmf-qcv7 t:meta.view v:id=pzmf-qcv7 v:averageRating=0 v:name="COA Key Indicators Pilot"

property e:pzmf-qcv7 t:meta.view.owner v:id=piyu-w39z v:screenName="Christine Robinson" v:lastNotificationSeenAt=1491334832 v:displayName="Christine Robinson"

property e:pzmf-qcv7 t:meta.view.tableauthor v:id=piyu-w39z v:screenName="Christine Robinson" v:lastNotificationSeenAt=1491334832 v:displayName="Christine Robinson"
```

## Top Records

```ls
| measure_id | measure_name                                                                                                                        | frequency_name | fy   | data_value | data_date           | data_type   | dashboard_ind | dashboard_ind_value | key_performance | key_performance_value | active | active_value | dept_cd | dept_name                  | 
| ========== | =================================================================================================================================== | ============== | ==== | ========== | =================== | =========== | ============= | =================== | =============== | ===================== | ====== | ============ | ======= | ========================== | 
| 1337       | Number of new jobs created through all economic development efforts                                                                 | Annual         | 2010 | 1550       | 2010-10-01T00:00:00 | Annual      | 0             | No                  | 1               | Yes                   | 1      | Yes          | EGRS    | Economic Development       | 
| 1337       | Number of new jobs created through all economic development efforts                                                                 | Annual         | 2011 | 1689       | 2011-10-01T00:00:00 | Annual      | 1             | Yes                 | 1               | Yes                   | 1      | Yes          | EGRS    | Economic Development       | 
| 1337       | Number of new jobs created through all economic development efforts                                                                 | Annual         | 2012 | 4139       | 2012-10-01T00:00:00 | Annual      | 1             | Yes                 | 1               | Yes                   | 1      | Yes          | EGRS    | Economic Development       | 
| 1337       | Number of new jobs created through all economic development efforts                                                                 | Annual         | 2013 | 1794       | 2013-10-01T00:00:00 | Annual      | 1             | Yes                 | 1               | Yes                   | 1      | Yes          | EGRS    | Economic Development       | 
| 1337       | Number of new jobs created through all economic development efforts                                                                 | Annual         | 2014 | 2315       | 2014-10-01T00:00:00 | Annual      | 1             | Yes                 | 1               | Yes                   | 1      | Yes          | EGRS    | Economic Development       | 
| 1337       | Number of new jobs created through all economic development efforts                                                                 | Annual         | 2015 |            | 2015-10-01T00:00:00 | Annual      | 1             | Yes                 | 1               | Yes                   | 1      | Yes          | EGRS    | Economic Development       | 
| 1337       | Number of new jobs created through all economic development efforts                                                                 | Annual         | 2016 |            | 2016-10-01T00:00:00 | Annual      | 1             | Yes                 | 1               | Yes                   | 1      | Yes          | EGRS    | Economic Development       | 
| 1405       | Percent of potentially life-threatening calls (priority one) responded to within 9 minutes and 59 seconds within the City of Austin | Annual         | 2010 | 90.78      | 2010-10-01T00:00:00 | Annual      | 0             | No                  | 0               | No                    | 1      | Yes          | EMS     | Emergency Medical Services | 
| 1405       | Percent of potentially life-threatening calls (priority one) responded to within 9 minutes and 59 seconds within the City of Austin | Monthly        | 2010 |            | 2009-10-31T00:00:00 | FY Month 1  | 0             | No                  | 0               | No                    | 1      | Yes          | EMS     | Emergency Medical Services | 
| 1405       | Percent of potentially life-threatening calls (priority one) responded to within 9 minutes and 59 seconds within the City of Austin | Monthly        | 2010 |            | 2009-07-31T00:00:00 | FY Month 10 | 0             | No                  | 0               | No                    | 1      | Yes          | EMS     | Emergency Medical Services | 
```