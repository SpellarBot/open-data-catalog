# Current Certified Pesticide Applicators

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/current-certified-pesticide-applicators) |
| Metadata | [Link](https://data.ny.gov/api/views/c7db-kwpj) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/c7db-kwpj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/c7db-kwpj/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | c7db-kwpj |
| Name | Current Certified Pesticide Applicators |
| Attribution | New York State Department of Environmental Conservation (DEC) |
| Category | Energy & Environment |
| Tags | pesticides, weeds, pests |
| Created | 2015-12-21T14:22:44Z |
| Publication Date | 2017-04-20T10:16:40Z |

## Description

This dataset is a list of pesticide applicators currently certified by New York State Department of Environmental Conservation (DEC) in the various categories of individual certification (6NYCRR Part 325).  It includes certificate number, name, DEC region, expiration date, applicator type and category.

## Columns

```ls
| Included | Schema Type | Field Name           | Name                 | Data Type     | Render Type   |
| ======== | =========== | ==================== | ==================== | ============= | ============= |
| Yes      | series tag  | cert_number          | Certificate Number   | text          | text          |
| Yes      | series tag  | first_name           | First Name           | text          | text          |
| Yes      | series tag  | last_name            | Last Name            | text          | text          |
| Yes      | series tag  | middle_name          | Middle Name          | text          | text          |
| Yes      | series tag  | suffix               | Suffix               | text          | text          |
| Yes      | series tag  | region               | DEC Region           | text          | number        |
| Yes      | time        | renewal_date         | Renewal Date         | calendar_date | calendar_date |
| No       |             | expiration_date      | Expiration Date      | calendar_date | calendar_date |
| Yes      | series tag  | applicator_type      | Applicator Type      | text          | text          |
| Yes      | series tag  | category             | Category             | text          | text          |
| Yes      | series tag  | category_description | Category Description | text          | text          |
```

## Time Field

```ls
Value = renewal_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = expiration_date
```

## Data Commands

```ls
series e:c7db-kwpj d:2017-09-21T00:00:00.000Z t:region=6 t:first_name=PETER t:cert_number=P6305400 t:category=10 t:applicator_type="Certified Private Pesticide Applicator" t:middle_name=M t:last_name=BARNEY t:category_description=Demonstration m:row_number.c7db-kwpj=1

series e:c7db-kwpj d:2017-06-21T00:00:00.000Z t:region=8 t:first_name=RUSSELL t:cert_number=C8307479 t:category=10 t:applicator_type="Certified Commercial Pesticide Applicator" t:middle_name=W t:last_name=WELSER t:category_description=Demonstration m:row_number.c7db-kwpj=2

series e:c7db-kwpj d:2017-05-21T00:00:00.000Z t:region=8 t:first_name=PECK t:cert_number=C8312938 t:category=10 t:applicator_type="Certified Commercial Pesticide Applicator" t:last_name=BABCOCK t:category_description=Demonstration m:row_number.c7db-kwpj=3
```

## Meta Commands

```ls
metric m:row_number.c7db-kwpj p:long l:"Row Number"

entity e:c7db-kwpj l:"Current Certified Pesticide Applicators" t:attribution="New York State Department of Environmental Conservation (DEC)" t:url=https://data.ny.gov/api/views/c7db-kwpj

property e:c7db-kwpj t:meta.view v:id=c7db-kwpj v:category="Energy & Environment" v:attributionLink=http://www.dec.ny.gov/nyspad/ v:averageRating=0 v:name="Current Certified Pesticide Applicators" v:attribution="New York State Department of Environmental Conservation (DEC)"

property e:c7db-kwpj t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:c7db-kwpj t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| cert_number | first_name | last_name | middle_name | suffix | region | renewal_date        | expiration_date     | applicator_type                           | category | category_description | 
| =========== | ========== | ========= | =========== | ====== | ====== | =================== | =================== | ========================================= | ======== | ==================== | 
| P6305400    | PETER      | BARNEY    | M           |        | 6      | 2017-09-21T00:00:00 | 2019-09-21T00:00:00 | Certified Private Pesticide Applicator    | 10       | Demonstration        | 
| C8307479    | RUSSELL    | WELSER    | W           |        | 8      | 2017-06-21T00:00:00 | 2019-06-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
| C8312938    | PECK       | BABCOCK   |             |        | 8      | 2017-05-21T00:00:00 | 2019-05-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
| C2269618    | RICHARD    | PAYTON    | F           |        | 2      | 2020-05-21T00:00:00 | 2022-05-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
| C9665411    | JOHN       | GIBBONS   | P           |        | 9      | 2017-10-21T00:00:00 | 2019-10-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
| C3671317    | JOHN       | WICKES    |             |        | 3      | 2017-04-21T00:00:00 | 2019-04-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
| C9659890    | THOMAS     | KNIGHT    | J           |        | 9      | 2019-09-21T00:00:00 | 2021-09-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
| C0673840    | SCOTT      | LINDE     |             |        | 0      | 2017-09-21T00:00:00 | 2019-09-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
| C5656620    | JEFFREY    | ERWIN     | W           |        | 5      | 2017-09-21T00:00:00 | 2019-09-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
| C1664653    | ANDREW     | SENESAC   | F           |        | 1      | 2019-12-21T00:00:00 | 2021-12-21T00:00:00 | Certified Commercial Pesticide Applicator | 10       | Demonstration        | 
```