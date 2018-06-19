# Rank Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/rank-of-subject-officers-against-whom-allegations-were-substantiated-2005-2009-3987a) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/mnqg-rcee) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/mnqg-rcee/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/mnqg-rcee/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | mnqg-rcee |
| Name | Rank Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T19:14:09Z |
| Publication Date | 2011-09-29T19:15:42Z |

## Description

CCRB: Rank of Subject Officers against Whom Allegations Were Substantiated 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                      | Data Type | Render Type |
| ======== | ============== | ===================== | ========================= | ========= | =========== |
| Yes      | series tag     | rank                  | Rank                      | text      | text        |
| Yes      | numeric metric | number_of_officers_1  | 2005 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_1 | 2005 Percent of Subtotal  | percent   | percent     |
| Yes      | numeric metric | nypd_population_2005  | 2005 NYPD Population 2005 | percent   | percent     |
| Yes      | numeric metric | number_of_officers_2  | 2006 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_2 | 2006 Percent of Subtotal  | percent   | percent     |
| Yes      | numeric metric | nypd_population_2006  | 2006 NYPD Population 2006 | percent   | percent     |
| Yes      | numeric metric | number_of_officers_3  | 2007 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_3 | 2007 Percent of Subtotal  | percent   | percent     |
| Yes      | numeric metric | nypd_population_2007  | 2007 NYPD Population 2007 | percent   | percent     |
| Yes      | numeric metric | number_of_officers_4  | 2008 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_4 | 2008 Percent of Subtotal  | percent   | percent     |
| Yes      | numeric metric | nypd_population_2008  | 2008 NYPD Population 2008 | percent   | percent     |
| Yes      | numeric metric | number_of_officers_5  | 2009 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_5 | 2009 Percent of Subtotal  | percent   | percent     |
| Yes      | numeric metric | nypd_population_2009  | 2009 NYPD Population 2009 | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:mnqg-rcee d:2005-01-01T00:00:00.000Z t:rank="Police officer" m:number_of_officers_5=199 m:number_of_officers_4=134 m:number_of_officers_1=240 m:number_of_officers_3=212 m:number_of_officers_2=248 m:nypd_population_2008=65 m:nypd_population_2009=64 m:percent_of_subtotal_3=70.9 m:percent_of_subtotal_4=61.2 m:percent_of_subtotal_1=65 m:percent_of_subtotal_2=71.5 m:percent_of_subtotal_5=72.4 m:nypd_population_2006=65.7 m:nypd_population_2007=65.8 m:nypd_population_2005=64.8

series e:mnqg-rcee d:2005-01-01T00:00:00.000Z t:rank="Detective 3" m:number_of_officers_5=11 m:number_of_officers_4=26 m:number_of_officers_1=40 m:number_of_officers_3=17 m:number_of_officers_2=30 m:nypd_population_2008=9 m:nypd_population_2009=9.4 m:percent_of_subtotal_3=5.7 m:percent_of_subtotal_4=11.9 m:percent_of_subtotal_1=10.8 m:percent_of_subtotal_2=8.6 m:percent_of_subtotal_5=4 m:nypd_population_2006=9.3 m:nypd_population_2007=8.7 m:nypd_population_2005=10.5

series e:mnqg-rcee d:2005-01-01T00:00:00.000Z t:rank="Detective 2" m:number_of_officers_5=3 m:number_of_officers_4=4 m:number_of_officers_1=0 m:number_of_officers_3=1 m:number_of_officers_2=3 m:nypd_population_2008=3 m:nypd_population_2009=3.1 m:percent_of_subtotal_3=0.3 m:percent_of_subtotal_4=1.8 m:percent_of_subtotal_1=0 m:percent_of_subtotal_2=0.9 m:percent_of_subtotal_5=1.1 m:nypd_population_2006=2.2 m:nypd_population_2007=2.6 m:nypd_population_2005=1.8
```

## Meta Commands

```ls
metric m:number_of_officers_1 p:integer l:"2005 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_1 p:float l:"2005 Percent of Subtotal" t:dataTypeName=percent

metric m:nypd_population_2005 p:float l:"2005 NYPD Population 2005" t:dataTypeName=percent

metric m:number_of_officers_2 p:integer l:"2006 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_2 p:float l:"2006 Percent of Subtotal" t:dataTypeName=percent

