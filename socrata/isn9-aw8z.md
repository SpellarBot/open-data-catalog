# Disposition Of Force Allegations 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-force-allegations-2005-2009-2ec94) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/isn9-aw8z) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/isn9-aw8z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/isn9-aw8z/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | isn9-aw8z |
| Name | Disposition Of Force Allegations 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:39:34Z |
| Publication Date | 2011-09-28T22:40:40Z |

## Description

CCRB: Disposition of Force Allegations 2005 - 2009

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
series e:isn9-aw8z d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun fired" t:substantiated_number=2 t:exonerated_number=65 t:unfounded_number=1 t:unsubstantiated_number=5 t:officer_unidentified_number=0 m:miscellaneous=10 m:unfounded_rate=1.2 m:officer_unidentified_rate=0 m:miscellaneous_rate=12 m:sunstantiated_rate=2.4 m:unsubstantiated_rate=6 m:exonerated_rate=78.3

series e:isn9-aw8z d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Gun pointed" t:substantiated_number=22 t:exonerated_number=707 t:unfounded_number=184 t:unsubstantiated_number=160 t:officer_unidentified_number=70 m:miscellaneous=27 m:unfounded_rate=15.7 m:officer_unidentified_rate=6 m:miscellaneous_rate=2.3 m:sunstantiated_rate=1.9 m:unsubstantiated_rate=13.7 m:exonerated_rate=60.4

series e:isn9-aw8z d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Nightstick as club" t:substantiated_number=12 t:exonerated_number=246 t:unfounded_number=219 t:unsubstantiated_number=142 t:officer_unidentified_number=114 m:miscellaneous=12 m:unfounded_rate=29.4 m:officer_unidentified_rate=15.3 m:miscellaneous_rate=1.6 m:sunstantiated_rate=1.6 m:unsubstantiated_rate=19.1 m:exonerated_rate=33
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

entity e:isn9-aw8z l:"Disposition Of Force Allegations 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/isn9-aw8z

property e:isn9-aw8z t:meta.view v:id=isn9-aw8z v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Force Allegations 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:isn9-aw8z t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:isn9-aw8z t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Gun fired                             | 2                    | 2.40               | 65                | 78.30           | 5                      | 6.00                 | 1                | 1.20           | 0                           | 0.00                      | 10            | 12.00              | 
| Gun pointed                           | 22                   | 1.90               | 707               | 60.40           | 160                    | 13.70                | 184              | 15.70          | 70                          | 6.00                      | 27            | 2.30               | 
| Nightstick as club                    | 12                   | 1.60               | 246               | 33.00           | 142                    | 19.10                | 219              | 29.40          | 114                         | 15.30                     | 12            | 1.60               | 
| Gun as club                           | 4                    | 4.30               | 8                 | 8.70            | 25                     | 27.20                | 43               | 46.70          | 6                           | 6.50                      | 6             | 6.50               | 
| Police shield                         | 0                    | 0.00               | 20                | 60.60           | 6                      | 18.20                | 2                | 6.10           | 5                           | 15.20                     | 0             | 0.00               | 
| Vehicle                               | 2                    | 2.30               | 11                | 12.80           | 27                     | 31.40                | 36               | 41.90          | 8                           | 9.30                      | 2             | 2.30               | 
| Other blunt instrument as club        | 5                    | 2.60               | 14                | 7.20            | 42                     | 21.50                | 99               | 50.80          | 29                          | 14.90                     | 6             | 3.10               | 
| Hit against inanimate object          | 5                    | 1.30               | 80                | 20.40           | 126                    | 32.10                | 141              | 36.00          | 32                          | 8.20                      | 8             | 2.00               | 
| Chokehold                             | 5                    | 1.00               | 1                 | 0.20            | 145                    | 30.00                | 274              | 56.70          | 55                          | 11.40                     | 3             | 0.60               | 
| Pepper spray                          | 24                   | 2.80               | 598               | 70.90           | 72                     | 8.50                 | 81               | 9.60           | 60                          | 7.10                      | 9             | 1.10               | 
```