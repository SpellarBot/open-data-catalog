# DPW Street & Sidewalk Evaluation Results, 7-1-2013 to Present

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dpw-street-sidewalk-evaluation-results-raw-data-to-1-30-15) |
| Metadata | [Link](https://data.sfgov.org/api/views/83ki-hu3p) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/83ki-hu3p/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/83ki-hu3p/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 83ki-hu3p |
| Name | DPW Street & Sidewalk Evaluation Results, 7-1-2013 to Present |
| Category | City Infrastructure |
| Tags | controller's street evaluation program, street, sidewalk, inspection, evaluation, results, performance, graffiti, trash, tree, grime, leaks, spills, litter, street sweeping |
| Created | 2015-02-05T00:58:14Z |
| Publication Date | 2017-03-07T01:12:44Z |

## Description

The Controller's Office's City Services Auditor (CSA) Division has worked with the Department of Public Works (DPW) to develop maintenance standards for streets and sidewalks and schedules and inspect for compliance since July 2004. This data file contains street and sidewalk evaluation results since 7/1/2013 under the new FY12 standards.  Older evaluation results are also available on DataSF but are not comparable due to changes in the way the standards are calculated.You can also access the annual reports in PDF at "Street Maintenance" section of http://sfcontroller.org/index.aspx?page=49

## Columns

```ls
| Included | Schema Type    | Field Name                                                    | Name                                                           | Data Type     | Render Type   |
| ======== | ============== | ============================================================= | ============================================================== | ============= | ============= |
| Yes      | numeric metric | corridor                                                      | Corridor #                                                     | number        | number        |
| Yes      | series tag     | corridor_description                                          | Corridor Description                                           | text          | text          |
| Yes      | series tag     | corridor_num_and_description                                  | Corridor Num and Description                                   | text          | text          |
| No       |                | fy                                                            | FY                                                             | text          | text          |
| Yes      | series tag     | clean_corridor                                                | Clean Corridor                                                 | text          | text          |
| Yes      | series tag     | type                                                          | Type                                                           | text          | text          |
| Yes      | series tag     | detailed_type                                                 | Detailed Type                                                  | text          | text          |
| Yes      | series tag     | midpoint_times                                                | Midpoint times                                                 | text          | text          |
| Yes      | series tag     | side_of_street                                                | Side of street                                                 | text          | text          |
| Yes      | series tag     | supdistrict                                                   | SupDistrict                                                    | text          | number        |
| Yes      | series tag     | dpw_zone                                                      | DPW Zone                                                       | text          | text          |
| Yes      | series tag     | representative_street_segment                                 | Representative Street Segment                                  | text          | text          |
| Yes      | series tag     | cnn_route_id                                                  | CNN (Route ID)                                                 | text          | number        |
| Yes      | time           | evaluation_date                                               | Evaluation date                                                | calendar_date | calendar_date |
| Yes      | series tag     | evaluator_name                                                | Evaluator name                                                 | text          | text          |
| Yes      | series tag     | inspector                                                     | Inspector                                                      | text          | text          |
| Yes      | numeric metric | 11_score_10_20_or_30_score                                    | 11 Score (10, 20, or 30 score)                                 | number        | number        |
| Yes      | numeric metric | 21_litter_10_20_or_30_score                                   | 21 Litter (10, 20, or 30 score)                                | number        | number        |
| Yes      | numeric metric | 22_grime_leaks_spills_of_sidewalk_w_out                       | 22 Grime, Leaks, Spills (% of sidewalk w/out)                  | number        | number        |
| Yes      | numeric metric | 24_illegal_dumping_y_n_where_y_none                           | 24 Illegal Dumping (Y/N, where Y=none)                         | number        | number        |
| Yes      | numeric metric | 251_feces_needles_condoms_y_n_where_y_none                    | 251 Feces, Needles, Condoms (Y/N, where Y=none)                | number        | number        |
| Yes      | numeric metric | 252_broken_glass_y_n_where_y_none                             | 252 Broken Glass (Y/N, where Y=none)                           | number        | number        |
| Yes      | numeric metric | 26_odors_dpw                                                  | 26 Odors (DPW)                                                 | number        | number        |
| Yes      | numeric metric | 27_odors_nondpw                                               | 27 Odors (nonDPW)                                              | number        | number        |
| Yes      | numeric metric | 31_public_dpw                                                 | 31 Public (DPW)                                                | number        | number        |
| Yes      | numeric metric | 32_public_nondpw                                              | 32 Public (nonDPW)                                             | number        | number        |
| No       |                | 33_private_please_indicate_nearest_address_on_attached_work_s | 33 Private (Please indicate nearest address on attached work s | number        | number        |
| Yes      | numeric metric | 34_sidewalk_on_sidewalk_preiously_23                          | 34 Sidewalk (# on sidewalk, preiously 23)                      | number        | number        |
| Yes      | numeric metric | total_trash_receptacles                                       | Total # Trash Receptacles                                      | number        | number        |
| Yes      | numeric metric | 41_fullness                                                   | 41 Fullness                                                    | number        | number        |
| Yes      | numeric metric | 42_cleanliness_of_trash_receptacles                           | 42 Cleanliness of trash receptacles                            | number        | number        |
| Yes      | numeric metric | 43_cleanliness_around_trash_receptacles                       | 43 Cleanliness around trash receptacles                        | number        | number        |
| Yes      | numeric metric | 44_painting                                                   | 44 Painting                                                    | number        | number        |
| Yes      | numeric metric | 45_structural_integrity_function                              | 45 Structural integrity & function                             | number        | number        |
| Yes      | numeric metric | 46_doors                                                      | 46 Doors                                                       | number        | number        |
| Yes      | numeric metric | total_trees                                                   | Total # Trees                                                  | number        | number        |
| Yes      | numeric metric | 51_cleanliness                                                | 51 Cleanliness                                                 | number        | number        |
| Yes      | numeric metric | 52_tree_appearance                                            | 52 Tree Appearance                                             | number        | number        |
| Yes      | numeric metric | 53_weediness                                                  | 53 Weediness                                                   | number        | number        |
| Yes      | numeric metric | 54_clearance                                                  | 54 Clearance                                                   | number        | number        |
| Yes      | numeric metric | 11_pass                                                       | 11 pass                                                        | number        | number        |
| Yes      | numeric metric | 21_pass                                                       | 21 Pass                                                        | number        | number        |
| Yes      | numeric metric | 22_pass                                                       | 22 Pass                                                        | number        | number        |
| Yes      | numeric metric | 31_pass                                                       | 31 Pass                                                        | number        | number        |
| Yes      | numeric metric | 32_pass                                                       | 32 Pass                                                        | number        | number        |
| Yes      | numeric metric | 33_pass                                                       | 33 Pass                                                        | number        | number        |
| Yes      | numeric metric | 34_pass                                                       | 34 Pass                                                        | number        | number        |
| Yes      | numeric metric | 41_pass                                                       | 41 Pass                                                        | number        | number        |
| Yes      | numeric metric | 42_pass                                                       | 42 Pass                                                        | number        | number        |
| Yes      | numeric metric | 43_pass                                                       | 43 Pass                                                        | number        | number        |
| Yes      | numeric metric | 44_pass                                                       | 44 Pass                                                        | number        | number        |
| Yes      | numeric metric | 45_pass                                                       | 45 Pass                                                        | number        | number        |
| Yes      | numeric metric | 46_pass                                                       | 46 Pass                                                        | number        | number        |
| Yes      | numeric metric | 51_pass                                                       | 51 Pass                                                        | number        | number        |
| Yes      | numeric metric | 52_pass                                                       | 52 Pass                                                        | number        | number        |
| Yes      | numeric metric | 53_pass                                                       | 53 Pass                                                        | number        | number        |
| Yes      | numeric metric | 54_pass                                                       | 54 Pass                                                        | number        | number        |
| Yes      | series tag     | priority                                                      | Priority                                                       | text          | text          |
```

## Time Field

```ls
Value = evaluation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = fy,33_private_please_indicate_nearest_address_on_attached_work_s
```

## Data Commands

```ls
series e:83ki-hu3p d:2017-03-07T01:10:54.000Z t:midpoint_times="Mon 12PM to 5PM" t:detailed_type=Commercial t:side_of_street=R t:inspector=JBR t:representative_street_segment="Mission St  :  Hwy 101 Northbound  -  Erie St" t:cnn_route_id=9112101 t:priority=Regular t:corridor_num_and_description="#1 Mission A: 18th - 13th" t:clean_corridor="Clean Corridor" t:corridor_description="Mission A: 18th - 13th" t:supdistrict=9 t:type=Commercial t:dpw_zone=D m:44_painting=0.83333333333 m:31_pass=0 m:251_feces_needles_condoms_y_n_where_y_none=0 m:46_pass=1 m:51_pass=0 m:43_pass=0 m:corridor=1 m:11_score_10_20_or_30_score=1.75714285714286 m:44_pass=0 m:24_illegal_dumping_y_n_where_y_none=1 m:45_structural_integrity_function=1 m:32_pass=0 m:31_public_dpw=0.0619 m:22_grime_leaks_spills_of_sidewalk_w_out=0.686190476190476 m:54_pass=1 m:252_broken_glass_y_n_where_y_none=1 m:33_pass=0 m:51_cleanliness=0.202884615384615 m:52_tree_appearance=1 m:21_pass=1 m:26_odors_dpw=0 m:54_clearance=1 m:53_pass=1 m:22_pass=0 m:52_pass=1 m:41_pass=1 m:42_cleanliness_of_trash_receptacles=1 m:42_pass=1 m:32_public_nondpw=0.242857142857143 m:27_odors_nondpw=0 m:11_pass=1 m:53_weediness=0.964285714285714 m:21_litter_10_20_or_30_score=1.7 m:34_sidewalk_on_sidewalk_preiously_23=0.257142857142857 m:34_pass=0 m:46_doors=1 m:41_fullness=1 m:43_cleanliness_around_trash_receptacles=0.66666666667 m:45_pass=1

series e:83ki-hu3p d:2017-03-07T01:10:54.000Z t:midpoint_times="Mon 12PM to 5PM" t:detailed_type=Commercial t:side_of_street=R t:inspector=JBR t:representative_street_segment="Mission St  :  Hwy 101 Northbound  -  Erie St" t:cnn_route_id=9112101 t:priority=Regular t:corridor_num_and_description="#1 Mission A: 18th - 13th" t:clean_corridor="Clean Corridor" t:corridor_description="Mission A: 18th - 13th" t:supdistrict=9 t:type=Commercial t:dpw_zone=D m:44_painting=1 m:31_pass=0 m:251_feces_needles_condoms_y_n_where_y_none=0 m:46_pass=1 m:51_pass=1 m:43_pass=1 m:corridor=1 m:11_score_10_20_or_30_score=1.95 m:44_pass=1 m:24_illegal_dumping_y_n_where_y_none=0 m:45_structural_integrity_function=1 m:32_pass=0 m:31_public_dpw=0.55 m:22_grime_leaks_spills_of_sidewalk_w_out=0.9975 m:54_pass=1 m:252_broken_glass_y_n_where_y_none=1 m:33_pass=0 m:51_cleanliness=0.966666666666667 m:52_tree_appearance=1 m:21_pass=1 m:26_odors_dpw=1 m:54_clearance=1 m:53_pass=1 m:22_pass=1 m:52_pass=1 m:41_pass=1 m:42_cleanliness_of_trash_receptacles=1 m:42_pass=1 m:32_public_nondpw=1.6 m:27_odors_nondpw=1 m:11_pass=1 m:53_weediness=1 m:21_litter_10_20_or_30_score=1.35 m:34_sidewalk_on_sidewalk_preiously_23=2.15 m:34_pass=0 m:46_doors=1 m:41_fullness=1 m:43_cleanliness_around_trash_receptacles=1 m:45_pass=1

series e:83ki-hu3p d:2017-03-07T01:10:54.000Z t:midpoint_times="Thu 12PM to 5PM" t:detailed_type=Residential/Public t:side_of_street=L t:inspector=JBR t:representative_street_segment="Larkin St  :  O'Farrell St  -  Myrtle St" t:cnn_route_id=8130000 t:priority=Regular t:corridor_num_and_description="#10 Larkin: O'Farrell - Sacramento" t:clean_corridor="Clean Corridor" t:corridor_description="Larkin: O'Farrell - Sacramento" t:supdistrict=6 t:type=Commercial t:dpw_zone=B m:44_painting=1 m:31_pass=0 m:251_feces_needles_condoms_y_n_where_y_none=0 m:46_pass=1 m:51_pass=0 m:43_pass=1 m:corridor=10 m:11_score_10_20_or_30_score=2.78571428571429 m:44_pass=1 m:24_illegal_dumping_y_n_where_y_none=0 m:45_structural_integrity_function=1 m:32_pass=0 m:31_public_dpw=1.21 m:22_grime_leaks_spills_of_sidewalk_w_out=0.988571428571429 m:54_pass=1 m:252_broken_glass_y_n_where_y_none=0 m:33_pass=0 m:51_cleanliness=0.572222222222222 m:52_tree_appearance=0.844444444444444 m:21_pass=1 m:26_odors_dpw=1 m:54_clearance=0.922222222222222 m:53_pass=1 m:22_pass=1 m:52_pass=0 m:41_pass=1 m:42_cleanliness_of_trash_receptacles=1 m:42_pass=1 m:32_public_nondpw=5.86 m:27_odors_nondpw=1 m:11_pass=0 m:53_weediness=1 m:21_litter_10_20_or_30_score=1.85714285714286 m:34_sidewalk_on_sidewalk_preiously_23=1.36 m:34_pass=0 m:46_doors=1 m:41_fullness=1 m:43_cleanliness_around_trash_receptacles=1 m:45_pass=1
```

## Meta Commands

```ls
metric m:corridor p:integer l:"Corridor #" t:dataTypeName=number

metric m:11_score_10_20_or_30_score p:double l:"11 Score (10, 20, or 30 score)" t:dataTypeName=number

metric m:21_litter_10_20_or_30_score p:double l:"21 Litter (10, 20, or 30 score)" t:dataTypeName=number

metric m:22_grime_leaks_spills_of_sidewalk_w_out p:double l:"22 Grime, Leaks, Spills (% of sidewalk w/out)" t:dataTypeName=number

metric m:24_illegal_dumping_y_n_where_y_none p:integer l:"24 Illegal Dumping (Y/N, where Y=none)" t:dataTypeName=number

metric m:251_feces_needles_condoms_y_n_where_y_none p:integer l:"251 Feces, Needles, Condoms (Y/N, where Y=none)" t:dataTypeName=number

metric m:252_broken_glass_y_n_where_y_none p:integer l:"252 Broken Glass (Y/N, where Y=none)" t:dataTypeName=number

metric m:26_odors_dpw p:integer l:"26 Odors (DPW)" t:dataTypeName=number

metric m:27_odors_nondpw p:integer l:"27 Odors (nonDPW)" t:dataTypeName=number

metric m:31_public_dpw p:float l:"31 Public (DPW)" t:dataTypeName=number

metric m:32_public_nondpw p:double l:"32 Public (nonDPW)" t:dataTypeName=number

metric m:34_sidewalk_on_sidewalk_preiously_23 p:decimal l:"34 Sidewalk (# on sidewalk, preiously 23)" t:dataTypeName=number

metric m:total_trash_receptacles p:integer l:"Total # Trash Receptacles" t:dataTypeName=number

metric m:41_fullness p:double l:"41 Fullness" t:dataTypeName=number

metric m:42_cleanliness_of_trash_receptacles p:double l:"42 Cleanliness of trash receptacles" t:dataTypeName=number

metric m:43_cleanliness_around_trash_receptacles p:double l:"43 Cleanliness around trash receptacles" t:dataTypeName=number

metric m:44_painting p:double l:"44 Painting" t:dataTypeName=number

metric m:45_structural_integrity_function p:double l:"45 Structural integrity & function" t:dataTypeName=number

metric m:46_doors p:double l:"46 Doors" t:dataTypeName=number

metric m:total_trees p:integer l:"Total # Trees" t:dataTypeName=number

metric m:51_cleanliness p:double l:"51 Cleanliness" t:dataTypeName=number

metric m:52_tree_appearance p:float l:"52 Tree Appearance" t:dataTypeName=number

metric m:53_weediness p:double l:"53 Weediness" t:dataTypeName=number

metric m:54_clearance p:float l:"54 Clearance" t:dataTypeName=number

metric m:11_pass p:integer l:"11 pass" t:dataTypeName=number

metric m:21_pass p:integer l:"21 Pass" t:dataTypeName=number

metric m:22_pass p:integer l:"22 Pass" t:dataTypeName=number

metric m:31_pass p:integer l:"31 Pass" t:dataTypeName=number

metric m:32_pass p:integer l:"32 Pass" t:dataTypeName=number

metric m:33_pass p:integer l:"33 Pass" t:dataTypeName=number

metric m:34_pass p:integer l:"34 Pass" t:dataTypeName=number

metric m:41_pass p:integer l:"41 Pass" t:dataTypeName=number

metric m:42_pass p:integer l:"42 Pass" t:dataTypeName=number

metric m:43_pass p:integer l:"43 Pass" t:dataTypeName=number

metric m:44_pass p:integer l:"44 Pass" t:dataTypeName=number

metric m:45_pass p:integer l:"45 Pass" t:dataTypeName=number

metric m:46_pass p:integer l:"46 Pass" t:dataTypeName=number

metric m:51_pass p:integer l:"51 Pass" t:dataTypeName=number

metric m:52_pass p:integer l:"52 Pass" t:dataTypeName=number

metric m:53_pass p:integer l:"53 Pass" t:dataTypeName=number

metric m:54_pass p:integer l:"54 Pass" t:dataTypeName=number

entity e:83ki-hu3p l:"DPW Street & Sidewalk Evaluation Results, 7-1-2013 to Present" t:url=https://data.sfgov.org/api/views/83ki-hu3p

property e:83ki-hu3p t:meta.view v:id=83ki-hu3p v:category="City Infrastructure" v:averageRating=0 v:name="DPW Street & Sidewalk Evaluation Results, 7-1-2013 to Present"

property e:83ki-hu3p t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:83ki-hu3p t:meta.view.owner v:id=99ku-nz3k v:screenName="Sherman Luk, CBIP" v:displayName="Sherman Luk, CBIP"

property e:83ki-hu3p t:meta.view.tableauthor v:id=99ku-nz3k v:screenName="Sherman Luk, CBIP" v:roleName=editor v:displayName="Sherman Luk, CBIP"
```

## Top Records

```ls
| corridor | corridor_description                      | corridor_num_and_description                   | fy      | clean_corridor | type       | detailed_type          | midpoint_times  | side_of_street | supdistrict | dpw_zone | representative_street_segment             | cnn_route_id | evaluation_date | evaluator_name | inspector | 11_score_10_20_or_30_score | 21_litter_10_20_or_30_score | 22_grime_leaks_spills_of_sidewalk_w_out | 24_illegal_dumping_y_n_where_y_none | 251_feces_needles_condoms_y_n_where_y_none | 252_broken_glass_y_n_where_y_none | 26_odors_dpw | 27_odors_nondpw | 31_public_dpw | 32_public_nondpw    | 33_private_please_indicate_nearest_address_on_attached_work_s | 34_sidewalk_on_sidewalk_preiously_23 | total_trash_receptacles | 41_fullness | 42_cleanliness_of_trash_receptacles | 43_cleanliness_around_trash_receptacles | 44_painting         | 45_structural_integrity_function | 46_doors | total_trees | 51_cleanliness      | 52_tree_appearance  | 53_weediness        | 54_clearance        | 11_pass | 21_pass | 22_pass | 31_pass | 32_pass | 33_pass | 34_pass | 41_pass | 42_pass | 43_pass | 44_pass | 45_pass | 46_pass | 51_pass | 52_pass | 53_pass | 54_pass | priority | 
| ======== | ========================================= | ============================================== | ======= | ============== | ========== | ====================== | =============== | ============== | =========== | ======== | ========================================= | ============ | =============== | ============== | ========= | ========================== | =========================== | ======================================= | =================================== | ========================================== | ================================= | ============ | =============== | ============= | =================== | ============================================================= | ==================================== | ======================= | =========== | =================================== | ======================================= | =================== | ================================ | ======== | =========== | =================== | =================== | =================== | =================== | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======= | ======== | 
| 1        | Mission A: 18th - 13th                    | #1 Mission A: 18th - 13th                      | 2013-14 | Clean Corridor | Commercial | Commercial             | Mon 12PM to 5PM | R              | 9           | D        | Mission St : Hwy 101 Northbound - Erie St | 9112101      |                 |                | JBR       | 1.75714285714286           | 1.7                         | 0.68619047619047602                     | 1                                   | 0                                          | 1                                 | 0            | 0               | 0.0619        | 0.24285714285714299 | 0.27619047619047599                                           | 0.25714285714285701                  |                         | 1           | 1                                   | 0.66666666666999996                     | 0.83333333333000004 | 1                                | 1        |             | 0.202884615384615   | 1                   | 0.96428571428571397 | 1                   | 1       | 1       | 0       | 0       | 0       | 0       | 0       | 1       | 1       | 0       | 0       | 1       | 1       | 0       | 1       | 1       | 1       | Regular  | 
| 1        | Mission A: 18th - 13th                    | #1 Mission A: 18th - 13th                      | 2013-14 | Clean Corridor | Commercial | Commercial             | Mon 12PM to 5PM | R              | 9           | D        | Mission St : Hwy 101 Northbound - Erie St | 9112101      |                 |                | JBR       | 1.95                       | 1.35                        | 0.99750000000000005                     | 0                                   | 0                                          | 1                                 | 1            | 1               | 0.55          | 1.60                | 4.50                                                          | 2.15                                 |                         | 1           | 1                                   | 1                                       | 1                   | 1                                | 1        |             | 0.96666666666666701 | 1                   | 1                   | 1                   | 1       | 1       | 1       | 0       | 0       | 0       | 0       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | 1       | Regular  | 
| 10       | Larkin: O'Farrell - Sacramento            | #10 Larkin: O'Farrell - Sacramento             | 2013-14 | Clean Corridor | Commercial | Residential/Public     | Thu 12PM to 5PM | L              | 6           | B        | Larkin St : O'Farrell St - Myrtle St      | 8130000      |                 |                | JBR       | 2.78571428571429           | 1.8571428571428601          | 0.98857142857142899                     | 0                                   | 0                                          | 0                                 | 1            | 1               | 1.21          | 5.86                | 1.64                                                          | 1.36                                 |                         | 1           | 1                                   | 1                                       | 1                   | 1                                | 1        |             | 0.57222222222222197 | 0.844444444444444   | 1                   | 0.92222222222222205 | 0       | 1       | 1       | 0       | 0       | 0       | 0       | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0       | 1       | 1       | Regular  | 
| 10       | Larkin: O'Farrell - Sacramento            | #10 Larkin: O'Farrell - Sacramento             | 2013-14 | Clean Corridor | Commercial | Residential/Public     | Thu 12PM to 5PM | L              | 6           | B        | Larkin St : O'Farrell St - Myrtle St      | 8130000      |                 |                | JBR       | 3                          | 2.5                         | 0.74404761904761896                     | 0                                   | 1                                          | 1                                 | 0            | 1               | 0.0476        | 0.76190476190476197 | 0.16666666666666699                                           | 0.28571428571428598                  |                         | 0.5         | 0.5                                 | 0.5                                     | 0.5                 | 0.5                              | 0.5      |             | 0.36111111111111099 | 0.91666666666666696 | 0.91666666666666696 | 0.91666666666666696 | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 0       | 1       | 1       | 1       | Regular  | 
| 100      | Fillmore F: McAllister, Steiner - Laguna  | #100 Fillmore F: McAllister, Steiner - Laguna  | 2013-14 |                | Commercial | Residential/Commercial | Mon 8AM to 12PM | L              | 5           | C        | McAllister St : Laguna St - Webster St    | 8898000      |                 |                | JBR       | 1.5833333333333299         | 1.1666666666666701          | 0.9375                                  | 1                                   | 0                                          | 1                                 | 1            | 0               | 0.17          | 0.75                | 0.00                                                          | 0.92                                 |                         | 1           | 1                                   | 1                                       | 1                   | 1                                | 1        |             | 0.62647352647352705 | 0.95227272727272705 | 0.84512987012986995 | 0.95227272727272705 | 1       | 1       | 1       | 0       | 0       | 1       | 0       | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 1       | 0       | 1       | Regular  | 
| 100      | Fillmore F: McAllister, Steiner - Laguna  | #100 Fillmore F: McAllister, Steiner - Laguna  | 2013-14 |                | Commercial | Residential/Commercial | Mon 8AM to 12PM | L              | 5           | C        | McAllister St : Laguna St - Webster St    | 8898000      |                 |                | JBR       | 1.6666666666666701         | 1.25                        | 0.9375                                  | 1                                   | 0                                          | 0                                 | 1            | 0               | 0.00          | 0.79                | 0.00                                                          | 1.63                                 |                         | 1           | 1                                   | 0.5                                     | 1                   | 1                                | 1        |             | 0.64068431568431605 | 0.95227272727272705 | 0.85811688311688294 | 0.91655844155844202 | 1       | 1       | 1       | 1       | 0       | 1       | 0       | 1       | 1       | 0       | 1       | 1       | 1       | 0       | 1       | 0       | 1       | Regular  | 
| 101      | Fillmore G: Golden Gate, Steiner - Laguna | #101 Fillmore G: Golden Gate, Steiner - Laguna | 2013-14 |                | Commercial | Residential            | Mon 8AM to 12PM | R              | 5           | C        | Golden Gate Ave : Laguna St - Webster St  | 6269000      |                 |                | JBR       | 2.1666666666666701         | 2.0833333333333299          | 0.9                                     | 1                                   | 0                                          | 1                                 | 1            | 0               | 0.00          | 0.58                | 0.08                                                          | 0.75                                 |                         | 1           | 1                                   | 1                                       | 1                   | 1                                | 1        |             | 0.55000000000000004 | 0.875               | 0.82916666666666705 | 0.875               | 0       | 0       | 1       | 1       | 0       | 0       | 0       | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0       | 0       | 0       | Regular  | 
| 101      | Fillmore G: Golden Gate, Steiner - Laguna | #101 Fillmore G: Golden Gate, Steiner - Laguna | 2013-14 |                | Commercial | Residential            | Mon 8AM to 12PM | R              | 5           | C        | Golden Gate Ave : Laguna St - Webster St  | 6269000      |                 |                | JBR       | 2                          | 1.25                        | 0.87916666666666698                     | 1                                   | 0                                          | 0                                 | 1            | 0               | 0.375         | 1.0416666666666701  | 0                                                             | 0.75                                 |                         | 1           | 1                                   | 1                                       | 1                   | 1                                | 1        |             | 0.55959595959595998 | 0.85                | 0.83838383838383801 | 0.81111111111111101 | 0       | 1       | 0       | 0       | 0       | 1       | 0       | 1       | 1       | 1       | 1       | 1       | 1       | 0       | 0       | 0       | 0       | Regular  | 
| 102      | Fillmore H: along Post                    | #102 Fillmore H: along Post                    | 2013-14 |                | Commercial | Commercial             | Tue 12PM to 5PM | L              | 5           | C        | Post St : Buchanan St - Webster St        | 10645000     |                 |                | JBR       | 1.7916666666666701         | 1.5                         | 0.99333333333333296                     | 1                                   | 0                                          | 0                                 | 1            | 1               | 0.17          | 0.67                | 0.58                                                          | 0.42                                 |                         | 1           | 1                                   | 0.75                                    | 1                   | 1                                | 1        |             | 0.85241147741147705 | 1                   | 1                   | 1                   | 1       | 1       | 1       | 0       | 0       | 0       | 0       | 1       | 1       | 0       | 1       | 1       | 1       | 0       | 1       | 1       | 1       | Regular  | 
| 102      | Fillmore H: along Post                    | #102 Fillmore H: along Post                    | 2013-14 |                | Commercial | Commercial             | Tue 12PM to 5PM | L              | 5           | C        | Post St : Buchanan St - Webster St        | 10645000     |                 |                | JBR       | 3                          | 1.875                       | 0.86750000000000005                     | 1                                   | 1                                          | 0                                 | 1            | 1               | 0             | 0                   | 0                                                             | 0.15                                 |                         | 0.75        | 1                                   | 1                                       | 1                   | 1                                | 1        |             | 0.307142857142857   | 1                   | 0.82976190476190503 | 1                   | 0       | 1       | 0       | 1       | 1       | 1       | 0       | 0       | 1       | 1       | 1       | 1       | 1       | 0       | 1       | 0       | 1       | Regular  | 
```