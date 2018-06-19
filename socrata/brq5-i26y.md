# 2010 Human Services Contracts with the City of Seattle

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2010-human-services-contracts-with-the-city-of-seattle-7a63d) |
| Metadata | [Link](https://data.seattle.gov/api/views/brq5-i26y) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/brq5-i26y/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/brq5-i26y/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | brq5-i26y |
| Name | 2010 Human Services Contracts with the City of Seattle |
| Attribution | Department of Human Services |
| Category | Community |
| Tags | contracts, agency, human services, services, 2010 |
| Created | 2010-04-29T19:39:06Z |
| Publication Date | 2011-04-17T00:03:09Z |

## Description

This data set provides the Human Services Department division, agency, contract amounts for 2009 for agencies that contract with the City of Seattle for human services.

## Columns

```ls
| Included | Schema Type    | Field Name                         | Name                               | Data Type | Render Type |
| ======== | ============== | ================================== | ================================== | ========= | =========== |
| Yes      | series tag     | human_services_department_division | Human Services Department Division | text      | text        |
| Yes      | series tag     | agency                             | Agency                             | text      | text        |
| Yes      | numeric metric | amount                             | Amount                             | number    | number      |
```

## Time Field

```ls
Value = 2010
Format & Zone = yyyy
```

## Data Commands

```ls
series e:brq5-i26y d:2010-01-01T00:00:00.000Z t:agency="A & B Homecare and Staffing, Inc." t:human_services_department_division="Aging & Disability Services" m:amount=33500

series e:brq5-i26y d:2010-01-01T00:00:00.000Z t:agency="AAA Residential Services Inc." t:human_services_department_division="Aging & Disability Services" m:amount=137750

series e:brq5-i26y d:2010-01-01T00:00:00.000Z t:agency="Addus HealthCare, Inc." t:human_services_department_division="Aging & Disability Services" m:amount=357520
```

## Meta Commands

```ls
metric m:amount p:double l:Amount d:"Amount of contract in dollars" t:dataTypeName=number

entity e:brq5-i26y l:"2010 Human Services Contracts with the City of Seattle" t:attribution="Department of Human Services" t:url=https://data.seattle.gov/api/views/brq5-i26y

property e:brq5-i26y t:meta.view v:id=brq5-i26y v:category=Community v:attributionLink=http://www.seattle.gov/humanservices/ v:averageRating=0 v:name="2010 Human Services Contracts with the City of Seattle" v:attribution="Department of Human Services"

property e:brq5-i26y t:meta.view.license v:name="Public Domain"

property e:brq5-i26y t:meta.view.owner v:id=zxcy-ghm5 v:screenName="Department of Human Services" v:displayName="Department of Human Services"

property e:brq5-i26y t:meta.view.tableauthor v:id=zxcy-ghm5 v:screenName="Department of Human Services" v:displayName="Department of Human Services"
```

## Top Records

```ls
| human_services_department_division | agency                                                  | amount     | 
| ================================== | ======================================================= | ========== | 
| Aging & Disability Services        | A & B Homecare and Staffing, Inc.                       | 33500      | 
| Aging & Disability Services        | AAA Residential Services Inc.                           | 137750     | 
| Aging & Disability Services        | Addus HealthCare, Inc.                                  | 357520     | 
| Aging & Disability Services        | Alzheimer's Association of Western & Central Washington | 126140     | 
| Aging & Disability Services        | American Healthcare Services, Inc.                      | 66300      | 
| Aging & Disability Services        | Amicable Healthcare, Inc.                               | 3382900    | 
| Aging & Disability Services        | Asian American Chemical Dependency Treatment Svcs.      | 37041.56   | 
| Aging & Disability Services        | Asian Counseling & Referral Service                     | 5942315.16 | 
| Aging & Disability Services        | Atlantic Street Center                                  | 31270      | 
| Aging & Disability Services        | Auburn Respite Program                                  | 3600       | 
```