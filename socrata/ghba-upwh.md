# Updated Treasure Island Addresses and Building Numbers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/updated-treasure-island-addresses-and-building-numbers) |
| Metadata | [Link](https://data.sfgov.org/api/views/ghba-upwh) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/ghba-upwh/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/ghba-upwh/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | ghba-upwh |
| Name | Updated Treasure Island Addresses and Building Numbers |
| Attribution | City and County of San Francisco |
| Category | Geographic Locations and Boundaries |
| Created | 2016-08-11T22:10:38Z |
| Publication Date | 2016-08-11T22:13:25Z |

## Description

List of addresses, building numbers, and building references on Treasure Island.

## Columns

```ls
| Included | Schema Type    | Field Name       | Name             | Data Type | Render Type |
| ======== | ============== | ================ | ================ | ========= | =========== |
| No       | time           | :updated_at      | updated_at       | meta_data | meta_data   |
| Yes      | series tag     | bldg_no          | Bldg_No          | text      | number      |
| Yes      | series tag     | existing_addr    | Existing_Addr    | text      | text        |
| Yes      | series tag     | new_addr         | New_Addr         | text      | text        |
| Yes      | series tag     | checked          | Checked          | text      | text        |
| Yes      | numeric metric | current_addr     | Current Addr     | number    | number      |
| Yes      | series tag     | current_add_v    | Current_add_v    | text      | text        |
| Yes      | numeric metric | change           | Change           | number    | number      |
| Yes      | series tag     | misc_info        | Misc_Info        | text      | text        |
| Yes      | series tag     | bldg_number      | Bldg_Number      | text      | number      |
| Yes      | series tag     | commonplace_name | Commonplace Name | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:ghba-upwh d:2016-08-11T15:10:42.000Z t:new_addr="1 Avenue Of The Palms" t:bldg_no=1 t:existing_addr="410 Avenue of the Palms" t:current_add_v="1 AVENUE OF THE PALMS" t:misc_info="Administration Building" t:checked=Y t:bldg_number=1 m:change=0 m:current_addr=0

series e:ghba-upwh d:2016-08-11T15:10:42.000Z t:new_addr="300 California Ave" t:bldg_no=2 t:existing_addr="50 Avenue D" t:current_add_v="300 CALIFORNIA AVE" t:misc_info="Island Creative" t:checked=Y t:bldg_number=2 m:change=0 m:current_addr=0

series e:ghba-upwh d:2016-08-11T15:10:42.000Z t:bldg_no=3 t:existing_addr="600 California Av" t:current_add_v="600 CALIFORNIA AV" t:misc_info="Building Three" t:checked=Y t:bldg_number=3 m:change=0 m:current_addr=0
```

## Meta Commands

```ls
metric m:current_addr p:integer l:"Current Addr" t:dataTypeName=number

metric m:change p:integer l:Change t:dataTypeName=number

entity e:ghba-upwh l:"Updated Treasure Island Addresses and Building Numbers" t:attribution="City and County of San Francisco" t:url=https://data.sfgov.org/api/views/ghba-upwh

property e:ghba-upwh t:meta.view v:id=ghba-upwh v:category="Geographic Locations and Boundaries" v:attributionLink=http://www.sfgov.org v:averageRating=0 v:name="Updated Treasure Island Addresses and Building Numbers" v:attribution="City and County of San Francisco"

property e:ghba-upwh t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:ghba-upwh t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:ghba-upwh t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| :updated_at | bldg_no | existing_addr           | new_addr              | checked | current_addr | current_add_v         | change | misc_info                                                 | bldg_number | commonplace_name | 
| =========== | ======= | ======================= | ===================== | ======= | ============ | ===================== | ====== | ========================================================= | =========== | ================ | 
| 1470928242  | 1       | 410 Avenue of the Palms | 1 Avenue Of The Palms | Y       | 0            | 1 AVENUE OF THE PALMS | 0      | Administration Building                                   | 1           |                  | 
| 1470928242  | 2       | 50 Avenue D             | 300 California Ave    | Y       | 0            | 300 CALIFORNIA AVE    | 0      | Island Creative                                           | 2           |                  | 
| 1470928242  | 3       | 600 California Av       |                       | Y       | 0            | 600 CALIFORNIA AV     | 0      | Building Three                                            | 3           |                  | 
| 1470928242  | 29      | 550 Avenue H            |                       | Y       | 0            | 550 AVENUE H          | 0      |                                                           | 29          |                  | 
| 1470928242  | 33      | 401 13th Street         |                       | Y       | 0            | 401 13TH STREET       | 0      | Elementary School, include building units in address plan | 33          | TI ES            | 
| 1470928242  | 34      | 725 California Avenue   |                       | Y       | 0            | 725 CALIFORNIA AVENUE | 0      | Golden Gate Rugby Club House                              | 34          |                  | 
| 1470928242  | 40      | 720 4th St              | 725 3rd Street        | Y       | 0            | 725 3RD STREET        | 0      |                                                           | 40          |                  | 
| 1470928242  | 62      | 775 13th St             | 849 13th St           | Y       | 0            | 849 13TH ST           | 0      | Walter Wong/Tenant                                        | 62          |                  | 
| 1470928242  | 64      | 998 Avenue N            | 898 12th Street       | Y       | 0            | 898 12TH STREET       | 0      |                                                           | 64          |                  | 
| 1470928242  | 69      | 850 8th St              |                       | Y       | 0            | 850 8TH ST            | 0      |                                                           | 69          |                  | 
```