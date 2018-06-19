# FDNY Repealed Rules And Corresponding New Fire Code And Rules

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/fdny-repealed-rules-and-corresponding-new-fire-code-and-rules-b48ca) |
| Metadata | [Link](https://data.cityofnewyork.us/api/views/isrj-349k) |
| Data: JSON | [100 Rows](https://data.cityofnewyork.us/api/views/isrj-349k/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofnewyork.us/api/views/isrj-349k/rows.csv?max_rows=100) |
| Host | data.cityofnewyork.us |
| Id | isrj-349k |
| Name | FDNY Repealed Rules And Corresponding New Fire Code And Rules |
| Attribution | Fire Department of New York City (FDNY) |
| Category | Public Safety |
| Tags | fdny, fire department, safety, fire safety, fire code, building standards, fire rule, new fire code |
| Created | 2013-01-31T16:13:28Z |
| Publication Date | 2013-01-31T16:16:30Z |

## Description

Repealed Rules and the replacement new codes and rules

## Columns

```ls
| Included | Schema Type | Field Name                 | Name                           | Data Type | Render Type |
| ======== | =========== | ========================== | ============================== | ========= | =========== |
| No       | time        | :updated_at                | updated_at                     | meta_data | meta_data   |
| Yes      | series tag  | repealed_rule_rcny_section | Repealed Rule (RCNY) Section   | text      | text        |
| Yes      | series tag  | repealed_section_title     | Repealed Section Title         | text      | text        |
| Yes      | series tag  | new_code_fc_rule_r_section | New Code (FC)/Rule (R) Section | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:isrj-349k d:2013-01-31T08:13:29.000Z t:repealed_section_title="Tanks Used for Bulk Storage of Acids" t:repealed_rule_rcny_section="3 RCNY 1-01" t:new_code_fc_rule_r_section="FC Chapters 27 and 31 R4831-01(d)" m:row_number.isrj-349k=1

series e:isrj-349k d:2013-01-31T08:13:29.000Z t:repealed_section_title="Conduct of Adjudications" t:repealed_rule_rcny_section="3 RCNY 2-01" t:new_code_fc_rule_r_section=R4900-01 m:row_number.isrj-349k=2

series e:isrj-349k d:2013-01-31T08:13:29.000Z t:repealed_section_title="Permits for Portable Air Compressors" t:repealed_rule_rcny_section="3 RCNY 3-01" t:new_code_fc_rule_r_section="FC 105.6 and A03.1(14)" m:row_number.isrj-349k=3
```

## Meta Commands

```ls
metric m:row_number.isrj-349k p:long l:"Row Number"

entity e:isrj-349k l:"FDNY Repealed  Rules And Corresponding New Fire Code And Rules" t:attribution="Fire Department of New York City (FDNY)" t:url=https://data.cityofnewyork.us/api/views/isrj-349k

property e:isrj-349k t:meta.view v:id=isrj-349k v:category="Public Safety" v:attributionLink=http://www.nyc.gov/html/fdny/pdf/rules/repealed_fire_dept_rules_with_new_codes_2010-05-29.pdf v:averageRating=0 v:name="FDNY Repealed  Rules And Corresponding New Fire Code And Rules" v:attribution="Fire Department of New York City (FDNY)"

property e:isrj-349k t:meta.view.owner v:id=5fuc-pqz2 v:screenName="NYC OpenData" v:lastNotificationSeenAt=1491336998 v:displayName="NYC OpenData"

property e:isrj-349k t:meta.view.tableauthor v:id=syvn-4vgv v:screenName="Sudhir Vasudeva" v:displayName="Sudhir Vasudeva"
```

## Top Records

```ls
| :updated_at | repealed_rule_rcny_section | repealed_section_title                                                                   | new_code_fc_rule_r_section                                           | 
| =========== | ========================== | ======================================================================================== | ==================================================================== | 
| 1359620009  | 3 RCNY 1-01                | Tanks Used for Bulk Storage of Acids                                                     | FC Chapters 27 and 31 R4831-01(d)                                    | 
| 1359620009  | 3 RCNY 2-01                | Conduct of Adjudications                                                                 | R4900-01                                                             | 
| 1359620009  | 3 RCNY 3-01                | Permits for Portable Air Compressors                                                     | FC 105.6 and A03.1(14)                                               | 
| 1359620009  | 3 RCNY 3-02                | Definition of a Unit                                                                     | FC 105.6 And A03.1(14)                                               | 
| 1359620009  | 3 RCNY 3-03                | Test of Consolidated Con Edison Company Air Compressors and Air Compressor Systems       | FC 3001.4 and 3003.1                                                 | 
| 1359620009  | 3 RCNY 4-01                | Fire Protection of Automotive Salvage and Wrecking Establishments                        | FC316                                                                | 
| 1359620009  | 3 RCNY 5-01                | Fire Protection Of Boatyards, Marinas and Similar Occupancies                            | R301-01                                                              | 
| 1359620009  | 3 RCNY 6-01                | Fire Drill and Evacuation in Office Buildings Classified as Occupancy Group E (Business) | FC 113.4, 401, 404, 405 and 406 R 113-01, 113-02 and 404-01          | 
| 1359620009  | 3 RCNY 6-02                | Office Building Emergency Action Plans                                                   | FC 401, 404, 405 and 406 R 113-01, 113-02, 113-03, 404-01 and 404-02 | 
| 1359620009  | 3 RCNY 7-01                | Required Periodic Tests of Fire Extinguishing Systems in Bulk Oil Storage Systems        | FC3406.4.10.7                                                        | 
```