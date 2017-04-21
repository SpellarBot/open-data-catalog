# HPD Development Team Element

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hpd-development-team-element-3b69e) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/wt5z-2wyg) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/wt5z-2wyg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/wt5z-2wyg/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | wt5z-2wyg |
| Name | HPD Development Team Element |
| Attribution | Department of Housing Preservation and Development (HPD) |
| Category | Housing & Development |
| Tags | department of housing preservation and development, hpd, development team |
| Created | 2014-02-26T21:30:07Z |
| Publication Date | 2014-02-27T16:50:08Z |

## Description

Development team information for the developer (Borrower Legal Entity), GC, and subcontractors for each project.

## Columns

```ls
| Included | Schema Type | Field Name                     | Name                           | Data Type | Render Type |
| ======== | =========== | ============================== | ============================== | ========= | =========== |
| No       | time        | :updated_at                    | updated_at                     | meta_data | meta_data   |
| Yes      | series tag  | development_team_dw_id         | Development Team DW ID         | text      | number      |
| Yes      | series tag  | project_id                     | Project ID                     | text      | number      |
| Yes      | series tag  | type                           | Type                           | text      | text        |
| Yes      | series tag  | entity_name                    | Entity Name                    | text      | text        |
| Yes      | series tag  | first_name                     | First Name                     | text      | text        |
| Yes      | series tag  | last_name                      | Last Name                      | text      | text        |
| Yes      | series tag  | entity_individual_indicator    | Entity Individual Indicator    | text      | text        |
| Yes      | series tag  | parent_entity_name             | Parent Entity Name             | text      | text        |
| Yes      | series tag  | individual_role                | Individual Role                | text      | text        |
| Yes      | series tag  | individual_title               | Individual Title               | text      | text        |
| Yes      | series tag  | individual_officer_equivalence | Individual Officer Equivalence | text      | text        |
| Yes      | series tag  | care_of                        | Care Of                        | text      | text        |
| Yes      | series tag  | house_number                   | House Number                   | text      | text        |
| Yes      | series tag  | street_name                    | Street Name                    | text      | text        |
| Yes      | series tag  | apartment_suite_floor          | Apartment/Suite/Floor          | text      | text        |
| Yes      | series tag  | city                           | City                           | text      | text        |
| Yes      | series tag  | state                          | State                          | text      | text        |
| Yes      | series tag  | zip                            | Zip                            | text      | text        |
| Yes      | series tag  | trade_type                     | Trade Type                     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wt5z-2wyg d:2014-02-26T13:30:20.000Z t:individual_title=President t:zip=07726 t:street_name="Highland Ridge Rd" t:state=NJ t:type="SUB CONTRACTOR" t:development_team_dw_id=4690 t:city=Manalapan t:first_name=Jason t:house_number=60 t:individual_officer_equivalence=CEO t:project_id=44336 t:last_name=Noto t:entity_individual_indicator=Individual t:parent_entity_name="Spray Force Systems Inc." t:individual_role=Both m:row_number.wt5z-2wyg=1

series e:wt5z-2wyg d:2014-02-26T13:30:20.000Z t:zip=11725 t:house_number=82 t:entity_name="Sterling Floor Designs Ltd." t:project_id=44336 t:street_name="Modular Dr" t:state=NY t:entity_individual_indicator=Entity t:parent_entity_name="Sterling Floor Designs Ltd." t:type="SUB CONTRACTOR" t:city=Commack t:development_team_dw_id=4691 m:row_number.wt5z-2wyg=2

series e:wt5z-2wyg d:2014-02-26T13:30:20.000Z t:individual_title=President t:zip=11747 t:street_name="Amberson Place" t:state=NY t:type="SUB CONTRACTOR" t:development_team_dw_id=4692 t:city=Melville t:first_name=Brian t:house_number=14 t:individual_officer_equivalence=CEO t:project_id=44336 t:last_name=Herz t:entity_individual_indicator=Individual t:parent_entity_name="Sterling Floor Designs Ltd." t:individual_role=Both m:row_number.wt5z-2wyg=3
```

## Meta Commands

