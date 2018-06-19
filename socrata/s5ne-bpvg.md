# Disposition Of Offensive Language Allegations 2005

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-offensive-language-allegations-2005-0883a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/s5ne-bpvg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/s5ne-bpvg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/s5ne-bpvg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | s5ne-bpvg |
| Name | Disposition Of Offensive Language Allegations 2005 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T23:09:07Z |
| Publication Date | 2011-09-28T23:10:13Z |

## Description

CCRB: Disposition of Offensive Language Allegations 2005

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
series e:s5ne-bpvg d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Race t:substantiated_number=13 t:exonerated_number=0 t:unfounded_number=78 t:unsubstantiated_number=42 t:officer_unidentified_number=11 m:miscellaneous=3 m:unfounded_rate=53.1 m:officer_unidentified_rate=7.5 m:miscellaneous_rate=2 m:sunstantiated_rate=8.8 m:unsubstantiated_rate=28.6 m:exonerated_rate=0

series e:s5ne-bpvg d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Ethnicity t:substantiated_number=3 t:exonerated_number=0 t:unfounded_number=22 t:unsubstantiated_number=34 t:officer_unidentified_number=6 m:miscellaneous=3 m:unfounded_rate=32.4 m:officer_unidentified_rate=8.8 m:miscellaneous_rate=4.4 m:sunstantiated_rate=4.4 m:unsubstantiated_rate=50 m:exonerated_rate=0

series e:s5ne-bpvg d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Religion t:substantiated_number=0 t:exonerated_number=1 t:unfounded_number=5 t:unsubstantiated_number=4 t:officer_unidentified_number=1 m:miscellaneous=0 m:unfounded_rate=45.5 m:officer_unidentified_rate=9.1 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=36.4 m:exonerated_rate=9.1
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

entity e:s5ne-bpvg l:"Disposition Of Offensive Language Allegations 2005" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/s5ne-bpvg

property e:s5ne-bpvg t:meta.view v:id=s5ne-bpvg v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Offensive Language Allegations 2005" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:s5ne-bpvg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:s5ne-bpvg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Race                                  | 13                   | 8.80               | 0                 | 0.00            | 42                     | 28.60                | 78               | 53.10          | 11                          | 7.50                      | 3             | 2.00               | 
| Ethnicity                             | 3                    | 4.40               | 0                 | 0.00            | 34                     | 50.00                | 22               | 32.40          | 6                           | 8.80                      | 3             | 4.40               | 
| Religion                              | 0                    | 0.00               | 1                 | 9.10            | 4                      | 36.40                | 5                | 45.50          | 1                           | 9.10                      | 0             | 0.00               | 
| Sex                                   | 2                    | 22.20              | 0                 | 0.00            | 4                      | 44.40                | 3                | 33.30          | 0                           | 0.00                      | 0             | 0.00               | 
| Physical disability                   | 2                    | 50.00              | 0                 | 0.00            | 1                      | 25.00                | 0                | 0.00           | 1                           | 25.00                     | 0             | 0.00               | 
| Sexual orientation                    | 2                    | 7.70               | 1                 | 3.80            | 10                     | 38.50                | 7                | 26.90          | 6                           | 23.10                     | 0             | 0.00               | 
| Other                                 | 0                    | 0.00               | 0                 | 0.00            | 5                      | 41.70                | 6                | 50.00          | 1                           | 8.30                      | 0             | 0.00               | 
| Total                                 | 22                   | 7.90               | 2                 | 0.70            | 100                    | 36.10                | 121              | 43.70          | 26                          | 9.40                      | 6             | 2.20               | 
```