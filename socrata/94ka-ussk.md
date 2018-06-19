# How Complaints Filed With The CCRB Were Reported 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/how-complaints-filed-with-the-ccrb-were-reported-2005-2009-36175) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/94ka-ussk) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/94ka-ussk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/94ka-ussk/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 94ka-ussk |
| Name | How Complaints Filed With The CCRB Were Reported 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation, misconduct |
| Created | 2011-09-29T17:39:25Z |
| Publication Date | 2011-09-29T17:40:48Z |

## Description

CCRB: Gender of Victims Whose Allegations Were Substantiated 2005 - 2009

## Columns

```ls
| Included | Schema Type    | Field Name                                       | Name                                             | Data Type | Render Type |
| ======== | ============== | ================================================ | ================================================ | ========= | =========== |
| Yes      | series tag     | how_complaints_filed_with_the_ccrb_were_reported | How Complaints Filed with the CCRB Were Reported | text      | text        |
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
series e:94ka-ussk d:2005-01-01T00:00:00.000Z t:how_complaints_filed_with_the_ccrb_were_reported="In person" t:number_1=167 t:number_3=183 t:number_2=209 t:number_5=178 t:number_4=190 m:percent_of_total_3=3.8 m:percent_of_total_4=4.1 m:percent_of_total_1=3.7 m:percent_of_total_2=4.1 m:percent_of_total_5=3.8

series e:94ka-ussk d:2005-01-01T00:00:00.000Z t:how_complaints_filed_with_the_ccrb_were_reported="By telephone" t:number_1=4063 t:number_3=4203 t:number_2=4549 t:number_5=4009 t:number_4=3896 m:percent_of_total_3=87.1 m:percent_of_total_4=83.9 m:percent_of_total_1=88.8 m:percent_of_total_2=88.3 m:percent_of_total_5=86.4

series e:94ka-ussk d:2005-01-01T00:00:00.000Z t:how_complaints_filed_with_the_ccrb_were_reported="By mail/fax" t:number_1=103 t:number_3=109 t:number_2=91 t:number_5=123 t:number_4=124 m:percent_of_total_3=2.3 m:percent_of_total_4=2.7 m:percent_of_total_1=2.3 m:percent_of_total_2=1.8 m:percent_of_total_5=2.6
```

## Meta Commands

```ls
metric m:percent_of_total_1 p:float l:"2005 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_2 p:float l:"2006 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_3 p:float l:"2007 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_4 p:float l:"2008 Percent of Total" t:dataTypeName=percent

metric m:percent_of_total_5 p:float l:"2009 Percent of Total" t:dataTypeName=percent

entity e:94ka-ussk l:"How Complaints Filed With The CCRB Were Reported 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/94ka-ussk

property e:94ka-ussk t:meta.view v:id=94ka-ussk v:category="Public Safety" v:averageRating=0 v:name="How Complaints Filed With The CCRB Were Reported 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:94ka-ussk t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:94ka-ussk t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| how_complaints_filed_with_the_ccrb_were_reported | number_1 | percent_of_total_1 | number_2 | percent_of_total_2 | number_3 | percent_of_total_3 | number_4 | percent_of_total_4 | number_5 | percent_of_total_5 | 
| ================================================ | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | ======== | ================== | 
| In person                                        | 167      | 3.70               | 209      | 4.10               | 183      | 3.80               | 190      | 4.10               | 178      | 3.80               | 
| By telephone                                     | 4063     | 88.80              | 4549     | 88.30              | 4203     | 87.10              | 3896     | 83.90              | 4009     | 86.40              | 
| By mail/fax                                      | 103      | 2.30               | 91       | 1.80               | 109      | 2.30               | 124      | 2.70               | 123      | 2.60               | 
| Electronically                                   | 242      | 5.30               | 303      | 5.90               | 328      | 6.80               | 431      | 9.30               | 332      | 7.20               | 
| Total                                            | 4575     | 100.00             | 5152     | 100.00             | 4823     | 100.00             | 4641     | 100.00             | 4642     | 100.00             | 
```