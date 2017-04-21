# Jackson List Of Capital Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-list-of-capital-projects) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/cay5-ipen) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/cay5-ipen/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/cay5-ipen/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | cay5-ipen |
| Name | Jackson List Of Capital Projects |
| Attribution | City of Jackson Public Works |
| Tags | infrastructure, roads, bridge, drainage, paving, capital, project |
| Created | 2016-11-30T21:39:37Z |
| Publication Date | 2017-03-13T16:58:33Z |

## Description

Information about the budget, spending, schedule, and status for City of Jackson capital projects.

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | project_id                   | Project ID                   | text          | text          |
| Yes      | series tag     | project_name                 | Project Name                 | text          | text          |
| Yes      | series tag     | project_description          | Project Description          | text          | text          |
| Yes      | numeric metric | budget                       | Budget                       | money         | money         |
| Yes      | numeric metric | amount_spent                 | Amount Spent                 | money         | money         |
| Yes      | series tag     | project_stage                | Project Stage                | text          | text          |
| Yes      | series tag     | website                      | Website                      | text          | text          |
| Yes      | series tag     | ward                         | Ward                         | text          | text          |
| Yes      | series tag     | project_category             | Project Category             | text          | text          |
| Yes      | series tag     | budget_indicator             | Budget Indicator             | text          | text          |
| Yes      | series tag     | budget_indicator_narrative   | Budget Indicator Narrative   | text          | text          |
| Yes      | series tag     | schedule_indicator           | Schedule Indicator           | text          | text          |
| Yes      | series tag     | schedule_indicator_narrative | Schedule Indicator Narrative | text          | text          |
| No       |                | design_completion_date       | Design Completion Date       | calendar_date | calendar_date |
| No       |                | construction_completion_date | Construction Completion Date | calendar_date | calendar_date |
| No       |                | project_start_optional_field | Project Start                | calendar_date | calendar_date |
| No       |                | project_end_optional_field   | Project End                  | calendar_date | calendar_date |
| Yes      | series tag     | project_design_consultant    | Project Design / Consultant  | text          | text          |
| Yes      | series tag     | project_contractor           | Project Contractor           | text          | text          |
| Yes      | series tag     | funding_source_s             | Funding Source(s)            | text          | text          |
| Yes      | series tag     | additional_comments          | Additional Comments          | text          | text          |
| Yes      | time           | data_update_date             | Data Update Date             | calendar_date | calendar_date |
| Yes      | series tag     | project_image                | project image                | text          | text          |
```

## Time Field

```ls
Value = data_update_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = construction_completion_date,design_completion_date,project_end_optional_field,project_start_optional_field
```

## Data Commands

```ls
series e:cay5-ipen d:2017-02-13T15:00:39.000Z t:budget_indicator_narrative="Project is on budget" t:project_name="McDowell Road" t:budget_indicator=green t:ward=5 t:schedule_indicator=green t:project_id=BR-08 t:schedule_indicator_narrative="Project is on schedule" t:project_stage=Planning t:project_category=Bridges t:project_description="The project is located between suncrest Dr and Greenway Ct. Realignment of existing roadway is needed. Water, sewer line and rail replacement is needed." m:budget=110000

series e:cay5-ipen d:2016-08-02T00:00:00.000Z t:funding_source_s="Special Municipal Sales Tax" t:budget_indicator_narrative="Project is on budget" t:project_name="John R. Lynch Street" t:budget_indicator=green t:ward=5 t:schedule_indicator=green t:project_id=ST-04 t:schedule_indicator_narrative="Project is on schedule" t:project_stage=Planning t:project_image=https://capitalprojects.jacksonms.gov/views/istu-jygi/files/71ad82f9-4727-4ff2-8d02-2cd9f995d053 t:project_design_consultant="To be Decided" t:project_category=Streets m:budget=122000

