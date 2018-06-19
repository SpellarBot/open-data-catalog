# ENERGY STAR Certified Commercial Hot Food Holding Cabinet

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-commercial-hot-food-holding-cabinet) |
| Metadata | [Link](https://data.energystar.gov/api/views/wyw6-sr4d) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/wyw6-sr4d/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/wyw6-sr4d/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | wyw6-sr4d |
| Name | ENERGY STAR Certified Commercial Hot Food Holding Cabinet |
| Category | Active Specifications |
| Tags | commercial hot food holding cabinets |
| Created | 2013-06-06T16:04:28Z |
| Publication Date | 2016-08-19T14:23:58Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 2.0 ENERGY STAR Program Requirements for Commercial Hot Food Holding Cabinets that are effective as of October 1, 2011. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=hfhc.pr_crit_hfhc

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                                      | Data Type     | Render Type   |
| ======== | ============== | ============================== | ========================================= | ============= | ============= |
| Yes      | series tag     | pd_id                          | ENERGY STAR Unique ID                     | text          | number        |
| Yes      | series tag     | energy_star_partner            | ENERGY STAR Partner                       | text          | text          |
| Yes      | series tag     | brand_name                     | Brand Name                                | text          | text          |
| Yes      | series tag     | model_name                     | Model Name                                | text          | text          |
| Yes      | series tag     | model_number                   | Model Number                              | text          | text          |
| Yes      | series tag     | additional_model_information   | Additional Model Information              | text          | text          |
| Yes      | series tag     | door_wall_type                 | Door Type                                 | text          | text          |
| Yes      | numeric metric | number_of_doors                | Number of Doors                           | number        | number        |
| Yes      | numeric metric | internal_volume_cu_ft          | Internal Volume (cu. ft.)                 | number        | number        |
| Yes      | numeric metric | energy_usage_watts             | Energy Usage (Watts)                      | number        | number        |
| Yes      | numeric metric | maximum_idle_energy_rate_watts | Energy Use (Max Idle Energy Rate) (Watts) | number        | number        |
| Yes      | time           | date_available_on_market       | Date Available on Market                  | calendar_date | calendar_date |
| No       |                | date_qualified                 | Date Qualified                            | calendar_date | calendar_date |
| Yes      | series tag     | markets                        | Markets                                   | text          | text          |
| Yes      | series tag     | energy_star_model_identifier   | CB Model Identifier                       | text          | text          |
```

## Time Field

```ls
Value = date_available_on_market
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_qualified
```

## Data Commands

```ls
series e:wyw6-sr4d d:2012-12-04T00:00:00.000Z t:energy_star_partner="Wittco (A division of ITW Food Equipment Group)" t:model_number=1826-15-PT t:markets="United States, Canada" t:energy_star_model_identifier="ES_1105798_WITTCO MFG INC (139363) | 1826-15-PT_12262012193216_0336093" t:door_wall_type=Solid t:brand_name=WITTCO t:model_name=1826-15-PT t:pd_id=2164665 m:internal_volume_cu_ft=20 m:energy_usage_watts=280 m:maximum_idle_energy_rate_watts=293 m:number_of_doors=1

series e:wyw6-sr4d d:2012-12-04T00:00:00.000Z t:energy_star_partner="Wittco (A division of ITW Food Equipment Group)" t:model_number=1826-5 t:markets="United States, Canada" t:energy_star_model_identifier="ES_1105798_WITTCO MFG INC (139363) | 1826-5_12262012193139_0299235" t:door_wall_type=Solid t:brand_name=WITTCO t:model_name=1826-5 t:pd_id=2164666 m:internal_volume_cu_ft=7 m:energy_usage_watts=124 m:maximum_idle_energy_rate_watts=143 m:number_of_doors=1

series e:wyw6-sr4d d:2012-12-04T00:00:00.000Z t:energy_star_partner="Vulcan (A division of ITW Food Equipment Group)" t:model_number=VPT13 t:markets="United States, Canada" t:energy_star_model_identifier="ES_1105798_WITTCO MFG INC (139363) | VPT13_12262012193105_0265119" t:door_wall_type=Solid t:brand_name=Vulcan t:model_name=VPT13 t:pd_id=2164667 m:internal_volume_cu_ft=18 m:energy_usage_watts=264 m:maximum_idle_energy_rate_watts=288 m:number_of_doors=1
```

## Meta Commands

```ls
metric m:number_of_doors p:integer l:"Number of Doors" d:"Amount of doors available on the hot food holding cabinet." t:dataTypeName=number

metric m:internal_volume_cu_ft p:double l:"Internal Volume (cu. ft.)" d:"Determined using straight-line segments following the gross interior dimensions of the appliance (Interior Volume = Interior Height x Interior Width x Interior Depth)." t:dataTypeName=number

metric m:energy_usage_watts p:double l:"Energy Usage (Watts)" d:"The rate of a hot food holding cabinets energy consumption while it is maintaining or holding at the control set point, without using a humidity-generating device." t:dataTypeName=number

metric m:maximum_idle_energy_rate_watts p:double l:"Energy Use (Max Idle Energy Rate) (Watts)" d:"Calculated value utilizing the equations in Section 3, Table 1 of the ENERGY STAR Product Specification for Commercial Hot Food Holding Cabinets." t:dataTypeName=number

entity e:wyw6-sr4d l:"ENERGY STAR Certified Commercial Hot Food Holding Cabinet" t:url=https://data.energystar.gov/api/views/wyw6-sr4d

property e:wyw6-sr4d t:meta.view v:id=wyw6-sr4d v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Commercial Hot Food Holding Cabinet"

property e:wyw6-sr4d t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:wyw6-sr4d t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:wyw6-sr4d t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner                             | brand_name                           | model_name | model_number | additional_model_information | door_wall_type | number_of_doors | internal_volume_cu_ft | energy_usage_watts | maximum_idle_energy_rate_watts | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                                                          | 
| ======= | =============================================== | ==================================== | ========== | ============ | ============================ | ============== | =============== | ===================== | ================== | ============================== | ======================== | =================== | ===================== | ===================================================================================== | 
| 2164665 | Wittco (A division of ITW Food Equipment Group) | WITTCO                               | 1826-15-PT | 1826-15-PT   |                              | Solid          | 1               | 20                    | 280                | 293                            | 2012-12-04T00:00:00      | 2012-12-17T00:00:00 | United States, Canada | ES_1105798_WITTCO MFG INC (139363) | 1826-15-PT_12262012193216_0336093                | 
| 2164666 | Wittco (A division of ITW Food Equipment Group) | WITTCO                               | 1826-5     | 1826-5       |                              | Solid          | 1               | 7                     | 124                | 143                            | 2012-12-04T00:00:00      | 2012-12-17T00:00:00 | United States, Canada | ES_1105798_WITTCO MFG INC (139363) | 1826-5_12262012193139_0299235                    | 
| 2164667 | Vulcan (A division of ITW Food Equipment Group) | Vulcan                               | VPT13      | VPT13        |                              | Solid          | 1               | 18                    | 264                | 288                            | 2012-12-04T00:00:00      | 2012-12-17T00:00:00 | United States, Canada | ES_1105798_WITTCO MFG INC (139363) | VPT13_12262012193105_0265119                     | 
| 2164668 | Vulcan (A division of ITW Food Equipment Group) | Vulcan                               | VPT15      | VPT15        |                              | Solid          | 1               | 20                    | 280                | 293                            | 2012-12-04T00:00:00      | 2012-12-17T00:00:00 | United States, Canada | ES_1105798_WITTCO MFG INC (139363) | VPT15_12262012193114_0274962                     | 
| 2164671 | Wittco (A division of ITW Food Equipment Group) | WITTCO                               | 1826-7-PT  | 1826-7-PT    |                              | Solid          | 1               | 10                    | 204                | 207                            | 2012-12-04T00:00:00      | 2012-12-17T00:00:00 | United States, Canada | ES_1105798_WITTCO MFG INC (139363) | 1826-7-PT_12262012193152_0312576                 | 
| 2164672 | Vulcan (A division of ITW Food Equipment Group) | Vulcan                               | VBP5I      | VBP5I        |                              | Solid          | 1               | 7                     | 124                | 143                            | 2012-12-04T00:00:00      | 2012-12-17T00:00:00 | United States, Canada | ES_1105798_WITTCO MFG INC (139363) | VPB5_12262012193045_0245687                      | 
| 2164673 | Vulcan (A division of ITW Food Equipment Group) | Vulcan                               | VPT7       | VPT7         |                              | Solid          | 1               | 10                    | 204                | 207                            | 2012-12-04T00:00:00      | 2012-12-17T00:00:00 | United States, Canada | ES_1105798_WITTCO MFG INC (139363) | VPT7_12262012193056_0256216                      | 
| 2164723 | Food Warming Equipment Company, Inc.            | Food Warming Equipment Company, Inc. | HLC-16     | HLC-16       |                              | Solid          | 1               | 4                     | 81.8               | 96                             | 2012-12-01T00:00:00      | 2012-12-19T00:00:00 | United States, Canada | ES_1105798_FOOD WARMING EQUIPMENT CO INC (276273) | HLC-16_12272012121643_0603008     | 
| 2164724 | Food Warming Equipment Company, Inc.            | Food Warming Equipment Company, Inc. | HLC-16-CHP | HLC-16-CHP   |                              | Solid          | 1               | 4                     | 81.8               | 96                             | 2012-12-01T00:00:00      | 2012-12-19T00:00:00 | United States, Canada | ES_1105798_FOOD WARMING EQUIPMENT CO INC (276273) | HLC-16-CHP_12272012121653_0613189 | 
| 2164725 | Food Warming Equipment Company, Inc.            | Food Warming Equipment Company, Inc. | HLC-16S    | HLC-16S      |                              | Solid          | 1               | 4                     | 81.8               | 96                             | 2012-12-01T00:00:00      | 2012-12-19T00:00:00 | United States, Canada | ES_1105798_FOOD WARMING EQUIPMENT CO INC (276273) | HLC-16S_12272012121711_0631650    | 
```