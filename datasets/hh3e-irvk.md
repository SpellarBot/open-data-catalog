# County Expenditures By Category ? Fiscal Year 2010

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/county-expenditures-by-category-fiscal-year-2010-6140d) |
| Metadata | [Link](https://data.maryland.gov/api/views/hh3e-irvk) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/hh3e-irvk/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/hh3e-irvk/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | hh3e-irvk |
| Name | County Expenditures By Category ? Fiscal Year 2010 |
| Attribution | Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Servic... |
| Category | Budget |
| Tags | expenditures, budget, county, counties, spending, dls, department of legislative services |
| Created | 2014-08-08T17:54:14Z |
| Publication Date | 2014-08-08T17:58:19Z |

## Description

Percentages of each county's expenditures towards general government, public safety, public works, health and social services, education and libraries, parks and recreation, and debt service. Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type | Render Type |
| ======== | ============== | ====================== | ====================== | ========= | =========== |
| Yes      | series tag     | county                 | County                 | text      | text        |
| Yes      | numeric metric | general_government     | General Government     | percent   | percent     |
| Yes      | numeric metric | public_safety          | Public Safety          | percent   | percent     |
| Yes      | numeric metric | public_works           | Public Works           | percent   | percent     |
| Yes      | numeric metric | health_social_services | Health/Social Services | percent   | percent     |
| Yes      | numeric metric | education_libraries    | Education/Libraries    | percent   | percent     |
| Yes      | numeric metric | parks_recreation       | Parks & Recreation     | percent   | percent     |
| Yes      | numeric metric | debt_service           | Debt Service           | percent   | percent     |
| Yes      | numeric metric | other                  | Other                  | percent   | percent     |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:hh3e-irvk d:2010-01-01T00:00:00.000Z t:county=Allegany m:public_safety=6.8 m:other=2.3 m:health_social_services=6.2 m:parks_recreation=0.2 m:general_government=3.1 m:debt_service=2.6 m:public_works=12.2 m:education_libraries=66.5

series e:hh3e-irvk d:2010-01-01T00:00:00.000Z t:county="Anne Arundel" m:public_safety=12.2 m:other=1.1 m:health_social_services=3.5 m:parks_recreation=1.8 m:general_government=5.4 m:debt_service=4.7 m:public_works=11.6 m:education_libraries=59.8

series e:hh3e-irvk d:2010-01-01T00:00:00.000Z t:county="Baltimore City" m:public_safety=14.3 m:other=13.5 m:health_social_services=4.8 m:parks_recreation=1.5 m:general_government=5.7 m:debt_service=2.9 m:public_works=16.7 m:education_libraries=40.6
```

## Meta Commands

```ls
metric m:general_government p:float l:"General Government" t:dataTypeName=percent

metric m:public_safety p:float l:"Public Safety" t:dataTypeName=percent

metric m:public_works p:float l:"Public Works" t:dataTypeName=percent

metric m:health_social_services p:float l:"Health/Social Services" t:dataTypeName=percent

metric m:education_libraries p:float l:Education/Libraries t:dataTypeName=percent

metric m:parks_recreation p:float l:"Parks & Recreation" t:dataTypeName=percent

metric m:debt_service p:float l:"Debt Service" t:dataTypeName=percent

metric m:other p:float l:Other t:dataTypeName=percent

entity e:hh3e-irvk l:"County Expenditures By Category ? Fiscal Year 2010" t:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)" t:url=https://data.maryland.gov/api/views/hh3e-irvk

property e:hh3e-irvk t:meta.view v:id=hh3e-irvk v:category=Budget v:attributionLink=http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf v:averageRating=0 v:name="County Expenditures By Category ? Fiscal Year 2010" v:attribution="Source: Local Government Finances Fiscal 2010 (Department of Legislative Services), via Overview of Maryland Local Governments Finances and Demographic Information (Department of Legislative Services, 2012. Link: http://mgaleg.maryland.gov/pubs/budgetfiscal/2012-local-government-finances-demographics.pdf)"

property e:hh3e-irvk t:meta.view.license v:name="Public Domain"

property e:hh3e-irvk t:meta.view.owner v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"

property e:hh3e-irvk t:meta.view.tableauthor v:id=cs6p-bz62 v:profileImageUrlMedium=/api/users/cs6p-bz62/profile_images/THUMB v:profileImageUrlLarge=/api/users/cs6p-bz62/profile_images/LARGE v:screenName="data.maryland.gov Administration" v:profileImageUrlSmall=/api/users/cs6p-bz62/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1491976108 v:displayName="data.maryland.gov Administration"
```

## Top Records

```ls
| county           | general_government | public_safety | public_works | health_social_services | education_libraries | parks_recreation | debt_service | other | 
| ================ | ================== | ============= | ============ | ====================== | =================== | ================ | ============ | ===== | 
| Allegany         | 3.1                | 6.8           | 12.2         | 6.2                    | 66.5                | 0.2              | 2.6          | 2.3   | 
| Anne Arundel     | 5.4                | 12.2          | 11.6         | 3.5                    | 59.8                | 1.8              | 4.7          | 1.1   | 
| Baltimore City   | 5.7                | 14.3          | 16.7         | 4.8                    | 40.6                | 1.5              | 2.9          | 13.5  | 
| Baltimore County | 4.8                | 11.8          | 11.7         | 2.5                    | 57.1                | 1.6              | 3.0          | 7.4   | 
| Calvert          | 4.0                | 7.3           | 8.1          | 3.1                    | 61.4                | 4.1              | 5.5          | 6.5   | 
| Caroline         | 3.0                | 7.7           | 2.8          | 4.3                    | 68.1                | 1.3              | 6.6          | 6.2   | 
| Carroll          | 6.2                | 5.4           | 6.5          | 3.3                    | 64.8                | 0.7              | 6.6          | 6.6   | 
| Cecil            | 3.9                | 9.0           | 7.0          | 4.0                    | 68.6                | 0.5              | 4.8          | 2.2   | 
| Charles          | 6.4                | 13.1          | 7.7          | 3.1                    | 60.4                | 1.8              | 5.4          | 2.2   | 
| Dorchester       | 10.4               | 8.7           | 7.0          | 4.6                    | 59.8                | 0.9              | 2.4          | 6.2   | 
```