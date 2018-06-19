# Distribution Of Abuse Of Authority Allegations 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/distribution-of-abuse-of-authority-allegations-2005-2009-acce0) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/99ez-fwvc) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/99ez-fwvc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/99ez-fwvc/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 99ez-fwvc |
| Name | Distribution Of Abuse Of Authority Allegations 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T00:05:56Z |
| Publication Date | 2011-09-29T00:07:17Z |

## Description

CCRB: Distribution of Abuse of Authority Allegations 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name                            | Name                                  | Data Type | Render Type |
| ======== | ============== | ===================================== | ===================================== | ========= | =========== |
| Yes      | series tag     | type_of_abuse_of_authority_allegation | Type of Abuse of Authority Allegation | text      | text        |
| Yes      | series tag     | number_1                              | 2005 Number                           | text      | number      |
| Yes      | numeric metric | percent_of_total_1                    | 2005 Percent of Total                 | percent   | percent     |
| Yes      | series tag     | number_2                              | 2006 Number                           | text      | number      |
| Yes      | numeric metric | percent_of_total_2                    | 2006 Percent of Total                 | percent   | percent     |
| Yes      | series tag     | number_3                              | 2007 Number                           | text      | number      |
| Yes      | numeric metric | percent_of_total_3                    | 2007 Percent of Total                 | percent   | percent     |
| Yes      | series tag     | number_4                              | 2008 Number                           | text      | number      |
| Yes      | numeric metric | percent_of_total_4                    | 2008 Percent of Total                 | percent   | percent     |
| Yes      | series tag     | number_5                              | 2009 Number                           | text      | number      |
| Yes      | numeric metric | percent_of_total_5                    | 2009Percent of Total                  | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:99ez-fwvc d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Frisk t:number_1=570 t:number_3=750 t:number_2=713 t:number_5=821 t:number_4=703 m:percent_of_total_3=6 m:percent_of_total_4=6.3 m:percent_of_total_1=5.5 m:percent_of_total_2=5.9 m:percent_of_total_5=6.6

series e:99ez-fwvc d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation=Search t:number_1=992 t:number_3=1601 t:number_2=1321 t:number_5=1640 t:number_4=1394 m:percent_of_total_3=12.7 m:percent_of_total_4=12.5 m:percent_of_total_1=9.5 m:percent_of_total_2=10.9 m:percent_of_total_5=13.3

series e:99ez-fwvc d:2005-01-01T00:00:00.000Z t:type_of_abuse_of_authority_allegation="Frisk and/or search*" t:number_1=6 t:number_3=0 t:number_2=0 t:number_5=0 t:number_4=0 m:percent_of_total_3=0 m:percent_of_total_4=0 m:percent_of_total_1=0.1 m:percent_of_total_2=0 m:percent_of_total_5=0
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_5 p:float l:"2009Percent of Total" t:dataTypeName=percent

entity e:99ez-fwvc l:"Distribution Of Abuse Of Authority Allegations 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/99ez-fwvc

property e:99ez-fwvc t:meta.view v:id=99ez-fwvc v:category="Public Safety" v:averageRating=0 v:name="Distribution Of Abuse Of Authority Allegations 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:99ez-fwvc t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:99ez-fwvc t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| type_of_abuse_of_authority_allegation | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | 
| ===================================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | 
| Frisk                                 | 570      | 5.50               | 713      | 5.90               | 750      | 6.00               | 703      | 6.30               | 821      | 6.60               | 
| Search                                | 992      | 9.50               | 1321     | 10.90              | 1601     | 12.70              | 1394     | 12.50              | 1640     | 13.30              | 
| Frisk and/or search*                  | 6        | 0.10               | 0        | 0.00               | 0        | 0.00               | 0        | 0.00               | 0        | 0.00               | 
| Question                              | 0        | 0.00               | 40       | 0.30               | 375      | 3.00               | 447      | 4.00               | 420      | 3.40               | 
| Stop                                  | 0        | 0.00               | 193      | 1.60               | 1482     | 11.80              | 1909     | 17.10              | 2267     | 18.30              | 
| Question and/or stop**                | 2122     | 20.40              | 2337     | 19.30              | 839      | 6.70               | 0        | 0.00               | 0        | 0.00               | 
| Strip search                          | 232      | 2.20               | 314      | 2.60               | 411      | 3.30               | 313      | 2.80               | 300      | 2.40               | 
| Vehicle stop                          | 529      | 5.10               | 575      | 4.70               | 604      | 4.80               | 461      | 4.10               | 583      | 4.70               | 
| Vehicle search                        | 385      | 3.70               | 519      | 4.30               | 588      | 4.70               | 545      | 4.90               | 604      | 4.90               | 
| Gun drawn                             | 172      | 1.70               | 227      | 1.90               | 179      | 1.40               | 172      | 1.50               | 208      | 1.70               | 
```