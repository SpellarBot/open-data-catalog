# CCRB: Disciplinary Recommendations for Officers against Whom the CCRB Substantiated Allegations 2005 - 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/ccrb-disciplinary-recommendations-for-officers-against-whom-the-ccrb-substantiated-allegat-41027) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/jabk-zf7i) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/jabk-zf7i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/jabk-zf7i/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | jabk-zf7i |
| Name | CCRB: Disciplinary Recommendations for Officers against Whom the CCRB Substantiated Allegations 2005 - 2009 |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | Public Safety |
| Tags | complaint, civilian, review, board, activity, ccrb, civilian complaint review board, 2005, 2006, 2007, 2008, 2009, complaint activity, statistics, disciplinary recommendation, allegation |
| Created | 2011-09-15T19:37:31Z |
| Publication Date | 2011-09-15T19:37:31Z |

## Description

Civilian Complaint Review Board (CCRB) complaint activity data, 2005-2009 Update Schedule: Annually

## Columns

```ls
| Included | Schema Type    | Field Name                       | Name                             | Data Type | Render Type |
| ======== | ============== | ================================ | ================================ | ========= | =========== |
| Yes      | series tag     | ccrb_disciplinary_recommendation | CCRB Disciplinary Recommendation | text      | text        |
| Yes      | numeric metric | number_of_officers_2005          | Number of Officers 2005          | number    | number      |
| Yes      | numeric metric | number_of_officers_2006          | Number of Officers 2006          | number    | number      |
| Yes      | numeric metric | number_of_officers_2007          | Number of Officers 2007          | number    | number      |
| Yes      | numeric metric | number_of_officers_2008          | Number of Officers 2008          | number    | number      |
| Yes      | numeric metric | number_of_officers_2009          | Number of Officers 2009          | number    | number      |
```

## Time Field

```ls
Value = 2005
Format & Zone = yyyy
```

## Data Commands

```ls
series e:jabk-zf7i d:2005-01-01T00:00:00.000Z t:ccrb_disciplinary_recommendation="No recommendation" m:number_of_officers_2005=0 m:number_of_officers_2006=3 m:number_of_officers_2007=3 m:number_of_officers_2008=3 m:number_of_officers_2009=10

series e:jabk-zf7i d:2005-01-01T00:00:00.000Z t:ccrb_disciplinary_recommendation=Charges m:number_of_officers_2005=310 m:number_of_officers_2006=265 m:number_of_officers_2007=225 m:number_of_officers_2008=166 m:number_of_officers_2009=175

series e:jabk-zf7i d:2005-01-01T00:00:00.000Z t:ccrb_disciplinary_recommendation="Command discipline" m:number_of_officers_2005=49 m:number_of_officers_2006=66 m:number_of_officers_2007=54 m:number_of_officers_2008=43 m:number_of_officers_2009=67
```

## Meta Commands

```ls
metric m:number_of_officers_2005 p:integer l:"Number of Officers 2005" t:dataTypeName=number

metric m:number_of_officers_2006 p:integer l:"Number of Officers 2006" t:dataTypeName=number

metric m:number_of_officers_2007 p:integer l:"Number of Officers 2007" t:dataTypeName=number

metric m:number_of_officers_2008 p:integer l:"Number of Officers 2008" t:dataTypeName=number

metric m:number_of_officers_2009 p:integer l:"Number of Officers 2009" t:dataTypeName=number

entity e:jabk-zf7i l:"CCRB: Disciplinary Recommendations for Officers against Whom the CCRB Substantiated Allegations 2005 - 2009" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/jabk-zf7i

property e:jabk-zf7i t:meta.view v:id=jabk-zf7i v:category="Public Safety" v:averageRating=0 v:name="CCRB: Disciplinary Recommendations for Officers against Whom the CCRB Substantiated Allegations 2005 - 2009" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:jabk-zf7i t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:jabk-zf7i t:meta.view.tableauthor v:id=k2fz-tf56 v:screenName="Gary A" v:displayName="Gary A"
```

## Top Records

```ls
| ccrb_disciplinary_recommendation | number_of_officers_2005 | number_of_officers_2006 | number_of_officers_2007 | number_of_officers_2008 | number_of_officers_2009 | 
| ================================ | ======================= | ======================= | ======================= | ======================= | ======================= | 
| No recommendation                | 0                       | 3                       | 3                       | 3                       | 10                      | 
| Charges                          | 310                     | 265                     | 225                     | 166                     | 175                     | 
| Command discipline               | 49                      | 66                      | 54                      | 43                      | 67                      | 
| Instructions                     | 12                      | 13                      | 18                      | 7                       | 24                      | 
| Total Number of Subject Officers | 371                     | 347                     | 300                     | 219                     | 276                     | 
```