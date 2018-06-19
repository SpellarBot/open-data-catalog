# Dialysis Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dialysis-centers-a6a36) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/wasd-qc7e) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/wasd-qc7e/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/wasd-qc7e/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | wasd-qc7e |
| Name | Dialysis Centers |
| Attribution | Baltimore City Department of Health |
| Category | Housing & Development |
| Tags | health, dialysis |
| Created | 2011-12-14T16:30:10Z |
| Publication Date | 2014-04-03T23:57:45Z |

## Description

Listing of area dialysis centers developed by the Baltimore City Department of Health

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
series e:wasd-qc7e d:2011-12-14T08:30:35.000Z t:councildistrict=14 t:zipcode=21218 t:name="25TH Street Dialysis, Inc" t:neighborhood="Coldstream Homestead Montebello" t:policedistrict=NORTHEASTERN m:row_number.wasd-qc7e=1

series e:wasd-qc7e d:2011-12-14T08:30:35.000Z t:councildistrict=4 t:zipcode=21212 t:name="Bertha Sirk Dialysis Center" t:neighborhood=Rosebank t:policedistrict=NORTHERN m:row_number.wasd-qc7e=2

series e:wasd-qc7e d:2011-12-14T08:30:35.000Z t:councildistrict=14 t:zipcode=21211 t:name="BMA Baltimore" t:neighborhood=Hampden t:policedistrict=NORTHERN m:row_number.wasd-qc7e=3
```

## Meta Commands

```ls
metric m:row_number.wasd-qc7e p:long l:"Row Number"

entity e:wasd-qc7e l:"Dialysis Centers" t:attribution="Baltimore City Department of Health" t:url=https://data.baltimorecity.gov/api/views/wasd-qc7e

property e:wasd-qc7e t:meta.view v:id=wasd-qc7e v:category="Housing & Development" v:attributionLink=http://www.baltimorehealth.org/ v:averageRating=0 v:name="Dialysis Centers" v:attribution="Baltimore City Department of Health"

property e:wasd-qc7e t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:wasd-qc7e t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:wasd-qc7e t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                                      | zipcode | neighborhood                    | councildistrict | policedistrict | 
| =========== | ========================================= | ======= | =============================== | =============== | ============== | 
| 1323851435  | 25TH Street Dialysis, Inc                 | 21218   | Coldstream Homestead Montebello | 14              | NORTHEASTERN   | 
| 1323851435  | Bertha Sirk Dialysis Center               | 21212   | Rosebank                        | 4               | NORTHERN       | 
| 1323851435  | BMA Baltimore                             | 21211   | Hampden                         | 14              | NORTHERN       | 
| 1323851435  | Bon Secours Hospital                      | 21223   | Penrose/Fayette Street Outreach | 9               | WESTERN        | 
| 1323851435  | Charing Cross Dialysis                    |         |                                 |                 |                | 
| 1323851435  | Community Dialysis Centers, Inc           |         |                                 |                 |                | 
| 1323851435  | Davita Baltimore Geriatric & Rehab Center | 21224   | Hopkins Bayview                 | 2               | SOUTHEASTERN   | 
| 1323851435  | Davita Catonsville                        |         |                                 |                 |                | 
| 1323851435  | Davita Dialysis Mercy                     | 21202   | Downtown                        | 11              | CENTRAL        | 
| 1323851435  | Davita Harbor Park Dialysis               | 21225   | Cherry Hill                     | 10              | SOUTHERN       | 
```