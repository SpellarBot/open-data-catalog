# Religious Buildings

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/religious-buildings-8437b) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/kbdc-bpw3) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/kbdc-bpw3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/kbdc-bpw3/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | kbdc-bpw3 |
| Name | Religious Buildings |
| Attribution | City of Baltimore |
| Category | Culture & Arts |
| Tags | religious, religion, church, synagogue |
| Created | 2011-12-14T19:13:44Z |
| Publication Date | 2014-04-03T23:24:22Z |

## Description

This dataset represents the location of religious buildings within the City of Baltimore. Personnel in the Mayor's Office track the coming and goings of religious organizations. The listing is currently limited to Christian and Jewish faiths.

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
series e:kbdc-bpw3 d:2011-12-14T11:13:55.000Z t:councildistrict=7 t:zipcode=21217 t:name="Christian Memorial Church" t:neighborhood=Easterwood t:policedistrict=WESTERN t:type=Church m:row_number.kbdc-bpw3=1

series e:kbdc-bpw3 d:2011-12-14T11:13:55.000Z t:councildistrict=1 t:zipcode=21231 t:name="Har Sinai Church Of Christ" t:neighborhood="Fells Point" t:policedistrict=SOUTHEASTERN t:type=Church m:row_number.kbdc-bpw3=2

series e:kbdc-bpw3 d:2011-12-14T11:13:55.000Z t:councildistrict=6 t:zipcode=21215 t:name="Lords Church" t:neighborhood="Central Park Heights" t:policedistrict=NORTHWESTERN t:type=Church m:row_number.kbdc-bpw3=3
```

## Meta Commands

```ls
metric m:row_number.kbdc-bpw3 p:long l:"Row Number"

entity e:kbdc-bpw3 l:"Religious Buildings" t:attribution="City of Baltimore" t:url=https://data.baltimorecity.gov/api/views/kbdc-bpw3

property e:kbdc-bpw3 t:meta.view v:id=kbdc-bpw3 v:category="Culture & Arts" v:attributionLink=http://www.baltimorecity.gov v:averageRating=0 v:name="Religious Buildings" v:attribution="City of Baltimore"

property e:kbdc-bpw3 t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:kbdc-bpw3 t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:kbdc-bpw3 t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                              | type   | zipcode | neighborhood                    | councildistrict | policedistrict | 
| =========== | ================================= | ====== | ======= | =============================== | =============== | ============== | 
| 1323861235  | Christian Memorial Church         | Church | 21217   | Easterwood                      | 7               | WESTERN        | 
| 1323861235  | Har Sinai Church Of Christ        | Church | 21231   | Fells Point                     | 1               | SOUTHEASTERN   | 
| 1323861235  | Lords Church                      | Church | 21215   | Central Park Heights            | 6               | NORTHWESTERN   | 
| 1323861235  | Hallelujah United Church Of God   | Church | 21215   | Arlington                       | 5               | NORTHWESTERN   | 
| 1323861235  | Fourth Mount Zion Baptist Church  | Church | 21216   | Hanlon-Longwood                 | 7               | NORTHWESTERN   | 
| 1323861235  | Church Of The Living God          | Church | 21223   | Penrose/Fayette Street Outreach | 9               | WESTERN        | 
| 1323861235  | Way Of The Cross Church           | Church | 21212   | Wilson Park                     | 4               | NORTHERN       | 
| 1323861235  | Rising Zion Baptist Church Inc    | Church | 21213   | Broadway East                   | 13              | EASTERN        | 
| 1323861235  | First Baptist Church Of Baltimore | Church | 21207   | Dorchester                      | 5               | NORTHWESTERN   | 
| 1323861235  | Pleasant Rock Baptist Church      | Church | 21230   | Washington Village              | 10              | SOUTHERN       | 
```