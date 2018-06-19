# Disposition Of Force Allegations 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-force-allegations-2009-f9aea) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qwi9-6tzj) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qwi9-6tzj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qwi9-6tzj/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qwi9-6tzj |
| Name | Disposition Of Force Allegations 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:58:35Z |
| Publication Date | 2011-09-28T22:59:42Z |

## Description

CCRB: Disposition of Force Allegations 2009

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
Value = 2009
Format & Zone = yyyy
```

## Data Commands

```ls
series e:qwi9-6tzj d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun fired" t:substantiated_number=2 t:exonerated_number=10 t:unfounded_number=1 t:unsubstantiated_number=0 t:officer_unidentified_number=0 m:miscellaneous=1 m:unfounded_rate=7.1 m:officer_unidentified_rate=0 m:miscellaneous_rate=7.1 m:sunstantiated_rate=14.3 m:unsubstantiated_rate=0 m:exonerated_rate=71.4

series e:qwi9-6tzj d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun pointed" t:substantiated_number=4 t:exonerated_number=155 t:unfounded_number=21 t:unsubstantiated_number=37 t:officer_unidentified_number=9 m:miscellaneous=4 m:unfounded_rate=9.1 m:officer_unidentified_rate=3.9 m:miscellaneous_rate=1.7 m:sunstantiated_rate=1.7 m:unsubstantiated_rate=16.1 m:exonerated_rate=67.4

series e:qwi9-6tzj d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Nightstick as club" t:substantiated_number=4 t:exonerated_number=62 t:unfounded_number=48 t:unsubstantiated_number=36 t:officer_unidentified_number=20 m:miscellaneous=5 m:unfounded_rate=27.4 m:officer_unidentified_rate=11.4 m:miscellaneous_rate=2.9 m:sunstantiated_rate=2.3 m:unsubstantiated_rate=20.6 m:exonerated_rate=35.4
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

entity e:qwi9-6tzj l:"Disposition Of Force Allegations 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/qwi9-6tzj

property e:qwi9-6tzj t:meta.view v:id=qwi9-6tzj v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Force Allegations 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:qwi9-6tzj t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qwi9-6tzj t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Gun fired                             | 2                    | 14.30              | 10                | 71.40           | 0                      | 0.00                 | 1                | 7.10           | 0                           | 0.00                      | 1             | 7.10               | 
| Gun pointed                           | 4                    | 1.70               | 155               | 67.40           | 37                     | 16.10                | 21               | 9.10           | 9                           | 3.90                      | 4             | 1.70               | 
| Nightstick as club                    | 4                    | 2.30               | 62                | 35.40           | 36                     | 20.60                | 48               | 27.40          | 20                          | 11.40                     | 5             | 2.90               | 
| Gun as club                           | 1                    | 7.10               | 0                 | 0.00            | 3                      | 21.40                | 9                | 64.30          | 0                           | 0.00                      | 1             | 7.10               | 
| Police shield                         | 0                    | 0.00               | 5                 | 55.60           | 2                      | 22.20                | 0                | 0.00           | 2                           | 22.20                     | 0             | 0.00               | 
| Vehicle                               | 0                    | 0.00               | 3                 | 15.80           | 8                      | 42.10                | 7                | 36.80          | 1                           | 5.30                      | 0             | 0.00               | 
| Other blunt instrument as club        | 2                    | 5.40               | 1                 | 2.70            | 9                      | 24.30                | 19               | 51.40          | 6                           | 16.20                     | 0             | 0.00               | 
| Hit against inanimate object          | 1                    | 1.40               | 20                | 28.60           | 21                     | 30.00                | 23               | 32.90          | 4                           | 5.70                      | 1             | 1.40               | 
| Chokehold                             | 3                    | 2.50               | 0                 | 0.00            | 45                     | 37.50                | 55               | 45.80          | 17                          | 14.20                     | 0             | 0.00               | 
| Pepper spray                          | 4                    | 2.70               | 116               | 77.30           | 8                      | 5.30                 | 16               | 10.70          | 6                           | 4.00                      | 0             | 0.00               | 
```