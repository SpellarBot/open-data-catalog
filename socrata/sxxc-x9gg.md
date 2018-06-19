# Disposition Of Offensive Language Allegations 2006

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-offensive-language-allegations-2006-da658) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/sxxc-x9gg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/sxxc-x9gg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/sxxc-x9gg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | sxxc-x9gg |
| Name | Disposition Of Offensive Language Allegations 2006 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T23:12:29Z |
| Publication Date | 2011-09-28T23:14:10Z |

## Description

CCRB: Disposition of Offensive Language Allegations 2006

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
series e:sxxc-x9gg d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Race t:substantiated_number=1 t:exonerated_number=0 t:unfounded_number=81 t:unsubstantiated_number=52 t:officer_unidentified_number=15 m:miscellaneous=6 m:unfounded_rate=52.3 m:officer_unidentified_rate=9.7 m:miscellaneous_rate=3.9 m:sunstantiated_rate=0.6 m:unsubstantiated_rate=33.5 m:exonerated_rate=0

series e:sxxc-x9gg d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Ethnicity t:substantiated_number=0 t:exonerated_number=2 t:unfounded_number=21 t:unsubstantiated_number=28 t:officer_unidentified_number=4 m:miscellaneous=2 m:unfounded_rate=36.8 m:officer_unidentified_rate=7 m:miscellaneous_rate=3.5 m:sunstantiated_rate=0 m:unsubstantiated_rate=49.1 m:exonerated_rate=3.5

series e:sxxc-x9gg d:2006-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Religion t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=5 t:unsubstantiated_number=3 t:officer_unidentified_number=1 m:miscellaneous=0 m:unfounded_rate=55.6 m:officer_unidentified_rate=11.1 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=33.3 m:exonerated_rate=0
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

entity e:sxxc-x9gg l:"Disposition Of Offensive Language Allegations 2006" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/sxxc-x9gg

property e:sxxc-x9gg t:meta.view v:id=sxxc-x9gg v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Offensive Language Allegations 2006" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:sxxc-x9gg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:sxxc-x9gg t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Race                                  | 1                    | 0.60               | 0                 | 0.00            | 52                     | 33.50                | 81               | 52.30          | 15                          | 9.70                      | 6             | 3.90               | 
| Ethnicity                             | 0                    | 0.00               | 2                 | 3.50            | 28                     | 49.10                | 21               | 36.80          | 4                           | 7.00                      | 2             | 3.50               | 
| Religion                              | 0                    | 0.00               | 0                 | 0.00            | 3                      | 33.30                | 5                | 55.60          | 1                           | 11.10                     | 0             | 0.00               | 
| Sex                                   | 0                    | 0.00               | 0                 | 0.00            | 5                      | 35.70                | 8                | 57.10          | 1                           | 7.10                      | 0             | 0.00               | 
| Physical disability                   | 0                    | 0.00               | 0                 | 0.00            | 0                      | 0.00                 | 0                | 0.00           | 1                           | 100.00                    | 0             | 0.00               | 
| Sexual orientation                    | 2                    | 6.90               | 0                 | 0.00            | 12                     | 41.40                | 5                | 17.20          | 5                           | 17.20                     | 5             | 17.20              | 
| Other                                 | 0                    | 0.00               | 0                 | 0.00            | 2                      | 50.00                | 0                | 0.00           | 0                           | 0.00                      | 2             | 50.00              | 
| Total                                 | 3                    | 1.10               | 2                 | 0.70            | 102                    | 37.90                | 120              | 44.60          | 27                          | 10.00                     | 15            | 5.60               | 
```