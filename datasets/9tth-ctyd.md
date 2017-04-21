# Disposition Of Force Allegations 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-force-allegations-2005-17330) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/9tth-ctyd) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/9tth-ctyd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/9tth-ctyd/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 9tth-ctyd |
| Name | Disposition Of Force Allegations 2005 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:42:13Z |
| Publication Date | 2011-09-28T22:43:16Z |

## Description

CCRB: Disposition of Force Allegations 2005

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
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:9tth-ctyd d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun fired" t:substantiated_number=0 t:exonerated_number=12 t:unfounded_number=0 t:unsubstantiated_number=0 t:officer_unidentified_number=0 m:miscellaneous=2 m:unfounded_rate=0 m:officer_unidentified_rate=0 m:miscellaneous_rate=14.3 m:sunstantiated_rate=0 m:unsubstantiated_rate=0 m:exonerated_rate=85.7

series e:9tth-ctyd d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun pointed" t:substantiated_number=9 t:exonerated_number=102 t:unfounded_number=52 t:unsubstantiated_number=13 t:officer_unidentified_number=15 m:miscellaneous=5 m:unfounded_rate=26.5 m:officer_unidentified_rate=7.7 m:miscellaneous_rate=2.6 m:sunstantiated_rate=4.6 m:unsubstantiated_rate=6.6 m:exonerated_rate=52

series e:9tth-ctyd d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Nightstick as club" t:substantiated_number=0 t:exonerated_number=31 t:unfounded_number=25 t:unsubstantiated_number=11 t:officer_unidentified_number=12 m:miscellaneous=1 m:unfounded_rate=31.3 m:officer_unidentified_rate=15 m:miscellaneous_rate=1.3 m:sunstantiated_rate=0 m:unsubstantiated_rate=13.8 m:exonerated_rate=38.8
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

entity e:9tth-ctyd l:"Disposition Of Force Allegations 2005" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/9tth-ctyd

property e:9tth-ctyd t:meta.view v:id=9tth-ctyd v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Force Allegations 2005" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:9tth-ctyd t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:9tth-ctyd t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Gun fired                             | 0                    | 0.00               | 12                | 85.70           | 0                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 2             | 14.30              | 
| Gun pointed                           | 9                    | 4.60               | 102               | 52.00           | 13                     | 6.60                 | 52               | 26.50          | 15                          | 7.70                      | 5             | 2.60               | 
| Nightstick as club                    | 0                    | 0.00               | 31                | 38.80           | 11                     | 13.80                | 25               | 31.30          | 12                          | 15.00                     | 1             | 1.30               | 
| Gun as club                           | 0                    | 0.00               | 3                 | 25.00           | 2                      | 16.70                | 4                | 33.30          | 1                           | 8.30                      | 2             | 16.70              | 
| Police shield                         | 0                    | 0.00               | 2                 | 66.70           | 0                      | 0.00                 | 1                | 33.30          | 0                           | 0.00                      | 0             | 0.00               | 
| Vehicle                               | 0                    | 0.00               | 0                 | 0.00            | 8                      | 50.00                | 6                | 37.50          | 1                           | 6.30                      | 1             | 6.30               | 
| Other blunt instrument as club        | 0                    | 0.00               | 5                 | 12.80           | 5                      | 12.80                | 22               | 56.40          | 3                           | 7.70                      | 4             | 10.30              | 
| Hit against inanimate object          | 2                    | 3.40               | 8                 | 13.80           | 26                     | 44.80                | 16               | 27.60          | 5                           | 8.60                      | 1             | 1.70               | 
| Chokehold                             | 0                    | 0.00               | 0                 | 0.00            | 23                     | 28.40                | 50               | 61.70          | 8                           | 9.90                      | 0             | 0.00               | 
| Pepper spray                          | 8                    | 5.40               | 106               | 71.10           | 10                     | 6.70                 | 9                | 6.00           | 10                          | 6.70                      | 6             | 4.00               | 
```