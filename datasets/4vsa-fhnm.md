# Reasons For Police- Civilian Encounters That Led To A Complaint 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/reasons-for-police-civilian-encounters-that-led-to-a-complaint-2005-2009-5a37d) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/4vsa-fhnm) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/4vsa-fhnm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/4vsa-fhnm/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 4vsa-fhnm |
| Name | Reasons For Police- Civilian Encounters That Led To A Complaint 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T19:25:49Z |
| Publication Date | 2011-09-29T19:27:06Z |

## Description

CCRB: Reasons for Police-Civilian Encounters that Led to a Complaint 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                  | Data Type | Render Type |
| ======== | ============== | ================== | ===================== | ========= | =========== |
| Yes      | series tag     | type_of_encounter  | Type of Encounter     | text      | text        |
| Yes      | series tag     | number_1           | 2005 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_1 | 2005 Percent of Total | percent   | percent     |
| Yes      | series tag     | number_2           | 2006 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_2 | 2006 Percent of Total | percent   | percent     |
| Yes      | series tag     | number_3           | 2007 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_3 | 2007 Percent of Total | percent   | percent     |
| Yes      | series tag     | number_4           | 2008 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_4 | 2008 Percent of Total | percent   | percent     |
| Yes      | series tag     | number_5           | 2009 Number           | text      | number      |
| Yes      | numeric metric | percent_of_total_5 | 2009 Percent of Total | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4vsa-fhnm d:2005-01-01T00:00:00.000Z t:type_of_encounter="Aided case" t:number_1=39 t:number_3=37 t:number_2=44 t:number_5=16 t:number_4=36 m:percent_of_total_3=0.5 m:percent_of_total_4=0.5 m:percent_of_total_1=0.6 m:percent_of_total_2=0.6 m:percent_of_total_5=0.2

series e:4vsa-fhnm d:2005-01-01T00:00:00.000Z t:type_of_encounter="Assisting Administration for Children Services" t:number_1=2 t:number_3=6 t:number_2=5 t:number_5=7 t:number_4=6 m:percent_of_total_3=0.1 m:percent_of_total_4=0.1 m:percent_of_total_1=0 m:percent_of_total_2=0.1 m:percent_of_total_5=0.1

series e:4vsa-fhnm d:2005-01-01T00:00:00.000Z t:type_of_encounter="Automobile checkpoint" t:number_1=18 t:number_3=14 t:number_2=18 t:number_5=4 t:number_4=14 m:percent_of_total_3=0.2 m:percent_of_total_4=0.2 m:percent_of_total_1=0.3 m:percent_of_total_2=0.2 m:percent_of_total_5=0.1
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=percent

entity e:4vsa-fhnm l:"Reasons For Police- Civilian Encounters That Led To A Complaint 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/4vsa-fhnm

property e:4vsa-fhnm t:meta.view v:id=4vsa-fhnm v:category="Public Safety" v:averageRating=0 v:name="Reasons For Police- Civilian Encounters That Led To A Complaint 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:4vsa-fhnm t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:4vsa-fhnm t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_encounter                                            | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | 
| ============================================================ | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | 
| Aided case                                                   | 39       | 0.60               | 44       | 0.60               | 37       | 0.50               | 36       | 0.50               | 16       | 0.20               | 
| Assisting Administration for Children Services               | 2        | 0.00               | 5        | 0.10               | 6        | 0.10               | 6        | 0.10               | 7        | 0.10               | 
| Automobile checkpoint                                        | 18       | 0.30               | 18       | 0.20               | 14       | 0.20               | 14       | 0.20               | 4        | 0.10               | 
| Complainant or victim at precinct to file complaint of crime | 57       | 0.80               | 73       | 1.00               | 38       | 0.50               | 56       | 0.80               | 45       | 0.60               | 
| Complainant or victim at precinct to obtain information      | 73       | 1.10               | 94       | 1.20               | 80       | 1.10               | 90       | 1.20               | 80       | 1.00               | 
| Complainant or victim at precinct to retrieve property       | 0        | 0.00               | 0        | 0.00               | 0        | 0.00               | 0        | 0.00               | 16       | 0.20               | 
| Complainant or victim observed encounter with third party    | 123      | 1.80               | 149      | 1.90               | 197      | 2.60               | 150      | 2.00               | 119      | 1.60               | 
| Complainant or victim requested information from officer     | 68       | 1.00               | 54       | 0.70               | 49       | 0.60               | 43       | 0.60               | 32       | 0.40               | 
| Complainant or victim requested investigation of crime       | 189      | 2.80               | 219      | 2.90               | 231      | 3.10               | 207      | 2.80               | 168      | 2.20               | 
| Complainant or victim telephoned precinct                    | 75       | 1.10               | 56       | 0.70               | 48       | 0.60               | 50       | 0.70               | 46       | 0.60               | 
```