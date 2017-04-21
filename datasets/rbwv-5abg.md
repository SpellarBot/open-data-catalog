# Disposition Of Discourtesy Allegations 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-discourtesy-allegations-2009-e3f99) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/rbwv-5abg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/rbwv-5abg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/rbwv-5abg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | rbwv-5abg |
| Name | Disposition Of Discourtesy Allegations 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:36:18Z |
| Publication Date | 2011-09-28T22:37:35Z |

## Description

CCRB: Disposition of Discourtesy Allegations 2009

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
series e:rbwv-5abg d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Word t:substantiated_number=37 t:exonerated_number=53 t:unfounded_number=343 t:unsubstantiated_number=918 t:officer_unidentified_number=167 m:miscellaneous=16 m:unfounded_rate=22.4 m:officer_unidentified_rate=10.9 m:miscellaneous_rate=1 m:sunstantiated_rate=2.4 m:unsubstantiated_rate=59.8 m:exonerated_rate=3.5

series e:rbwv-5abg d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Gesture t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=3 t:unsubstantiated_number=9 t:officer_unidentified_number=4 m:miscellaneous=0 m:unfounded_rate=18.8 m:officer_unidentified_rate=25 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=56.3 m:exonerated_rate=0

series e:rbwv-5abg d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Demeanor/tone t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=0 t:unsubstantiated_number=1 t:officer_unidentified_number=0 m:miscellaneous=0 m:unfounded_rate=0 m:officer_unidentified_rate=0 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=100 m:exonerated_rate=0
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

entity e:rbwv-5abg l:"Disposition Of Discourtesy Allegations 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/rbwv-5abg

property e:rbwv-5abg t:meta.view v:id=rbwv-5abg v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Discourtesy Allegations 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:rbwv-5abg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:rbwv-5abg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Word                                  | 37                   | 2.40               | 53                | 3.50            | 918                    | 59.80                | 343              | 22.40          | 167                         | 10.90                     | 16            | 1.00               | 
| Gesture                               | 0                    | 0.00               | 0                 | 0.00            | 9                      | 56.30                | 3                | 18.80          | 4                           | 25.00                     | 0             | 0.00               | 
| Demeanor/tone                         | 0                    | 0.00               | 0                 | 0.00            | 1                      | 100.00               | 0                | 0.00           | 0                           | 0.00                      | 0             | 0.00               | 
| Action                                | 2                    | 2.10               | 2                 | 2.10            | 56                     | 59.60                | 22               | 23.40          | 8                           | 8.50                      | 4             | 4.30               | 
| Other                                 | 0                    | 0.00               | 0                 | 0.00            | 2                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 0             | 0.00               | 
| Total                                 | 39                   | 2.40               | 55                | 3.30            | 986                    | 59.90                | 368              | 22.30          | 179                         | 10.90                     | 20            | 1.20               | 
```