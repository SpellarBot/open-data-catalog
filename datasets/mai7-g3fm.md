# Disposition Of Force Allegations 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-force-allegations-2006-632d7) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mai7-g3fm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mai7-g3fm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mai7-g3fm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mai7-g3fm |
| Name | Disposition Of Force Allegations 2006 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:45:15Z |
| Publication Date | 2011-09-28T22:46:18Z |

## Description

CCRB: Disposition of Force Allegations 2006

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
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mai7-g3fm d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun fired" t:substantiated_number=0 t:exonerated_number=13 t:unfounded_number=0 t:unsubstantiated_number=5 t:officer_unidentified_number=0 m:miscellaneous=4 m:unfounded_rate=0 m:officer_unidentified_rate=0 m:miscellaneous_rate=18.2 m:sunstantiated_rate=0 m:unsubstantiated_rate=22.7 m:exonerated_rate=59.1

series e:mai7-g3fm d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun pointed" t:substantiated_number=1 t:exonerated_number=129 t:unfounded_number=40 t:unsubstantiated_number=24 t:officer_unidentified_number=28 m:miscellaneous=9 m:unfounded_rate=17.3 m:officer_unidentified_rate=12.1 m:miscellaneous_rate=3.9 m:sunstantiated_rate=0.4 m:unsubstantiated_rate=10.4 m:exonerated_rate=55.8

series e:mai7-g3fm d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Nightstick as club" t:substantiated_number=2 t:exonerated_number=30 t:unfounded_number=61 t:unsubstantiated_number=20 t:officer_unidentified_number=26 m:miscellaneous=2 m:unfounded_rate=43.3 m:officer_unidentified_rate=18.4 m:miscellaneous_rate=1.4 m:sunstantiated_rate=1.4 m:unsubstantiated_rate=14.2 m:exonerated_rate=21.3
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

entity e:mai7-g3fm l:"Disposition Of Force Allegations 2006" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/mai7-g3fm

property e:mai7-g3fm t:meta.view v:id=mai7-g3fm v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Force Allegations 2006" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:mai7-g3fm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mai7-g3fm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Gun fired                             | 0                    | 0.00               | 13                | 59.10           | 5                      | 22.70                | 0                | 0.00           | 0                           | 0.00                      | 4             | 18.20              | 
| Gun pointed                           | 1                    | 0.40               | 129               | 55.80           | 24                     | 10.40                | 40               | 17.30          | 28                          | 12.10                     | 9             | 3.90               | 
| Nightstick as club                    | 2                    | 1.40               | 30                | 21.30           | 20                     | 14.20                | 61               | 43.30          | 26                          | 18.40                     | 2             | 1.40               | 
| Gun as club                           | 2                    | 9.10               | 2                 | 9.10            | 5                      | 22.70                | 9                | 40.90          | 3                           | 13.60                     | 1             | 4.50               | 
| Police shield                         | 0                    | 0.00               | 2                 | 40.00           | 0                      | 0.00                 | 1                | 20.00          | 2                           | 40.00                     | 0             | 0.00               | 
| Vehicle                               | 1                    | 4.50               | 5                 | 22.70           | 2                      | 9.10                 | 11               | 50.00          | 3                           | 13.60                     | 0             | 0.00               | 
| Other blunt instrument as club        | 0                    | 0.00               | 0                 | 0.00            | 6                      | 17.60                | 20               | 58.80          | 7                           | 20.60                     | 1             | 2.90               | 
| Hit against inanimate object          | 1                    | 1.10               | 15                | 16.90           | 28                     | 31.50                | 40               | 44.90          | 5                           | 5.60                      | 0             | 0.00               | 
| Chokehold                             | 2                    | 2.40               | 1                 | 1.20            | 13                     | 15.30                | 61               | 71.80          | 7                           | 8.20                      | 1             | 1.20               | 
| Pepper spray                          | 4                    | 2.00               | 145               | 72.50           | 17                     | 8.50                 | 18               | 9.00           | 16                          | 8.00                      | 0             | 0.00               | 
```