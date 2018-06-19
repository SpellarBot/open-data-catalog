# Jackson Capital Budget

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/jackson-capital-budget) |
| Metadata | [Link](https://data.jacksonms.gov/api/views/gm3p-a6ku) |
| Data: JSON | [100 Rows](https://data.jacksonms.gov/api/views/gm3p-a6ku/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.jacksonms.gov/api/views/gm3p-a6ku/rows.csv?max_rows=100) |
| Host | data.jacksonms.gov |
| Id | gm3p-a6ku |
| Name | Jackson Capital Budget |
| Category | Public Works |
| Created | 2016-12-22T17:07:07Z |
| Publication Date | 2016-12-22T17:26:03Z |

## Description

Budget data that describes the Projects and Phases of the Infrastructure Master Plan.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | time           | fiscal_year         | Fiscal Year         | number    | number      |
| Yes      | series tag     | service             | Service             | text      | text        |
| Yes      | series tag     | department          | Department          | text      | text        |
| Yes      | series tag     | project             | Project             | text      | text        |
| Yes      | series tag     | project_category    | Project Category    | text      | text        |
| Yes      | series tag     | project_name        | Project Name        | text      | text        |
| Yes      | series tag     | project_id          | Project ID          | text      | text        |
| Yes      | series tag     | project_description | Project Description | text      | text        |
| Yes      | numeric metric | budgeted_amount     | Budgeted Amount     | money     | money       |
| Yes      | numeric metric | amount_spent        | Amount Spent        | money     | money       |
| Yes      | series tag     | funding_source_s    | Funding Source(s)   | text      | text        |
```

## Time Field

```ls
Value = fiscal_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:gm3p-a6ku d:2016-01-01T00:00:00.000Z t:funding_source_s="Special Municipal Sales Tax" t:project="Infrastructure Master Plan" t:project_name="John R. Lynch Street" t:department="Public Works" t:project_id=ST-04 t:project_category=Streets t:service="Infrastructure Improvement" m:budgeted_amount=122000

series e:gm3p-a6ku d:2016-01-01T00:00:00.000Z t:funding_source_s="Special Municipal Sales Tax" t:project="Infrastructure Master Plan" t:project_name="Drainage Study" t:department="Public Works" t:project_id=DR-16 t:project_category=Drainage t:service="Infrastructure Improvement" m:budgeted_amount=375000

series e:gm3p-a6ku d:2016-01-01T00:00:00.000Z t:funding_source_s="Special Municipal Sales Tax" t:project="Infrastructure Master Plan" t:project_name="Hanging Moss Road" t:department="Public Works" t:project_id=BR-01 t:project_category=Bridges t:service="Infrastructure Improvement" t:project_description="The proposed project will repair the bridge located on Hanging Moss Road, and the tributary of Hanging Moss Creek. Major activity includes replacing the bridge with a structure that meets or exceeds the substandard load carrying capacity. This bridge received a sufficiency rating of 9 out of 100 during a recent MDOT State Aid inspection." m:budgeted_amount=395000 m:amount_spent=362765.29
```

## Meta Commands

```ls
metric m:budgeted_amount p:integer l:"Budgeted Amount" t:dataTypeName=money

metric m:amount_spent p:double l:"Amount Spent" t:dataTypeName=money

entity e:gm3p-a6ku l:"Jackson Capital Budget" t:url=https://data.jacksonms.gov/api/views/gm3p-a6ku

property e:gm3p-a6ku t:meta.view v:id=gm3p-a6ku v:category="Public Works" v:averageRating=0 v:name="Jackson Capital Budget"

property e:gm3p-a6ku t:meta.view.owner v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"

property e:gm3p-a6ku t:meta.view.tableauthor v:id=6ngd-c2u2 v:profileImageUrlMedium=/api/users/6ngd-c2u2/profile_images/THUMB v:profileImageUrlLarge=/api/users/6ngd-c2u2/profile_images/LARGE v:screenName="Justin Bruce" v:profileImageUrlSmall=/api/users/6ngd-c2u2/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492180672 v:displayName="Justin Bruce"
```

## Top Records

```ls
| fiscal_year | service                    | department   | project                    | project_category | project_name                  | project_id | project_description                                                                                                                                                                                                                                                                                                                                                                      | budgeted_amount | amount_spent | funding_source_s            | 
| =========== | ========================== | ============ | ========================== | ================ | ============================= | ========== | ======================================================================================================================================================================================================================================================================================================================================================================================== | =============== | ============ | =========================== | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Streets          | John R. Lynch Street          | ST-04      |                                                                                                                                                                                                                                                                                                                                                                                          | 122000          |              | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Drainage         | Drainage Study                | DR-16      |                                                                                                                                                                                                                                                                                                                                                                                          | 375000          |              | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Bridges          | Hanging Moss Road             | BR-01      | The proposed project will repair the bridge located on Hanging Moss Road, and the tributary of Hanging Moss Creek. Major activity includes replacing the bridge with a structure that meets or exceeds the substandard load carrying capacity. This bridge received a sufficiency rating of 9 out of 100 during a recent MDOT State Aid inspection.                                      | 395000          | 362765.29    | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Bridges          | Country Club Drive            | BR-02      | The proposed project will repair the bridge located on Country Club Drive above Lynch Creek. Major activity include replacing the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating less than 40 out of 100 during a recent MDOT State Aid inspection.                                                         | 45000           |              | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Bridges          | Robinson Road                 | BR-03      | The proposed project will repair the bridge located on Robinson Road above Caney Creek. Major activity includes replacing the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating less than 50 out of 100 during a recent MDOT State Aid inspection.                                                             | 167002          | 5061.57      | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Bridges          | Alta Woods Boulevard          | BR-04      | The proposed project will repair the bridge located on Alta Woods Boulevard above Small Stream. Major activity includes the replacement of the bridge with a structure that meets or exceeds substandard load carrying capacity. This bridge received a sufficiency rating of 41 out of 100 during a recent MDOT State Aid inspection.                                                   | 78000           |              | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Bridges          | Mayes Street Bridge           | BR-06      |                                                                                                                                                                                                                                                                                                                                                                                          | 877600          |              | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Drainage         | Beechcrest Drive              | DR-01      | To improve 3200 feet of drainage starting at the east of Beechcrest Drive where Purple Creek intersects with a major tributary and extends upstream along Purple Creek to Old Canton Road. Embankment solutions will be used to improve the drainage which is currently causing severe erosion resulting in property loss.                                                               | 78900           |              | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Drainage         | North Canton Club             | DR-02      | Due to erosion, there is limited access and egress in the North Canton Club area. To combat this, a combination of erosion methods such as rock and vegetation along with a new piping system can be used to help slow down storm water runoff. The proposed project will improve the drainage system along North Canton Club for an estimated linear footage of 3100 feet.              | 124000          |              | Special Municipal Sales Tax | 
| 2016        | Infrastructure Improvement | Public Works | Infrastructure Master Plan | Drainage         | Woodhill Road to Beasley Road | DR-03      | A combination of erosion and flooding concerns exist along Woodhill Road and can be addressed by implementing both stabilization activities as well as some piping where hydraulics will support it. Clearing and grubbing activities will be necessary as well. The proposed project will improve the drainage system along Woodhill Road for an estimated linear footage of 2000 feet. | 198000          |              | Special Municipal Sales Tax | 
```