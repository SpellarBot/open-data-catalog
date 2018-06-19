# Gender Of Victims Whose Allegations Were Substantiated 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/gender-of-victims-whose-allegations-were-substantiated-2005-2009-8587e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ffgt-jimk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ffgt-jimk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ffgt-jimk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ffgt-jimk |
| Name | Gender Of Victims Whose Allegations Were Substantiated 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T17:16:28Z |
| Publication Date | 2011-09-29T17:18:00Z |

## Description

CCRB: Gender of Victims Whose Allegations Were Substantiated 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                     | Data Type | Render Type |
| ======== | ============== | ====================== | ======================== | ========= | =========== |
| Yes      | series tag     | gender                 | Gender                   | text      | text        |
| Yes      | series tag     | number_1               | 2005 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_1     | 2005 Percent of Total    | number    | text        |
| Yes      | series tag     | number_2               | 2006 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_2     | 2006 Percent of Total    | number    | text        |
| Yes      | series tag     | number_3               | 2007 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_3     | 2007 Percent of Total    | number    | text        |
| Yes      | series tag     | number_4               | 2008 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_4     | 2008 Percent of Total    | number    | text        |
| Yes      | series tag     | number_5               | 2009 Number              | text      | number      |
| Yes      | numeric metric | percent_of_total_5     | 2009 Percent of Total    | number    | text        |
| Yes      | series tag     | yr_number              | 5 yr Number              | text      | text        |
| Yes      | numeric metric | yr_percent_of_subtotal | 5 yr Percent of Subtotal | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ffgt-jimk d:2005-01-01T00:00:00.000Z t:gender=Male t:number_1=326 t:number_3=308 t:number_2=330 t:number_5=270 t:yr_number=47.70% t:number_4=233 m:percent_of_total_3=73.9000015258789 m:percent_of_total_4=73.5 m:percent_of_total_1=73.5999984741211 m:percent_of_total_2=75.5 m:yr_percent_of_subtotal=1467 m:percent_of_total_5=75.5999984741211

series e:ffgt-jimk d:2005-01-01T00:00:00.000Z t:gender=Female t:number_1=117 t:number_3=109 t:number_2=107 t:number_5=87 t:yr_number=52.30% t:number_4=84 m:percent_of_total_3=26.100000381469727 m:percent_of_total_4=26.5 m:percent_of_total_1=26.399999618530273 m:percent_of_total_2=24.5 m:yr_percent_of_subtotal=504 m:percent_of_total_5=24.399999618530273

series e:ffgt-jimk d:2005-01-01T00:00:00.000Z t:gender=Subtotal t:number_1=443 t:number_3=417 t:number_2=437 t:number_5=357 t:yr_number=100.00% t:number_4=317 m:percent_of_total_3=100 m:percent_of_total_4=100 m:percent_of_total_1=100 m:percent_of_total_2=100 m:yr_percent_of_subtotal=1971 m:percent_of_total_5=100
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=number

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=number

metric m:yr_percent_of_subtotal p:integer l:"5 yr Percent of Subtotal" t:dataTypeName=number

entity e:ffgt-jimk l:"Gender Of Victims Whose Allegations Were Substantiated 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/ffgt-jimk

property e:ffgt-jimk t:meta.view v:id=ffgt-jimk v:category="Public Safety" v:averageRating=0 v:name="Gender Of Victims Whose Allegations Were Substantiated 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:ffgt-jimk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ffgt-jimk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| gender   | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | yr_number | yr_percent_of_subtotal | 
| ======== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ========= | ====================== | 
| Male     | 326      | 73.60%             | 330      | 75.50%             | 308      | 73.90%             | 233      | 73.50%             | 270      | 75.60%             | 47.70%    | 1467                   | 
| Female   | 117      | 26.40%             | 107      | 24.50%             | 109      | 26.10%             | 84       | 26.50%             | 87       | 24.40%             | 52.30%    | 504                    | 
| Subtotal | 443      | 100.00%            | 437      | 100.00%            | 417      | 100.00%            | 317      | 100.00%            | 357      | 100.00%            | 100.00%   | 1971                   | 
| Unknown  | 10       |                    | 10       |                    | 24       |                    | 26       |                    | 15       |                    |           | 85                     | 
| Total    | 453      |                    | 447      |                    | 441      |                    | 343      |                    | 372      |                    |           | 2056                   | 
```