series e:cay5-ipen d:2016-08-02T00:00:00.000Z t:budget_indicator=green t:project_name="Hanging Moss Road" t:schedule_indicator=green t:schedule_indicator_narrative="Project is on schedule" t:project_category=Bridges t:project_design_consultant=CiViLTech t:project_image=https://capitalprojects.jacksonms.gov/views/istu-jygi/files/0b5854d9-b098-47af-a970-6763e6f3d719 t:project_description="The proposed project will repair the bridge located on Hanging Moss Road, and the tributary of Hanging Moss Creek. Major activity includes replacing the bridge with a structure that meets or exceeds the substandard load carrying capacity. This bridge received a sufficiency rating of 9 out of 100 during a recent MDOT State Aid inspection." t:budget_indicator_narrative="Project is on budget" t:funding_source_s="Special Municipal Sales Tax" t:project_contractor=UCI t:ward=2 t:project_id=BR-01 t:project_stage=Completed m:budget=395000 m:amount_spent=362765.29
```

## Meta Commands

```ls
metric m:budget p:integer l:Budget d:"Dollar amount budgeted for this capital project" t:dataTypeName=money

metric m:amount_spent p:double l:"Amount Spent" d:"Amount of budget that has been spent to date on this capital project" t:dataTypeName=money

entity e:cay5-ipen l:"Jackson List Of Capital Projects" t:attribution="City of Jackson Public Works" t:url=https://data.jacksonms.gov/api/views/cay5-ipen

property e:cay5-ipen t:meta.view v:id=cay5-ipen v:averageRating=0 v:name="Jackson List Of Capital Projects" v:attribution="City of Jackson Public Works"

