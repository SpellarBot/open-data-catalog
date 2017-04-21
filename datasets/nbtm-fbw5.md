# Notices of Violation issued by the Department of Building Inspection

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/notices-of-violation-issued-by-the-department-of-building-inspection) |
| Metadata | [Link](https://data.sfgov.org/api/views/nbtm-fbw5) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/nbtm-fbw5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/nbtm-fbw5/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | nbtm-fbw5 |
| Name | Notices of Violation issued by the Department of Building Inspection |
| Category | Housing and Buildings |
| Created | 2016-11-13T10:31:09Z |
| Publication Date | 2016-11-23T20:47:54Z |

## Description

These records indicate the actual violations and comments by the inspector found during the inspection. The data should be sorted on the Complaint Number field and the Item Sequence Number field.  The user should be able to link this file with the Building Complaints dataset (https://data.sfgov.org/d/gm2e-bten) to get a more accurate picture of the violations.

## Columns

```ls
| Included | Schema Type    | Field Name                        | Name                                | Data Type | Render Type |
| ======== | ============== | ================================= | =================================== | ========= | =========== |
| Yes      | series tag     | complaint_number                  | Complaint Number                    | text      | text        |
| Yes      | series tag     | item_sequence_number              | Item Sequence Number                | text      | text        |
| Yes      | time           | date_filed                        | Date Filed                          | date      | date        |
| Yes      | series tag     | block                             | Block                               | text      | text        |
| Yes      | series tag     | lot                               | Lot                                 | text      | text        |
| Yes      | series tag     | street_number                     | Street Number                       | text      | text        |
| Yes      | series tag     | street_name                       | Street Name                         | text      | text        |
| Yes      | series tag     | street_suffix                     | Street Suffix                       | text      | text        |
| Yes      | numeric metric | unit                              | Unit                                | number    | text        |
| Yes      | series tag     | status                            | Status                              | text      | text        |
| Yes      | series tag     | item                              | Item                                | text      | text        |
| Yes      | series tag     | assigned_division                 | Assigned Division                   | text      | text        |
| Yes      | series tag     | receiving_division                | Receiving Division                  | text      | text        |
| Yes      | series tag     | nov_category_description          | NOV Category Description            | text      | text        |
| Yes      | series tag     | nov_item_description              | NOV Item Description                | text      | text        |
| Yes      | series tag     | neighborhoods_analysis_boundaries | Neighborhoods - Analysis Boundaries | text      | text        |
| Yes      | series tag     | supervisor_district               | Supervisor District                 | text      | text        |
| Yes      | series tag     | zipcode                           | Zipcode                             | text      | text        |
```

## Time Field

```ls
Value = date_filed
Format & Zone = seconds
```

## Data Commands

```ls
```

## Meta Commands

```ls
metric m:unit p:integer l:Unit t:dataTypeName=number

entity e:nbtm-fbw5 l:"Notices of Violation issued by the Department of Building Inspection" t:url=https://data.sfgov.org/api/views/nbtm-fbw5

property e:nbtm-fbw5 t:meta.view v:id=nbtm-fbw5 v:category="Housing and Buildings" v:averageRating=0 v:name="Notices of Violation issued by the Department of Building Inspection"

property e:nbtm-fbw5 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:nbtm-fbw5 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:nbtm-fbw5 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| complaint_number | item_sequence_number | date_filed | block | lot | street_number | street_name | street_suffix | unit | status | item                                                                 | assigned_division           | receiving_division            | nov_category_description        | nov_item_description                                                               | neighborhoods_analysis_boundaries | supervisor_district | zipcode | 
| ================ | ==================== | ========== | ===== | === | ============= | =========== | ============= | ==== | ====== | ==================================================================== | =========================== | ============================= | =============================== | ================================================================================== | ================================= | =================== | ======= | 
| 199928213        | 44811                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | this notice includes violations for the areas noted.                 | Housing Inspection Services | Department Of Bldg Inspection | building section                | 65 bertha ln #102                                                                  |                                   |                     |         | 
| 199928213        | 44812                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | repair damaged walls (1001b h o hc)                                  | Housing Inspection Services | Department Of Bldg Inspection | interior surfaces section       | repair fire damaged wall in kitchen (next to cabinet)                              |                                   |                     |         | 
| 199928213        | 44813                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | repair damaged ceilings (1001b h o hc)                               | Housing Inspection Services | Department Of Bldg Inspection | interior surfaces section       | repair fire damaged ceiling in kitchen (next cabinets)                             |                                   |                     |         | 
| 199928213        | 44814                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | paint walls (1001b 1301 hc)                                          | Housing Inspection Services | Department Of Bldg Inspection | interior surfaces section       | paint all repairs                                                                  |                                   |                     |         | 
| 199928213        | 44815                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | provide electrical permit (90.25 ec)                                 | Housing Inspection Services | Department Of Bldg Inspection | plumbing and electrical section | electrical premit needed for fire damaged at kitchen.                              |                                   |                     |         | 
| 199928213        | 44816                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | provide adequate lighting (504g hc)                                  | Housing Inspection Services | Department Of Bldg Inspection | plumbing and electrical section | provide adequate lighting at kitchen (fire damaged)                                |                                   |                     |         | 
| 199928213        | 44817                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | repair smoke detector (908 911 hc)                                   | Housing Inspection Services | Department Of Bldg Inspection | smoke detection section         | repair smoke detectors throughout unit.                                            |                                   |                     |         | 
| 199928213        | 44818                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | provide fire extinguisher type 2a 10bc or equivalent.(905 1001(m)hc) | Housing Inspection Services | Department Of Bldg Inspection | fire section                    | provide fire extinguisher at common hallways                                       |                                   |                     |         | 
| 199928213        | 44821                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | building permit required (301 hc)                                    | Housing Inspection Services | Department Of Bldg Inspection | building section                | provide building permit for fire damaged repair (at kitchen wall and ceiling).     |                                   |                     |         | 
| 199928213        | 44824                | 944611200  | 4712  | 007 | 227           | Harbor      | Rd            |      | active | inspector comments                                                   | Housing Inspection Services | Department Of Bldg Inspection | other section                   | atthe time of inspection tenant was to contact pg&e regarding the heater (furance) |                                   |                     |         | 
```