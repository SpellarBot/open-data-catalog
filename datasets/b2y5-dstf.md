# Disposition Of Discourtesy Allegations 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-discourtesy-allegations-2006-c2393) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/b2y5-dstf) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/b2y5-dstf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/b2y5-dstf/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | b2y5-dstf |
| Name | Disposition Of Discourtesy Allegations 2006 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Recreation |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:12:46Z |
| Publication Date | 2013-06-21T20:27:40Z |

## Description

CCRB: Disposition of Discourtesy Allegations 2006

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
series e:b2y5-dstf d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Word t:substantiated_number=75 t:exonerated_number=87 t:unfounded_number=458 t:unsubstantiated_number=541 t:officer_unidentified_number=178 m:miscellaneous=51 m:unfounded_rate=32.9 m:officer_unidentified_rate=12.8 m:miscellaneous_rate=3.7 m:sunstantiated_rate=5.4 m:unsubstantiated_rate=38.9 m:exonerated_rate=6.3

series e:b2y5-dstf d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Gesture t:substantiated_number=2 t:exonerated_number=0 t:unfounded_number=3 t:unsubstantiated_number=8 t:officer_unidentified_number=0 m:miscellaneous=0 m:unfounded_rate=23.1 m:officer_unidentified_rate=0 m:miscellaneous_rate=0 m:sunstantiated_rate=15.4 m:unsubstantiated_rate=61.5 m:exonerated_rate=0

series e:b2y5-dstf d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Demeanor/tone t:substantiated_number=0 t:exonerated_number=6 t:unfounded_number=6 t:unsubstantiated_number=20 t:officer_unidentified_number=3 m:miscellaneous=4 m:unfounded_rate=15.4 m:officer_unidentified_rate=7.7 m:miscellaneous_rate=10.3 m:sunstantiated_rate=0 m:unsubstantiated_rate=51.3 m:exonerated_rate=15.4
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

entity e:b2y5-dstf l:"Disposition Of Discourtesy Allegations 2006" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/b2y5-dstf

property e:b2y5-dstf t:meta.view v:id=b2y5-dstf v:category=Recreation v:averageRating=0 v:name="Disposition Of Discourtesy Allegations 2006" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:b2y5-dstf t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:b2y5-dstf t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Word                                  | 75                   | 5.40               | 87                | 6.30            | 541                    | 38.90                | 458              | 32.90          | 178                         | 12.80                     | 51            | 3.70               | 
| Gesture                               | 2                    | 15.40              | 0                 | 0.00            | 8                      | 61.50                | 3                | 23.10          | 0                           | 0.00                      | 0             | 0.00               | 
| Demeanor/tone                         | 0                    | 0.00               | 6                 | 15.40           | 20                     | 51.30                | 6                | 15.40          | 3                           | 7.70                      | 4             | 10.30              | 
| Action                                | 2                    | 2.00               | 7                 | 6.90            | 50                     | 49.50                | 24               | 23.80          | 16                          | 15.80                     | 2             | 2.00               | 
| Other                                 | 0                    | 0.00               | 0                 | 0.00            | 2                      | 66.70                | 1                | 33.30          | 0                           | 0.00                      | 0             | 0.00               | 
| Total                                 | 79                   | 5.10               | 100               | 6.50            | 621                    | 40.20                | 492              | 31.80          | 197                         | 12.70                     | 57            | 3.70               | 
```