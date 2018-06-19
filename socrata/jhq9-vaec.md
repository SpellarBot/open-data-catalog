# Gender Of Subject Officers Compared To New York City Police Department Demographics 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gender-of-subject-officers-compared-to-new-york-city-police-department-demographics-2005-2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jhq9-vaec) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jhq9-vaec/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jhq9-vaec/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jhq9-vaec |
| Name | Gender Of Subject Officers Compared To New York City Police Department Demographics 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T16:56:37Z |
| Publication Date | 2011-09-29T16:59:25Z |

## Description

CCRB: Gender of Subject Officers Compared to New York City Police Department Demographics 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                      | Data Type | Render Type |
| ======== | ============== | ===================== | ========================= | ========= | =========== |
| Yes      | series tag     | gender                | Gender                    | text      | text        |
| Yes      | numeric metric | number_of_officers_1  | 2005 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_1 | 2005 Percent of Subtotal  | number    | text        |
| Yes      | numeric metric | nypd_population_2005  | 2005 NYPD Population 2005 | number    | text        |
| Yes      | numeric metric | number_of_officers_2  | 2006 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_2 | 2006 Percent of Subtotal  | number    | text        |
| Yes      | numeric metric | nypd_population_2006  | 2006 NYPD Population 2006 | number    | text        |
| Yes      | numeric metric | number_of_officers_3  | 2007 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_3 | 2007 Percent of Subtotal  | number    | text        |
| Yes      | numeric metric | nypd_population_2007  | 2007 NYPD Population 2007 | number    | text        |
| Yes      | numeric metric | number_of_officers_4  | 2008 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_4 | 2008 Percent of Subtotal  | number    | text        |
| Yes      | numeric metric | nypd_population_2008  | 2008 NYPD Population 2008 | number    | text        |
| Yes      | numeric metric | number_of_officers_5  | 2009 Number of Officers   | number    | number      |
| Yes      | numeric metric | percent_of_subtotal_5 | 2009 Percent of Subtotal  | number    | text        |
| Yes      | numeric metric | nypd_population_2009  | 2009 NYPD Population 2009 | number    | text        |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jhq9-vaec d:2005-01-01T00:00:00.000Z t:gender=Male m:number_of_officers_5=5653 m:number_of_officers_4=5373 m:number_of_officers_1=5969 m:number_of_officers_3=6063 m:number_of_officers_2=6464 m:nypd_population_2008=82.5 m:nypd_population_2009=82.5 m:percent_of_subtotal_3=89.69999694824219 m:percent_of_subtotal_4=90.19999694824219 m:percent_of_subtotal_1=89.80000305175781 m:percent_of_subtotal_2=89.9000015258789 m:percent_of_subtotal_5=89.4000015258789 m:nypd_population_2006=82.5999984741211 m:nypd_population_2007=82.5 m:nypd_population_2005=82.80000305175781

series e:jhq9-vaec d:2005-01-01T00:00:00.000Z t:gender=Female m:number_of_officers_5=673 m:number_of_officers_4=583 m:number_of_officers_1=676 m:number_of_officers_3=695 m:number_of_officers_2=729 m:nypd_population_2008=17.5 m:nypd_population_2009=17.5 m:percent_of_subtotal_3=10.300000190734863 m:percent_of_subtotal_4=9.800000190734863 m:percent_of_subtotal_1=10.199999809265137 m:percent_of_subtotal_2=10.100000381469727 m:percent_of_subtotal_5=10.600000381469727 m:nypd_population_2006=17.399999618530273 m:nypd_population_2007=17.5 m:nypd_population_2005=17.200000762939453

series e:jhq9-vaec d:2005-01-01T00:00:00.000Z t:gender=Subtotal m:number_of_officers_5=6326 m:number_of_officers_4=5956 m:number_of_officers_1=6645 m:number_of_officers_3=6758 m:number_of_officers_2=7193 m:nypd_population_2008=100 m:nypd_population_2009=100 m:percent_of_subtotal_3=100 m:percent_of_subtotal_4=100 m:percent_of_subtotal_1=100 m:percent_of_subtotal_2=100 m:percent_of_subtotal_5=100 m:nypd_population_2006=100 m:nypd_population_2007=100 m:nypd_population_2005=100
```

## Meta Commands

```ls
metric m:number_of_officers_1 p:integer l:"2005 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_1 p:float l:"2005 Percent of Subtotal" t:dataTypeName=number

metric m:nypd_population_2005 p:float l:"2005 NYPD Population 2005" t:dataTypeName=number

metric m:number_of_officers_2 p:integer l:"2006 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_2 p:float l:"2006 Percent of Subtotal" t:dataTypeName=number

metric m:nypd_population_2006 p:float l:"2006 NYPD Population 2006" t:dataTypeName=number

metric m:number_of_officers_3 p:integer l:"2007 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_3 p:float l:"2007 Percent of Subtotal" t:dataTypeName=number

metric m:nypd_population_2007 p:float l:"2007 NYPD Population 2007" t:dataTypeName=number

metric m:number_of_officers_4 p:integer l:"2008 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_4 p:float l:"2008 Percent of Subtotal" t:dataTypeName=number

metric m:nypd_population_2008 p:float l:"2008 NYPD Population 2008" t:dataTypeName=number

metric m:number_of_officers_5 p:integer l:"2009 Number of Officers" t:dataTypeName=number

metric m:percent_of_subtotal_5 p:float l:"2009 Percent of Subtotal" t:dataTypeName=number

metric m:nypd_population_2009 p:float l:"2009 NYPD Population 2009" t:dataTypeName=number

entity e:jhq9-vaec l:"Gender Of Subject Officers Compared To New York City Police Department Demographics 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/jhq9-vaec

property e:jhq9-vaec t:meta.view v:id=jhq9-vaec v:category="Public Safety" v:averageRating=0 v:name="Gender Of Subject Officers Compared To New York City Police Department Demographics 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:jhq9-vaec t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jhq9-vaec t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| gender               | number_of_officers_1 | percent_of_subtotal_1 | nypd_population_2005 | number_of_officers_2 | percent_of_subtotal_2 | nypd_population_2006 | number_of_officers_3 | percent_of_subtotal_3 | nypd_population_2007 | number_of_officers_4 | percent_of_subtotal_4 | nypd_population_2008 | number_of_officers_5 | percent_of_subtotal_5 | nypd_population_2009 | 
| ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | ==================== | ===================== | ==================== | 
| Male                 | 5969                 | 89.80%                | 82.80%               | 6464                 | 89.90%                | 82.60%               | 6063                 | 89.70%                | 82.50%               | 5373                 | 90.20%                | 82.50%               | 5653                 | 89.40%                | 82.50%               | 
| Female               | 676                  | 10.20%                | 17.20%               | 729                  | 10.10%                | 17.40%               | 695                  | 10.30%                | 17.50%               | 583                  | 9.80%                 | 17.50%               | 673                  | 10.60%                | 17.50%               | 
| Subtotal             | 6645                 | 100.00%               | 100.00%              | 7193                 | 100.00%               | 100.00%              | 6758                 | 100.00%               | 100.00%              | 5956                 | 100.00%               | 100.00%              | 6326                 | 100.00%               | 100.00%              | 
| Officer unidentified | 3919                 |                       |                      | 4989                 |                       |                      | 5454                 |                       |                      | 5556                 |                       |                      | 6145                 |                       |                      | 
| Total                | 10564                |                       |                      | 12182                |                       |                      | 12212                |                       |                      | 11512                |                       |                      | 12471                |                       |                      | 
```