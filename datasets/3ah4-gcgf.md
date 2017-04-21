# Senior Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/senior-centers-c3eb2) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/3ah4-gcgf) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/3ah4-gcgf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/3ah4-gcgf/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 3ah4-gcgf |
| Name | Senior Centers |
| Attribution | Baltimore City Commission on Aging and Retirement |
| Category | Health |
| Tags | senior center |
| Created | 2011-12-14T19:27:34Z |
| Publication Date | 2014-04-03T23:45:53Z |

## Description

This feature class represents the location of senior centers in Baltimore City. The list used to create this data was provided by CARE on the March 5, 2010.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
| Yes      | series tag  | type            | type            | text      | text        |
| Yes      | series tag  | zipcode         | zipCode         | text      | text        |
| Yes      | series tag  | neighborhood    | neighborhood    | text      | text        |
| Yes      | series tag  | councildistrict | councilDistrict | text      | number      |
| Yes      | series tag  | policedistrict  | policeDistrict  | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:3ah4-gcgf d:2011-12-14T11:27:53.000Z t:councildistrict=1 t:zipcode=21224 t:name="Hatton Senior Center" t:neighborhood=Canton t:policedistrict=SOUTHEASTERN t:type=Care m:row_number.3ah4-gcgf=1

series e:3ah4-gcgf d:2011-12-14T11:27:53.000Z t:councildistrict=12 t:zipcode=21213 t:name="Oliver Senior Center" t:neighborhood="Broadway East" t:policedistrict=EASTERN t:type=Care m:row_number.3ah4-gcgf=2

series e:3ah4-gcgf d:2011-12-14T11:27:53.000Z t:councildistrict=7 t:zipcode=21217 t:name="Sandtown-Winchester Senior Center" t:neighborhood=Sandtown-Winchester t:policedistrict=WESTERN t:type=Care m:row_number.3ah4-gcgf=3
```

## Meta Commands

```ls
metric m:row_number.3ah4-gcgf p:long l:"Row Number"

entity e:3ah4-gcgf l:"Senior Centers" t:attribution="Baltimore City Commission on Aging and Retirement" t:url=https://data.baltimorecity.gov/api/views/3ah4-gcgf

property e:3ah4-gcgf t:meta.view v:id=3ah4-gcgf v:category=Health v:attributionLink=http://baltimorehealth.org/care.html v:averageRating=0 v:name="Senior Centers" v:attribution="Baltimore City Commission on Aging and Retirement"

property e:3ah4-gcgf t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:3ah4-gcgf t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:3ah4-gcgf t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                              | type       | zipcode | neighborhood        | councildistrict | policedistrict | 
| =========== | ================================= | ========== | ======= | =================== | =============== | ============== | 
| 1323862073  | Hatton Senior Center              | Care       | 21224   | Canton              | 1               | SOUTHEASTERN   | 
| 1323862073  | Oliver Senior Center              | Care       | 21213   | Broadway East       | 12              | EASTERN        | 
| 1323862073  | Sandtown-Winchester Senior Center | Care       | 21217   | Sandtown-Winchester | 7               | WESTERN        | 
| 1323862073  | Waxter Center for Senior Citizens | Care       | 21201   | Mid-Town Belvedere  | 11              | CENTRAL        | 
| 1323862073  | Action in Maturity, Inc. (AIM)    | Non-Profit | 21211   | Hampden             | 14              | NORTHERN       | 
| 1323862073  | Allen Senior Center               | Non-Profit | 21230   | SBIC                | 10              | SOUTHERN       | 
| 1323862073  | Cherry Hill Senior Life Center    | Non-Profit | 21225   | Cherry Hill         | 10              | SOUTHERN       | 
| 1323862073  | Forest Park Senior Center         | Non-Profit | 21207   | Howard Park         | 5               | NORTHWESTERN   | 
| 1323862073  | Harford Senior Center             | Non-Profit | 21214   | Lauraville          | 3               | NORTHEASTERN   | 
| 1323862073  | Greenmount Senior Center          | Non-Profit | 21202   | Greenmount West     | 12              | EASTERN        | 
```