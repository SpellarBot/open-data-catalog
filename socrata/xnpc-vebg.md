# Disposition Of Discourtesy Allegations 2007

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-discourtesy-allegations-2007-9ae0c) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/xnpc-vebg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/xnpc-vebg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/xnpc-vebg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | xnpc-vebg |
| Name | Disposition Of Discourtesy Allegations 2007 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T22:15:29Z |
| Publication Date | 2011-09-28T22:16:20Z |

## Description

CCRB: Disposition of Discourtesy Allegations 2007

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | type_of_abuse_of_authority_allegation | Type of Abuse of Authority Allegation | text      | text        |
| Yes      | series tag     | substantiated_number                  | Substantiated Number                  | text      | number      |
| Yes      | series tag     | sunstantiated_rate                    | Sunstantiated rate                    | text      | text        |
| Yes      | series tag     | exonerated_number                     | Exonerated number                     | text      | number      |
| Yes      | series tag     | exonerated_rate                       | Exonerated rate                       | text      | text        |
| Yes      | series tag     | unsubstantiated_number                | Unsubstantiated number                | text      | number      |
| Yes      | series tag     | unsubstantiated_rate                  | Unsubstantiated rate                  | text      | text        |
| Yes      | series tag     | unfounded_number                      | Unfounded number                      | text      | number      |
| Yes      | series tag     | unfounded_rate                        | Unfounded rate                        | text      | text        |
| Yes      | series tag     | officer_unidentified_number           | Officer Unidentified number           | text      | number      |
| Yes      | series tag     | officer_unidentified_rate             | Officer Unidentified rate             | text      | text        |
| Yes      | numeric metric | miscellaneous                         | Miscellaneous                         | number    | number      |
| Yes      | series tag     | miscellaneous_rate                    | Miscellaneous rate                    | text      | text        |
```

## Time Field

```ls
Value = 2007
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xnpc-vebg d:2007-01-01T00:00:00.000Z t:miscellaneous_rate=2.40% t:officer_unidentified_rate=12.40% t:unfounded_rate=31.70% t:sunstantiated_rate=2.40% t:unsubstantiated_rate=44.20% t:type_of_abuse_of_authority_allegation=Word t:substantiated_number=37 t:exonerated_number=109 t:unfounded_number=496 t:exonerated_rate=7.00% t:unsubstantiated_number=691 t:officer_unidentified_number=194 m:miscellaneous=37

series e:xnpc-vebg d:2007-01-01T00:00:00.000Z t:miscellaneous_rate=0.00% t:officer_unidentified_rate=28.60% t:unfounded_rate=19.00% t:sunstantiated_rate=0.00% t:unsubstantiated_rate=52.40% t:type_of_abuse_of_authority_allegation=Gesture t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=4 t:exonerated_rate=0.00% t:unsubstantiated_number=11 t:officer_unidentified_number=6 m:miscellaneous=0

series e:xnpc-vebg d:2007-01-01T00:00:00.000Z t:miscellaneous_rate=0.00% t:officer_unidentified_rate=9.10% t:unfounded_rate=36.40% t:sunstantiated_rate=0.00% t:unsubstantiated_rate=45.50% t:type_of_abuse_of_authority_allegation=Demeanor/tone t:substantiated_number=0 t:exonerated_number=1 t:unfounded_number=4 t:exonerated_rate=9.10% t:unsubstantiated_number=5 t:officer_unidentified_number=1 m:miscellaneous=0
```

## Meta Commands

```ls
metric m:miscellaneous p:integer l:Miscellaneous t:dataTypeName=number

entity e:xnpc-vebg l:"Disposition Of Discourtesy Allegations 2007" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/xnpc-vebg

property e:xnpc-vebg t:meta.view v:id=xnpc-vebg v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Discourtesy Allegations 2007" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:xnpc-vebg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:xnpc-vebg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Word                                  | 37                   | 2.40%              | 109               | 7.00%           | 691                    | 44.20%               | 496              | 31.70%         | 194                         | 12.40%                    | 37            | 2.40%              | 
| Gesture                               | 0                    | 0.00%              | 0                 | 0.00%           | 11                     | 52.40%               | 4                | 19.00%         | 6                           | 28.60%                    | 0             | 0.00%              | 
| Demeanor/tone                         | 0                    | 0.00%              | 1                 | 9.10%           | 5                      | 45.50%               | 4                | 36.40%         | 1                           | 9.10%                     | 0             | 0.00%              | 
| Action                                | 2                    | 2.90%              | 1                 | 1.40%           | 36                     | 52.20%               | 21               | 30.40%         | 8                           | 11.60%                    | 1             | 1.40%              | 
| Other                                 | 0                    | #DIV/0!            | 0                 | #DIV/0!         | 0                      | #DIV/0!              | 0                | #DIV/0!        | 0                           | #DIV/0!                   | 0             | #DIV/0!            | 
| Total                                 | 39                   | 2.30%              | 111               | 6.70%           | 743                    | 44.60%               | 525              | 31.50%         | 209                         | 12.60%                    | 38            | 2.30%              | 
```