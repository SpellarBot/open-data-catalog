# Missouri Docket Locations

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-docket-locations-8214b) |
| Metadata | [Link](https://data.mo.gov/api/views/7ghq-u8j6) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/7ghq-u8j6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/7ghq-u8j6/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 7ghq-u8j6 |
| Name | Missouri Docket Locations |
| Created | 2013-11-01T16:24:37Z |
| Publication Date | 2015-09-14T19:06:50Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | venue       | Venue      | text      | text        |
| Yes      | series tag  | location    | Location   | text      | text        |
| Yes      | series tag  | region      | Region     | text      | text        |
| Yes      | series tag  | phone       | Phone      | text      | text        |
| Yes      | series tag  | fax         | Fax        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7ghq-u8j6 d:2015-09-14T12:06:10.000Z t:region="CAPE GIRARDEAU" t:phone=573-290-5757 t:fax=573-290-5760 t:location="Division Office" t:venue="Cape Girardeau" m:row_number.7ghq-u8j6=1

series e:7ghq-u8j6 d:2015-09-14T12:06:10.000Z t:region="CAPE GIRARDEAU" t:location="Stoddard County Courthouse" t:venue=Bloomfield m:row_number.7ghq-u8j6=2

series e:7ghq-u8j6 d:2015-09-14T12:06:10.000Z t:region="CAPE GIRARDEAU" t:location="Pemiscot County Courthouse" t:venue=Caruthersville m:row_number.7ghq-u8j6=3
```

## Meta Commands

```ls
metric m:row_number.7ghq-u8j6 p:long l:"Row Number"

entity e:7ghq-u8j6 l:"Missouri Docket Locations" t:url=https://data.mo.gov/api/views/7ghq-u8j6

property e:7ghq-u8j6 t:meta.view v:id=7ghq-u8j6 v:averageRating=0 v:name="Missouri Docket Locations"

property e:7ghq-u8j6 t:meta.view.owner v:id=eb88-upz2 v:screenName=DOLIR v:displayName=DOLIR

property e:7ghq-u8j6 t:meta.view.tableauthor v:id=eb88-upz2 v:screenName=DOLIR v:roleName=editor v:displayName=DOLIR
```

## Top Records

```ls
| :updated_at | venue                         | location                                 | region         | phone        | fax          | 
| =========== | ============================= | ======================================== | ============== | ============ | ============ | 
| 1442232370  | Cape Girardeau                | Division Office                          | CAPE GIRARDEAU | 573-290-5757 | 573-290-5760 | 
| 1442232370  | Bloomfield                    | Stoddard County Courthouse               | CAPE GIRARDEAU |              |              | 
| 1442232370  | Caruthersville                | Pemiscot County Courthouse               | CAPE GIRARDEAU |              |              | 
| 1442232370  | Festus                        | City Hall                                | CAPE GIRARDEAU |              |              | 
| 1442232370  | Farmington - Hearings         | St. Francois County Courthouse Annex     | CAPE GIRARDEAU |              |              | 
| 1442232370  | Farmington - Mediation/Pro se | Ste. Genevieve Courthouse                | CAPE GIRARDEAU |              |              | 
| 1442232370  | Ironton                       | Iron County Courthouse                   | CAPE GIRARDEAU |              |              | 
| 1442232370  | New Madrid                    | New Madrid County Courthouse             | CAPE GIRARDEAU |              |              | 
| 1442232370  | Poplar Bluff                  | Butler County Courthouse (Hearings)      | CAPE GIRARDEAU |              |              | 
| 1442232370  | Poplar Bluff                  | Sikeston Municipal Court Bldg. (Dockets) | CAPE GIRARDEAU |              |              | 
```