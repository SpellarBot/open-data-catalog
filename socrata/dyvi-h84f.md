# Table 21.25 STATE GOVERNMENT CAPITAL IMPROVEMENT PROJECT EXPENDITURES 1990 TO 2014

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/table-21-25-state-government-capital-improvement-project-expenditures-1990-to-2013) |
| Metadata | [Link](https://data.hawaii.gov/api/views/dyvi-h84f) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/dyvi-h84f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/dyvi-h84f/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | dyvi-h84f |
| Name | Table 21.25 STATE GOVERNMENT CAPITAL IMPROVEMENT PROJECT EXPENDITURES 1990 TO 2014 |
| Attribution | Department of Economic Development and Tourism |
| Category | Government-Wide Support |
| Tags | cip, capital |
| Created | 2012-08-28T22:02:20Z |
| Publication Date | 2015-10-13T02:06:47Z |

## Description

* General obligation bond consists of general obligation bonds and reimbursable general obligation bonds.    							
* Revenue bond consists of revenue bonds and special purpose revenue bonds.    							
* Federal funds includes special federal aid:  interstate, primary, secondary; and federal funds.   							
     Source:  Hawaii State Department of Accounting and General Services, records, and calculations by DBEDT							
Please go to the DBEDT Databook site, http://hawaii.gov/dbedt/info/economic/databook,  for the complete data source.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                    | Data Type | Render Type |
| ======== | ============== | ====================== | ======================= | ========= | =========== |
| Yes      | time           | year                   | Year                    | number    | text        |
| Yes      | numeric metric | totalexpenditures      | Total expenditures      | money     | money       |
| Yes      | numeric metric | general_obligationbond | General obligation bond | money     | money       |
| Yes      | numeric metric | revenue_bond           | Revenue bond            | money     | money       |
| Yes      | numeric metric | general_fund_cash      | General fund(cash)      | money     | money       |
| Yes      | numeric metric | special_fund           | Special fund            | money     | money       |
| Yes      | numeric metric | federal_funds          | Federal funds           | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:dyvi-h84f d:1990-01-01T00:00:00.000Z m:general_obligationbond=248379 m:totalexpenditures=995163 m:general_fund_cash=133529 m:revenue_bond=368502 m:federal_funds=164755 m:special_fund=79998

series e:dyvi-h84f d:1991-01-01T00:00:00.000Z m:general_obligationbond=210022 m:totalexpenditures=1027189 m:general_fund_cash=121108 m:revenue_bond=326414 m:federal_funds=204730 m:special_fund=164915

series e:dyvi-h84f d:1992-01-01T00:00:00.000Z m:general_obligationbond=331720 m:totalexpenditures=1323450 m:general_fund_cash=138867 m:revenue_bond=512432 m:federal_funds=215826 m:special_fund=124605
```

## Meta Commands

```ls
metric m:totalexpenditures p:integer l:"Total expenditures" t:dataTypeName=money

metric m:general_obligationbond p:double l:"General obligation bond" t:dataTypeName=money

metric m:revenue_bond p:integer l:"Revenue bond" t:dataTypeName=money

metric m:general_fund_cash p:integer l:"General fund(cash)" t:dataTypeName=money

metric m:special_fund p:double l:"Special fund" t:dataTypeName=money

metric m:federal_funds p:double l:"Federal funds" t:dataTypeName=money

entity e:dyvi-h84f l:"Table 21.25 STATE GOVERNMENT CAPITAL IMPROVEMENT PROJECT EXPENDITURES  1990 TO 2014" t:attribution="Department of Economic Development and Tourism" t:url=https://data.hawaii.gov/api/views/dyvi-h84f

property e:dyvi-h84f t:meta.view v:id=dyvi-h84f v:category="Government-Wide Support" v:attributionLink=http://dbedt.hawaii.gov/economic/databook/ v:averageRating=0 v:name="Table 21.25 STATE GOVERNMENT CAPITAL IMPROVEMENT PROJECT EXPENDITURES  1990 TO 2014" v:attribution="Department of Economic Development and Tourism"

property e:dyvi-h84f t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:dyvi-h84f t:meta.view.owner v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:displayName="Yang-Seon Kim"

property e:dyvi-h84f t:meta.view.tableauthor v:id=6k8y-ahyw v:screenName="Yang-Seon Kim" v:roleName=editor v:displayName="Yang-Seon Kim"
```

## Top Records

```ls
| year | totalexpenditures | general_obligationbond | revenue_bond | general_fund_cash | special_fund | federal_funds | 
| ==== | ================= | ====================== | ============ | ================= | ============ | ============= | 
| 1990 | 995163            | 248379                 | 368502       | 133529            | 79998        | 164755        | 
| 1991 | 1027189           | 210022                 | 326414       | 121108            | 164915       | 204730        | 
| 1992 | 1323450           | 331720                 | 512432       | 138867            | 124605       | 215826        | 
| 1993 | 1188315           | 472515                 | 225431       | 89917             | 147351       | 253101        | 
| 1994 | 1214487           | 492048                 | 327980       | 56662             | 135440       | 202357        | 
| 1995 | 822327            | 342423                 | 77560        | 19672             | 169901       | 212772        | 
| 1996 | 720580            | 286472                 | 66625        | 6719              | 165426       | 195338        | 
| 1997 | 898496            | 345440                 | 220496       | 3181              | 163130       | 166249        | 
| 1998 | 818181            | 329218                 | 199294       | 1963              | 192397       | 95309         | 
| 1999 | 626916            | 293229                 | 35735        | 348               | 212446       | 85159         | 
```