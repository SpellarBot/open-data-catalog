# Fire Safety Complaints

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-safety-complaints) |
| Metadata | [Link](https://data.sfgov.org/api/views/2wsq-7wmv) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/2wsq-7wmv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/2wsq-7wmv/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 2wsq-7wmv |
| Name | Fire Safety Complaints |
| Category | Housing and Buildings |
| Tags | fire inspections, public complaints, 311 |
| Created | 2015-12-17T00:51:58Z |
| Publication Date | 2016-02-05T01:00:24Z |

## Description

Information on Complaints received by the Fire Department (from the public) for a particular location. Key fields include Complaint Number, Complaint Type, Address, Disposition

## Columns

```ls
| Included | Schema Type | Field Name                      | Name                            | Data Type     | Render Type   |
| ======== | =========== | =============================== | =============================== | ============= | ============= |
| Yes      | series tag  | complaint_id                    | Complaint Id                    | text          | text          |
| Yes      | series tag  | complaint_number                | Complaint Number                | text          | number        |
| Yes      | series tag  | complaint_item_type             | Complaint Item Type             | text          | text          |
| Yes      | series tag  | complaint_item_type_description | Complaint Item Type Description | text          | text          |
| Yes      | series tag  | 311_case_number                 | 311 Case Number                 | text          | text          |
| Yes      | series tag  | inspection_number               | Inspection Number               | text          | text          |
| No       |             | address                         | Address                         | text          | text          |
| Yes      | series tag  | zipcode                         | Zipcode                         | text          | text          |
| Yes      | series tag  | battalion                       | Battalion                       | text          | text          |
| Yes      | series tag  | station                         | Station Area                    | text          | text          |
| Yes      | series tag  | bfp_district                    | Fire Prevention District        | text          | text          |
| Yes      | time        | received_date                   | Received Date                   | calendar_date | calendar_date |
| No       |             | entry_date                      | Entry Date                      | calendar_date | calendar_date |
| Yes      | series tag  | disposition                     | Disposition                     | text          | text          |
| No       |             | disposition_date                | Disposition Date                | calendar_date | calendar_date |
| Yes      | series tag  | supervisor_district             | Supervisor District             | text          | text          |
| Yes      | series tag  | neighborhood_district           | Neighborhood District           | text          | text          |
```

## Time Field

```ls
Value = received_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,entry_date,disposition_date
```

## Data Commands

```ls
series e:2wsq-7wmv d:2016-12-18T00:00:00.000Z t:inspection_number=297761 t:complaint_item_type_description=extinguishers t:station=02 t:complaint_number=44797 t:bfp_district=01N t:complaint_id=4479706 t:zipcode=94133 t:battalion=01 t:neighborhood_district=Chinatown t:complaint_item_type=06 t:supervisor_district=3 t:disposition="violation issued" m:row_number.2wsq-7wmv=1

series e:2wsq-7wmv d:2016-12-12T00:00:00.000Z t:inspection_number=298084 t:complaint_item_type_description="uncategorized complaint" t:station=24 t:complaint_number=44882 t:bfp_district=05 t:complaint_id=4488299 t:zipcode=94114 t:battalion=08 t:neighborhood_district="Castro/Upper Market" t:complaint_item_type=99 t:supervisor_district=8 t:disposition="no merit" m:row_number.2wsq-7wmv=2

series e:2wsq-7wmv d:2016-12-15T00:00:00.000Z t:inspection_number=297645 t:complaint_item_type_description="alarm systems" t:station=02 t:complaint_number=44757 t:bfp_district=01N t:complaint_id=4475705 t:zipcode=94108 t:battalion=01 t:neighborhood_district=Chinatown t:complaint_item_type=05 t:supervisor_district=3 t:disposition="condition corrected" m:row_number.2wsq-7wmv=3
```

## Meta Commands

```ls
metric m:row_number.2wsq-7wmv p:long l:"Row Number"

entity e:2wsq-7wmv l:"Fire Safety Complaints" t:url=https://data.sfgov.org/api/views/2wsq-7wmv

property e:2wsq-7wmv t:meta.view v:id=2wsq-7wmv v:category="Housing and Buildings" v:averageRating=0 v:name="Fire Safety Complaints"

property e:2wsq-7wmv t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:2wsq-7wmv t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:2wsq-7wmv t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| complaint_id | complaint_number | complaint_item_type | complaint_item_type_description | 311_case_number | inspection_number | address                | zipcode | battalion | station | bfp_district | received_date       | entry_date          | disposition         | disposition_date    | supervisor_district | neighborhood_district          | 
| ============ | ================ | =================== | =============================== | =============== | ================= | ====================== | ======= | ========= | ======= | ============ | =================== | =================== | =================== | =================== | =================== | ============================== | 
| 4479706      | 44797            | 06                  | extinguishers                   |                 | 297761            | 1300 - 1308 Powell St  | 94133   | 01        | 02      | 01N          | 2016-12-18T00:00:00 | 2016-12-18T00:00:00 | violation issued    | 2016-12-28T00:00:00 | 3                   | Chinatown                      | 
| 4488299      | 44882            | 99                  | uncategorized complaint         |                 | 298084            | 301 Twin Peaks Blvd    | 94114   | 08        | 24      | 05           | 2016-12-12T00:00:00 | 2016-12-23T00:00:00 | no merit            | 2016-12-27T00:00:00 | 8                   | Castro/Upper Market            | 
| 4475705      | 44757            | 05                  | alarm systems                   |                 | 297645            | 39 - 49 Spofford St    | 94108   | 01        | 02      | 01N          | 2016-12-15T00:00:00 | 2016-12-15T00:00:00 | condition corrected | 2016-12-28T00:00:00 | 3                   | Chinatown                      | 
| 4489710      | 44897            | 10                  | combustible materials           |                 | 298101            | 161 - 165 Fair Oaks St | 94110   | 06        | 11      | 06           | 2016-12-19T00:00:00 | 2016-12-23T00:00:00 | no merit            | 2016-12-28T00:00:00 | 8                   | Mission                        | 
| 4493906      | 44939            | 06                  | extinguishers                   |                 | 298220            | 1976 Green St          | 94123   | 04        | 16      | 04           | 2016-12-28T00:00:00 | 2016-12-28T14:32:12 |                     |                     | 2                   | Marina                         | 
| 4056005      | 40560            | 05                  | alarm systems                   |                 | 226047            | 1575 Filbert St        | 94123   | 04        | 16      | 04           | 2015-09-24T00:00:00 | 2015-09-24T00:00:00 | no merit            | 2016-01-15T00:00:00 | 2                   | Marina                         | 
| 4002219      | 40022            | 19                  | sprinkler/standpipe systems     |                 | 223235            | 1160 Clay St           | 94108   | 01        | 02      | 01N          | 2015-08-11T00:00:00 | 2015-08-12T00:00:00 | condition corrected | 2016-01-15T00:00:00 | 3                   | Nob Hill                       | 
| 4492508      | 44925            | 08                  | operating without a permit      |                 | 298190            | 642 - 650 Howard St    | 94105   | 03        | 01      | 03N          | 2016-12-28T00:00:00 | 2016-12-28T00:00:00 |                     |                     | 6                   | Financial District/South Beach | 
| 4480921      | 44809            | 21                  | street numbering                |                 | 297805            | 895 Pacific Ave        | 94133   | 01        | 02      | 01N          | 2016-12-19T00:00:00 | 2016-12-19T00:00:00 | no merit            | 2016-12-28T00:00:00 | 3                   | Chinatown                      | 
| 4351618      | 43516            | 18                  | hoarding                        |                 | 292285            | 89 Belle Ave           | 94132   | 09        | 33      | 09           | 2016-08-08T00:00:00 | 2016-08-11T00:00:00 | violation issued    | 2016-12-28T00:00:00 | 7                   | Oceanview/Merced/Ingleside     | 
```