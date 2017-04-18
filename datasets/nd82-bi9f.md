# Procurement By Industry

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/procurement-by-industry-eb653) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/nd82-bi9f) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/nd82-bi9f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/nd82-bi9f/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | nd82-bi9f |
| Name | Procurement By Industry |
| Attribution | Office of the Mayor (OTM) |
| Category | City Government |
| Tags | otm, mayor's office, procurement, industry |
| Created | 2014-10-23T20:13:42Z |
| Publication Date | 2014-10-23T20:16:17Z |

## Description

Summary table of procurements in the fiscal year grouped by agency and industry

## Columns

```ls
| Included | Schema Type    | Field Name    | Name          | Data Type | Render Type |
| ======== | ============== | ============= | ============= | ========= | =========== |
| No       | time           | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag     | agency        | Agency        | text      | text        |
| Yes      | numeric metric | 2014_fy_count | 2014 FY Count | number    | number      |
| Yes      | numeric metric | 2014_fy_value | 2014 FY Value | money     | money       |
| Yes      | numeric metric | 2013_fy_count | 2013 FY Count | number    | number      |
| Yes      | numeric metric | 2013_fy_value | 2013 FY Value | money     | money       |
| Yes      | numeric metric | 2012_fy_count | 2012 FY Count | number    | number      |
| Yes      | numeric metric | 2012_fy_value | 2012 FY Value | money     | money       |
| Yes      | numeric metric | 2011_fy_count | 2011 FY Count | number    | number      |
| Yes      | numeric metric | 2011_fy_value | 2011 FY Value | money     | money       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:nd82-bi9f d:2014-10-23T13:13:45.000Z t:agency=ACS m:2012_fy_value=15174204 m:2011_fy_value=25794461 m:2014_fy_count=631 m:2012_fy_count=551 m:2013_fy_count=529 m:2013_fy_value=496551457 m:2011_fy_count=375 m:2014_fy_value=168622554

series e:nd82-bi9f d:2014-10-23T13:13:45.000Z t:agency=BIC m:2012_fy_value=140424 m:2011_fy_value=139509 m:2014_fy_count=31 m:2012_fy_count=111 m:2013_fy_count=44 m:2013_fy_value=760097 m:2011_fy_count=38 m:2014_fy_value=187816

series e:nd82-bi9f d:2014-10-23T13:13:45.000Z t:agency=CCHR m:2012_fy_value=61253 m:2011_fy_value=87707 m:2014_fy_count=55 m:2012_fy_count=40 m:2013_fy_count=63 m:2013_fy_value=105841 m:2011_fy_count=42 m:2014_fy_value=91575
```

## Meta Commands

```ls
metric m:2014_fy_count p:integer l:"2014 FY Count" t:dataTypeName=number

metric m:2014_fy_value p:long l:"2014 FY Value" t:dataTypeName=money

metric m:2013_fy_count p:integer l:"2013 FY Count" t:dataTypeName=number

metric m:2013_fy_value p:integer l:"2013 FY Value" t:dataTypeName=money

metric m:2012_fy_count p:integer l:"2012 FY Count" t:dataTypeName=number

metric m:2012_fy_value p:integer l:"2012 FY Value" t:dataTypeName=money

metric m:2011_fy_count p:integer l:"2011 FY Count" t:dataTypeName=number

metric m:2011_fy_value p:integer l:"2011 FY Value" t:dataTypeName=money

entity e:nd82-bi9f l:"Procurement By Industry" t:attribution="Office of the Mayor (OTM)" t:url=https://data.cityofnewyork.us/api/views/nd82-bi9f

property e:nd82-bi9f t:meta.view v:id=nd82-bi9f v:category="City Government" v:averageRating=0 v:name="Procurement By Industry" v:attribution="Office of the Mayor (OTM)"

property e:nd82-bi9f t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:nd82-bi9f t:meta.view.tableauthor v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:roleName=administrator v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"
```

## Top Records

```ls
| :updated_at | agency | 2014_fy_count | 2014_fy_value | 2013_fy_count | 2013_fy_value | 2012_fy_count | 2012_fy_value | 2011_fy_count | 2011_fy_value | 
| =========== | ====== | ============= | ============= | ============= | ============= | ============= | ============= | ============= | ============= | 
| 1414070025  | ACS    | 631           | 168622554     | 529           | 496551457     | 551           | 15174204      | 375           | 25794461      | 
| 1414070025  | BIC    | 31            | 187816        | 44            | 760097        | 111           | 140424        | 38            | 139509        | 
| 1414070025  | CCHR   | 55            | 91575         | 63            | 105841        | 40            | 61253         | 42            | 87707         | 
| 1414070025  | CCRB   | 92            | 416309        | 65            | 149390        | 75            | 206601        | 67            | 236668        | 
| 1414070025  | CCSC   |               |               |               |               |               |               | 4             | 35503         | 
| 1414070025  | DCA    | 161           | 1426206       | 159           | 937709        | 174           | 939835        | 102           | 864807        | 
| 1414070025  | DCAS   | 475           | 434038234     | 588           | 1350238346    | 745           | 288395272     | 287           | 384176671     | 
| 1414070025  | DCLA   | 21            | 169427        | 39            | 178185        | 24            | 93743         | 17            | 93560         | 
| 1414070025  | DCP    | 44            | 195110        | 54            | 1682822       | 75            | 145938        | 51            | 26608         | 
| 1414070025  | DDC    | 226           | 13472561      | 198           | 13646382      | 206           | 6735637       | 121           | 3992812       | 
```