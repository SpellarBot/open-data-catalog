# Disposition Of Abuse Of Authority Allegations 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-abuse-of-authority-allegations-2008-7948e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yid9-y2bb) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yid9-y2bb/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yid9-y2bb/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yid9-y2bb |
| Name | Disposition Of Abuse Of Authority Allegations 2008 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T21:40:45Z |
| Publication Date | 2011-09-28T21:41:32Z |

## Description

CCRB: Disposition of Abuse of Authority Allegations 2008

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
series e:yid9-y2bb d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Question and/or stop**" t:substantiated_number=6 t:exonerated_number=24 t:unfounded_number=1 t:unsubstantiated_number=6 t:officer_unidentified_number=17 m:miscellaneous=2 m:unfounded_rate=1.8 m:officer_unidentified_rate=30.4 m:miscellaneous_rate=3.6 m:sunstantiated_rate=10.7 m:unsubstantiated_rate=10.7 m:exonerated_rate=42.9

series e:yid9-y2bb d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Question t:substantiated_number=5 t:exonerated_number=113 t:unfounded_number=3 t:unsubstantiated_number=36 t:officer_unidentified_number=14 m:miscellaneous=4 m:unfounded_rate=1.7 m:officer_unidentified_rate=8 m:miscellaneous_rate=2.3 m:sunstantiated_rate=2.9 m:unsubstantiated_rate=20.6 m:exonerated_rate=64.6

series e:yid9-y2bb d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Stop t:substantiated_number=45 t:exonerated_number=368 t:unfounded_number=7 t:unsubstantiated_number=236 t:officer_unidentified_number=49 m:miscellaneous=17 m:unfounded_rate=1 m:officer_unidentified_rate=6.8 m:miscellaneous_rate=2.4 m:sunstantiated_rate=6.2 m:unsubstantiated_rate=32.7 m:exonerated_rate=51
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

entity e:yid9-y2bb l:"Disposition Of Abuse Of Authority Allegations 2008" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/yid9-y2bb

property e:yid9-y2bb t:meta.view v:id=yid9-y2bb v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Abuse Of Authority Allegations 2008" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:yid9-y2bb t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yid9-y2bb t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Question and/or stop**                | 6                    | 10.70              | 24                | 42.90           | 6                      | 10.70                | 1                | 1.80           | 17                          | 30.40                     | 2             | 3.60               | 
| Question                              | 5                    | 2.90               | 113               | 64.60           | 36                     | 20.60                | 3                | 1.70           | 14                          | 8.00                      | 4             | 2.30               | 
| Stop                                  | 45                   | 6.20               | 368               | 51.00           | 236                    | 32.70                | 7                | 1.00           | 49                          | 6.80                      | 17            | 2.40               | 
| Frisk and/or search*                  | 0                    | 0.00               | 1                 | 50.00           | 0                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 1             | 50.00              | 
| Search                                | 27                   | 5.40               | 112               | 22.40           | 257                    | 51.50                | 23               | 4.60           | 72                          | 14.40                     | 8             | 1.60               | 
| Frisk                                 | 35                   | 9.90               | 142               | 40.20           | 113                    | 32.00                | 9                | 2.50           | 48                          | 13.60                     | 6             | 1.70               | 
| Vehicle search                        | 26                   | 10.80              | 93                | 38.80           | 81                     | 33.80                | 7                | 2.90           | 26                          | 10.80                     | 7             | 2.90               | 
| Vehicle stop                          | 12                   | 5.60               | 121               | 56.50           | 62                     | 29.00                | 0                | 0.00           | 15                          | 7.00                      | 4             | 1.90               | 
| Premises entered or searched          | 26                   | 5.50               | 309               | 65.20           | 90                     | 19.00                | 15               | 3.20           | 24                          | 5.10                      | 10            | 2.10               | 
| Strip search                          | 16                   | 7.10               | 63                | 28.10           | 104                    | 46.40                | 21               | 9.40           | 16                          | 7.10                      | 4             | 1.80               | 
```