property e:cay5-ipen t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:cay5-ipen t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| project_id | project_name          | project_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | budget | amount_spent | project_stage | website | ward | project_category | budget_indicator | budget_indicator_narrative | schedule_indicator | schedule_indicator_narrative | design_completion_date | construction_completion_date | project_start_optional_field | project_end_optional_field | project_design_consultant | project_contractor | funding_source_s            | additional_comments | data_update_date    | project_image                                                                                    | 
| ========== | ===================== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | ====== | ============ | ============= | ======= | ==== | ================ | ================ | ========================== | ================== | ============================ | ====================== | ============================ | ============================ | ========================== | ========================= | ================== | =========================== | =================== | =================== | ================================================================================================ | 
| BR-08      | McDowell Road         | The project is located between suncrest Dr and Greenway Ct. Realignment of existing roadway is needed. Water, sewer line and rail replacement is needed.                                                                                                                                                                                                                                                                                                                                 | 110000 |              | Planning      |         | 5    | Bridges          | green            | Project is on budget       | green              | Project is on schedule       |                        |                              |                              |                            |                           |                    |                             |                     |                     |                                                                                                  | 
| ST-04      | John R. Lynch Street  |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 122000 |              | Planning      |         | 5    | Streets          | green            | Project is on budget       | green              | Project is on schedule       |                        |                              |                              |                            | To be Decided             |                    | Special Municipal Sales Tax |                     | 2016-08-02T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/71ad82f9-4727-4ff2-8d02-2cd9f995d053 | 
| BR-01      | Hanging Moss Road     | The proposed project will repair the bridge located on Hanging Moss Road, and the tributary of Hanging Moss Creek. Major activity includes replacing the bridge with a structure that meets or exceeds the substandard load carrying capacity. This bridge received a sufficiency rating of 9 out of 100 during a recent MDOT State Aid inspection.                                                                                                                                      | 395000 | 362765.29    | Completed     |         | 2    | Bridges          | green            | Project is on budget       | green              | Project is on schedule       |                        | 2016-06-13T00:00:00          | 2015-11-17T00:00:00          | 2016-06-13T00:00:00        | CiViLTech                 | UCI                | Special Municipal Sales Tax |                     | 2016-08-02T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/0b5854d9-b098-47af-a970-6763e6f3d719 | 
| BR-02      | Country Club Drive    | The proposed project will repair the bridge located on Country Club Drive above Lynch Creek. Major activity include replacing the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating less than 40 out of 100 during a recent MDOT State Aid inspection.                                                                                                                                                         | 45000  |              | Design        |         | 4    | Bridges          | green            | Project is on budget       | green              | Project is on schedule       | 2017-02-22T00:00:00    |                              | 2016-09-21T00:00:00          | 2017-02-22T00:00:00        | EJES                      |                    | Special Municipal Sales Tax |                     | 2016-10-21T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/71ad82f9-4727-4ff2-8d02-2cd9f995d053 | 
| BR-03      | Robinson Road         | The proposed project will repair the bridge located on Robinson Road above Caney Creek. Major activity includes replacing the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating less than 50 out of 100 during a recent MDOT State Aid inspection.                                                                                                                                                             | 167002 | 5061.57      | Design        |         | 4,5  | Bridges          | green            | Project is on budget       | green              | Project is on schedule       | 2016-12-30T00:00:00    |                              | 2016-06-14T00:00:00          |                            | Volkert, Inc.             |                    | Special Municipal Sales Tax |                     | 2016-10-21T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/71ad82f9-4727-4ff2-8d02-2cd9f995d054 | 
| BR-04      | Alta Woods Boulevard  | The proposed project will repair the bridge located on Alta Woods Boulevard above Small Stream. Major activity includes the replacement of the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating of 41 out of 100 during a recent MDOT State Aid inspection.                                                                                                                                                   | 78000  |              | Planning      |         | 5    | Bridges          | green            | Project is on budget       | green              | Project is on schedule       |                        |                              |                              |                            | CiViLTech                 |                    | Special Municipal Sales Tax |                     | 2016-08-02T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/71ad82f9-4727-4ff2-8d02-2cd9f995d055 | 
| BR-06      | Mayes Street Bridge   | The proposed project is a design and construction for replacing the Mayes Street Bridge over the CN Railway in Jackson, Mississippi. The intersection of Mayes Street and West St will be evaluated based on possible grade changes and for any necessary improvements. The traffic signal at this intersection will be evaluated for any necessary upgrades. Roadway lighting will be required on the bridge. Access to businesses will also be evaluated in the roadway design process | 877600 |              | Design        |         | 7    | Bridges          | green            | Project is on budget       | green              | Project is on schedule       | 2018-03-01T00:00:00    |                              | 2016-09-10T00:00:00          |                            | Micheal Baker             |                    | Special Municipal Sales Tax |                     | 2016-08-02T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/71ad82f9-4727-4ff2-8d02-2cd9f995d057 | 
| BR-07      | West Street/Southaven | The West Street Bridge over Towne Creek in Ward 7 was closed in Mid-December 2015 due to erosion and structural damage.  Three months later it had even more damage after a rain storm moved through the area.                                                                                                                                                                                                                                                                           | 110000 |              | Design        |         | 7    | Bridges          | green            | Project is on budget       | green              | Project is on schedule       | 2017-12-21T00:00:00    |                              |                              |                            | Stantec                   |                    | Special Municipal Sales Tax |                     | 2017-02-02T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/7b8bd946-bf97-4eec-8e7e-c41b2f05f5dc | 
| DR-01      | Beechcrest Drive      | To improve 3200 feet of drainage starting at the east of Beechcrest Drive where Purple Creek intersects with a major tributary and extends upstream along Purple Creek to Old Canton Road. Embankment solutions will be used to improve the drainage which is currently causing severe erosion resulting in property loss.                                                                                                                                                               | 78900  |              | Planning      |         | 1    | Drainage         | green            | Project is on budget       | green              | Project is on schedule       |                        |                              |                              |                            |                           |                    | Special Municipal Sales Tax |                     | 2016-08-02T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/7b8bd946-bf97-4eec-8e7e-c41b2f05f5dc | 
| DR-02      | North Canton Club     | Due to erosion, there is limited access and egress in the North Canton Club area. To combat this, a combination of erosion methods such as rock and vegetation along with a new piping system can be used to help slow down storm water runoff. The proposed project will improve the drainage system along North Canton Club for an estimated linear footage of 3100 feet.                                                                                                              | 124000 |              | Planning      |         | 1    | Drainage         | green            | Project is on budget       | green              | Project is on schedule       |                        |                              |                              |                            |                           |                    | Special Municipal Sales Tax |                     | 2016-08-02T00:00:00 | https://capitalprojects.jacksonms.gov/views/istu-jygi/files/232d482b-172c-4737-86f0-2aabecf7b892 | 
```