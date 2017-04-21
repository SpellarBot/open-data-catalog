# Disposition Of Offensive Language Allegations 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/disposition-of-offensive-language-allegations-2008-00223) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mkxg-y5uc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mkxg-y5uc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mkxg-y5uc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mkxg-y5uc |
| Name | Disposition Of Offensive Language Allegations 2008 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-28T23:54:17Z |
| Publication Date | 2011-09-28T23:56:01Z |

## Description

CCRB: Disposition of Offensive Language Allegations 2008

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
series e:mkxg-y5uc d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Race t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=48 t:unsubstantiated_number=52 t:officer_unidentified_number=25 m:miscellaneous=0 m:unfounded_rate=38.4 m:officer_unidentified_rate=20 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=41.6 m:exonerated_rate=0

series e:mkxg-y5uc d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Ethnicity t:substantiated_number=1 t:exonerated_number=0 t:unfounded_number=11 t:unsubstantiated_number=22 t:officer_unidentified_number=4 m:miscellaneous=1 m:unfounded_rate=28.2 m:officer_unidentified_rate=10.3 m:miscellaneous_rate=2.6 m:sunstantiated_rate=2.6 m:unsubstantiated_rate=56.4 m:exonerated_rate=0

series e:mkxg-y5uc d:2008-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Religion t:substantiated_number=0 t:exonerated_number=0 t:unfounded_number=4 t:unsubstantiated_number=3 t:officer_unidentified_number=4 m:miscellaneous=0 m:unfounded_rate=36.4 m:officer_unidentified_rate=36.4 m:miscellaneous_rate=0 m:sunstantiated_rate=0 m:unsubstantiated_rate=27.3 m:exonerated_rate=0
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

entity e:mkxg-y5uc l:"Disposition Of Offensive Language Allegations 2008" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/mkxg-y5uc

property e:mkxg-y5uc t:meta.view v:id=mkxg-y5uc v:category="Public Safety" v:averageRating=0 v:name="Disposition Of Offensive Language Allegations 2008" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:mkxg-y5uc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mkxg-y5uc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | substantiated_number | sunstantiated_rate | exonerated_number | exonerated_rate | unsubstantiated_number | unsubstantiated_rate | unfounded_number | unfounded_rate | officer_unidentified_number | officer_unidentified_rate | miscellaneous | miscellaneous_rate | 
| ===================================== | ==================== | ================== | ================= | =============== | ====================== | ==================== | ================ | ============== | =========================== | ========================= | ============= | ================== | 
| Race                                  | 0                    | 0.00               | 0                 | 0.00            | 52                     | 41.60                | 48               | 38.40          | 25                          | 20.00                     | 0             | 0.00               | 
| Ethnicity                             | 1                    | 2.60               | 0                 | 0.00            | 22                     | 56.40                | 11               | 28.20          | 4                           | 10.30                     | 1             | 2.60               | 
| Religion                              | 0                    | 0.00               | 0                 | 0.00            | 3                      | 27.30                | 4                | 36.40          | 4                           | 36.40                     | 0             | 0.00               | 
| Sex                                   | 0                    | 0.00               | 0                 | 0.00            | 11                     | 50.00                | 10               | 45.50          | 0                           | 0.00                      | 1             | 4.50               | 
| Physical disability                   | 0                    | 0.00               | 0                 | 0.00            | 1                      | 20.00                | 2                | 40.00          | 2                           | 40.00                     | 0             | 0.00               | 
| Sexual orientation                    | 1                    | 4.00               | 0                 | 0.00            | 16                     | 64.00                | 6                | 24.00          | 2                           | 8.00                      | 0             | 0.00               | 
| Other                                 | 0                    | 0.00               | 0                 | 0.00            | 3                      | 100.00               | 0                | 0.00           | 0                           | 0.00                      | 0             | 0.00               | 
| Total                                 | 2                    | 0.90               | 0                 | 0.00            | 108                    | 47.00                | 81               | 35.20          | 37                          | 16.10                     | 2             | 0.90               | 
```