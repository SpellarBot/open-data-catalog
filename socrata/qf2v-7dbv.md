# Disposition Of Abuse Of Authority Allegations 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-abuse-of-authority-allegations-2005-f8a99) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/qf2v-7dbv) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/qf2v-7dbv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/qf2v-7dbv/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | qf2v-7dbv |
| Name | Disposition Of Abuse Of Authority Allegations 2005 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T20:58:03Z |
| Publication Date | 2011-09-28T20:59:35Z |

## Description

CCRB: Disposition of Abuse of Authority Allegations 2005

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
series e:qf2v-7dbv d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Question and/or stop**" t:substantiated_number=78 t:exonerated_number=641 t:unfounded_number=24 t:unsubstantiated_number=118 t:officer_unidentified_number=70 m:miscellaneous=23 m:unfounded_rate=2.5 m:officer_unidentified_rate=7.3 m:miscellaneous_rate=2.4 m:sunstantiated_rate=8.2 m:unsubstantiated_rate=12.4 m:exonerated_rate=67.2

series e:qf2v-7dbv d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Question t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=0 t:unsubstantiated_number=0 t:officer_unidentified_number=0 m:miscellaneous=0 m:unfounded_rate=0 m:officer_unidentified_rate=0 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=0 m:exonerated_rate=0

series e:qf2v-7dbv d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Stop t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=0 t:unsubstantiated_number=0 t:officer_unidentified_number=0 m:miscellaneous=0 m:unfounded_rate=0 m:officer_unidentified_rate=0 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=0 m:exonerated_rate=0
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

entity e:qf2v-7dbv l:"Disposition Of Abuse Of Authority Allegations 2005" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/qf2v-7dbv

property e:qf2v-7dbv t:meta.view v:id=qf2v-7dbv v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Abuse Of Authority Allegations 2005" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:qf2v-7dbv t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:qf2v-7dbv t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Type of Abuse of Authority Allegation |                      |                    |                   |                 |                        |                      |                  |                |                             |                           |               |                    | 
| Question and/or stop**                | 78                   | 8.20               | 641               | 67.20           | 118                    | 12.40                | 24               | 2.50           | 70                          | 7.30                      | 23            | 2.40               | 
| Question                              | 0                    | 0.00               | 0                 | 0.00            | 0                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 0             | 0.00               | 
| Stop                                  | 0                    | 0.00               | 0                 | 0.00            | 0                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 0             | 0.00               | 
| Frisk and/or search*                  | 34                   | 15.00              | 75                | 33.00           | 60                     | 26.40                | 18               | 7.90           | 37                          | 16.30                     | 3             | 1.30               | 
| Search                                | 41                   | 0.00               | 76                | 0.00            | 82                     | 0.00                 | 46               | 0.00           | 34                          | 0.00                      | 7             | 0.00               | 
| Frisk                                 | 29                   | 0.00               | 105               | 0.00            | 31                     | 0.00                 | 7                | 0.00           | 21                          | 0.00                      | 3             | 0.00               | 
| Vehicle search                        | 36                   | 15.30              | 92                | 39.00           | 64                     | 27.10                | 19               | 8.10           | 22                          | 9.30                      | 3             | 1.30               | 
| Vehicle stop                          | 22                   | 7.80               | 183               | 64.70           | 42                     | 14.80                | 2                | 0.70           | 24                          | 8.50                      | 10            | 3.50               | 
| Premises entered or searched          | 32                   | 7.10               | 305               | 67.60           | 63                     | 14.00                | 24               | 5.30           | 18                          | 4.00                      | 9             | 2.00               | 
```