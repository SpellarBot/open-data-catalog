# HDA - Illinois Housing Dev Auth - HomeOwnership - FY2012

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hda-illinois-housing-dev-auth-homeownership-fy2012-f9d18) |
| Metadata | [Link](https://data.illinois.gov/api/views/spg7-snr5) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/spg7-snr5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/spg7-snr5/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | spg7-snr5 |
| Name | HDA - Illinois Housing Dev Auth - HomeOwnership - FY2012 |
| Category | Housing |
| Tags | ihda, illinois housing development authority, home ownership |
| Created | 2013-03-01T20:19:41Z |
| Publication Date | 2013-03-01T20:24:14Z |

## Description

Data reported is for projects that have been Board approved, not closed or placed in service

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type     | Render Type   |
| ======== | ============== | ================== | ================== | ============= | ============= |
| Yes      | series tag     | development_name   | DEVELOPMENT NAME   | text          | text          |
| Yes      | series tag     | city               | CITY               | text          | text          |
| Yes      | series tag     | county             | COUNTY             | text          | text          |
| Yes      | time           | board_date         | BOARD DATE         | calendar_date | calendar_date |
| Yes      | numeric metric | total_units        | TOTAL UNITS        | number        | number        |
| Yes      | series tag     | tenant_type        | TENANT TYPE        | text          | text          |
| Yes      | numeric metric | total_ihda_dollars | TOTAL IHDA DOLLARS | money         | money         |
| Yes      | numeric metric | leveraged_dollars  | LEVERAGED DOLLARS  | money         | money         |
| Yes      | numeric metric | total_project_cost | TOTAL PROJECT COST | money         | money         |
| No       |                | fiscal_year        | FISCAL YEAR        | number        | number        |
```

## Time Field

```ls
Value = board_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fiscal_year
```

## Data Commands

```ls
series e:spg7-snr5 d:2012-04-18T00:00:00.000Z t:tenant_type=FAMILY t:county=MARION t:development_name="B.C.M.W. COMMUNITY SERVICES, INC." t:city="MULTIPLE CITIES" m:total_project_cost=640000 m:leveraged_dollars=0 m:total_ihda_dollars=640000 m:total_units=16

series e:spg7-snr5 d:2012-04-18T00:00:00.000Z t:tenant_type=FAMILY t:county=CLAY t:development_name="C.E.F.S. ECONOMIC OPPORTUNITY CORPORATION" t:city="MULTIPLE CITIES" m:total_project_cost=210000 m:leveraged_dollars=0 m:total_ihda_dollars=210000 m:total_units=5

series e:spg7-snr5 d:2012-04-18T00:00:00.000Z t:tenant_type=FAMILY t:county=MCLEAN t:development_name="CITY OF BLOOMINGTON SFOOR" t:city=BLOOMINGTON m:total_project_cost=200000 m:leveraged_dollars=0 m:total_ihda_dollars=200000 m:total_units=5
```

## Meta Commands

```ls
metric m:total_units p:integer l:"TOTAL UNITS" t:dataTypeName=number

metric m:total_ihda_dollars p:integer l:"TOTAL IHDA DOLLARS" t:dataTypeName=money

metric m:leveraged_dollars p:integer l:"LEVERAGED DOLLARS" t:dataTypeName=money

metric m:total_project_cost p:integer l:"TOTAL PROJECT COST" t:dataTypeName=money

entity e:spg7-snr5 l:"HDA - Illinois Housing Dev Auth - HomeOwnership - FY2012" t:url=https://data.illinois.gov/api/views/spg7-snr5

property e:spg7-snr5 t:meta.view v:id=spg7-snr5 v:category=Housing v:averageRating=0 v:name="HDA - Illinois Housing Dev Auth - HomeOwnership - FY2012"

property e:spg7-snr5 t:meta.view.owner v:id=aj8g-k6pc v:screenName=Tanya v:displayName=Tanya

property e:spg7-snr5 t:meta.view.tableauthor v:id=aj8g-k6pc v:screenName=Tanya v:roleName=publisher v:displayName=Tanya
```

## Top Records

```ls
| development_name                          | city            | county     | board_date          | total_units | tenant_type | total_ihda_dollars | leveraged_dollars | total_project_cost | fiscal_year | 
| ========================================= | =============== | ========== | =================== | =========== | =========== | ================== | ================= | ================== | =========== | 
| B.C.M.W. COMMUNITY SERVICES, INC.         | MULTIPLE CITIES | MARION     | 2012-04-18T00:00:00 | 16          | FAMILY      | 640000             | 0                 | 640000             | 2012        | 
| C.E.F.S. ECONOMIC OPPORTUNITY CORPORATION | MULTIPLE CITIES | CLAY       | 2012-04-18T00:00:00 | 5           | FAMILY      | 210000             | 0                 | 210000             | 2012        | 
| CITY OF BLOOMINGTON SFOOR                 | BLOOMINGTON     | MCLEAN     | 2012-04-18T00:00:00 | 5           | FAMILY      | 200000             | 0                 | 200000             | 2012        | 
| CITY OF CARBONDALE - SFOOR                | CARBONDALE      | JACKSON    | 2012-04-18T00:00:00 | 6           | FAMILY      | 240000             | 0                 | 240000             | 2012        | 
| CITY OF CHARLESTON - SFOOR                | CHARLESTON      | COLES      | 2012-04-18T00:00:00 | 6           | FAMILY      | 240000             | 0                 | 240000             | 2012        | 
| CITY OF FREEPORT                          | FREEPORT        | STEPHENSON | 2012-04-18T00:00:00 | 5           | FAMILY      | 200000             | 0                 | 200000             | 2012        | 
| CITY OF GREENVILLE - SFOOR                | GREENVILLE      | BOND       | 2012-04-18T00:00:00 | 5           | FAMILY      | 200000             | 0                 | 200000             | 2012        | 
| CITY OF JOHNSTON CITY - SFOOR             | JOHNSTON CITY   | WILLIAMSON | 2012-04-18T00:00:00 | 5           | FAMILY      | 200000             | 0                 | 200000             | 2012        | 
| CITY OF KANKAKEE - SFOOR                  | KANKAKEE        | KANKAKEE   | 2012-04-18T00:00:00 | 6           | FAMILY      | 240000             | 0                 | 240000             | 2012        | 
| CITY OF MARION - SFOOR                    | MARION          | WILLIAMSON | 2012-04-18T00:00:00 | 5           | FAMILY      | 200000             | 0                 | 200000             | 2012        | 
```