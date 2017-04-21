# Libraries

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/libraries-239ee) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/tgtv-wr5u) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/tgtv-wr5u/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/tgtv-wr5u/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | tgtv-wr5u |
| Name | Libraries |
| Attribution | Enoch Pratt Free Library |
| Category | Culture & Arts |
| Tags | books, library |
| Created | 2011-12-14T18:21:05Z |
| Publication Date | 2014-04-03T23:45:09Z |

## Description

This data set shows the location of Baltimore City public libraries listed on the Enoch Pratt Library website.

## Columns

```ls
| Included | Schema Type | Field Name      | Name            | Data Type | Render Type |
| ======== | =========== | =============== | =============== | ========= | =========== |
| No       | time        | :updated_at     | updated_at      | meta_data | meta_data   |
| Yes      | series tag  | name            | name            | text      | text        |
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
series e:tgtv-wr5u d:2011-12-14T10:21:18.000Z t:councildistrict=11 t:zipcode=21201 t:name=Central t:neighborhood=Downtown t:policedistrict=CENTRAL m:row_number.tgtv-wr5u=1

series e:tgtv-wr5u d:2011-12-14T10:21:18.000Z t:councildistrict=10 t:zipcode=21225 t:name=Brooklyn t:neighborhood=Brooklyn t:policedistrict=SOUTHERN m:row_number.tgtv-wr5u=2

series e:tgtv-wr5u d:2011-12-14T10:21:18.000Z t:councildistrict=1 t:zipcode=21224 t:name=Canton t:neighborhood=Canton t:policedistrict=SOUTHEASTERN m:row_number.tgtv-wr5u=3
```

## Meta Commands

```ls
metric m:row_number.tgtv-wr5u p:long l:"Row Number"

entity e:tgtv-wr5u l:Libraries t:attribution="Enoch Pratt Free Library" t:url=https://data.baltimorecity.gov/api/views/tgtv-wr5u

property e:tgtv-wr5u t:meta.view v:id=tgtv-wr5u v:category="Culture & Arts" v:attributionLink=http://www.prattlibrary.org/ v:averageRating=0 v:name=Libraries v:attribution="Enoch Pratt Free Library"

property e:tgtv-wr5u t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:tgtv-wr5u t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:tgtv-wr5u t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name        | zipcode | neighborhood                     | councildistrict | policedistrict | 
| =========== | =========== | ======= | ================================ | =============== | ============== | 
| 1323858078  | Central     | 21201   | Downtown                         | 11              | CENTRAL        | 
| 1323858078  | Brooklyn    | 21225   | Brooklyn                         | 10              | SOUTHERN       | 
| 1323858078  | Canton      | 21224   | Canton                           | 1               | SOUTHEASTERN   | 
| 1323858078  | Cherry Hill | 21225   | Cherry Hill                      | 10              | SOUTHERN       | 
| 1323858078  | Clifton     | 21213   | South Clifton Park               | 12              | EASTERN        | 
| 1323858078  | Edmondson   | 21229   | Rognel Heights                   | 8               | SOUTHWESTERN   | 
| 1323858078  | Forest Park | 21216   | Forest Park                      | 6               | NORTHWESTERN   | 
| 1323858078  | Govans      | 21212   | Homeland                         | 4               | NORTHERN       | 
| 1323858078  | Hamilton    | 21214   | Harford-Echodale/Perring Parkway | 3               | NORTHEASTERN   | 
| 1323858078  | Hampden     | 21211   | Hampden                          | 7               | NORTHERN       | 
```