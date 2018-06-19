# CCRB: Disposition Of Abuse Of Authority Allegations 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-disposition-of-abuse-of-authority-allegations-2005-2009-86593) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mtfg-8ayp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mtfg-8ayp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mtfg-8ayp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mtfg-8ayp |
| Name | CCRB: Disposition Of Abuse Of Authority Allegations 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-27T21:13:53Z |
| Publication Date | 2011-09-27T21:18:24Z |

## Description

Disposition Of Abuse Of Authority Allegations 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | type_of_abuse_of_authority_allegation | Type of Abuse of Authority Allegation | text      | text        |
| Yes      | series tag     | substantiated_number                  | Substantiated Number                  | text      | number      |
| Yes      | numeric metric | substantiated_raterate                | Substantiated RateRate                | percent   | percent     |
| Yes      | numeric metric | number_exonerated                     | Number Exonerated                     | number    | number      |
| Yes      | numeric metric | exoneration_rate                      | Exoneration Rate                      | percent   | percent     |
| Yes      | series tag     | unsubstaniated_number                 | Unsubstaniated Number                 | text      | number      |
| Yes      | numeric metric | rate_unsubstantiated                  | Rate unsubstantiated                  | percent   | percent     |
| Yes      | series tag     | unfounded_number                      | Unfounded Number                      | text      | number      |
| Yes      | numeric metric | rate_unfounded                        | Rate unfounded                        | percent   | percent     |
| Yes      | numeric metric | number_that_were_officer_unidentified | Number that were Officer unidentified | number    | number      |
| Yes      | numeric metric | rate_officer_unidentified_            | Rate (Officer unidentified)           | percent   | percent     |
| Yes      | series tag     | miscellaneous_number                  | Miscellaneous Number                  | text      | number      |
| Yes      | numeric metric | miscellaneous_rate                    | Miscellaneous Rate                    | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mtfg-8ayp d:2005-01-01T00:00:00.000Z t:unsubstaniated_number=434 t:miscellaneous_number=66 t:type_of_abuse_of_authority_allegation="Question and/or stop**" t:substantiated_number=247 t:unfounded_number=51 m:rate_unfounded=1.7 m:number_exonerated=1946 m:exoneration_rate=65.4 m:rate_officer_unidentified_=7.8 m:miscellaneous_rate=2.2 m:rate_unsubstantiated=14.6 m:substantiated_raterate=8.3 m:number_that_were_officer_unidentified=231

series e:mtfg-8ayp d:2005-01-01T00:00:00.000Z t:unsubstaniated_number=78 t:miscellaneous_number=8 t:type_of_abuse_of_authority_allegation=Question t:substantiated_number=40 t:unfounded_number=7 m:rate_unfounded=1.5 m:number_exonerated=312 m:exoneration_rate=65.3 m:rate_officer_unidentified_=6.9 m:miscellaneous_rate=1.7 m:rate_unsubstantiated=16.3 m:substantiated_raterate=8.4 m:number_that_were_officer_unidentified=33

series e:mtfg-8ayp d:2005-01-01T00:00:00.000Z t:unsubstaniated_number=463 t:miscellaneous_number=29 t:type_of_abuse_of_authority_allegation=Stop t:substantiated_number=131 t:unfounded_number=26 m:rate_unfounded=1.6 m:number_exonerated=870 m:exoneration_rate=53.2 m:rate_officer_unidentified_=7 m:miscellaneous_rate=1.8 m:rate_unsubstantiated=28.3 m:substantiated_raterate=8 m:number_that_were_officer_unidentified=115
```

## Meta Commands

```ls
metric m:substantiated_raterate p:float l:"Substantiated RateRate" t:dataTypeName=percent

metric m:number_exonerated p:integer l:"Number Exonerated" t:dataTypeName=number

metric m:exoneration_rate p:float l:"Exoneration Rate" t:dataTypeName=percent

metric m:rate_unsubstantiated p:float l:"Rate unsubstantiated" t:dataTypeName=percent

metric m:rate_unfounded p:float l:"Rate unfounded" t:dataTypeName=percent

metric m:number_that_were_officer_unidentified p:integer l:"Number that were Officer unidentified" t:dataTypeName=number

metric m:rate_officer_unidentified_ p:float l:"Rate (Officer unidentified)" t:dataTypeName=percent

metric m:miscellaneous_rate p:float l:"Miscellaneous Rate" t:dataTypeName=percent

entity e:mtfg-8ayp l:"CCRB: Disposition Of Abuse Of Authority Allegations 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/mtfg-8ayp

property e:mtfg-8ayp t:meta.view v:id=mtfg-8ayp v:category="Public Safety" v:averageRating=0 v:name="CCRB: Disposition Of Abuse Of Authority Allegations 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:mtfg-8ayp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mtfg-8ayp t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | substantiated_raterate | number_exonerated | exoneration_rate | unsubstaniated_number | rate_unsubstantiated | unfounded_number | rate_unfounded | number_that_were_officer_unidentified | rate_officer_unidentified_ | miscellaneous_number | miscellaneous_rate | 
| ===================================== | ==================== | ====================== | ================= | ================ | ===================== | ==================== | ================ | ============== | ===================================== | ========================== | ==================== | ================== | 
| Type of Abuse of Authority Allegation |                      |                        |                   |                  |                       |                      |                  |                |                                       |                            |                      |                    | 
| Question and/or stop**                | 247                  | 8.30                   | 1946              | 65.40            | 434                   | 14.60                | 51               | 1.70           | 231                                   | 7.80                       | 66                   | 2.20               | 
| Question                              | 40                   | 8.40                   | 312               | 65.30            | 78                    | 16.30                | 7                | 1.50           | 33                                    | 6.90                       | 8                    | 1.70               | 
| Stop                                  | 131                  | 8.00                   | 870               | 53.20            | 463                   | 28.30                | 26               | 1.60           | 115                                   | 7.00                       | 29                   | 1.80               | 
| Frisk and/or search*                  | 35                   | 14.50                  | 78                | 32.40            | 66                    | 27.40                | 18               | 7.50           | 39                                    | 16.20                      | 5                    | 2.10               | 
| Search                                | 213                  | 9.00                   | 548               | 23.20            | 1032                  | 43.70                | 200              | 8.50           | 325                                   | 13.80                      | 45                   | 1.90               | 
| Frisk                                 | 220                  | 12.70                  | 747               | 43.00            | 468                   | 26.90                | 62               | 3.60           | 213                                   | 12.30                      | 27                   | 1.60               | 
| Vehicle search                        | 167                  | 12.10                  | 551               | 40.10            | 419                   | 30.50                | 72               | 5.20           | 137                                   | 10.00                      | 29                   | 2.10               | 
| Vehicle stop                          | 74                   | 5.70                   | 794               | 61.20            | 282                   | 21.70                | 7                | 0.50           | 106                                   | 8.20                       | 35                   | 2.70               | 
| Premises entered or searched          | 126                  | 5.10                   | 1727              | 70.10            | 391                   | 15.90                | 80               | 3.20           | 108                                   | 4.40                       | 33                   | 1.30               | 
```