```ls
metric m:row_number.wt5z-2wyg p:long l:"Row Number"

entity e:wt5z-2wyg l:"HPD Development Team  Element" t:attribution="Department of Housing Preservation and Development (HPD)" t:url=https://data.cityofnewyork.us/api/views/wt5z-2wyg

property e:wt5z-2wyg t:meta.view v:id=wt5z-2wyg v:category="Housing & Development" v:averageRating=0 v:name="HPD Development Team  Element" v:attribution="Department of Housing Preservation and Development (HPD)"

property e:wt5z-2wyg t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:wt5z-2wyg t:meta.view.tableauthor v:id=uurm-7z6x v:screenName=Siddhartha v:displayName=Siddhartha
```

## Top Records

```ls
| :updated_at | development_team_dw_id | project_id | type           | entity_name                   | first_name | last_name | entity_individual_indicator | parent_entity_name            | individual_role | individual_title | individual_officer_equivalence | care_of | house_number | street_name       | apartment_suite_floor | city       | state | zip   | trade_type | 
| =========== | ====================== | ========== | ============== | ============================= | ========== | ========= | =========================== | ============================= | =============== | ================ | ============================== | ======= | ============ | ================= | ===================== | ========== | ===== | ===== | ========== | 
| 1393421420  | 4690                   | 44336      | SUB CONTRACTOR |                               | Jason      | Noto      | Individual                  | Spray Force Systems Inc.      | Both            | President        | CEO                            |         | 60           | Highland Ridge Rd |                       | Manalapan  | NJ    | 07726 |            | 
| 1393421420  | 4691                   | 44336      | SUB CONTRACTOR | Sterling Floor Designs Ltd.   |            |           | Entity                      | Sterling Floor Designs Ltd.   |                 |                  |                                |         | 82           | Modular Dr        |                       | Commack    | NY    | 11725 |            | 
| 1393421420  | 4692                   | 44336      | SUB CONTRACTOR |                               | Brian      | Herz      | Individual                  | Sterling Floor Designs Ltd.   | Both            | President        | CEO                            |         | 14           | Amberson Place    |                       | Melville   | NY    | 11747 |            | 
| 1393421420  | 4693                   | 44336      | SUB CONTRACTOR |                               | Erik       | Herz      | Individual                  | Sterling Floor Designs Ltd.   | Both            | Vice President   | COO                            |         | 26           | Pond Park Rd      |                       | Great Neck | NY    | 11023 |            | 
| 1393421420  | 4694                   | 44336      | SUB CONTRACTOR |                               | Jerry      | Herz      | Individual                  | Sterling Floor Designs Ltd.   | Owner           | Secretary        |                                |         | 63           | Hunting Hill Dr   |                       | Dix Hills  | NY    | 11746 |            | 
| 1393421420  | 4695                   | 44336      | SUB CONTRACTOR |                               | Ilene      | Herz      | Individual                  | Sterling Floor Designs Ltd.   | Owner           | Secretary        |                                |         | 63           | Hunting Hill Dr   |                       | Dix Hills  | NY    | 11746 |            | 
| 1393421420  | 4696                   | 44336      | SUB CONTRACTOR | Otis Elevator Corp.           |            |           | Entity                      | United Technologies Corp.     |                 |                  |                                |         | 1            | Odel Plaza        | Suite 120             | Yonkers    | NY    | 10701 |            | 
| 1393421420  | 4697                   | 44336      | SUB CONTRACTOR | Bay Restoration Corp.         |            |           | Entity                      | Bay Restoration Corp.         |                 |                  |                                |         | 32-47        | 62nd Street       |                       | Woodside   | NY    | 11377 |            | 
| 1393421420  | 4698                   | 44336      | SUB CONTRACTOR |                               | Stelios    | Banagos   | Individual                  | Bay Restoration Corp.         | Both            | President        | CEO                            |         | 395          | Limestreet Rd     |                       | Coxsackie  | NY    | 12051 |            | 
| 1393421420  | 4699                   | 44336      | SUB CONTRACTOR | MJ Quality Construction Corp. |            |           | Entity                      | MJ Quality Construction Corp. |                 |                  |                                |         | 121          | Meserole Ave      |                       | Brooklyn   | NY    | 11222 |            | 
```