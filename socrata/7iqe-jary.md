# Method of Filing Complaint

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/method-of-filing-complaint-eb2f2) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/7iqe-jary) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/7iqe-jary/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/7iqe-jary/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | 7iqe-jary |
| Name | Method of Filing Complaint |
| Attribution | Civilian Complaint Review Board (CCRB) |
| Category | City Government |
| Tags | ccrb, nypd, fax, telephone, mail, electronically, inperson |
| Created | 2013-02-25T21:41:54Z |
| Publication Date | 2013-06-21T20:06:24Z |

## Description

This table represents the method adopted to file a complaint

## Columns

```ls
| Included | Schema Type    | Field Name     | Name           | Data Type | Render Type |
| ======== | ============== | ============== | ============== | ========= | =========== |
| Yes      | time           | year           | Year           | number    | text        |
| Yes      | numeric metric | inperson       | In-person      | number    | text        |
| Yes      | numeric metric | by_telephone   | By Telephone   | number    | text        |
| Yes      | numeric metric | by_fax_mail    | By Fax / Mail  | number    | text        |
| Yes      | numeric metric | electronically | Electronically | number    | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7iqe-jary d:2009-01-01T00:00:00.000Z m:inperson=178 m:by_fax_mail=124 m:electronically=330 m:by_telephone=124

series e:7iqe-jary d:2010-01-01T00:00:00.000Z m:inperson=137 m:by_fax_mail=49 m:electronically=396 m:by_telephone=49

series e:7iqe-jary d:2011-01-01T00:00:00.000Z m:inperson=132 m:by_fax_mail=66 m:electronically=467 m:by_telephone=66
```

## Meta Commands

```ls
metric m:inperson p:integer l:In-person t:dataTypeName=number

metric m:by_telephone p:integer l:"By Telephone" t:dataTypeName=number

metric m:by_fax_mail p:integer l:"By Fax / Mail" t:dataTypeName=number

metric m:electronically p:integer l:Electronically t:dataTypeName=number

entity e:7iqe-jary l:"Method of Filing Complaint" t:attribution="Civilian Complaint Review Board (CCRB)" t:url=https://data.cityofnewyork.us/api/views/7iqe-jary

property e:7iqe-jary t:meta.view v:id=7iqe-jary v:category="City Government" v:attributionLink=http://www.nyc.gov/html/ccrb/pdf/ccrbappendices2011.pdf v:averageRating=0 v:name="Method of Filing Complaint" v:attribution="Civilian Complaint Review Board (CCRB)"

property e:7iqe-jary t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:7iqe-jary t:meta.view.tableauthor v:id=iacr-duv5 v:screenName=Tejas.Patel v:displayName=Tejas.Patel
```

## Top Records

```ls
| year | inperson | by_telephone | by_fax_mail | electronically | 
| ==== | ======== | ============ | =========== | ============== | 
| 2009 | 178      | 124          | 124         | 330            | 
| 2010 | 137      | 49           | 49          | 396            | 
| 2011 | 132      | 66           | 66          | 467            | 
```