# Education Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/education-of-subject-officers-against-whom-allegations-were-substantiated-2005-2009-4d5ec) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/yjbz-vif8) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/yjbz-vif8/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/yjbz-vif8/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | yjbz-vif8 |
| Name | Education Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T16:13:15Z |
| Publication Date | 2011-09-29T16:14:11Z |

## Description

CCRB: Education of Subject Officers against Whom Allegations Were Substantiated 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                      | Data Type | Render Type |
| ======== | ============== | ===================== | ========================= | ========= | =========== |
| Yes      | series tag     | education_level       | Education Level           | text      | text        |
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
series e:yjbz-vif8 d:2005-01-01T00:00:00.000Z t:education_level="HS diploma/GED" m:number_of_officers_5=27 m:number_of_officers_4=27 m:number_of_officers_1=63 m:number_of_officers_3=46 m:number_of_officers_2=50 m:nypd_population_2008=16.1 m:nypd_population_2009=15.8 m:percent_of_subtotal_3=15.4 m:percent_of_subtotal_4=12.3 m:percent_of_subtotal_1=17.1 m:percent_of_subtotal_2=14.4 m:percent_of_subtotal_5=9.8 m:nypd_population_2006=18.3 m:nypd_population_2007=17.3 m:nypd_population_2005=19.7

series e:yjbz-vif8 d:2005-01-01T00:00:00.000Z t:education_level="College - no degree" m:number_of_officers_5=117 m:number_of_officers_4=101 m:number_of_officers_1=175 m:number_of_officers_3=114 m:number_of_officers_2=161 m:nypd_population_2008=43.8 m:nypd_population_2009=43.6 m:percent_of_subtotal_3=38.1 m:percent_of_subtotal_4=46.1 m:percent_of_subtotal_1=47.4 m:percent_of_subtotal_2=46.4 m:percent_of_subtotal_5=42.5 m:nypd_population_2006=43.3 m:nypd_population_2007=43.5 m:nypd_population_2005=42.2

series e:yjbz-vif8 d:2005-01-01T00:00:00.000Z t:education_level="Associate degree" m:number_of_officers_5=48 m:number_of_officers_4=38 m:number_of_officers_1=41 m:number_of_officers_3=52 m:number_of_officers_2=42 m:nypd_population_2008=13.9 m:nypd_population_2009=14 m:percent_of_subtotal_3=17.4 m:percent_of_subtotal_4=17.4 m:percent_of_subtotal_1=11.1 m:percent_of_subtotal_2=12.1 m:percent_of_subtotal_5=17.5 m:nypd_population_2006=13.4 m:nypd_population_2007=13.7 m:nypd_population_2005=13.3
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

entity e:yjbz-vif8 l:"Education Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/yjbz-vif8

property e:yjbz-vif8 t:meta.view v:id=yjbz-vif8 v:category="Public Safety" v:averageRating=0 v:name="Education Of Subject Officers Against Whom Allegations Were Substantiated 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:yjbz-vif8 t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:yjbz-vif8 t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| education_level      | number_of_officers_1 | percent_of_subtotal_1 | nypd_population_2005 | number_of_officers_2 | percent_of_subtotal_2 | nypd_population_2006 | number_of_officers_3 | percent_of_subtotal_3 | nypd_population_2007 | number_of_officers_4 | percent_of_subtotal_4 | nypd_population_2008 | number_of_officers_5 | percent_of_subtotal_5 | nypd_population_2009 | 
| ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | 
| HS diploma/GED       | 63                   | 17.10                 | 19.70                | 50                   | 14.40                 | 18.30                | 46                   | 15.40                 | 17.30                | 27                   | 12.30                 | 16.10                | 27                   | 9.80                  | 15.80                | 
| College - no degree  | 175                  | 47.40                 | 42.20                | 161                  | 46.40                 | 43.30                | 114                  | 38.10                 | 43.50                | 101                  | 46.10                 | 43.80                | 117                  | 42.50                 | 43.60                | 
| Associate degree     | 41                   | 11.10                 | 13.30                | 42                   | 12.10                 | 13.40                | 52                   | 17.40                 | 13.70                | 38                   | 17.40                 | 13.90                | 48                   | 17.50                 | 14.00                | 
| Undergraduate degree | 83                   | 22.50                 | 22.50                | 87                   | 25.10                 | 22.80                | 79                   | 26.40                 | 23.30                | 51                   | 23.30                 | 23.90                | 76                   | 27.60                 | 24.30                | 
| Post-graduate work   | 3                    | 0.80                  | 0.50                 | 1                    | 0.30                  | 0.50                 | 3                    | 1.00                  | 0.40                 | 2                    | 0.90                  | 0.40                 | 2                    | 0.70                  | 0.40                 | 
| Master's degree      | 4                    | 1.10                  | 1.40                 | 6                    | 1.70                  | 1.30                 | 5                    | 1.70                  | 1.40                 | 0                    | 0.00                  | 1.50                 | 5                    | 1.80                  | 1.50                 | 
| Doctorate work       | 0                    | 0.00                  | 0.10                 | 0                    | 0.00                  | 0.10                 | 0                    | 0.00                  | 0.10                 | 0                    | 0.00                  | 0.10                 | 0                    | 0.00                  | 0.10                 | 
| Doctorate degree/JD  | 0                    | 0.00                  | 0.30                 | 0                    | 0.00                  | 0.30                 | 0                    | 0.00                  | 0.30                 | 0                    | 0.00                  | 0.30                 | 0                    | 0.00                  | 0.30                 | 
| Subtotal             | 369                  | 100.00                | 100.00               | 347                  | 100.00                | 100.00               | 299                  | 100.00                | 100.00               | 219                  | 100.00                | 100.00               | 275                  | 100.00                | 100.00               | 
| Unknown              | 2                    |                       |                      | 0                    |                       |                      | 1                    |                       |                      | 0                    |                       |                      | 1                    |                       |                      | 
```