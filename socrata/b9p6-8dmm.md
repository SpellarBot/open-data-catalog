# Construction Bids 13-14

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/construction-bids-13-14-c59e6) |
| Metadata | [Link](https://data.hawaii.gov/api/views/b9p6-8dmm) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/b9p6-8dmm/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/b9p6-8dmm/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | b9p6-8dmm |
| Name | Construction Bids 13-14 |
| Created | 2014-12-31T22:28:06Z |
| Publication Date | 2014-12-31T22:29:02Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name        | Data Type     | Render Type   |
| ======== | =========== | =========== | =========== | ============= | ============= |
| No       | time        | :updated_at | updated_at  | meta_data     | meta_data     |
| No       |             | bid_opening | Bid Opening | calendar_date | calendar_date |
| Yes      | series tag  | description | Description | text          | text          |
| Yes      | series tag  | jobnumber   | JobNumber   | text          | text          |
| Yes      | series tag  | version     | Version     | text          | text          |
| Yes      | series tag  | file        | File        | url           | url           |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = bid_opening
```

## Data Commands

```ls
series e:b9p6-8dmm d:2014-12-31T14:28:09.000Z t:jobnumber=12-10-0758 t:file="http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=12-10-0758ADD2.zip" t:description="STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS" t:version="Addendum 2" m:row_number.b9p6-8dmm=1

series e:b9p6-8dmm d:2014-12-31T14:28:09.000Z t:jobnumber=12-10-0758 t:file="http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=12-10-0758ADD3.zip" t:description="STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS" t:version="Addendum 3" m:row_number.b9p6-8dmm=2

series e:b9p6-8dmm d:2014-12-31T14:28:09.000Z t:jobnumber=12-10-0758 t:file="http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=12-10-0758bc1.zip" t:description="STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS" t:version="Bid Clarification 1" m:row_number.b9p6-8dmm=3
```

## Meta Commands

```ls
metric m:row_number.b9p6-8dmm p:long l:"Row Number"

entity e:b9p6-8dmm l:"Construction Bids 13-14" t:url=https://data.hawaii.gov/api/views/b9p6-8dmm

property e:b9p6-8dmm t:meta.view v:id=b9p6-8dmm v:averageRating=0 v:name="Construction Bids 13-14"

property e:b9p6-8dmm t:meta.view.owner v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:displayName=sojiri

property e:b9p6-8dmm t:meta.view.tableauthor v:id=ck4w-i5dk v:profileImageUrlMedium=/api/users/ck4w-i5dk/profile_images/THUMB v:profileImageUrlLarge=/api/users/ck4w-i5dk/profile_images/LARGE v:screenName=sojiri v:profileImageUrlSmall=/api/users/ck4w-i5dk/profile_images/TINY v:roleName=publisher v:displayName=sojiri
```

## Top Records

```ls
| :updated_at | bid_opening | description                                                                     | jobnumber  | version                 | file                                                                             | 
| =========== | =========== | =============================================================================== | ========== | ======================= | ================================================================================ | 
| 1420036089  |             | STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS | 12-10-0758 | Addendum 2              | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=12-10-0758ADD2.zip, null] | 
| 1420036089  |             | STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS | 12-10-0758 | Addendum 3              | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=12-10-0758ADD3.zip, null] | 
| 1420036089  |             | STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS | 12-10-0758 | Bid Clarification 1     | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=12-10-0758bc1.zip, null]  | 
| 1420036089  |             | STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS | 12-10-0758 | download specs and plan | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=12-10-0758.zip, null]     | 
| 1420036089  |             | STATE CAPITOL BUILDING - 5TH FLOOR EXTERIOR WALL REPLACEMENT & EXTERIOR REPAIRS | 12-10-0758 | Addendum 1              | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=12-10-0758ADD1.zip, null] | 
| 1420036089  |             | MAUI VETERANS CEMETERY - EXPANSION AND IMPROVEMENTS                             | 15-14-7509 | download specs and plan | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=15-14-7509.zip, null]     | 
| 1420036089  |             | MAUI VETERANS CEMETERY - EXPANSION AND IMPROVEMENTS                             | 15-14-7509 | addendum 1              | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=15-14-7509add1.zip, null] | 
| 1420036089  |             | MAUI VETERANS CEMETERY - EXPANSION AND IMPROVEMENTS                             | 15-14-7509 | bid clarification 1     | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=15-14-7509bc1.zip, null]  | 
| 1420036089  |             | MARITIME WIRELESS NETWORK SYSTEM - KAUNAKAKAI HARBOR, NETWORK INFRASTRUCTURE    | 25-14-7588 | download specs and plan | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=25-14-7588.zip, null]     | 
| 1420036089  |             | MARITIME WIRELESS NETWORK SYSTEM - KAUNAKAKAI HARBOR, NETWORK INFRASTRUCTURE    | 25-14-7588 | Addendum 1              | [http://dags.hawaii.gov/cgi-bin/download.d2w/start?doc=25-14-7588ADD1.zip, null] | 
```