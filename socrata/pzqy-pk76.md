# Residence Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/residence-of-subject-officers-against-whom-allegations-were-substantiated-2005-2009-82316) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/pzqy-pk76) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/pzqy-pk76/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/pzqy-pk76/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | pzqy-pk76 |
| Name | Residence Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T19:30:40Z |
| Publication Date | 2011-09-29T19:39:09Z |

## Description

CCRB: Residence of Subject Officers against Whom Allegations Were Substantiated 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                      | Data Type | Render Type |
| ======== | ============== | ===================== | ========================= | ========= | =========== |
| Yes      | series tag     | residence             | Residence                 | text      | text        |
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
series e:pzqy-pk76 d:2005-01-01T00:00:00.000Z t:residence=Bronx m:number_of_officers_5=38 m:number_of_officers_4=19 m:number_of_officers_1=49 m:number_of_officers_3=19 m:number_of_officers_2=35 m:nypd_population_2008=9.7 m:nypd_population_2009=9.5 m:percent_of_subtotal_3=6.4 m:percent_of_subtotal_4=8.8 m:percent_of_subtotal_1=13.3 m:percent_of_subtotal_2=10.1 m:percent_of_subtotal_5=13.8 m:nypd_population_2006=9.6 m:nypd_population_2007=9.7 m:nypd_population_2005=9.4

series e:pzqy-pk76 d:2005-01-01T00:00:00.000Z t:residence=Brooklyn m:number_of_officers_5=27 m:number_of_officers_4=20 m:number_of_officers_1=39 m:number_of_officers_3=22 m:number_of_officers_2=45 m:nypd_population_2008=12.7 m:nypd_population_2009=12.4 m:percent_of_subtotal_3=7.4 m:percent_of_subtotal_4=9.3 m:percent_of_subtotal_1=10.6 m:percent_of_subtotal_2=13 m:percent_of_subtotal_5=9.8 m:nypd_population_2006=13 m:nypd_population_2007=13.2 m:nypd_population_2005=12.5

series e:pzqy-pk76 d:2005-01-01T00:00:00.000Z t:residence=Manhattan m:number_of_officers_5=26 m:number_of_officers_4=7 m:number_of_officers_1=18 m:number_of_officers_3=11 m:number_of_officers_2=12 m:nypd_population_2008=4.1 m:nypd_population_2009=4 m:percent_of_subtotal_3=3.7 m:percent_of_subtotal_4=3.2 m:percent_of_subtotal_1=4.9 m:percent_of_subtotal_2=3.5 m:percent_of_subtotal_5=9.5 m:nypd_population_2006=4.4 m:nypd_population_2007=4.3 m:nypd_population_2005=4.4
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

entity e:pzqy-pk76 l:"Residence Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/pzqy-pk76

property e:pzqy-pk76 t:meta.view v:id=pzqy-pk76 v:category="Public Safety" v:averageRating=0 v:name="Residence Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:pzqy-pk76 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:pzqy-pk76 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| residence          | number_of_officers_1 | percent_of_subtotal_1 | nypd_population_2005 | number_of_officers_2 | percent_of_subtotal_2 | nypd_population_2006 | number_of_officers_3 | percent_of_subtotal_3 | nypd_population_2007 | number_of_officers_4 | percent_of_subtotal_4 | nypd_population_2008 | number_of_officers_5 | percent_of_subtotal_5 | nypd_population_2009 | 
| ================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | 
| Bronx              | 49                   | 13.30                 | 9.40                 | 35                   | 10.10                 | 9.60                 | 19                   | 6.40                  | 9.70                 | 19                   | 8.80                  | 9.70                 | 38                   | 13.80                 | 9.50                 | 
| Brooklyn           | 39                   | 10.60                 | 12.50                | 45                   | 13.00                 | 13.00                | 22                   | 7.40                  | 13.20                | 20                   | 9.30                  | 12.70                | 27                   | 9.80                  | 12.40                | 
| Manhattan          | 18                   | 4.90                  | 4.40                 | 12                   | 3.50                  | 4.40                 | 11                   | 3.70                  | 4.30                 | 7                    | 3.20                  | 4.10                 | 26                   | 9.50                  | 4.00                 | 
| Queens             | 51                   | 13.80                 | 15.80                | 46                   | 13.30                 | 16.10                | 68                   | 22.70                 | 16.10                | 48                   | 22.20                 | 16.20                | 42                   | 15.30                 | 16.10                | 
| Staten Island      | 36                   | 9.80                  | 11.50                | 37                   | 10.70                 | 11.40                | 27                   | 9.00                  | 11.40                | 22                   | 10.20                 | 11.20                | 26                   | 9.50                  | 11.20                | 
| NYC Resident Total | 193                  | 52.30                 | 53.60                | 175                  | 50.40                 | 54.50                | 147                  | 49.20                 | 54.70                | 116                  | 53.70                 | 53.90                | 159                  | 57.80                 | 53.20                | 
| Nassau             | 47                   | 12.70                 | 15.20                | 51                   | 14.70                 | 14.50                | 34                   | 11.40                 | 14.40                | 16                   | 7.40                  | 14.60                | 19                   | 6.90                  | 14.90                | 
| Orange             | 22                   | 6.00                  | 6.00                 | 18                   | 5.20                  | 6.10                 | 23                   | 7.70                  | 6.20                 | 10                   | 4.60                  | 6.50                 | 14                   | 5.10                  | 6.60                 | 
| Putnam             | 8                    | 2.20                  | 1.50                 | 8                    | 2.30                  | 1.50                 | 3                    | 1.00                  | 1.50                 | 3                    | 1.40                  | 1.50                 | 2                    | 0.70                  | 1.50                 | 
| Rockland           | 15                   | 4.10                  | 3.90                 | 27                   | 7.80                  | 3.80                 | 19                   | 6.40                  | 3.70                 | 13                   | 6.00                  | 3.70                 | 15                   | 5.50                  | 3.80                 | 
```