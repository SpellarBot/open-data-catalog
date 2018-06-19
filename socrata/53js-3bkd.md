# Nursing Homes

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/nursing-homes-46c05) |
| Metadata | [Link](https://data.baltimorecity.gov/api/views/53js-3bkd) |
| Data: JSON | [100 Rows](https://data.baltimorecity.gov/api/views/53js-3bkd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.baltimorecity.gov/api/views/53js-3bkd/rows.csv?max_rows=100) |
| Host | data.baltimorecity.gov |
| Id | 53js-3bkd |
| Name | Nursing Homes |
| Attribution | Baltimore City Commission on Aging and Retirement |
| Category | Health |
| Tags | nursing home |
| Created | 2011-12-14T18:38:19Z |
| Publication Date | 2014-04-03T23:40:51Z |

## Description

This data set shows the point location of nursing homes within the City of Baltimore. These data were geocoded from a list provided by the Maryland State Office of Health Care Quality. The list was provided to EGIS via CARE on the 6th of March, 2008.

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
series e:53js-3bkd d:2011-12-14T10:38:23.000Z t:councildistrict=7 t:zipcode=21211 t:name="ALICE MANOR NURSING HOME" t:neighborhood=Woodberry t:policedistrict=NORTHERN m:row_number.53js-3bkd=1

series e:53js-3bkd d:2011-12-14T10:38:23.000Z t:councildistrict=6 t:zipcode=21215 t:name="BLUE POINT NURSING CENTER" t:neighborhood=Levindale t:policedistrict=NORTHERN m:row_number.53js-3bkd=2

series e:53js-3bkd d:2011-12-14T10:38:23.000Z t:councildistrict=8 t:zipcode=21229 t:name="CATON MANOR" t:neighborhood="Saint Agnes" t:policedistrict=SOUTHWESTERN m:row_number.53js-3bkd=3
```

## Meta Commands

```ls
metric m:row_number.53js-3bkd p:long l:"Row Number"

entity e:53js-3bkd l:"Nursing Homes" t:attribution="Baltimore City Commission on Aging and Retirement" t:url=https://data.baltimorecity.gov/api/views/53js-3bkd

property e:53js-3bkd t:meta.view v:id=53js-3bkd v:category=Health v:attributionLink=http://baltimorehealth.org/care.html v:averageRating=0 v:name="Nursing Homes" v:attribution="Baltimore City Commission on Aging and Retirement"

property e:53js-3bkd t:meta.view.license v:name="Creative Commons Attribution 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by/3.0/legalcode v:logoUrl=images/licenses/cc30by.png

property e:53js-3bkd t:meta.view.owner v:id=6r9a-dfdj v:screenName="Open Baltimore" v:displayName="Open Baltimore"

property e:53js-3bkd t:meta.view.tableauthor v:id=6r9a-dfdj v:screenName="Open Baltimore" v:roleName=administrator v:displayName="Open Baltimore"
```

## Top Records

```ls
| :updated_at | name                                        | zipcode | neighborhood    | councildistrict | policedistrict | 
| =========== | =========================================== | ======= | =============== | =============== | ============== | 
| 1323859103  | ALICE MANOR NURSING HOME                    | 21211   | Woodberry       | 7               | NORTHERN       | 
| 1323859103  | BLUE POINT NURSING CENTER                   | 21215   | Levindale       | 6               | NORTHERN       | 
| 1323859103  | CATON MANOR                                 | 21229   | Saint Agnes     | 8               | SOUTHWESTERN   | 
| 1323859103  | CRAWFORD RETREAT                            | 21216   | Walbrook        | 7               | SOUTHWESTERN   | 
| 1323859103  | FAYETTE HEALTH AND REHABILITATION CENTER    | 21223   | Poppleton       | 9               | WESTERN        | 
| 1323859103  | FRANKFORD NURSING AND REHABILITATION CENTER | 21206   | Frankford       | 2               | NORTHEASTERN   | 
| 1323859103  | FUTURE CARE CANTON HARBOR                   | 21224   | Canton          | 1               | SOUTHEASTERN   | 
| 1323859103  | FUTURE CARE CHARLES VILLAGE, LLC            | 21218   | Charles Village | 12              | NORTHERN       | 
| 1323859103  | FUTURE CARE HOMEWOOD                        | 21218   | Charles Village | 12              | NORTHERN       | 
| 1323859103  | FUTURE CARE IRVINGTON, LLC                  | 21229   | Irvington       | 8               | SOUTHWESTERN   | 
```