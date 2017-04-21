# Eviction Notices

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/eviction-notices) |
| Metadata | [Link](https://data.sfgov.org/api/views/5cei-gny5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/5cei-gny5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/5cei-gny5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 5cei-gny5 |
| Name | Eviction Notices |
| Category | Housing and Buildings |
| Tags | rent control, protected status, eviction notices |
| Created | 2014-12-23T19:11:54Z |
| Publication Date | 2016-04-27T17:21:37Z |

## Description

Data includes eviction notices filed with the San Francisco Rent Board per San Francisco Administrative Code 37.9(c). A notice of eviction does not necessarily indicate that the tenant was eventually evicted, so the notices below may differ from actual evictions. Notices are published since January 1, 1997.

## Columns

```ls
| Included | Schema Type | Field Name              | Name                                | Data Type     | Render Type   |
| ======== | =========== | ======================= | =================================== | ============= | ============= |
| Yes      | series tag  | eviction_id             | Eviction ID                         | text          | text          |
| No       |             | address                 | Address                             | text          | text          |
| Yes      | series tag  | city                    | City                                | text          | text          |
| Yes      | series tag  | state                   | State                               | text          | text          |
| Yes      | series tag  | zip                     | Eviction Notice Source Zipcode      | text          | text          |
| Yes      | time        | file_date               | File Date                           | calendar_date | calendar_date |
| Yes      | series tag  | non_payment             | Non Payment                         | checkbox      | checkbox      |
| Yes      | series tag  | breach                  | Breach                              | checkbox      | checkbox      |
| Yes      | series tag  | nuisance                | Nuisance                            | checkbox      | checkbox      |
| Yes      | series tag  | illegal_use             | Illegal Use                         | checkbox      | checkbox      |
| Yes      | series tag  | failure_to_sign_renewal | Failure to Sign Renewal             | checkbox      | checkbox      |
| Yes      | series tag  | access_denial           | Access Denial                       | checkbox      | checkbox      |
| Yes      | series tag  | unapproved_subtenant    | Unapproved Subtenant                | checkbox      | checkbox      |
| Yes      | series tag  | owner_move_in           | Owner Move In                       | checkbox      | checkbox      |
| Yes      | series tag  | demolition              | Demolition                          | checkbox      | checkbox      |
| Yes      | series tag  | capital_improvement     | Capital Improvement                 | checkbox      | checkbox      |
| Yes      | series tag  | substantial_rehab       | Substantial Rehab                   | checkbox      | checkbox      |
| Yes      | series tag  | ellis_act_withdrawal    | Ellis Act WithDrawal                | checkbox      | checkbox      |
| Yes      | series tag  | condo_conversion        | Condo Conversion                    | checkbox      | checkbox      |
| Yes      | series tag  | roommate_same_unit      | Roommate Same Unit                  | checkbox      | checkbox      |
| Yes      | series tag  | other_cause             | Other Cause                         | checkbox      | checkbox      |
| Yes      | series tag  | late_payments           | Late Payments                       | checkbox      | checkbox      |
| Yes      | series tag  | lead_remediation        | Lead Remediation                    | checkbox      | checkbox      |
| Yes      | series tag  | development             | Development                         | checkbox      | checkbox      |
| Yes      | series tag  | good_samaritan_ends     | Good Samaritan Ends                 | checkbox      | checkbox      |
| No       |             | constraints_date        | Constraints Date                    | calendar_date | calendar_date |
| Yes      | series tag  | supervisor_district     | Supervisor District                 | text          | number        |
| Yes      | series tag  | neighborhood            | Neighborhoods - Analysis Boundaries | text          | text          |
```

## Time Field

```ls
Value = file_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address,constraints_date
```

## Data Commands

```ls
series e:5cei-gny5 d:2016-06-06T00:00:00.000Z t:other_cause=false t:zip=94110 t:capital_improvement=false t:demolition=false t:failure_to_sign_renewal=false t:development=false t:ellis_act_withdrawal=true t:condo_conversion=false t:neighborhood="Bernal Heights" t:state=CA t:nuisance=false t:eviction_id=M161957 t:supervisor_district=9 t:illegal_use=false t:city="San Francisco" t:good_samaritan_ends=false t:owner_move_in=false t:breach=false t:unapproved_subtenant=false t:late_payments=false t:access_denial=false t:non_payment=false t:lead_remediation=false t:substantial_rehab=false t:roommate_same_unit=false m:row_number.5cei-gny5=1

series e:5cei-gny5 d:2016-06-29T00:00:00.000Z t:other_cause=false t:zip=94112 t:capital_improvement=false t:demolition=false t:failure_to_sign_renewal=false t:development=false t:ellis_act_withdrawal=false t:condo_conversion=false t:neighborhood="Outer Mission" t:state=CA t:nuisance=false t:eviction_id=M162256 t:supervisor_district=11 t:illegal_use=false t:city="San Francisco" t:good_samaritan_ends=false t:owner_move_in=true t:breach=false t:unapproved_subtenant=false t:late_payments=false t:access_denial=false t:non_payment=false t:lead_remediation=false t:substantial_rehab=false t:roommate_same_unit=false m:row_number.5cei-gny5=2

series e:5cei-gny5 d:2016-06-28T00:00:00.000Z t:other_cause=false t:zip=94103 t:capital_improvement=false t:demolition=false t:failure_to_sign_renewal=false t:development=false t:ellis_act_withdrawal=false t:condo_conversion=false t:neighborhood="Castro/Upper Market" t:state=CA t:nuisance=false t:eviction_id=M162135 t:supervisor_district=8 t:illegal_use=false t:city="San Francisco" t:good_samaritan_ends=false t:owner_move_in=false t:breach=true t:unapproved_subtenant=false t:late_payments=false t:access_denial=false t:non_payment=false t:lead_remediation=false t:substantial_rehab=false t:roommate_same_unit=false m:row_number.5cei-gny5=3
```

## Meta Commands

```ls
metric m:row_number.5cei-gny5 p:long l:"Row Number"

entity e:5cei-gny5 l:"Eviction Notices" t:url=https://data.sfgov.org/api/views/5cei-gny5

property e:5cei-gny5 t:meta.view v:id=5cei-gny5 v:category="Housing and Buildings" v:averageRating=0 v:name="Eviction Notices"

property e:5cei-gny5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:5cei-gny5 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:5cei-gny5 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| eviction_id | address                     | city          | state | zip   | file_date           | non_payment | breach | nuisance | illegal_use | failure_to_sign_renewal | access_denial | unapproved_subtenant | owner_move_in | demolition | capital_improvement | substantial_rehab | ellis_act_withdrawal | condo_conversion | roommate_same_unit | other_cause | late_payments | lead_remediation | development | good_samaritan_ends | constraints_date    | supervisor_district | neighborhood        | 
| =========== | =========================== | ============= | ===== | ===== | =================== | =========== | ====== | ======== | =========== | ======================= | ============= | ==================== | ============= | ========== | =================== | ================= | ==================== | ================ | ================== | =========== | ============= | ================ | =========== | =================== | =================== | =================== | =================== | 
| M161957     | 300 Block Of Park Street    | San Francisco | CA    | 94110 | 2016-06-06T00:00:00 | false       | false  | false    | false       | false                   | false         | false                | false         | false      | false               | false             | true                 | false            | false              | false       | false         | false            | false       | false               |                     | 9                   | Bernal Heights      | 
| M162256     | 200 Block Of Seneca Avenue  | San Francisco | CA    | 94112 | 2016-06-29T00:00:00 | false       | false  | false    | false       | false                   | false         | false                | true          | false      | false               | false             | false                | false            | false              | false       | false         | false            | false       | false               | 2021-08-25T00:00:00 | 11                  | Outer Mission       | 
| M162135     | 200 Block Of Dolores Street | San Francisco | CA    | 94103 | 2016-06-28T00:00:00 | false       | true   | false    | false       | false                   | false         | false                | false         | false      | false               | false             | false                | false            | false              | false       | false         | false            | false       | false               |                     | 8                   | Castro/Upper Market | 
| M161901     | 1200 Block Of 9th Avenue    | San Francisco | CA    | 94122 | 2016-06-02T00:00:00 | false       | false  | false    | false       | false                   | false         | false                | false         | false      | false               | false             | true                 | false            | false              | false       | false         | false            | false       | false               |                     | 5                   | Inner Sunset        | 
| M162428     | 1400 Block Of Larkin Street | San Francisco | CA    | 94109 | 2016-02-28T00:00:00 | false       | false  | false    | false       | false                   | false         | false                | false         | false      | true                | false             | false                | false            | false              | false       | false         | false            | false       | false               |                     | 3                   | Nob Hill            | 
| M161943     | 300 Block Of Wilde Avenue   | San Francisco | CA    | 94134 | 2016-06-06T00:00:00 | false       | false  | true     | false       | false                   | false         | false                | false         | false      | false               | false             | false                | false            | false              | false       | false         | false            | false       | false               |                     | 10                  | Visitacion Valley   | 
| M161986     | 0 Block Of Fair Avenue      | San Francisco | CA    | 94110 | 2016-06-13T00:00:00 | false       | true   | false    | false       | false                   | false         | false                | false         | false      | false               | false             | false                | false            | false              | false       | false         | false            | false       | false               |                     | 9                   | Bernal Heights      | 
| M161976     | 1300 Block Of Market Street | San Francisco | CA    | 94102 | 2016-06-13T00:00:00 | true        | false  | false    | false       | false                   | false         | false                | false         | false      | false               | false             | false                | false            | false              | false       | false         | false            | false       | false               |                     | 6                   | Tenderloin          | 
| M162257     | 300 Block Of Lombard Street | San Francisco | CA    | 94133 | 2016-06-30T00:00:00 | false       | false  | false    | false       | false                   | false         | false                | true          | false      | false               | false             | false                | false            | false              | false       | false         | false            | false       | false               | 2021-08-27T00:00:00 | 3                   | North Beach         | 
| M161838     | 2800 Block Of Pierce Street | San Francisco | CA    | 94123 | 2016-06-01T00:00:00 | false       | false  | false    | false       | false                   | false         | false                | true          | false      | false               | false             | false                | false            | false              | false       | false         | false            | false       | false               | 2021-08-01T00:00:00 | 2                   | Marina              | 
```