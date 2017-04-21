# List of 3rd Party Organizations for Closed Loop Well Contractors

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/list-of-3rd-party-organizations-for-closed-loop-well-contractors-1685d) |
| Metadata | [Link](https://data.illinois.gov/api/views/8ehz-c6vp) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/8ehz-c6vp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/8ehz-c6vp/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | 8ehz-c6vp |
| Name | List of 3rd Party Organizations for Closed Loop Well Contractors |
| Attribution | Illinois Department of Public Health - Division of Environmental Health |
| Category | Public Health |
| Tags | closed loop, well, 3rd party |
| Created | 2014-10-10T20:21:20Z |
| Publication Date | 2014-10-29T14:49:42Z |

## Description

The list contains a list of approved 3rd Party Organizations that can provide certification to closed loop well contractors. Last Update October 2014.

## Columns

```ls
| Included | Schema Type | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | =========== | ========================================== | ========================================== | ========= | =========== |
| No       | time        | :updated_at                                | updated_at                                 | meta_data | meta_data   |
| Yes      | series tag  | closed_loop_well_third_party_organizations | CLOSED LOOP WELL/THIRD PARTY ORGANIZATIONS | text      | text        |
| No       |             | third_party_organization_address           | THIRD PARTY ORGANIZATION ADDRESS           | text      | text        |
| Yes      | series tag  | third_party_organization_city              | THIRD PARTY ORGANIZATION CITY              | text      | text        |
| Yes      | series tag  | third_party_organization_state             | THIRD PARTY ORGANIZATION STATE             | text      | text        |
| Yes      | series tag  | third_party_organization_zipcode           | THIRD PARTY ORGANIZATION ZIPCODE           | text      | number      |
| Yes      | series tag  | phone                                      | PHONE                                      | text      | text        |
| Yes      | series tag  | e_mail                                     | E-Mail                                     | email     | email       |
| Yes      | series tag  | website                                    | Website                                    | url       | url         |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = third_party_organization_address
```

## Data Commands

```ls
series e:8ehz-c6vp d:2014-10-10T13:21:24.000Z t:third_party_organization_zipcode=61085 t:third_party_organization_state=IL t:phone=815-973-3000 t:website=http://www.iagp.org t:closed_loop_well_third_party_organizations="Illinois Association of Groundwater Professionals (IAGP)" t:e_mail=info@iagp.org t:third_party_organization_city=Stockton m:row_number.8ehz-c6vp=1

series e:8ehz-c6vp d:2014-10-10T13:21:24.000Z t:third_party_organization_zipcode=62708 t:third_party_organization_state=IL t:phone=217-971-3533 t:website=http://www.gaoi.org t:closed_loop_well_third_party_organizations="Geothermal Alliance of Illinois (GAOI)" t:third_party_organization_city=Springfield m:row_number.8ehz-c6vp=2

series e:8ehz-c6vp d:2014-10-10T13:21:24.000Z t:third_party_organization_zipcode=74074 t:third_party_organization_state=OK t:phone=800-626-4747 t:website=http://www.igshpa.okstate.edu/training/drillers.asp t:closed_loop_well_third_party_organizations="International Ground Source Health Pump Association (IGSPHA)" t:e_mail=igshpa@okstate.edu t:third_party_organization_city=Stillwater m:row_number.8ehz-c6vp=3
```

## Meta Commands

```ls
metric m:row_number.8ehz-c6vp p:long l:"Row Number"

entity e:8ehz-c6vp l:"List of 3rd Party Organizations for Closed Loop Well Contractors" t:attribution="Illinois Department of Public Health - Division of Environmental Health" t:url=https://data.illinois.gov/api/views/8ehz-c6vp

property e:8ehz-c6vp t:meta.view v:id=8ehz-c6vp v:category="Public Health" v:attributionLink=http://dph.illinois.gov/topics-services/environmental-health-protection/private-water v:averageRating=0 v:name="List of 3rd Party Organizations for Closed Loop Well Contractors" v:attribution="Illinois Department of Public Health - Division of Environmental Health"

property e:8ehz-c6vp t:meta.view.owner v:id=mkk8-dris v:screenName="Greg Matheny" v:displayName="Greg Matheny"

property e:8ehz-c6vp t:meta.view.tableauthor v:id=mkk8-dris v:screenName="Greg Matheny" v:roleName=publisher v:displayName="Greg Matheny"
```

## Top Records

```ls
| :updated_at | closed_loop_well_third_party_organizations                   | third_party_organization_address | third_party_organization_city | third_party_organization_state | third_party_organization_zipcode | phone        | e_mail             | website                                                     | 
| =========== | ============================================================ | ================================ | ============================= | ============================== | ================================ | ============ | ================== | =========================================================== | 
| 1412947284  | Illinois Association of Groundwater Professionals (IAGP)     | PO Box 210                       | Stockton                      | IL                             | 61085                            | 815-973-3000 | info@iagp.org      | [http://www.iagp.org, null]                                 | 
| 1412947284  | Geothermal Alliance of Illinois (GAOI)                       | PO Box 3787                      | Springfield                   | IL                             | 62708                            | 217-971-3533 |                    | [http://www.gaoi.org, null]                                 | 
| 1412947284  | International Ground Source Health Pump Association (IGSPHA) | 1201 S. Innovation Way, Ste 400  | Stillwater                    | OK                             | 74074                            | 800-626-4747 | igshpa@okstate.edu | [http://www.igshpa.okstate.edu/training/drillers.asp, null] | 
```