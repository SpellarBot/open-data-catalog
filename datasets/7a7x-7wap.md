# City of Albany Budget Summary: 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-albany-budget-summary-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/7a7x-7wap) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/7a7x-7wap/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/7a7x-7wap/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 7a7x-7wap |
| Name | City of Albany Budget Summary: 2013 |
| Attribution | City of Albany |
| Category | Government & Finance |
| Tags | albany, budget |
| Created | 2013-03-02T00:31:02Z |
| Publication Date | 2013-03-07T20:31:27Z |

## Description

This data summarizes the 2013 adopted budget for the City of Albany.  Over the years, we've consolidated or eliminated departments, cut personnel, refinanced debt, reduced departmental expenditures, extended the life of our landfill, successfully lobbied for increase State aid and identified new sources of revenue.  These actions are the blocks upon which this budget is built, as they continue to have a recurring benefit to our bottom line.  It is important to note that, in fact, 84% of this budget, exclusive of debt services, is related to personnel costs.  The remainder is related to essential operating services, such as utility expenses; building maintenance; insurance costs and the like.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | series tag     | department           | Department           | text      | text        |
| Yes      | numeric metric | personal_services    | Personal Services    | money     | money       |
| Yes      | numeric metric | equipment            | Equipment            | money     | money       |
| Yes      | numeric metric | contractual_expenses | Contractual Expenses | money     | money       |
| Yes      | numeric metric | benefits             | Benefits             | money     | money       |
| Yes      | numeric metric | debt_service         | Debt Service         | money     | money       |
| Yes      | numeric metric | total                | Total                | money     | money       |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:7a7x-7wap d:2013-01-01T00:00:00.000Z t:department=Mayor m:total=735784 m:personal_services=598685 m:debt_service=0 m:contractual_expenses=10300 m:equipment=0 m:benefits=126799

series e:7a7x-7wap d:2013-01-01T00:00:00.000Z t:department="Central Data Processing" m:total=668792 m:personal_services=394605 m:debt_service=0 m:contractual_expenses=133000 m:equipment=52000 m:benefits=89187

series e:7a7x-7wap d:2013-01-01T00:00:00.000Z t:department="Common Council" m:total=592268 m:personal_services=435920 m:debt_service=0 m:contractual_expenses=33500 m:equipment=1500 m:benefits=121348
```

## Meta Commands

```ls
metric m:personal_services p:integer l:"Personal Services" t:dataTypeName=money

metric m:equipment p:integer l:Equipment t:dataTypeName=money

metric m:contractual_expenses p:integer l:"Contractual Expenses" t:dataTypeName=money

metric m:benefits p:integer l:Benefits t:dataTypeName=money

metric m:debt_service p:integer l:"Debt Service" t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:7a7x-7wap l:"City of Albany Budget Summary: 2013" t:attribution="City of Albany" t:url=https://data.ny.gov/api/views/7a7x-7wap

property e:7a7x-7wap t:meta.view d:2017-06-09T13:57:37.956Z v:id=7a7x-7wap v:category="Government & Finance" v:attributionLink=http://albanyny.gov/Government/MayorsOffice/Budget.aspx v:averageRating=0 v:name="City of Albany Budget Summary: 2013" v:attribution="City of Albany"

property e:7a7x-7wap t:meta.view.owner d:2017-06-09T13:57:37.956Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:7a7x-7wap t:meta.view.tableauthor d:2017-06-09T13:57:37.956Z v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:7a7x-7wap t:meta.view.metadata.custom_fields.common_core d:2017-06-09T13:57:37.956Z v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| department                  | personal_services | equipment | contractual_expenses | benefits | debt_service | total   | 
| =========================== | ================= | ========= | ==================== | ======== | ============ | ======= | 
| Mayor                       | 598685            | 0         | 10300                | 126799   | 0            | 735784  | 
| Central Data Processing     | 394605            | 52000     | 133000               | 89187    | 0            | 668792  | 
| Common Council              | 435920            | 1500      | 33500                | 121348   | 0            | 592268  | 
| Treasurer                   | 980014            | 0         | 353600               | 289971   | 0            | 1623585 | 
| Office of Audit & Control   | 260036            | 1000      | 111000               | 74893    | 0            | 446929  | 
| Development & Planning      | 95402             | 0         | 0                    | 42103    | 0            | 137505  | 
| Housing & Comm. Development | 760428            | 0         | 68500                | 374038   | 0            | 1202966 | 
| Division of Planning        | 436780            | 0         | 124000               | 92414    | 0            | 653194  | 
| Law Department              | 739948            | 3000      | 434700               | 148606   | 0            | 1326254 | 
| Admin.Services/Personnel    | 710800            | 0         | 23000                | 119731   | 0            | 853531  | 
```