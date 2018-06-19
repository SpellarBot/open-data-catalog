# Health Care Facilities

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/health-care-facilities-fb3ac) |
| Metadata | [Link](https://data.sfgov.org/api/views/jhsu-2pka) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/jhsu-2pka/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/jhsu-2pka/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | jhsu-2pka |
| Name | Health Care Facilities |
| Category | Health and Social Services |
| Created | 2016-02-12T20:56:20Z |
| Publication Date | 2016-02-12T21:03:51Z |

## Description

Health care facilities located in San Francisco

## Columns

```ls
| Included | Schema Type | Field Name    | Name          | Data Type | Render Type |
| ======== | =========== | ============= | ============= | ========= | =========== |
| No       | time        | :updated_at   | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | uid           | UID           | text      | text        |
| Yes      | series tag  | oshpd_id      | OSHPD_ID      | text      | text        |
| Yes      | series tag  | facility_name | Facility Name | text      | text        |
| Yes      | series tag  | facility_type | Facility Type | text      | text        |
| Yes      | series tag  | services      | Services      | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:jhsu-2pka d:2016-02-12T13:02:58.000Z t:uid=0 t:services=Hospital t:facility_name="California Pacific Med Ctr-california East" t:oshpd_id=106380826 t:facility_type="General Acute Care Hospital" m:row_number.jhsu-2pka=1

series e:jhsu-2pka d:2016-02-12T13:02:58.000Z t:uid=1 t:services=Hospital t:facility_name="California Pacific Med Ctr-california West" t:oshpd_id=106380777 t:facility_type="General Acute Care Hospital" m:row_number.jhsu-2pka=2

series e:jhsu-2pka d:2016-02-12T13:02:58.000Z t:uid=2 t:services=Hospital t:facility_name="California Pacific Med Ctr-davies Campus" t:oshpd_id=106380933 t:facility_type="General Acute Care Hospital" m:row_number.jhsu-2pka=3
```

## Meta Commands

```ls
metric m:row_number.jhsu-2pka p:long l:"Row Number"

entity e:jhsu-2pka l:"Health Care Facilities" t:url=https://data.sfgov.org/api/views/jhsu-2pka

property e:jhsu-2pka t:meta.view v:id=jhsu-2pka v:category="Health and Social Services" v:averageRating=0 v:name="Health Care Facilities"

property e:jhsu-2pka t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:jhsu-2pka t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:jhsu-2pka t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | uid | oshpd_id  | facility_name                                         | facility_type               | services | 
| =========== | === | ========= | ===================================================== | =========================== | ======== | 
| 1455282178  | 0   | 106380826 | California Pacific Med Ctr-california East            | General Acute Care Hospital | Hospital | 
| 1455282178  | 1   | 106380777 | California Pacific Med Ctr-california West            | General Acute Care Hospital | Hospital | 
| 1455282178  | 2   | 106380933 | California Pacific Med Ctr-davies Campus              | General Acute Care Hospital | Hospital | 
| 1455282178  | 3   | 106380929 | California Pacific Med Ctr-pacific Campus             | General Acute Care Hospital | Hospital | 
| 1455282178  | 4   | 106380964 | California Pacific Medical Center - St. Luke's Campus | General Acute Care Hospital | Hospital | 
| 1455282178  | 5   | 106382715 | Chinese Hospital                                      | General Acute Care Hospital | Hospital | 
| 1455282178  | 6   | 106380857 | Kaiser Fnd Hosp - San Francisco                       | General Acute Care Hospital | Hospital | 
| 1455282178  | 7   | 106380865 | Laguna Honda Hospital And Rehabilitation Center       | General Acute Care Hospital | Hospital | 
| 1455282178  | 8   | 106380939 | San Francisco General Hospital                        | General Acute Care Hospital | Hospital | 
| 1455282178  | 9   | 106380960 | St. Francis Memorial Hospital                         | General Acute Care Hospital | Hospital | 
```