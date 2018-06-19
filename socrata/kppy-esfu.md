# Property Management Area Uses

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/property-management-area-uses-9fd64) |
| Metadata | [Link](https://data.seattle.gov/api/views/kppy-esfu) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/kppy-esfu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/kppy-esfu/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | kppy-esfu |
| Name | Property Management Area Uses |
| Attribution | City of Seattle |
| Category | Land Base |
| Created | 2014-04-01T18:11:57Z |
| Publication Date | 2014-04-03T19:51:40Z |

## Description

Data on the uses categories of City owned property

## Columns

```ls
| Included | Schema Type | Field Name        | Name          | Data Type | Render Type |
| ======== | =========== | ================= | ============= | ========= | =========== |
| No       | time        | :updated_at       | updated_at    | meta_data | meta_data   |
| Yes      | series tag  | pma_num           | PMA_NUM       | text      | number      |
| Yes      | series tag  | pma_name          | PMA_NAME      | text      | text        |
| Yes      | series tag  | juris_dept        | JURIS_DEPT    | text      | text        |
| Yes      | series tag  | use               | USE           | text      | text        |
| Yes      | series tag  | use_class         | USE_CLASS     | text      | text        |
| Yes      | series tag  | city_owned        | CITY_OWNED    | text      | text        |
| Yes      | series tag  | status            | STATUS        | text      | text        |
| Yes      | series tag  | name              | NAME          | text      | text        |
| Yes      | series tag  | comp_plan_element | Plan Element  | text      | text        |
| Yes      | series tag  | comp_plan_use     | Comp Plan Use | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:kppy-esfu d:2014-04-01T11:13:24.000Z t:city_owned=OWNED t:status=Surplus t:juris_dept=FAS t:name="SEATTLE FINANCE AND ADMINISTRATIVE SERVICES" t:use_class="Utility Facilities/ROW & Maintenance" t:use="Slope Protection" t:pma_name="Snippet at 156 MLK Jr Way - Lot 2" t:pma_num=4576 m:row_number.kppy-esfu=1

series e:kppy-esfu d:2014-04-01T11:12:01.000Z t:city_owned="MIXED OWNERSHIP" t:status="Fully Utilized" t:juris_dept=SPU t:name="SEATTLE PUBLIC UTILITIES" t:use_class="Utility Facilities/ROW & Maintenance" t:use="Water Use" t:pma_name="LAKE YOUNGS SUPPLY LINE R/W (PART ESMT)" t:pma_num=9066 m:row_number.kppy-esfu=2

series e:kppy-esfu d:2014-04-01T11:13:24.000Z t:city_owned="CITY USE ON NON-CITY PPTY" t:status="Fully Utilized" t:juris_dept=DOIT t:name="SEATTLE DEPT OF INFORMATION TECHNOLOGY" t:use_class="Utility Facilities/ROW & Maintenance" t:use="Telecommunications Facilities" t:pma_name="Columbia Center- Lease" t:pma_num=4072 m:row_number.kppy-esfu=3
```

## Meta Commands

```ls
metric m:row_number.kppy-esfu p:long l:"Row Number"

entity e:kppy-esfu l:"Property Management Area Uses" t:attribution="City of Seattle" t:url=https://data.seattle.gov/api/views/kppy-esfu

property e:kppy-esfu t:meta.view v:id=kppy-esfu v:category="Land Base" v:averageRating=0 v:name="Property Management Area Uses" v:attribution="City of Seattle"

property e:kppy-esfu t:meta.view.owner v:id=fqtv-q6su v:profileImageUrlMedium=/api/users/fqtv-q6su/profile_images/THUMB v:profileImageUrlLarge=/api/users/fqtv-q6su/profile_images/LARGE v:screenName="FAS - Real Estate Services" v:profileImageUrlSmall=/api/users/fqtv-q6su/profile_images/TINY v:displayName="FAS - Real Estate Services"

property e:kppy-esfu t:meta.view.tableauthor v:id=fqtv-q6su v:profileImageUrlMedium=/api/users/fqtv-q6su/profile_images/THUMB v:profileImageUrlLarge=/api/users/fqtv-q6su/profile_images/LARGE v:screenName="FAS - Real Estate Services" v:profileImageUrlSmall=/api/users/fqtv-q6su/profile_images/TINY v:roleName=publisher v:displayName="FAS - Real Estate Services"
```

## Top Records

```ls
| :updated_at | pma_num | pma_name                                        | juris_dept | use                           | use_class                               | city_owned                | status            | name                                        | comp_plan_element | comp_plan_use | 
| =========== | ======= | =============================================== | ========== | ============================= | ======================================= | ========================= | ================= | =========================================== | ================= | ============= | 
| 1396350804  | 4576    | Snippet at 156 MLK Jr Way - Lot 2               | FAS        | Slope Protection              | Utility Facilities/ROW & Maintenance    | OWNED                     | Surplus           | SEATTLE FINANCE AND ADMINISTRATIVE SERVICES |                   |               | 
| 1396350721  | 9066    | LAKE YOUNGS SUPPLY LINE R/W (PART ESMT)         | SPU        | Water Use                     | Utility Facilities/ROW & Maintenance    | MIXED OWNERSHIP           | Fully Utilized    | SEATTLE PUBLIC UTILITIES                    |                   |               | 
| 1396350804  | 4072    | Columbia Center- Lease                          | DOIT       | Telecommunications Facilities | Utility Facilities/ROW & Maintenance    | CITY USE ON NON-CITY PPTY | Fully Utilized    | SEATTLE DEPT OF INFORMATION TECHNOLOGY      |                   |               | 
| 1396350721  | 9133    | LAKE YOUNGS AQUEDUCT R/W SURPLUS PORTION        | SPU        | Vacant (Undeveloped)          | Roadways, Excess ROW, Tidelands, Vacant | OWNED                     | Surplus           | SEATTLE PUBLIC UTILITIES                    |                   |               | 
| 1396350721  | 9064    | MERCER ISLAND PIPE LINE                         | SPU        | Water Use                     | Utility Facilities/ROW & Maintenance    | OWNED                     | Fully Utilized    | SEATTLE PUBLIC UTILITIES                    |                   |               | 
| 1396350721  | 9072    | LAKE YOUNGS AQUEDUCT R/W                        | SPU        | Water Use                     | Utility Facilities/ROW & Maintenance    | OWNED                     | Fully Utilized    | SEATTLE PUBLIC UTILITIES                    |                   |               | 
| 1396529194  | 3332    | MERCER CORRIDOR PROJECT: 1104 MERCER ST- R/W    | SDOT       | Roadway                       | Roadways, Excess ROW, Tidelands, Vacant | ACCEPTED FOR STREET       | Inactive/Disposed | SEATTLE DEPT OF TRANSPORTATION              |                   |               | 
| 1396529232  | 4571    | Ballard Terminal Rail Road Parcels in R/W       | SDOT       | Transportation Uses           | Roadways, Excess ROW, Tidelands, Vacant | OWNED                     | Inactive/Disposed | SEATTLE DEPT OF TRANSPORTATION              |                   |               | 
| 1396529236  | 4375    | Ballard Terminal Rail Road Parcels on Real Ppty | SDOT       | Unused (Vacant Improved)      | Roadways, Excess ROW, Tidelands, Vacant | OWNED                     | Excess            | SEATTLE DEPT OF TRANSPORTATION              |                   |               | 
| 1396529246  | 291     | MINERAL SPRINGS PARK                            | DPR        | Park/Playground/Viewpoint     | Parks and Open Space                    | OWNED                     | Fully Utilized    | SEATTLE DEPT OF PARKS AND RECREATION        |                   |               | 
```