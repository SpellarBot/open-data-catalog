# Disposition Of Force Allegations 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-force-allegations-2007-a67b0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qc6h-hbw3) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qc6h-hbw3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qc6h-hbw3/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qc6h-hbw3 |
| Name | Disposition Of Force Allegations 2007 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:48:46Z |
| Publication Date | 2011-09-28T22:50:05Z |

## Description

CCRB: Disposition of Force Allegations 2007

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | type_of_abuse_of_authority_allegation | Type of Abuse of Authority Allegation | text      | text        |
| Yes      | series tag     | substantiated_number                  | Substantiated Number                  | text      | number      |
| Yes      | numeric metric | sunstantiated_rate                    | Sunstantiated rate                    | percent   | percent     |
| Yes      | series tag     | exonerated_number                     | Exonerated number                     | text      | number      |
| Yes      | numeric metric | exonerated_rate                       | Exonerated rate                       | percent   | percent     |
| Yes      | series tag     | unsubstantiated_number                | Unsubstantiated number                | text      | number      |
| Yes      | numeric metric | unsubstantiated_rate                  | Unsubstantiated rate                  | percent   | percent     |
| Yes      | series tag     | unfounded_number                      | Unfounded number                      | text      | number      |
| Yes      | numeric metric | unfounded_rate                        | Unfounded rate                        | percent   | percent     |
| Yes      | series tag     | officer_unidentified_number           | Officer Unidentified number           | text      | number      |
| Yes      | numeric metric | officer_unidentified_rate             | Officer Unidentified rate             | percent   | percent     |
| Yes      | numeric metric | miscellaneous                         | Miscellaneous                         | number    | number      |
| Yes      | numeric metric | miscellaneous_rate                    | Miscellaneous rate                    | percent   | percent     |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qc6h-hbw3 d:2007-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun fired" t:substantiated_number=0 t:exonerated_number=18 t:unfounded_number=0 t:unsubstantiated_number=0 t:officer_unidentified_number=0 m:miscellaneous=1 m:unfounded_rate=0 m:officer_unidentified_rate=0 m:miscellaneous_rate=5.3 m:sunstantiated_rate=0 m:unsubstantiated_rate=0 m:exonerated_rate=94.7

series e:qc6h-hbw3 d:2007-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun pointed" t:substantiated_number=4 t:exonerated_number=199 t:unfounded_number=47 t:unsubstantiated_number=36 t:officer_unidentified_number=12 m:miscellaneous=7 m:unfounded_rate=15.4 m:officer_unidentified_rate=3.9 m:miscellaneous_rate=2.3 m:sunstantiated_rate=1.3 m:unsubstantiated_rate=11.8 m:exonerated_rate=65.2

series e:qc6h-hbw3 d:2007-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Nightstick as club" t:substantiated_number=4 t:exonerated_number=73 t:unfounded_number=54 t:unsubstantiated_number=31 t:officer_unidentified_number=28 m:miscellaneous=4 m:unfounded_rate=27.8 m:officer_unidentified_rate=14.4 m:miscellaneous_rate=2.1 m:sunstantiated_rate=2.1 m:unsubstantiated_rate=16 m:exonerated_rate=37.6
```

## Meta Commands

```ls
metric m:sunstantiated_rate p:float l:"Sunstantiated rate" t:dataTypeName=percent

metric m:exonerated_rate p:float l:"Exonerated rate" t:dataTypeName=percent

metric m:unsubstantiated_rate p:float l:"Unsubstantiated rate" t:dataTypeName=percent

metric m:unfounded_rate p:float l:"Unfounded rate" t:dataTypeName=percent

metric m:officer_unidentified_rate p:float l:"Officer Unidentified rate" t:dataTypeName=percent

metric m:miscellaneous p:integer l:Miscellaneous t:dataTypeName=number

metric m:miscellaneous_rate p:float l:"Miscellaneous rate" t:dataTypeName=percent

entity e:qc6h-hbw3 l:"Disposition Of Force Allegations 2007" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/qc6h-hbw3

property e:qc6h-hbw3 t:meta.view v:id=qc6h-hbw3 v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Force Allegations 2007" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:qc6h-hbw3 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qc6h-hbw3 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Gun fired                             | 0                    | 0.00               | 18                | 94.70           | 0                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 1             | 5.30               | 
| Gun pointed                           | 4                    | 1.30               | 199               | 65.20           | 36                     | 11.80                | 47               | 15.40          | 12                          | 3.90                      | 7             | 2.30               | 
| Nightstick as club                    | 4                    | 2.10               | 73                | 37.60           | 31                     | 16.00                | 54               | 27.80          | 28                          | 14.40                     | 4             | 2.10               | 
| Gun as club                           | 1                    | 4.00               | 1                 | 4.00            | 6                      | 24.00                | 14               | 56.00          | 2                           | 8.00                      | 1             | 4.00               | 
| Police shield                         | 0                    | 0.00               | 5                 | 83.30           | 0                      | 0.00                 | 0                | 0.00           | 1                           | 16.70                     | 0             | 0.00               | 
| Vehicle                               | 1                    | 6.30               | 3                 | 18.80           | 2                      | 12.50                | 9                | 56.30          | 0                           | 0.00                      | 1             | 6.30               | 
| Other blunt instrument as club        | 0                    | 0.00               | 6                 | 12.50           | 11                     | 22.90                | 23               | 47.90          | 8                           | 16.70                     | 0             | 0.00               | 
| Hit against inanimate object          | 1                    | 0.90               | 23                | 21.70           | 21                     | 19.80                | 45               | 42.50          | 12                          | 11.30                     | 4             | 3.80               | 
| Chokehold                             | 0                    | 0.00               | 0                 | 0.00            | 28                     | 24.80                | 70               | 61.90          | 13                          | 11.50                     | 2             | 1.80               | 
| Pepper spray                          | 5                    | 2.60               | 138               | 72.60           | 14                     | 7.40                 | 24               | 12.60          | 9                           | 4.70                      | 0             | 0.00               | 
```