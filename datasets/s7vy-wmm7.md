# List Of Cases Filed By Type At OATH

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/list-of-cases-filed-by-type-at-oath-ab64f) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s7vy-wmm7) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s7vy-wmm7/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s7vy-wmm7/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s7vy-wmm7 |
| Name | List Of Cases Filed By Type At OATH |
| Attribution | Office of Administrative Trials and Hearings (OATH) |
| Category | City Government |
| Tags | oath, office of administrative trials and hearings, cases |
| Created | 2013-03-06T15:33:26Z |
| Publication Date | 2013-06-21T20:08:52Z |

## Description

This is the list of cases filed by type, the break down of case type is listed as percentage value

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       | time           | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag     | case_type                      | Case Type                      | text      | text        |
| Yes      | numeric metric | percent_of_the_case_type_filed | Percent of the Case Type Filed | percent   | percent     |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:s7vy-wmm7 d:2013-03-06T07:33:27.000Z t:case_type="Disciplinary / Disability / COIB Hearings" m:percent_of_the_case_type_filed=49.9

series e:s7vy-wmm7 d:2013-03-06T07:33:27.000Z t:case_type="Vehicle Forfeiture" m:percent_of_the_case_type_filed=18.7

series e:s7vy-wmm7 d:2013-03-06T07:33:27.000Z t:case_type="Discrimination Under City Human Rights Law" m:percent_of_the_case_type_filed=1.6
```

## Meta Commands

```ls
metric m:percent_of_the_case_type_filed p:float l:"Percent of the Case Type Filed" t:dataTypeName=percent

entity e:s7vy-wmm7 l:"List Of Cases Filed By Type At OATH" t:attribution="Office of Administrative Trials and Hearings (OATH)" t:url=https://data.cityofnewyork.us/api/views/s7vy-wmm7

property e:s7vy-wmm7 t:meta.view v:id=s7vy-wmm7 v:category="City Government" v:attributionLink=http://www.nyc.gov/html/oath/downloads/pdf/oath_stats/OATH.pdf v:averageRating=0 v:name="List Of Cases Filed By Type At OATH" v:attribution="Office of Administrative Trials and Hearings (OATH)"

property e:s7vy-wmm7 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:s7vy-wmm7 t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| :updated_at | case_type                                      | percent_of_the_case_type_filed | 
| =========== | ============================================== | ============================== | 
| 1362555207  | Disciplinary / Disability / COIB Hearings      | 49.90                          | 
| 1362555207  | Vehicle Forfeiture                             | 18.70                          | 
| 1362555207  | Discrimination Under City Human Rights Law     | 1.60                           | 
| 1362555207  | City Contract Disputes                         | 6.80                           | 
| 1362555207  | City Issued Licenses                           | 19.70                          | 
| 1362555207  | Loft Law Cases / Zoning Violations / SRO       | 6.80                           | 
| 1362555207  | Lobbyist Registration & Other Regulatory Cases | 2.50                           | 
```