# How Complaints Filed With The NYPD Were Reported 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/how-complaints-filed-with-the-nypd-were-reported-2005-2009-f1c5b) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/ihvw-cp8d) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/ihvw-cp8d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/ihvw-cp8d/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | ihvw-cp8d |
| Name | How Complaints Filed With The NYPD Were Reported 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T17:44:19Z |
| Publication Date | 2011-09-29T17:46:05Z |

## Description

CCRB: How Complaints Filed with the NYPD Were Reported 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================ | ========= | =========== |
| Yes      | series tag     | how_complaints_filed_with_the_nypd_were_reported | How Complaints Filed with the NYPD Were Reported | text      | text        |
| Yes      | series tag     | number_1                                         | 2005 Number                                      | text      | number      |
| Yes      | numeric metric | percent_of_total_1                               | 2005 Percent of Total                            | percent   | percent     |
| Yes      | series tag     | number_2                                         | 2006 Number                                      | text      | number      |
| Yes      | numeric metric | percent_of_total_2                               | 2006 Percent of Total                            | percent   | percent     |
| Yes      | series tag     | number_3                                         | 2007 Number                                      | text      | number      |
| Yes      | numeric metric | percent_of_total_3                               | 2007 Percent of Total                            | percent   | percent     |
| Yes      | series tag     | number_4                                         | 2008 Number                                      | text      | number      |
| Yes      | numeric metric | percent_of_total_4                               | 2008 Percent of Total                            | percent   | percent     |
| Yes      | series tag     | number_5                                         | 2009 Number                                      | text      | number      |
| Yes      | numeric metric | percent_of_total_5                               | 2009 Percent of Total                            | percent   | percent     |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:ihvw-cp8d d:2005-01-01T00:00:00.000Z t:number_1=184 t:number_3=125 t:number_2=152 t:how_complaints_filed_with_the_nypd_were_reported="In person" t:number_5=71 t:number_4=105 m:percent_of_total_3=4.6 m:percent_of_total_4=3.8 m:percent_of_total_1=8.4 m:percent_of_total_2=6.1 m:percent_of_total_5=2.4

series e:ihvw-cp8d d:2005-01-01T00:00:00.000Z t:number_1=1981 t:number_3=2556 t:number_2=2322 t:how_complaints_filed_with_the_nypd_were_reported="By telephone" t:number_5=2915 t:number_4=2625 m:percent_of_total_3=94.2 m:percent_of_total_4=95.7 m:percent_of_total_1=90.5 m:percent_of_total_2=92.9 m:percent_of_total_5=96.9

series e:ihvw-cp8d d:2005-01-01T00:00:00.000Z t:number_1=14 t:number_3=9 t:number_2=8 t:how_complaints_filed_with_the_nypd_were_reported="By letter" t:number_5=11 t:number_4=7 m:percent_of_total_3=0.3 m:percent_of_total_4=0.3 m:percent_of_total_1=0.6 m:percent_of_total_2=0.3 m:percent_of_total_5=0.4
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=percent

entity e:ihvw-cp8d l:"How Complaints Filed With The NYPD Were Reported 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/ihvw-cp8d

property e:ihvw-cp8d t:meta.view v:id=ihvw-cp8d v:category="Public Safety" v:averageRating=0 v:name="How Complaints Filed With The NYPD Were Reported 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:ihvw-cp8d t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:ihvw-cp8d t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| how_complaints_filed_with_the_nypd_were_reported | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | 
| ================================================ | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | 
| In person                                        | 184      | 8.40               | 152      | 6.10               | 125      | 4.60               | 105      | 3.80               | 71       | 2.40               | 
| By telephone                                     | 1981     | 90.50              | 2322     | 92.90              | 2556     | 94.20              | 2625     | 95.70              | 2915     | 96.90              | 
| By letter                                        | 14       | 0.60               | 8        | 0.30               | 9        | 0.30               | 7        | 0.30               | 11       | 0.40               | 
| By e-mail/internet/fax                           | 10       | 0.50               | 17       | 0.70               | 23       | 0.80               | 7        | 0.30               | 12       | 0.40               | 
| Total                                            | 2189     | 100.00             | 2499     | 100.00             | 2713     | 100.00             | 2744     | 100.00             | 3009     | 100.00             | 
```