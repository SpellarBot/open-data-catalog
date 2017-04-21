# Hospitals

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hospitals-75be8) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/g9ck-7zns) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/g9ck-7zns/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/g9ck-7zns/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | g9ck-7zns |
| Name | Hospitals |
| Attribution | City of Baltimore |
| Category | Health |
| Tags | health, hospital, emergency |
| Created | 2011-12-14T18:16:39Z |
| Publication Date | 2014-04-03T23:42:54Z |

## Description

This data set shows the location of Baltimore City hospitals. The purpose of this data is to assist the City of Baltimore in identifying institutions that provides health care treatment by specialized staff and equipment. To assist the City's emergency organizations in identifying health institution during an emergency event. Cartographic, analysis, and planning.

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
series e:g9ck-7zns d:2011-12-14T10:16:57.000Z t:councildistrict=13 t:zipcode=21287 t:name="John Hopkins Hospital" t:neighborhood=Dunbar-Broadway t:policedistrict=EASTERN t:type=Hospital m:row_number.g9ck-7zns=1

series e:g9ck-7zns d:2011-12-14T10:16:57.000Z t:councildistrict=11 t:zipcode=21201 t:name="Maryland General Hospital" t:neighborhood="Mount Vernon" t:policedistrict=CENTRAL t:type=Hospital m:row_number.g9ck-7zns=2

series e:g9ck-7zns d:2011-12-14T10:16:57.000Z t:councildistrict=9 t:zipcode=21223 t:name="Bon Secours Hospital" t:neighborhood="Penrose/Fayette Street Outreach" t:policedistrict=WESTERN t:type=Hospital m:row_number.g9ck-7zns=3
```

## Meta Commands

```ls
metric m:row_number.g9ck-7zns p:long l:"Row Number"

entity e:g9ck-7zns l:Hospitals t:attribution="City of Baltimore" t:url=https://data.baltimorecity.gov/api/views/g9ck-7zns

property e:g9ck-7zns t:meta.view v:id=g9ck-7zns v:category=Health v:attributionLink=http://www.baltimorecity.gov v:averageRating=0 v:name=Hospitals v:attribution="City of Baltimore"

property e:g9ck-7zns t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:g9ck-7zns t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:g9ck-7zns t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                                | type     | zipcode | neighborhood                    | councildistrict | policedistrict | 
| =========== | =================================== | ======== | ======= | =============================== | =============== | ============== | 
| 1323857817  | John Hopkins Hospital               | Hospital | 21287   | Dunbar-Broadway                 | 13              | EASTERN        | 
| 1323857817  | Maryland General Hospital           | Hospital | 21201   | Mount Vernon                    | 11              | CENTRAL        | 
| 1323857817  | Bon Secours Hospital                | Hospital | 21223   | Penrose/Fayette Street Outreach | 9               | WESTERN        | 
| 1323857817  | Sinai Hospital                      | Hospital | 21215   | Levindale                       | 6               | NORTHERN       | 
| 1323857817  | Harbor Hospital Center              | Hospital | 21225   | Middle Branch/Reedbird Parks    | 10              | SOUTHERN       | 
| 1323857817  | St. Agnes Hospital                  | Hospital | 21229   | Violetville                     | 8               | SOUTHWESTERN   | 
| 1323857817  | Union Memorial Hospital             | Hospital | 21218   | Charles Village                 | 14              | NORTHERN       | 
| 1323857817  | Good Samaritan Hospital             | Hospital | 21239   | Loch Raven                      | 3               | NORTHEASTERN   | 
| 1323857817  | John Hopkins Bayview Medical Center | Hospital | 21224   | Hopkins Bayview                 | 2               | SOUTHEASTERN   | 
| 1323857817  | Mercy Medical Cen.                  | Hospital | 21202   | Downtown                        | 11              | CENTRAL        | 
```