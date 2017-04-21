# Monuments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/monuments-43693) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/cpxf-kxp3) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/cpxf-kxp3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/cpxf-kxp3/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | cpxf-kxp3 |
| Name | Monuments |
| Attribution | City of Baltimore |
| Category | Culture & Arts |
| Tags | monument |
| Created | 2011-12-14T18:27:21Z |
| Publication Date | 2014-04-03T23:43:55Z |

## Description

This data set shows the point location of Baltimore City monuments. However, the completness and currentness of these data are uncertain.

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
series e:cpxf-kxp3 d:2011-12-14T10:27:38.000Z t:councildistrict=11 t:zipcode=21201 t:name="James Cardinal Gibbons" t:neighborhood=Downtown t:policedistrict=CENTRAL m:row_number.cpxf-kxp3=1

series e:cpxf-kxp3 d:2011-12-14T10:27:38.000Z t:councildistrict=11 t:zipcode=21202 t:name="The Battle Monument" t:neighborhood=Downtown t:policedistrict=CENTRAL m:row_number.cpxf-kxp3=2

series e:cpxf-kxp3 d:2011-12-14T10:27:38.000Z t:councildistrict=11 t:zipcode=21202 t:name="Negro Heroes of the U.S Monument" t:neighborhood=Downtown t:policedistrict=CENTRAL m:row_number.cpxf-kxp3=3
```

## Meta Commands

```ls
metric m:row_number.cpxf-kxp3 p:long l:"Row Number"

entity e:cpxf-kxp3 l:Monuments t:attribution="City of Baltimore" t:url=https://data.baltimorecity.gov/api/views/cpxf-kxp3

property e:cpxf-kxp3 t:meta.view v:id=cpxf-kxp3 v:category="Culture & Arts" v:attributionLink=http://www.baltimorecity.gov v:averageRating=0 v:name=Monuments v:attribution="City of Baltimore"

property e:cpxf-kxp3 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:cpxf-kxp3 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:cpxf-kxp3 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                                    | zipcode | neighborhood           | councildistrict | policedistrict | 
| =========== | ======================================= | ======= | ====================== | =============== | ============== | 
| 1323858458  | James Cardinal Gibbons                  | 21201   | Downtown               | 11              | CENTRAL        | 
| 1323858458  | The Battle Monument                     | 21202   | Downtown               | 11              | CENTRAL        | 
| 1323858458  | Negro Heroes of the U.S Monument        | 21202   | Downtown               | 11              | CENTRAL        | 
| 1323858458  | Star Bangled Banner                     | 21202   | Downtown               | 11              | CENTRAL        | 
| 1323858458  | Flame at the Holocaust Monument         | 21202   | Downtown               | 11              | CENTRAL        | 
| 1323858458  | Calvert Statue                          | 21202   | Downtown               | 11              | CENTRAL        | 
| 1323858458  | War Memorial Building/Aquatic Wa Horses | 21202   | Downtown               | 11              | CENTRAL        | 
| 1323858458  | Boy Scout                               | 21211   | Remington              | 7               | NORTHERN       | 
| 1323858458  | Reese Monument                          | 21213   | Clifton Park           | 14              | NORTHEASTERN   | 
| 1323858458  | Serviceman's Memorial                   | 21211   | Johns Hopkins Homewood | 14              | NORTHEASTERN   | 
```