metric m:nypd_population_2006 p:float l:"2006 NYPD Population 2006" t:dataTypeName=percent

metric m:number_of_officers_3 p:integer l:"2007 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_3 p:float l:"2007 Percent of Subtotal" t:dataTypeName=percent

metric m:nypd_population_2007 p:float l:"2007 NYPD Population 2007" t:dataTypeName=percent

metric m:number_of_officers_4 p:integer l:"2008 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_4 p:float l:"2008 Percent of Subtotal" t:dataTypeName=percent

metric m:nypd_population_2008 p:float l:"2008 NYPD Population 2008" t:dataTypeName=percent

metric m:number_of_officers_5 p:integer l:"2009 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_5 p:float l:"2009 Percent of Subtotal" t:dataTypeName=percent

metric m:nypd_population_2009 p:float l:"2009 NYPD Population 2009" t:dataTypeName=percent

entity e:mnqg-rcee l:"Rank Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/mnqg-rcee

property e:mnqg-rcee t:meta.view v:id=mnqg-rcee v:category="Public Safety" v:averageRating=0 v:name="Rank Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:mnqg-rcee t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:mnqg-rcee t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| rank                           | number_of_officers_1 | percent_of_subtotal_1 | nypd_population_2005 | number_of_officers_2 | percent_of_subtotal_2 | nypd_population_2006 | number_of_officers_3 | percent_of_subtotal_3 | nypd_population_2007 | number_of_officers_4 | percent_of_subtotal_4 | nypd_population_2008 | number_of_officers_5 | percent_of_subtotal_5 | nypd_population_2009 | 
| ============================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | 
| Police officer                 | 240                  | 65.00                 | 64.80                | 248                  | 71.50                 | 65.70                | 212                  | 70.90                 | 65.80                | 134                  | 61.20                 | 65.00                | 199                  | 72.40                 | 64.00                | 
| Detective 3                    | 40                   | 10.80                 | 10.50                | 30                   | 8.60                  | 9.30                 | 17                   | 5.70                  | 8.70                 | 26                   | 11.90                 | 9.00                 | 11                   | 4.00                  | 9.40                 | 
| Detective 2                    | 0                    | 0.00                  | 1.80                 | 3                    | 0.90                  | 2.20                 | 1                    | 0.30                  | 2.60                 | 4                    | 1.80                  | 3.00                 | 3                    | 1.10                  | 3.10                 | 
| Detective 1                    | 0                    | 0.00                  | 0.60                 | 1                    | 0.30                  | 0.80                 | 1                    | 0.30                  | 0.90                 | 0                    | 0.00                  | 1.00                 | 0                    | 0.00                  | 1.10                 | 
| Detective specialist           | 6                    | 1.60                  | 1.70                 | 3                    | 0.90                  | 1.60                 | 2                    | 0.70                  | 1.70                 | 0                    | 0.00                  | 1.70                 | 1                    | 0.40                  | 1.80                 | 
| Sergeant                       | 65                   | 17.60                 | 13.50                | 48                   | 13.80                 | 13.30                | 51                   | 17.10                 | 12.90                | 40                   | 18.30                 | 13.20                | 50                   | 18.20                 | 13.50                | 
| Lieutenant                     | 14                   | 3.80                  | 4.70                 | 11                   | 3.20                  | 4.70                 | 11                   | 3.70                  | 4.80                 | 12                   | 5.50                  | 4.80                 | 11                   | 4.00                  | 4.60                 | 
| Lieutenant commander detective | 1                    | 0.30                  | 0.20                 | 0                    | 0.00                  | 0.20                 | 0                    | 0.00                  | 0.30                 | 0                    | 0.00                  | 0.30                 | 0                    | 0.00                  | 0.40                 | 
| Captain                        | 3                    | 0.80                  | 1.40                 | 1                    | 0.30                  | 1.30                 | 2                    | 0.70                  | 1.30                 | 3                    | 1.40                  | 1.10                 | 0                    | 0.00                  | 1.20                 | 
| Deputy Inspector/Inspector     | 0                    | 0.00                  | 0.70                 | 1                    | 0.30                  | 0.70                 | 1                    | 0.30                  | 0.80                 | 0                    | 0.00                  | 0.70                 | 0                    | 0.00                  | 0.70                 | 
```