# Fire Inspections

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fire-inspections) |
| Metadata | [Link](https://data.sfgov.org/api/views/wb4c-6hwj) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wb4c-6hwj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wb4c-6hwj/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wb4c-6hwj |
| Name | Fire Inspections |
| Category | Housing and Buildings |
| Tags | fire inspections, building safety, fire safety |
| Created | 2015-12-17T23:36:27Z |
| Publication Date | 2016-07-06T18:29:43Z |

## Description

Information on Fire Inspections performed at a given location by the Fire Department. Key fields include Inspection Number, Address, Inspection Type, Start DtTm, End Dttm, Disposition

## Columns

```ls
| Included | Schema Type    | Field Name                           | Name                                 | Data Type     | Render Type   |
| ======== | ============== | ==================================== | ==================================== | ============= | ============= |
| Yes      | series tag     | inspection_number                    | Inspection Number                    | text          | text          |
| Yes      | series tag     | inspection_type                      | Inspection Type                      | text          | text          |
| Yes      | series tag     | inspection_type_description          | Inspection Type Description          | text          | text          |
| No       |                | address                              | Address                              | text          | text          |
| No       |                | zipcode                              | Inspection Address Zipcode           | text          | text          |
| Yes      | series tag     | battalion                            | Battalion                            | text          | text          |
| Yes      | series tag     | station                              | Station Area                         | text          | text          |
| Yes      | series tag     | bfp_district                         | Fire Prevention District             | text          | text          |
| Yes      | series tag     | billable_inspection                  | Billable Inspection                  | checkbox      | checkbox      |
| Yes      | time           | inspection_start_date                | Inspection Start Date                | calendar_date | calendar_date |
| No       |                | inspection_end_date                  | Inspection End Date                  | calendar_date | calendar_date |
| Yes      | series tag     | inspection_status                    | Inspection Status                    | text          | text          |
| No       |                | return_date                          | Return Date                          | calendar_date | calendar_date |
| No       |                | corrective_action_date               | Corrective Action Date               | calendar_date | calendar_date |
| Yes      | series tag     | referral_agency                      | Referral Agency                      | text          | text          |
| Yes      | series tag     | complaint_number                     | Complaint Number                     | text          | number        |
| Yes      | series tag     | permit_number                        | Permit Number                        | text          | number        |
| Yes      | series tag     | referral_number                      | Referral Number                      | text          | number        |
| Yes      | series tag     | violation_number                     | Violation Number                     | text          | number        |
| Yes      | series tag     | dbi_application_number               | DBI Application Number               | text          | text          |
| No       |                | invoice_date                         | Invoice Date                         | calendar_date | calendar_date |
| No       |                | second_notice_date                   | Second Notice Date                   | calendar_date | calendar_date |
| No       |                | final_notice_date                    | Final Notice Date                    | calendar_date | calendar_date |
| No       |                | lien_date                            | Lien Date                            | calendar_date | calendar_date |
| Yes      | series tag     | sent_to_bureau_of_delinquent_revenue | Sent to Bureau of Delinquent Revenue | checkbox      | checkbox      |
| Yes      | numeric metric | invoice_amount                       | Invoice Amount                       | number        | text          |
| Yes      | numeric metric | fee                                  | Fee                                  | number        | number        |
| Yes      | numeric metric | penalty_amount                       | Penalty Amount                       | number        | number        |
| Yes      | numeric metric | posting_fee                          | Posting Fee                          | number        | number        |
| Yes      | numeric metric | interest_amount                      | Interest Amount                      | number        | number        |
| Yes      | numeric metric | paid_amount                          | Paid Amount                          | number        | number        |
| No       |                | paid_date                            | Paid Date                            | calendar_date | calendar_date |
| Yes      | series tag     | supervisor_district                  | Supervisor District                  | text          | text          |
| Yes      | series tag     | neighborhood_district                | Neighborhood District                | text          | text          |
```

## Time Field

```ls
Value = inspection_start_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,zipcode,inspection_end_date,return_date,corrective_action_date,invoice_date,second_notice_date,final_notice_date,lien_date,paid_date
```

## Data Commands

```ls
series e:wb4c-6hwj d:2015-12-20T00:00:00.000Z t:inspection_number=204810 t:inspection_type_description="r1 company inspection" t:station=06 t:bfp_district=02S t:neighborhood_district=Mission t:battalion=02 t:inspection_type=21 t:inspection_status=completed t:sent_to_bureau_of_delinquent_revenue=false t:billable_inspection=false t:supervisor_district=8 m:fee=157 m:invoice_amount=157 m:paid_amount=157

series e:wb4c-6hwj d:2015-12-02T00:00:00.000Z t:inspection_number=205965 t:inspection_type_description="r1 company inspection" t:station=16 t:bfp_district=04 t:neighborhood_district=Marina t:battalion=04 t:inspection_type=21 t:inspection_status=completed t:sent_to_bureau_of_delinquent_revenue=false t:billable_inspection=false t:supervisor_district=2 m:fee=157 m:invoice_amount=157 m:paid_amount=157

series e:wb4c-6hwj d:2015-11-23T00:00:00.000Z t:inspection_number=228694 t:inspection_type_description="police dept. ref. insp." t:station=01 t:bfp_district=01W t:neighborhood_district="Financial District/South Beach" t:battalion=01 t:inspection_type=54 t:inspection_status=completed t:sent_to_bureau_of_delinquent_revenue=false t:referral_number=32163 t:billable_inspection=false t:supervisor_district=3 m:fee=120 m:invoice_amount=120 m:paid_amount=120
```

## Meta Commands

```ls
metric m:invoice_amount p:integer l:"Invoice Amount" t:dataTypeName=number

metric m:fee p:float l:Fee t:dataTypeName=number

metric m:penalty_amount p:float l:"Penalty Amount" t:dataTypeName=number

metric m:posting_fee p:double l:"Posting Fee" t:dataTypeName=number

metric m:interest_amount p:double l:"Interest Amount" t:dataTypeName=number

metric m:paid_amount p:float l:"Paid Amount" t:dataTypeName=number

entity e:wb4c-6hwj l:"Fire Inspections" t:url=https://data.sfgov.org/api/views/wb4c-6hwj

property e:wb4c-6hwj t:meta.view v:id=wb4c-6hwj v:category="Housing and Buildings" v:averageRating=0 v:name="Fire Inspections"

property e:wb4c-6hwj t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wb4c-6hwj t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:wb4c-6hwj t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| inspection_number | inspection_type | inspection_type_description | address                | zipcode | battalion | station | bfp_district | billable_inspection | inspection_start_date | inspection_end_date | inspection_status | return_date | corrective_action_date | referral_agency | complaint_number | permit_number | referral_number | violation_number | dbi_application_number | invoice_date        | second_notice_date | final_notice_date | lien_date | sent_to_bureau_of_delinquent_revenue | invoice_amount | fee | penalty_amount | posting_fee | interest_amount | paid_amount | paid_date           | supervisor_district | neighborhood_district          | 
| ================= | =============== | =========================== | ====================== | ======= | ========= | ======= | ============ | =================== | ===================== | =================== | ================= | =========== | ====================== | =============== | ================ | ============= | =============== | ================ | ====================== | =================== | ================== | ================= | ========= | ==================================== | ============== | === | ============== | =========== | =============== | =========== | =================== | =================== | ============================== | 
| 234121            | 18              | on-site consultation        | 1000 - 1014 Larkin St  | 94109   | 04        | 03      | 04           | false               | 2016-01-14T00:00:00   | 2016-01-14T00:00:00 | completed         |             |                        |                 |                  |               |                 |                  |                        |                     |                    |                   |           | false                                |                |     |                |             |                 |             |                     | 3                   | Nob Hill                       | 
| 234119            | 31              | dbi inspection              | 1700 California St     | 94109   | 04        | 38      | 04           | false               | 2016-01-14T00:00:00   | 2016-01-14T00:00:00 | completed         |             |                        |                 |                  |               |                 |                  | 201511041713           |                     |                    |                   |           | false                                |                |     |                |             |                 |             |                     | 2                   | Pacific Heights                | 
| 234117            | 31              | dbi inspection              | 5 Embarcadero Ctr      | 94111   | 01        | 13      | 01S          | false               | 2016-01-13T00:00:00   | 2016-01-13T00:00:00 | completed         |             |                        |                 |                  |               |                 |                  | 201512074283           |                     |                    |                   |           | false                                |                |     |                |             |                 |             |                     | 3                   | Financial District/South Beach | 
| 231206            | 21              | r1 company inspection       | 843 - 855 Clay St      | 94108   | 01        | 02      | 01N          | false               | 2016-01-16T00:00:00   |                     | pending           |             |                        |                 |                  |               |                 |                  |                        |                     |                    |                   |           | false                                |                |     |                |             |                 |             |                     | 3                   | Chinatown                      | 
| 204810            | 21              | r1 company inspection       | 255 Dolores St         | 94103   | 02        | 06      | 02S          | false               | 2015-12-20T00:00:00   | 2015-12-20T00:00:00 | completed         |             |                        |                 |                  |               |                 |                  |                        | 2015-12-24T00:00:00 |                    |                   |           | false                                | 157            | 157 |                |             |                 | 157         | 2016-01-15T00:00:00 | 8                   | Mission                        | 
| 205965            | 21              | r1 company inspection       | 3015 Van Ness Ave      | 94123   | 04        | 16      | 04           | false               | 2015-12-02T00:00:00   | 2015-12-02T00:00:00 | completed         |             |                        |                 |                  |               |                 |                  |                        | 2015-12-09T00:00:00 |                    |                   |           | false                                | 157            | 157 |                |             |                 | 157         | 2016-01-15T00:00:00 | 2                   | Marina                         | 
| 234107            | 20              | port permits                | 575 North Mcdonnell Rd |         | AP        | AP      | AP           | false               | 2016-01-15T00:00:00   |                     | pending           |             |                        |                 |                  |               |                 |                  | PORT10610000           |                     |                    |                   |           | false                                |                |     |                |             |                 |             |                     |                     |                                | 
| 226047            | 04              | complaint inspection        | 1575 Filbert St        | 94123   | 04        | 16      | 04           | false               | 2015-11-13T00:00:00   | 2016-01-14T00:00:00 | completed         |             |                        |                 | 40560            |               |                 |                  |                        |                     |                    |                   |           | false                                |                |     |                |             |                 |             |                     | 2                   | Marina                         | 
| 234109            | 31              | dbi inspection              | 101 California St      | 94111   | 01        | 13      | 01S          | false               | 2016-01-14T00:00:00   | 2016-01-14T00:00:00 | completed         |             |                        |                 |                  |               |                 |                  | 201510291132           |                     |                    |                   |           | false                                |                |     |                |             |                 |             |                     | 3                   | Financial District/South Beach | 
| 229816            | 05              | permit approval inspection  | 444 - 448 Brannan St   | 94107   | 03        | 08      | 03S          | false               | 2016-01-15T00:00:00   | 2016-01-15T00:00:00 | completed         |             |                        |                 |                  | 69736         |                 |                  |                        |                     |                    |                   |           | false                                |                |     |                |             |                 |             |                     | 6                   | South of Market                | 
```