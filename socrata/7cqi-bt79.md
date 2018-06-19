# Special Event Concession Fee Details

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/special-event-concession-fee-details-a1f44) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7cqi-bt79) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7cqi-bt79/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7cqi-bt79/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7cqi-bt79 |
| Name | Special Event Concession Fee Details |
| Attribution | Department of Parks and Recreation (DPR) |
| Category | Recreation |
| Tags | dpr, recreation, park, event, permit, fee, healthy living |
| Created | 2013-01-25T15:58:43Z |
| Publication Date | 2013-06-21T20:28:38Z |

## Description

Special Event Concession Fee details for Various Events

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | events        | Events        | text      | text        |
| Yes      | series tag  | level_a_parks | Level A Parks | text      | text        |
| Yes      | series tag  | level_b_parks | Level B Parks | text      | text        |
| Yes      | series tag  | level_c_parks | Level C Parks | text      | text        |
| Yes      | series tag  | level_d_parks | Level D Parks | text      | text        |
| Yes      | series tag  | category      | Category      | text      | text        |
| Yes      | series tag  | comments      | Comments      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7cqi-bt79 d:2013-01-25T07:58:45.000Z t:category="Basic Event" t:events="Promotional/Commercial, Private - 
Under 25% of Designated Area" t:level_d_parks=$2,400 t:level_c_parks=$7,200 t:level_a_parks=N/A t:level_b_parks=$12,000 m:row_number.7cqi-bt79=1

series e:7cqi-bt79 d:2013-01-25T07:58:45.000Z t:category="Basic Event" t:events="Promotional/Commercial, Private - 
25%-50% of Designated Area" t:level_d_parks=$4,000 t:level_c_parks=$12,000 t:level_a_parks=N/A t:level_b_parks=$20,000 m:row_number.7cqi-bt79=2

series e:7cqi-bt79 d:2013-01-25T07:58:45.000Z t:category="Basic Event" t:events="Promotional/Commercial, Private - 
Over 50% of Designated Area" t:level_d_parks=$4,400 t:level_c_parks=$13,200 t:level_a_parks=$35,000 t:level_b_parks=$22,000 m:row_number.7cqi-bt79=3
```

## Meta Commands

```ls
metric m:row_number.7cqi-bt79 p:long l:"Row Number"

entity e:7cqi-bt79 l:"Special Event Concession Fee Details" t:attribution="Department of Parks and Recreation (DPR)" t:url=https://data.cityofnewyork.us/api/views/7cqi-bt79

property e:7cqi-bt79 t:meta.view v:id=7cqi-bt79 v:category=Recreation v:attributionLink=http://www.nycgovparks.org/rules/section-2-10#cfs v:averageRating=0 v:name="Special Event Concession Fee Details" v:attribution="Department of Parks and Recreation (DPR)"

property e:7cqi-bt79 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7cqi-bt79 t:meta.view.tableauthor v:id=8b43-zkvh v:screenName="Ram S." v:displayName="Ram S."
```

## Top Records

```ls
| :updated_at | events                                                         | level_a_parks | level_b_parks | level_c_parks | level_d_parks | category    | comments | 
| =========== | ============================================================== | ============= | ============= | ============= | ============= | =========== | ======== | 
| 1359100725  | Promotional/Commercial, Private - Under 25% of Designated Area | N/A           | $12,000       | $7,200        | $2,400        | Basic Event |          | 
| 1359100725  | Promotional/Commercial, Private - 25%-50% of Designated Area   | N/A           | $20,000       | $12,000       | $4,000        | Basic Event |          | 
| 1359100725  | Promotional/Commercial, Private - Over 50% of Designated Area  | $35,000       | $22,000       | $13,200       | $4,400        | Basic Event |          | 
| 1359100725  | Athletic Non-Charitable Event - Under 25% of Designated Area   | N/A           | $8,000        | $4,800        | $1,600        | Basic Event |          | 
| 1359100725  | Athletic Non-Charitable Event - 25%-50% of Designated Area     | N/A           | $16,000       | $9,600        | $3,200        | Basic Event |          | 
| 1359100725  | Athletic Non-Charitable Event - Over 50% of Designated Area    | N/A           | $18,000       | $10,800       | $3,600        | Basic Event |          | 
| 1359100725  | Athletic Charitable Event - Under 25% of Designated Area       | N/A           | $1,000        | $600          | $200          | Basic Event |          | 
| 1359100725  | Athletic Charitable Event - 25%-50% of Designated Area         | N/A           | $2,000        | $1,200        | $400          | Basic Event |          | 
| 1359100725  | Athletic Charitable Event - Over 50% of Designated Area        | N/A           | $3,000        | $1,800        | $600          | Basic Event |          | 
| 1359100725  | General Events - Under 25% of Designated Area                  | N/A           | $3,000        | $1,800        | $600          | Basic Event |          | 
```