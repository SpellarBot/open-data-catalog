# Disposition Of Discourtesy Allegations 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-discourtesy-allegations-2005-2009-39223) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/cwjt-kigp) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/cwjt-kigp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/cwjt-kigp/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | cwjt-kigp |
| Name | Disposition Of Discourtesy Allegations 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:06:18Z |
| Publication Date | 2011-09-28T22:11:12Z |

## Description

CCRB: Disposition of Discourtesy Allegations 2005 - 2009

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
series e:cwjt-kigp d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Word t:substantiated_number=257 t:exonerated_number=339 t:unfounded_number=2006 t:unsubstantiated_number=3550 t:officer_unidentified_number=893 m:miscellaneous=190 m:unfounded_rate=27.7 m:officer_unidentified_rate=12.3 m:miscellaneous_rate=2.6 m:sunstantiated_rate=3.6 m:unsubstantiated_rate=49.1 m:exonerated_rate=4.7

series e:cwjt-kigp d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Gesture t:substantiated_number=3 t:exonerated_number=0 t:unfounded_number=20 t:unsubstantiated_number=45 t:officer_unidentified_number=14 m:miscellaneous=4 m:unfounded_rate=23.3 m:officer_unidentified_rate=16.3 m:miscellaneous_rate=4.7 m:sunstantiated_rate=3.5 m:unsubstantiated_rate=52.3 m:exonerated_rate=0

series e:cwjt-kigp d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Demeanor/tone t:substantiated_number=4 t:exonerated_number=18 t:unfounded_number=28 t:unsubstantiated_number=48 t:officer_unidentified_number=10 m:miscellaneous=7 m:unfounded_rate=24.3 m:officer_unidentified_rate=8.7 m:miscellaneous_rate=6.1 m:sunstantiated_rate=3.5 m:unsubstantiated_rate=41.7 m:exonerated_rate=15.7
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

entity e:cwjt-kigp l:"Disposition Of Discourtesy Allegations 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/cwjt-kigp

property e:cwjt-kigp t:meta.view v:id=cwjt-kigp v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Discourtesy Allegations 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:cwjt-kigp t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:cwjt-kigp t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Word                                  | 257                  | 3.60               | 339               | 4.70            | 3550                   | 49.10                | 2006             | 27.70          | 893                         | 12.30                     | 190           | 2.60               | 
| Gesture                               | 3                    | 3.50               | 0                 | 0.00            | 45                     | 52.30                | 20               | 23.30          | 14                          | 16.30                     | 4             | 4.70               | 
| Demeanor/tone                         | 4                    | 3.50               | 18                | 15.70           | 48                     | 41.70                | 28               | 24.30          | 10                          | 8.70                      | 7             | 6.10               | 
| Action                                | 14                   | 3.20               | 24                | 5.50            | 224                    | 50.90                | 120              | 27.30          | 44                          | 10.00                     | 14            | 3.20               | 
| Other                                 | 2                    | 10.50              | 1                 | 5.30            | 8                      | 42.10                | 7                | 36.80          | 0                           | 0.00                      | 1             | 5.30               | 
| Total                                 | 280                  | 3.50               | 382               | 4.80            | 3875                   | 49.10                | 2181             | 27.60          | 961                         | 12.20                     | 216           | 2.70               | 
```