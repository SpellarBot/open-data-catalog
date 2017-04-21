# Test-2

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/test-2) |
| Metadata | [Link](https://data.wa.gov/api/views/ehju-t29q) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/ehju-t29q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/ehju-t29q/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | ehju-t29q |
| Name | Test-2 |
| Created | 2016-05-07T00:21:45Z |
| Publication Date | 2016-05-07T00:55:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                    | Data Type | Render Type |
| ======== | ============== | ======================= | ======================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | primary_funding_program | Primary Funding Program | text      | text        |
| Yes      | series tag     | sponsor                 | Sponsor                 | text      | text        |
| Yes      | series tag     | project_number          | Project Number          | text      | text        |
| Yes      | series tag     | project_name            | Project Name            | text      | text        |
| No       |                | active_date             | Active Date             | text      | text        |
| Yes      | numeric metric | cbs_funding             | CBS Funding             | number    | number      |
| Yes      | numeric metric | cbs_funding_spent       | CBS Funding Spent       | number    | number      |
| Yes      | numeric metric | percent_paid            | Percent Paid            | number    | number      |
| Yes      | numeric metric | bills_paid              | Bills Paid              | number    | number      |
| No       |                | last_bill_date          | Last Bill Date          | text      | text        |
| Yes      | series tag     | legislative_district    | Legislative District    | text      | number      |
| Yes      | series tag     | project_summary         | Project Summary         | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = active_date,last_bill_date
```

## Data Commands

```ls
series e:ehju-t29q d:2016-05-06T17:54:23.000Z t:project_name="K1320 Chehalis Basin Flood Analysis and Evaluation" t:legislative_district=43 t:project_number=15-1454 t:project_summary="https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=15-1454" t:sponsor="Anchor QEA, LLC" t:primary_funding_program="CBS Activities" m:cbs_funding_spent=1093534 m:percent_paid=96 m:bills_paid=5 m:cbs_funding=1136949

series e:ehju-t29q d:2016-05-06T17:54:23.000Z t:project_name="Flood Strategy" t:legislative_district=43 t:project_number=15-1479 t:project_summary="https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=15-1479" t:sponsor="Anchor QEA, LLC" t:primary_funding_program="CBS Activities" m:cbs_funding_spent=2379465 m:percent_paid=18 m:bills_paid=4 m:cbs_funding=13310000

series e:ehju-t29q d:2016-05-06T17:54:23.000Z t:project_name="Black River Watershed Habitat Restoration" t:legislative_district=35 t:project_number=15-1534 t:project_summary="https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=15-1534" t:sponsor="Capitol Land Trust" t:primary_funding_program="Coast Rst Initiative Projects" m:cbs_funding_spent=0 m:percent_paid=0 m:bills_paid=0 m:cbs_funding=100000
```

## Meta Commands

```ls
metric m:cbs_funding p:integer l:"CBS Funding" t:dataTypeName=number

metric m:cbs_funding_spent p:integer l:"CBS Funding Spent" t:dataTypeName=number

metric m:percent_paid p:integer l:"Percent Paid" t:dataTypeName=number

metric m:bills_paid p:integer l:"Bills Paid" t:dataTypeName=number

entity e:ehju-t29q l:Test-2 t:url=https://data.wa.gov/api/views/ehju-t29q

property e:ehju-t29q t:meta.view v:id=ehju-t29q v:averageRating=0 v:name=Test-2

property e:ehju-t29q t:meta.view.owner v:id=ugen-sv2k v:screenName=Scott v:displayName=Scott

property e:ehju-t29q t:meta.view.tableauthor v:id=ugen-sv2k v:screenName=Scott v:roleName=publisher v:displayName=Scott
```

## Top Records

```ls
| :updated_at | primary_funding_program         | sponsor                             | project_number | project_name                                       | active_date    | cbs_funding | cbs_funding_spent | percent_paid | bills_paid | last_bill_date | legislative_district | project_summary                                                                           | 
| =========== | =============================== | =================================== | ============== | ================================================== | ============== | =========== | ================= | ============ | ========== | ============== | ==================== | ========================================================================================= | 
| 1462557263  | CBS Activities                  | Anchor QEA, LLC                     | 15-1454        | K1320 Chehalis Basin Flood Analysis and Evaluation | 7/29/15        | 1136949     | 1093534           | 96           | 5          | 11/25/15       | 43                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=15-1454, null] | 
| 1462557263  | CBS Activities                  | Anchor QEA, LLC                     | 15-1479        | Flood Strategy                                     | 10/9/15        | 13310000    | 2379465           | 18           | 4          | 2/29/16        | 43                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=15-1479, null] | 
| 1462557263  | Coast Rst Initiative Projects   | Capitol Land Trust                  | 15-1534        | Black River Watershed Habitat Restoration          | 4/19/16        | 100000      | 0                 | 0            | 0          | None           | 35                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=15-1534, null] | 
| 1462557263  | CBS Habitat Restoration Project | Chehalis Basin Fisheries Task Force | 16-1327        | Grays Harbor County Barrier Correction Design      | Not Yet Active | 308000      | 0                 | 0            | 0          | None           |                      | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=16-1327, null] | 
| 1462557263  | CBS Habitat Restoration Project | Chehalis Basin Fisheries Task Force | 16-1328        | Big Creek Polson Camp Rd Barrier Correction        | 5/4/16         | 520925      | 0                 | 0            | 0          | None           | 24                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=16-1328, null] | 
| 1462557263  | CBS Habitat Restoration Project | Chehalis Basin Fisheries Task Force | 16-1329        | Gaddis Creek South Bank Rd. Barrier Correction     | 4/20/16        | 306721      | 0                 | 0            | 0          | None           | 19                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=16-1329, null] | 
| 1462557263  | CBS Habitat Restoration Project | Chehalis Basin Fisheries Task Force | 16-1334        | Harstad Creek Middle Satsop Rd Barrier Correction  | 5/4/16         | 305356      | 0                 | 0            | 0          | None           | 24                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=16-1334, null] | 
| 1462557263  | CBS Habitat Restoration Project | Chehalis Basin Fisheries Task Force | 16-1335        | Eaton Creek South Bank Rd Barrier Correction       | 4/20/16        | 306572      | 0                 | 0            | 0          | None           | 19                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=16-1335, null] | 
| 1462557263  | CBS Habitat Restoration Project | Chehalis Basin Fisheries Task Force | 16-1336        | Taylor Creek Taylors Ferry Rd Barrier Correction   | 5/3/16         | 292259      | 0                 | 0            | 0          | None           | 19                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=16-1336, null] | 
| 1462557263  | CBS Habitat Restoration Project | Chehalis Basin Fisheries Task Force | 16-1337        | Johns River Tributaries Barrier Correction         | 4/20/16        | 1037048     | 0                 | 0            | 0          | None           | 19                   | [https://secure.rco.wa.gov/prism/search/projectsnapshot.aspx?ProjectNumber=16-1337, null] | 
```