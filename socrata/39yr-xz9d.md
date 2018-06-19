# City of Albany Five Year Capital Plan: Beginning 2013

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-of-albany-five-year-capital-plan-beginning-2013) |
| Metadata | [Link](https://data.ny.gov/api/views/39yr-xz9d) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/39yr-xz9d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/39yr-xz9d/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 39yr-xz9d |
| Name | City of Albany Five Year Capital Plan: Beginning 2013 |
| Attribution | City of Albany |
| Category | Government & Finance |
| Tags | albany, capital plan, budget, finance |
| Created | 2013-03-02T00:30:02Z |
| Publication Date | 2013-03-04T22:21:47Z |

## Description

This data summarizes the capital budget requests for 2013 and the five-year capital plan.  Although the five-year capital plan is a plan only and is subject to changes as needed over the years, the capital budget is a one-year proposal reviewed as part of the financial authorization for 2013.The 2013 capital program totals $17,833,000 of which $190,000 is funded through the operating budget, $12,418,000 is expected to be borrowed and $5,225,000 will come from other funds such as the Consolidated Highway Improvement Program (CHIPs) and federal and state grants.  Included in this budget are monies for street and sidewalk reconstruction projects, building improvement projects and various equipment and vehicle replacement items.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| Yes      | series tag     | department       | Department       | text      | text        |
| Yes      | series tag     | item             | Item             | text      | text        |
| Yes      | numeric metric | 2013             | 2013             | money     | money       |
| Yes      | numeric metric | 2014             | 2014             | money     | money       |
| Yes      | numeric metric | 2015             | 2015             | money     | money       |
| Yes      | numeric metric | 2016             | 2016             | money     | money       |
| Yes      | numeric metric | 2017             | 2017             | money     | money       |
| Yes      | numeric metric | total            | Total            | money     | money       |
| Yes      | series tag     | financing_method | Financing Method | text      | text        |
```

## Time Field

```ls
Value = 2013
Format & Zone = yyyy
```

## Data Commands

```ls
series e:39yr-xz9d d:2013-01-01T00:00:00.000Z t:department="Department of General Services (DGS)" t:item="Recycling Packers (2)" t:financing_method=Borrowings m:2017=0 m:total=620000 m:2013=240000 m:2014=0 m:2015=0 m:2016=380000

series e:39yr-xz9d d:2013-01-01T00:00:00.000Z t:department="Department of General Services (DGS)" t:item="Medium Duty Dump Truck" t:financing_method=Borrowings m:2017=140000 m:total=410000 m:2013=130000 m:2014=0 m:2015=140000 m:2016=0

series e:39yr-xz9d d:2013-01-01T00:00:00.000Z t:department="Department of General Services (DGS)" t:item="Pick Up Trucks (5)" t:financing_method=Borrowings m:2017=70000 m:total=315000 m:2013=125000 m:2014=60000 m:2015=60000 m:2016=0
```

## Meta Commands

```ls
metric m:2013 p:integer l:2013 t:dataTypeName=money

metric m:2014 p:integer l:2014 t:dataTypeName=money

metric m:2015 p:integer l:2015 t:dataTypeName=money

metric m:2016 p:integer l:2016 t:dataTypeName=money

metric m:2017 p:integer l:2017 t:dataTypeName=money

metric m:total p:integer l:Total t:dataTypeName=money

entity e:39yr-xz9d l:"City of Albany Five Year Capital Plan: Beginning 2013" t:attribution="City of Albany" t:url=https://data.ny.gov/api/views/39yr-xz9d

property e:39yr-xz9d t:meta.view v:id=39yr-xz9d v:category="Government & Finance" v:attributionLink=http://albanyny.gov/Government/MayorsOffice/Budget.aspx v:averageRating=0 v:name="City of Albany Five Year Capital Plan: Beginning 2013" v:attribution="City of Albany"

property e:39yr-xz9d t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:39yr-xz9d t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:39yr-xz9d t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| department                           | item                   | 2013   | 2014  | 2015   | 2016   | 2017   | total  | financing_method | 
| ==================================== | ====================== | ====== | ===== | ====== | ====== | ====== | ====== | ================ | 
| Department of General Services (DGS) | Recycling Packers (2)  | 240000 | 0     | 0      | 380000 | 0      | 620000 | Borrowings       | 
| Department of General Services (DGS) | Medium Duty Dump Truck | 130000 | 0     | 140000 | 0      | 140000 | 410000 | Borrowings       | 
| Department of General Services (DGS) | Pick Up Trucks (5)     | 125000 | 60000 | 60000  | 0      | 70000  | 315000 | Borrowings       | 
| Department of General Services (DGS) | Street Vacs (2)        | 60000  | 0     | 0      | 0      | 0      | 60000  | Borrowings       | 
| Department of General Services (DGS) | One Ton Flipper Truck  | 85000  | 0     | 0      | 0      | 0      | 85000  | Borrowings       | 
| Department of General Services (DGS) | One Ton Utility Truck  | 50000  | 0     | 90000  | 0      | 50000  | 190000 | Borrowings       | 
| Department of General Services (DGS) | One Ton Dump Truck     | 100000 | 0     | 100000 | 100000 | 0      | 300000 | Borrowings       | 
| Department of General Services (DGS) | Heavy Duty CDL Truck   | 250000 | 0     | 0      | 0      | 0      | 250000 | Borrowings       | 
| Department of General Services (DGS) | Folding Bucket Truck   | 110000 | 0     | 0      | 0      | 0      | 110000 | Borrowings       | 
| Department of General Services (DGS) | Street Sweeper         | 170000 | 0     | 175000 | 0      | 180000 | 525000 | Borrowings       | 
```