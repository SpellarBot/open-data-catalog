# Disposition Of Force Allegations 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-force-allegations-2008-0b1d4) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nufv-bxfc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nufv-bxfc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nufv-bxfc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nufv-bxfc |
| Name | Disposition Of Force Allegations 2008 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:56:02Z |
| Publication Date | 2011-09-28T22:57:08Z |

## Description

CCRB: Disposition of Force Allegations 2008

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
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:nufv-bxfc d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun fired" t:substantiated_number=0 t:exonerated_number=12 t:unfounded_number=0 t:unsubstantiated_number=0 t:officer_unidentified_number=0 m:miscellaneous=2 m:unfounded_rate=0 m:officer_unidentified_rate=0 m:miscellaneous_rate=14.3 m:sunstantiated_rate=0 m:unsubstantiated_rate=0 m:exonerated_rate=85.7

series e:nufv-bxfc d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun pointed" t:substantiated_number=4 t:exonerated_number=122 t:unfounded_number=24 t:unsubstantiated_number=50 t:officer_unidentified_number=6 m:miscellaneous=2 m:unfounded_rate=11.5 m:officer_unidentified_rate=2.9 m:miscellaneous_rate=1 m:sunstantiated_rate=1.9 m:unsubstantiated_rate=24 m:exonerated_rate=58.7

series e:nufv-bxfc d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Nightstick as club" t:substantiated_number=2 t:exonerated_number=50 t:unfounded_number=31 t:unsubstantiated_number=44 t:officer_unidentified_number=28 m:miscellaneous=0 m:unfounded_rate=20 m:officer_unidentified_rate=18.1 m:miscellaneous_rate=0 m:sunstantiated_rate=1.3 m:unsubstantiated_rate=28.4 m:exonerated_rate=32.3
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

entity e:nufv-bxfc l:"Disposition Of Force Allegations 2008" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/nufv-bxfc

property e:nufv-bxfc t:meta.view v:id=nufv-bxfc v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Force Allegations 2008" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:nufv-bxfc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nufv-bxfc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Gun fired                             | 0                    | 0.00               | 12                | 85.70           | 0                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 2             | 14.30              | 
| Gun pointed                           | 4                    | 1.90               | 122               | 58.70           | 50                     | 24.00                | 24               | 11.50          | 6                           | 2.90                      | 2             | 1.00               | 
| Nightstick as club                    | 2                    | 1.30               | 50                | 32.30           | 44                     | 28.40                | 31               | 20.00          | 28                          | 18.10                     | 0             | 0.00               | 
| Gun as club                           | 0                    | 0.00               | 2                 | 10.50           | 9                      | 47.40                | 7                | 36.80          | 0                           | 0.00                      | 1             | 5.30               | 
| Police shield                         | 0                    | 0.00               | 6                 | 60.00           | 4                      | 40.00                | 0                | 0.00           | 0                           | 0.00                      | 0             | 0.00               | 
| Vehicle                               | 0                    | 0.00               | 0                 | 0.00            | 7                      | 53.80                | 3                | 23.10          | 3                           | 23.10                     | 0             | 0.00               | 
| Other blunt instrument as club        | 3                    | 8.10               | 2                 | 5.40            | 11                     | 29.70                | 15               | 40.50          | 5                           | 13.50                     | 1             | 2.70               | 
| Hit against inanimate object          | 0                    | 0.00               | 14                | 20.30           | 30                     | 43.50                | 17               | 24.60          | 6                           | 8.70                      | 2             | 2.90               | 
| Chokehold                             | 0                    | 0.00               | 0                 | 0.00            | 36                     | 42.90                | 38               | 45.20          | 10                          | 11.90                     | 0             | 0.00               | 
| Pepper spray                          | 3                    | 1.90               | 93                | 60.00           | 23                     | 14.80                | 14               | 9.00           | 19                          | 12.30                     | 3             | 1.90               | 
```