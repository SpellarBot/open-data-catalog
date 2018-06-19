# Municipal Expenditures By Category ? Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/municipal-expenditures-by-category-fiscal-year-2010-85332) |
| Metadata | [Link](https://data.maryland.gov/api/views/6ndv-zvyu) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/6ndv-zvyu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/6ndv-zvyu/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 6ndv-zvyu |
| Name | Municipal Expenditures By Category ? Fiscal Year 2010 |
| Attribution | Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Servic... |
| Category | Budget |
| Tags | expenditures, budget, municipal, municipalities, county, counties, spending, dls, department of legislative services |
| Created | 2014-08-08T18:32:06Z |
| Publication Date | 2014-08-08T18:36:16Z |

## Description

Percentages of municipalities' expenditures towards general government, public safety, public works, health and social services, education and libraries, parks and recreation, and debt service -- broken out by county. Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                  | Data Type | Render Type |
| ======== | ============== | ===================== | ===================== | ========= | =========== |
| Yes      | series tag     | county                | County                | text      | text        |
| Yes      | numeric metric | general_government    | General Government    | percent   | percent     |
| Yes      | numeric metric | public_safety         | Public Safety         | percent   | percent     |
| Yes      | numeric metric | public_works          | Public Works          | percent   | percent     |
| Yes      | numeric metric | parks_recreation      | Parks & Recreation    | percent   | percent     |
| Yes      | numeric metric | community_development | Community Development | percent   | percent     |
| Yes      | numeric metric | economic_development  | Economic Development  | percent   | percent     |
| Yes      | numeric metric | debt_service          | Debt Service          | percent   | percent     |
| Yes      | numeric metric | other                 | Other                 | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:6ndv-zvyu d:2010-01-01T00:00:00.000Z t:county=Allegany m:public_safety=22 m:other=2.8 m:parks_recreation=3.2 m:economic_development=0.1 m:general_government=5.5 m:debt_service=6.5 m:community_development=9.9 m:public_works=50.1

series e:6ndv-zvyu d:2010-01-01T00:00:00.000Z t:county="Anne Arundel" m:public_safety=36.4 m:other=0 m:parks_recreation=5 m:economic_development=0.4 m:general_government=21.8 m:debt_service=6.7 m:community_development=0.9 m:public_works=28.8

series e:6ndv-zvyu d:2010-01-01T00:00:00.000Z t:county=Calvert m:public_safety=11.4 m:other=2.3 m:parks_recreation=15 m:economic_development=1.4 m:general_government=17.6 m:debt_service=10.9 m:community_development=0.1 m:public_works=41.2
```

## Meta Commands

```ls
metric m:general_government p:float l:"General Government" t:dataTypeName=percent

metric m:public_safety p:float l:"Public Safety" t:dataTypeName=percent

metric m:public_works p:float l:"Public Works" t:dataTypeName=percent

metric m:parks_recreation p:float l:"Parks & Recreation" t:dataTypeName=percent

metric m:community_development p:float l:"Community Development" t:dataTypeName=percent

metric m:economic_development p:float l:"Economic Development" t:dataTypeName=percent

metric m:debt_service p:float l:"Debt Service" t:dataTypeName=percent

metric m:other p:float l:Other t:dataTypeName=percent

entity e:6ndv-zvyu l:"Municipal Expenditures By Category ? Fiscal Year 2010" t:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)" t:url=https://data.maryland.gov/api/views/6ndv-zvyu

property e:6ndv-zvyu t:meta.view v:id=6ndv-zvyu v:category=Budget v:attributionLink=http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf v:averageRating=0 v:name="Municipal Expenditures By Category ? Fiscal Year 2010" v:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)"

property e:6ndv-zvyu t:meta.view.license v:name="Public Domain"

property e:6ndv-zvyu t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:6ndv-zvyu t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| county       | general_government | public_safety | public_works | parks_recreation | community_development | economic_development | debt_service | other | 
| ============ | ================== | ============= | ============ | ================ | ===================== | ==================== | ============ | ===== | 
| Allegany     | 5.5                | 22.0          | 50.1         | 3.2              | 9.9                   | 0.1                  | 6.5          | 2.8   | 
| Anne Arundel | 21.8               | 36.4          | 28.8         | 5.0              | 0.9                   | 0.4                  | 6.7          | 0.0   | 
| Calvert      | 17.6               | 11.4          | 41.2         | 15.0             | 0.1                   | 1.4                  | 10.9         | 2.3   | 
| Caroline     | 12.3               | 25.1          | 43.3         | 4.5              | 5.7                   | 0.6                  | 6.7          | 1.9   | 
| Carroll      | 9.3                | 16.1          | 52.0         | 4.0              | 6.5                   | 0.3                  | 3.3          | 8.4   | 
| Cecil        | 12.5               | 22.5          | 54.8         | 5.2              | 0.0                   | 0.0                  | 4.5          | 0.4   | 
| Charles      | 15.3               | 9.9           | 58.4         | 5.8              | 0.1                   | 0.6                  | 3.7          | 6.1   | 
| Dorchester   | 8.1                | 23.9          | 41.6         | 3.1              | 0.6                   | 1.9                  | 6.9          | 13.7  | 
| Frederick    | 13.2               | 20.7          | 45.4         | 7.4              | 0.5                   | 2.7                  | 9.5          | 0.7   | 
| Garrett      | 11.5               | 4.5           | 55.9         | 4.7              | 4.7                   | 12.1                 | 5.2          | 1.4   | 
```