# Disposition Of Abuse Of Authority Allegations 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-abuse-of-authority-allegations-2009-a130c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/kcgr-4dqx) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/kcgr-4dqx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/kcgr-4dqx/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | kcgr-4dqx |
| Name | Disposition Of Abuse Of Authority Allegations 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T21:42:43Z |
| Publication Date | 2011-09-28T21:43:33Z |

## Description

CCRB: Disposition of Abuse of Authority Allegations 2009

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
series e:kcgr-4dqx d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Question and/or stop**" t:substantiated_number=0 t:exonerated_number=1 t:unfounded_number=0 t:unsubstantiated_number=0 t:officer_unidentified_number=0 m:miscellaneous=1 m:unfounded_rate=0 m:officer_unidentified_rate=0 m:miscellaneous_rate=50 m:sunstantiated_rate=0 m:unsubstantiated_rate=0 m:exonerated_rate=50

series e:kcgr-4dqx d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Question t:substantiated_number=29 t:exonerated_number=148 t:unfounded_number=3 t:unsubstantiated_number=29 t:officer_unidentified_number=10 m:miscellaneous=4 m:unfounded_rate=1.3 m:officer_unidentified_rate=4.5 m:miscellaneous_rate=1.8 m:sunstantiated_rate=13 m:unsubstantiated_rate=13 m:exonerated_rate=66.4

series e:kcgr-4dqx d:2009-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Stop t:substantiated_number=75 t:exonerated_number=385 t:unfounded_number=17 t:unsubstantiated_number=184 t:officer_unidentified_number=53 m:miscellaneous=11 m:unfounded_rate=2.3 m:officer_unidentified_rate=7.3 m:miscellaneous_rate=1.5 m:sunstantiated_rate=10.3 m:unsubstantiated_rate=25.4 m:exonerated_rate=53.1
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

entity e:kcgr-4dqx l:"Disposition Of Abuse Of Authority Allegations 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/kcgr-4dqx

property e:kcgr-4dqx t:meta.view v:id=kcgr-4dqx v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Abuse Of Authority Allegations 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:kcgr-4dqx t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:kcgr-4dqx t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Question and/or stop**                | 0                    | 0.00               | 1                 | 50.00           | 0                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 1             | 50.00              | 
| Question                              | 29                   | 13.00              | 148               | 66.40           | 29                     | 13.00                | 3                | 1.30           | 10                          | 4.50                      | 4             | 1.80               | 
| Stop                                  | 75                   | 10.30              | 385               | 53.10           | 184                    | 25.40                | 17               | 2.30           | 53                          | 7.30                      | 11            | 1.50               | 
| Frisk and/or search*                  | 0                    |                    | 0                 |                 | 0                      |                      | 0                |                | 0                           |                           | 0             |                    | 
| Search                                | 51                   | 9.10               | 105               | 18.80           | 289                    | 51.60                | 42               | 7.50           | 64                          | 11.40                     | 9             | 1.60               | 
| Frisk                                 | 53                   | 13.00              | 162               | 39.80           | 126                    | 31.00                | 13               | 3.20           | 52                          | 12.80                     | 1             | 0.20               | 
| Vehicle search                        | 30                   | 8.70               | 145               | 41.90           | 120                    | 34.70                | 13               | 3.80           | 29                          | 8.40                      | 9             | 2.60               | 
| Vehicle stop                          | 16                   | 6.70               | 127               | 52.90           | 67                     | 27.90                | 2                | 0.80           | 22                          | 9.20                      | 6             | 2.50               | 
| Premises entered or searched          | 12                   | 2.60               | 360               | 76.60           | 75                     | 16.00                | 8                | 1.70           | 12                          | 2.60                      | 3             | 0.60               | 
| Strip search                          | 5                    | 2.60               | 50                | 26.00           | 83                     | 43.20                | 33               | 17.20          | 16                          | 8.30                      | 5             | 2.60               | 
```