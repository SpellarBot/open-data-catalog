# Disposition Of All Allegations 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-all-allegations-2005-2009-5a2e6) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/h8eh-b25q) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/h8eh-b25q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/h8eh-b25q/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | h8eh-b25q |
| Name | Disposition Of All Allegations 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-30T17:24:51Z |
| Publication Date | 2011-09-30T17:25:57Z |

## Description

CCRB: Disposition of all Allegations 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name                                                        | Name                                                                | Data Type | Render Type |
| ======== | ============== | ================================================================= | =================================================================== | ========= | =========== |
| Yes      | series tag     | full_investigations_dispositions_and_disciplinary_recommendations | Full Investigations - Dispositions and Disciplinary Recommendations | text      | text        |
| Yes      | series tag     | number_1                                                          | 2005 Number                                                         | text      | number      |
| Yes      | numeric metric | percent_1                                                         | 2005 Percent                                                        | percent   | percent     |
| Yes      | series tag     | number_2                                                          | 2006 Number                                                         | text      | number      |
| Yes      | numeric metric | percent_2                                                         | 2006 Percent                                                        | percent   | percent     |
| Yes      | series tag     | number_3                                                          | 2007 Number                                                         | text      | number      |
| Yes      | numeric metric | percent_3                                                         | 2007 Percent                                                        | percent   | percent     |
| Yes      | series tag     | number_4                                                          | 2008 Number                                                         | text      | number      |
| Yes      | numeric metric | percent_4                                                         | 2008 Percent                                                        | percent   | percent     |
| Yes      | series tag     | number_5                                                          | 2009 Number                                                         | text      | number      |
| Yes      | numeric metric | percent_5                                                         | 2009 Percent                                                        | percent   | percent     |
| Yes      | series tag     | five_year_total_number                                            | Five-year Total Number                                              | text      | number      |
| Yes      | numeric metric | five_year_total_percent                                           | Five-year Total Percent                                             | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:h8eh-b25q d:2005-01-01T00:00:00.000Z t:full_investigations_dispositions_and_disciplinary_recommendations="Substantiated - Charges" t:five_year_total_number=2133 t:number_1=640 t:number_3=412 t:number_2=493 t:number_5=309 t:number_4=279 m:five_year_total_percent=4.1 m:percent_2=4.6 m:percent_3=3.6 m:percent_4=2.9 m:percent_5=3 m:percent_1=6.3

series e:h8eh-b25q d:2005-01-01T00:00:00.000Z t:full_investigations_dispositions_and_disciplinary_recommendations="Substantiated - Command discipline" t:five_year_total_number=355 t:number_1=55 t:number_3=69 t:number_2=83 t:number_5=93 t:number_4=55 m:five_year_total_percent=0.7 m:percent_2=0.8 m:percent_3=0.6 m:percent_4=0.6 m:percent_5=0.9 m:percent_1=0.5

series e:h8eh-b25q d:2005-01-01T00:00:00.000Z t:full_investigations_dispositions_and_disciplinary_recommendations="Substantiated - Instructions" t:five_year_total_number=85 t:number_1=13 t:number_3=20 t:number_2=13 t:number_5=31 t:number_4=8 m:five_year_total_percent=0.2 m:percent_2=0.1 m:percent_3=0.2 m:percent_4=0.1 m:percent_5=0.3 m:percent_1=0.1
```

## Meta Commands

```ls
metric m:percent_1 p:float l:"2005 Percent" t:dataTypeName=percent

metric m:percent_2 p:float l:"2006 Percent" t:dataTypeName=percent

metric m:percent_3 p:float l:"2007 Percent" t:dataTypeName=percent

metric m:percent_4 p:float l:"2008 Percent" t:dataTypeName=percent

metric m:percent_5 p:float l:"2009 Percent" t:dataTypeName=percent

metric m:five_year_total_percent p:float l:"Five-year Total Percent" t:dataTypeName=percent

entity e:h8eh-b25q l:"Disposition Of All Allegations 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/h8eh-b25q

property e:h8eh-b25q t:meta.view v:id=h8eh-b25q v:category="Public Safety" v:averageRating=0 v:name="Disposition Of All Allegations 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:h8eh-b25q t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:h8eh-b25q t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| full_investigations_dispositions_and_disciplinary_recommendations | number_1 | percent_1 | number_2 | percent_2 | number_3 | percent_3 | number_4 | percent_4 | number_5 | percent_5 | five_year_total_number | five_year_total_percent | 
| ================================================================= | ======== | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ======== | ========= | ====================== | ======================= | 
| Substantiated - Charges                                           | 640      | 6.30      | 493      | 4.60      | 412      | 3.60      | 279      | 2.90      | 309      | 3.00      | 2133                   | 4.10                    | 
| Substantiated - Command discipline                                | 55       | 0.50      | 83       | 0.80      | 69       | 0.60      | 55       | 0.60      | 93       | 0.90      | 355                    | 0.70                    | 
| Substantiated - Instructions                                      | 13       | 0.10      | 13       | 0.10      | 20       | 0.20      | 8        | 0.10      | 31       | 0.30      | 85                     | 0.20                    | 
| Substantiated - No Recommendation                                 | 0        | 0.00      | 5        | 0.00      | 3        | 0.00      | 3        | 0.00      | 13       | 0.10      | 24                     | 0.00                    | 
| Subtotal - Substantiated Allegations                              | 708      | 7.00      | 594      | 5.60      | 504      | 4.40      | 345      | 3.60      | 446      | 4.40      | 2597                   | 5.00                    | 
| Unfounded                                                         | 2132     | 21.00     | 2056     | 19.30     | 2060     | 17.90     | 1162     | 12.10     | 1548     | 15.30     | 8958                   | 17.20                   | 
| Employee exonerated                                               | 3704     | 36.50     | 4033     | 37.80     | 4610     | 40.10     | 3151     | 32.90     | 3361     | 33.10     | 18859                  | 36.20                   | 
| Subtotal - Findings on the Merits                                 | 6544     | 64.50     | 6683     | 62.60     | 7174     | 62.40     | 4658     | 48.60     | 5355     | 52.80     | 30414                  | 58.50                   | 
| Unsubstantiated                                                   | 2416     | 23.80     | 2626     | 24.60     | 3031     | 26.40     | 3706     | 38.70     | 3706     | 36.50     | 15485                  | 29.80                   | 
| Department employee unidentified                                  | 912      | 9.00      | 1091     | 10.20     | 1031     | 9.00      | 992      | 10.40     | 930      | 9.20      | 4956                   | 9.50                    | 
```