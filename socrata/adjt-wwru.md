# Capital Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/capital-projects-60d4c) |
| Metadata | [Link](https://data.illinois.gov/api/views/adjt-wwru) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/adjt-wwru/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/adjt-wwru/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | adjt-wwru |
| Name | Capital Projects |
| Created | 2014-01-22T20:36:47Z |
| Publication Date | 2014-03-25T16:58:06Z |

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | agency_name            | Agency Name            | text          | text          |
| Yes      | series tag     | project_name           | Project Name           | text          | text          |
| Yes      | series tag     | project_description    | Project Description    | text          | text          |
| Yes      | series tag     | project_type           | Project Type           | text          | text          |
| Yes      | series tag     | recipient              | Recipient              | text          | text          |
| Yes      | series tag     | city                   | City                   | text          | text          |
| Yes      | series tag     | county                 | County                 | text          | text          |
| Yes      | series tag     | congressional_district | Congressional District | text          | number        |
| Yes      | series tag     | state_rep_district     | State Rep District     | text          | number        |
| Yes      | series tag     | state_senate_district  | State Senate District  | text          | number        |
| Yes      | numeric metric | total_amount           | Total Amount           | money         | money         |
| Yes      | numeric metric | state_amount           | State Amount           | money         | money         |
| Yes      | numeric metric | federal_amount         | Federal Amount         | money         | money         |
| Yes      | numeric metric | local_amount           | Local Amount           | money         | money         |
| Yes      | time           | date_started           | Date Started           | calendar_date | calendar_date |
| No       |                | date_completed         | Date Completed         | calendar_date | calendar_date |
| Yes      | series tag     | status                 | Status                 | text          | text          |
```

## Time Field

```ls
Value = date_started
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_completed
```

## Data Commands

```ls
series e:adjt-wwru d:2010-01-01T00:00:00.000Z t:project_name="Clean Water Act Section 319 Nonpoint Source Management Program" t:county=COLES t:status=In-Progress t:state_senate_district=55 t:agency_name="Environmental Protection Agency" t:congressional_district=15 t:project_type=Water t:project_description="This project restored 2000 feet of bank and channel stability in combination with the establishment of deep pool habitats and riffles along a segment of Kickapoo Creek near Charleston Illinois. Post-construction assessment and monitoring activities was performed to evaluate 1) the effectiveness of the installed streambank and channel stabilization measures 2) bed load sediment transport and in-stream habitat diversity 3) hydrologic flow and 4) fish and macroinvertebrates." t:recipient="Illinois Department of Natural Resources" m:total_amount=206250

series e:adjt-wwru d:2009-01-01T00:00:00.000Z t:project_name="Clean Water Act Section 319 Nonpoint Source Management Program" t:county=LAKE t:status=In-Progress t:state_senate_district=30 t:agency_name="Environmental Protection Agency" t:congressional_district=10 t:project_type=Water t:project_description="This project restored 450 feet of failed streambank stabilization practices installed on the Waukegan River. Restoration was designed to arrest streambank erosion and reduce nonpoint source pollution through the installation of environmentally sound practices while protecting or enhancing habitat ameliorating damage from peak flows reducing velocity of peak flows and enhancing aesthetic qualities." t:recipient="Waukegan Park District" t:state_rep_district=60 m:total_amount=28388

series e:adjt-wwru d:2009-01-01T00:00:00.000Z t:project_name="Clean Water Act Section 319 Nonpoint Source Management Program" t:county=KANE t:status=In-Progress t:state_senate_district=26 t:agency_name="Environmental Protection Agency" t:congressional_district=6 t:project_type=Water t:project_description="This project restored 500 feet of failed streambank stabilization practices installed on Four Winds Way Creek a tributary of the Fox River. Rehabilitation was designed to arrest streambank erosion and reduce nonpoint source pollution through the installation of environmentally sound practices while protecting or enhancing habitat ameliorating damage from peak flows reducing velocity of peak flows and enhancing aesthetic qualities." t:recipient="Kane County Department of Environmental Management" t:state_rep_district=52 m:total_amount=42031
```

## Meta Commands

```ls
metric m:total_amount p:integer l:"Total Amount" t:dataTypeName=money

metric m:state_amount p:integer l:"State Amount" t:dataTypeName=money

metric m:federal_amount p:integer l:"Federal Amount" t:dataTypeName=money

metric m:local_amount p:integer l:"Local Amount" t:dataTypeName=money

entity e:adjt-wwru l:"Capital Projects" t:url=https://data.illinois.gov/api/views/adjt-wwru

property e:adjt-wwru t:meta.view v:id=adjt-wwru v:averageRating=0 v:name="Capital Projects"

property e:adjt-wwru t:meta.view.owner v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"

property e:adjt-wwru t:meta.view.tableauthor v:id=vcvp-yass v:profileImageUrlMedium=/api/users/vcvp-yass/profile_images/THUMB v:profileImageUrlLarge=/api/users/vcvp-yass/profile_images/LARGE v:screenName="Dylan Bussone" v:profileImageUrlSmall=/api/users/vcvp-yass/profile_images/TINY v:displayName="Dylan Bussone"
```

## Top Records

```ls
| agency_name                     | project_name                                                   | project_description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | project_type | recipient                                                      | city | county     | congressional_district | state_rep_district | state_senate_district | total_amount | state_amount | federal_amount | local_amount | date_started        | date_completed | status      | 
| =============================== | ============================================================== | ======================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================= | ============ | ============================================================== | ==== | ========== | ====================== | ================== | ===================== | ============ | ============ | ============== | ============ | =================== | ============== | =========== | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project restored 2000 feet of bank and channel stability in combination with the establishment of deep pool habitats and riffles along a segment of Kickapoo Creek near Charleston Illinois. Post-construction assessment and monitoring activities was performed to evaluate 1) the effectiveness of the installed streambank and channel stabilization measures 2) bed load sediment transport and in-stream habitat diversity 3) hydrologic flow and 4) fish and macroinvertebrates.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Water        | Illinois Department of Natural Resources                       |      | COLES      | 15                     |                    | 55                    | 206250       |              |                |              | 2010-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project restored 450 feet of failed streambank stabilization practices installed on the Waukegan River. Restoration was designed to arrest streambank erosion and reduce nonpoint source pollution through the installation of environmentally sound practices while protecting or enhancing habitat ameliorating damage from peak flows reducing velocity of peak flows and enhancing aesthetic qualities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Water        | Waukegan Park District                                         |      | LAKE       | 10                     | 60                 | 30                    | 28388        |              |                |              | 2009-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project restored 500 feet of failed streambank stabilization practices installed on Four Winds Way Creek a tributary of the Fox River. Rehabilitation was designed to arrest streambank erosion and reduce nonpoint source pollution through the installation of environmentally sound practices while protecting or enhancing habitat ameliorating damage from peak flows reducing velocity of peak flows and enhancing aesthetic qualities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Water        | Kane County Department of Environmental Management             |      | KANE       | 6                      | 52                 | 26                    | 42031        |              |                |              | 2009-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project restored a portion of the floodplains of the Des Plaines River (ILG07) and researched significant ecological elements (i.e. hydrologic conditions water chemistry and vegetation reestablishment). Wetlands Research Inc. (WRI) created 6.8 acres of wetland and enhanced 4.22 acres of existing wetland. The performance of the restored wetland was monitored to determine if water quality hydrology and vegetation characteristics evolved in a manner reflective of a natural wetland. WRI also executed a public communications campaign to educate the public about the values of wetlands particularly in minimizing non-point source pollution.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Water        | Wetland Research Inc.                                          |      | LAKE       | 14                     | 61                 | 31                    | 14344        |              |                |              | 2009-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project restored approximately 20 acres of wetlands within the American Bottom floodplain to improve water quality and enhance aquatic habitat. Other best management practices (BMPs) were installed in and around the restored wetlands to reduce nonpoint source pollution including 464 linear feet of elevated boardwalk over the wetland a 469 linear foot gravel trail on the west side of the wetland and a 13482 square foot permeable pavement parking lot. To educate the public about wetlands nine interpretive signs were placed at the site a website was developed and educational events held.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Water        | Southwestern Illinois Resource Conservation & Development Area |      | MADISON    | 12                     |                    | 56                    | 381729       |              |                |              | 2010-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project restored the South Pond at Lincoln Park Zoo in Chicago Illinois. Existing asphalt walkways and concrete retaining walls which have deteriorated were removed and 3850 feet of pond edge was re-graded and vegetated with pollutant filtering plants. A 10 to 20 foot buffer strip of prairie grasses and other plants was installed between the park and the pond???s shoreline. Asphalt walkways were replaced with a porous boardwalk made of recycled plastic. This project also used South Pond to educate visitors about water quality and non-point source pollution. Educational activities include hiring a part-time South Pond Program Assistant development and delivery of teacher training workshops support for the 4th and 5th annual Build and Grow South Pond Science and Project Fairs in 2008 and 2009 a mobile display booth on the South Pond and clean water issues displayed at events around Chicago and the state by staff and volunteers and presentations at two conferences. Finally Integrated Lakes Management trained volunteer naturalists and analyzed the results of a water quality monitoring program. | Water        | Lincoln Park Zoo                                               |      | COOK       | 5                      | 12                 | 6                     | 390648       |              |                |              | 2009-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project retrofitted an existing detention basin located at the Lake Barrington Village Hall by replacing existing turf grass with wet and mesic prairie vegetation and constructing vegetated swales along the east side of the parking lot to collect and filter runoff. Signage was placed at the site to explain the water quality and infiltration benefits of the project. Also an existing three acre pond (pond 4) in the Braymore Hills subdivision was converted into a stormwater wetland through the addition of floating islands of wetland plants to reduce nutrients in the water. Turf grass along the shoreline was replaced with native vegetation to create a 0.4 acre prairie buffer. Enzyme B504 was applied to the entire 20 acre pond system of which pond 4 is a part to break down the organic material on the bottom of the ponds which is a major source of nutrients. Ultrasonic algae control was also used in pond 4.                                                                                                                                                                                                 | Water        | Citizens for Conservation Flint Creek Watershed Partnership    |      | COOK, LAKE | 6                      | 52                 | 26                    | 29413        |              |                |              | 2009-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project served as a model for developers and municipalities who are interested in implementing Low Impact Development (LID) Best Management Practices (BMPs) within the county. A complementary project funded by the IDNR C2000 program and introduced by the Southwestern Illinois RC&D developed a Guidance Document for the implementation of Conservation Subdivision design. Using this document staff provided technical assistance to developers and municipal staff to lead toward the implementation of demonstrative BMPs. This project provided funding to developers to implement LID practices to offset costs over and above traditional design.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Water        | Southwestern Illinois Resource Conservation & Development Area |      | MADISON    | 13                     |                    | 56                    | 143484       |              |                |              | 2009-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Drinking Water Loan                                            | Water Main Replacement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Water        | Paw Paw                                                        |      | Lee        | 16                     |                    |                       | 287644       |              |                |              | 2012-01-01T00:00:00 |                | In-Progress | 
| Environmental Protection Agency | Clean Water Act Section 319 Nonpoint Source Management Program | This project stabilized 1309 feet of eroding streambanks along a segment of Silver Creek (ILGM01) a tributary of the DesPlaines River located in Melrose Park Illinois. Streambanks were stabilized using stone toe protection vegetated geogrid slope re-grading minor clearing of non-native vegetation re-vegetation with native wetland plugs and seed and riffles.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Water        | Village of Melrose Park                                        |      | COOK       | 4                      | 77                 | 39                    | 187269       |              |                |              | 2009-01-01T00:00:00 |                | In-Progress | 
```