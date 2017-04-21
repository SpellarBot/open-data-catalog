# Disposition Of Offensive Language Allegations 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-offensive-language-allegations-2005-2009-63988) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sxh6-h6ph) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sxh6-h6ph/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sxh6-h6ph/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sxh6-h6ph |
| Name | Disposition Of Offensive Language Allegations 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T23:01:29Z |
| Publication Date | 2011-09-28T23:02:46Z |

## Description

CCRB: Disposition of Offensive Language Allegations 2005 - 2009

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
series e:sxh6-h6ph d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Race t:substantiated_number=18 t:exonerated_number=0 t:unfounded_number=346 t:unsubstantiated_number=279 t:officer_unidentified_number=83 m:miscellaneous=20 m:unfounded_rate=46.4 m:officer_unidentified_rate=11.1 m:miscellaneous_rate=2.7 m:sunstantiated_rate=2.4 m:unsubstantiated_rate=37.4 m:exonerated_rate=0

series e:sxh6-h6ph d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Ethnicity t:substantiated_number=5 t:exonerated_number=2 t:unfounded_number=98 t:unsubstantiated_number=131 t:officer_unidentified_number=20 m:miscellaneous=6 m:unfounded_rate=37.4 m:officer_unidentified_rate=7.6 m:miscellaneous_rate=2.3 m:sunstantiated_rate=1.9 m:unsubstantiated_rate=50 m:exonerated_rate=0.8

series e:sxh6-h6ph d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Religion t:substantiated_number=0 t:exonerated_number=1 t:unfounded_number=21 t:unsubstantiated_number=19 t:officer_unidentified_number=6 m:miscellaneous=0 m:unfounded_rate=44.7 m:officer_unidentified_rate=12.8 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=40.4 m:exonerated_rate=2.1
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

entity e:sxh6-h6ph l:"Disposition Of Offensive Language Allegations 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/sxh6-h6ph

property e:sxh6-h6ph t:meta.view v:id=sxh6-h6ph v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Offensive Language Allegations 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:sxh6-h6ph t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sxh6-h6ph t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Race                                  | 18                   | 2.40               | 0                 | 0.00            | 279                    | 37.40                | 346              | 46.40          | 83                          | 11.10                     | 20            | 2.70               | 
| Ethnicity                             | 5                    | 1.90               | 2                 | 0.80            | 131                    | 50.00                | 98               | 37.40          | 20                          | 7.60                      | 6             | 2.30               | 
| Religion                              | 0                    | 0.00               | 1                 | 2.10            | 19                     | 40.40                | 21               | 44.70          | 6                           | 12.80                     | 0             | 0.00               | 
| Sex                                   | 3                    | 3.00               | 0                 | 0.00            | 46                     | 46.50                | 43               | 43.40          | 6                           | 6.10                      | 1             | 1.00               | 
| Physical disability                   | 2                    | 14.30              | 0                 | 0.00            | 6                      | 42.90                | 2                | 14.30          | 4                           | 28.60                     | 0             | 0.00               | 
| Sexual orientation                    | 7                    | 5.20               | 1                 | 0.70            | 69                     | 51.10                | 33               | 24.40          | 19                          | 14.10                     | 6             | 4.40               | 
| Other                                 | 0                    | 0.00               | 0                 | 0.00            | 14                     | 53.80                | 7                | 26.90          | 3                           | 11.50                     | 2             | 7.70               | 
| Total                                 | 35                   | 2.60               | 4                 | 0.30            | 564                    | 42.40                | 550              | 41.40          | 141                         | 10.60                     | 35            | 2.60               | 
```