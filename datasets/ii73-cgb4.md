# Disposition Of Discourtesy Allegations 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-discourtesy-allegations-2008-230ac) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ii73-cgb4) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ii73-cgb4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ii73-cgb4/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ii73-cgb4 |
| Name | Disposition Of Discourtesy Allegations 2008 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:30:54Z |
| Publication Date | 2011-09-28T22:32:17Z |

## Description

CCRB: Disposition of Discourtesy Allegations 2008

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
series e:ii73-cgb4 d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Word t:substantiated_number=31 t:exonerated_number=21 t:unfounded_number=255 t:unsubstantiated_number=847 t:officer_unidentified_number=178 m:miscellaneous=43 m:unfounded_rate=18.5 m:officer_unidentified_rate=12.9 m:miscellaneous_rate=3.1 m:sunstantiated_rate=2.3 m:unsubstantiated_rate=61.6 m:exonerated_rate=1.5

series e:ii73-cgb4 d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Gesture t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=0 t:unsubstantiated_number=6 t:officer_unidentified_number=3 m:miscellaneous=2 m:unfounded_rate=0 m:officer_unidentified_rate=27.3 m:miscellaneous_rate=18.2 m:sunstantiated_rate=0 m:unsubstantiated_rate=54.5 m:exonerated_rate=0

series e:ii73-cgb4 d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Demeanor/tone t:substantiated_number=0 t:exonerated_number=1 t:unfounded_number=0 t:unsubstantiated_number=2 t:officer_unidentified_number=1 m:miscellaneous=0 m:unfounded_rate=0 m:officer_unidentified_rate=25 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=50 m:exonerated_rate=25
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

entity e:ii73-cgb4 l:"Disposition Of Discourtesy Allegations 2008" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/ii73-cgb4

property e:ii73-cgb4 t:meta.view v:id=ii73-cgb4 v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Discourtesy Allegations 2008" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:ii73-cgb4 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ii73-cgb4 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Word                                  | 31                   | 2.30               | 21                | 1.50            | 847                    | 61.60                | 255              | 18.50          | 178                         | 12.90                     | 43            | 3.10               | 
| Gesture                               | 0                    | 0.00               | 0                 | 0.00            | 6                      | 54.50                | 0                | 0.00           | 3                           | 27.30                     | 2             | 18.20              | 
| Demeanor/tone                         | 0                    | 0.00               | 1                 | 25.00           | 2                      | 50.00                | 0                | 0.00           | 1                           | 25.00                     | 0             | 0.00               | 
| Action                                | 1                    | 1.40               | 3                 | 4.30            | 45                     | 64.30                | 13               | 18.60          | 4                           | 5.70                      | 4             | 5.70               | 
| Other                                 | 0                    | 0.00               | 0                 | 0.00            | 0                      | 0.00                 | 0                | 0.00           | 0                           | 0.00                      | 0             | 0.00               | 
| Total                                 | 32                   | 2.20               | 25                | 1.70            | 900                    | 61.60                | 268              | 18.40          | 186                         | 12.70                     | 49            | 3.40               | 
```