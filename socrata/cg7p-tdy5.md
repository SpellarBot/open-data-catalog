# New York's Great Appliance Swap Out

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/new-yorks-great-appliance-swap-out) |
| Metadata | [Link](https://data.ny.gov/api/views/cg7p-tdy5) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/cg7p-tdy5/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/cg7p-tdy5/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | cg7p-tdy5 |
| Name | New York's Great Appliance Swap Out |
| Attribution | New York State Energy Research and Development Authority |
| Category | Energy & Environment |
| Tags | energy efficiency, appliance rebate, appliance recycling, high-efficiency appliances, energy star appliances, american recovery and reinvestment act |
| Created | 2014-06-25T21:30:29Z |
| Publication Date | 2015-04-30T20:00:44Z |

## Description

As part of the American Recovery and Reinvestment Act, NYSERDA administered an $18.7 million residential high-efficiency appliance rebate program called New York's Great Appliance Swap Out. Under the approved U.S. Department of Energy plan, customers purchasing appliances qualified for a rebate of $75 ($105 with documented recycling) for ENERGY STAR qualified refrigerators, $75 ($100 with documented recycling) for clothes washers and $50 ($75 with documented recycling) for freezers. $500 rebate ($555 with documented recycling) were also available for high-efficiency dishwashers, clothes washers and refrigerators that meet CEE super efficiency levels when they were purchased as part of a three-appliance package. The plan was approved by the DOE on December 1, 2009. The program was launched February 12, 2010 and closed March 4, 2011 after processing over $16.58 million in rebates

## Columns

```ls
| Included | Schema Type    | Field Name                                  | Name                                          | Data Type     | Render Type   |
| ======== | ============== | =========================================== | ============================================= | ============= | ============= |
| Yes      | series tag     | program_name                                | Program Name                                  | text          | text          |
| Yes      | time           | program_launch_date                         | Program Launch Date                           | calendar_date | calendar_date |
| No       |                | program_close_date                          | Program Close Date                            | calendar_date | calendar_date |
| Yes      | series tag     | rebate_application_id                       | Rebate Application ID                         | text          | text          |
| Yes      | series tag     | rebate_applicant_zip_code                   | Rebate Applicant Zip Code                     | text          | text          |
| Yes      | series tag     | rebate_applicant_county                     | Rebate Applicant County                       | text          | text          |
| No       |                | rebate_application_date                     | Rebate Application Date                       | calendar_date | calendar_date |
| Yes      | series tag     | rebate_applicant_electric_utility           | Rebate Applicant Electric Utility             | text          | text          |
| Yes      | series tag     | rebate_option_number                        | Rebate Option Number                          | text          | text          |
| Yes      | series tag     | rebate_option_description                   | Rebate Option Description                     | text          | text          |
| Yes      | series tag     | appliance_type                              | Appliance Type                                | text          | text          |
| Yes      | series tag     | appliance_make                              | Appliance Make                                | text          | text          |
| Yes      | series tag     | appliance_model                             | Appliance Model                               | text          | text          |
| Yes      | numeric metric | rebate_amount                               | Rebate Amount ($)                             | number        | number        |
| Yes      | series tag     | existing_appliance_removed_and_recycled_y_n | Existing Appliance Removed and Recycled (Y/N) | text          | text          |
| Yes      | series tag     | recycled_appliance_make                     | Recycled Appliance Make                       | text          | text          |
| Yes      | series tag     | recycled_appliance_model                    | Recycled Appliance Model                      | text          | text          |
| Yes      | numeric metric | estimated_age_of_recycled_appliance         | Estimated Age of Recycled Appliance           | number        | number        |
| No       |                | date_appliance_was_picked_up_for_recycling  | Date Appliance was Picked Up for Recycling    | calendar_date | calendar_date |
```

## Time Field

```ls
Value = program_launch_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = program_close_date,rebate_application_date,date_appliance_was_picked_up_for_recycling
```

## Data Commands

```ls
series e:cg7p-tdy5 d:2010-02-12T00:00:00.000Z t:rebate_application_id=168881 t:rebate_applicant_county=Oneida t:appliance_model=28712 t:rebate_option_number="Rebate Option 1" t:appliance_make=Kenmore t:rebate_option_description="ENERGY STAR Freezer" t:existing_appliance_removed_and_recycled_y_n=N t:appliance_type="ENERGY STAR Freezer" t:rebate_applicant_zip_code=13501 t:program_name="New York?s Great Appliance Swap Out Program" t:rebate_applicant_electric_utility="National Grid" m:rebate_amount=50

series e:cg7p-tdy5 d:2010-02-12T00:00:00.000Z t:rebate_application_id=119133 t:rebate_applicant_county=Queens t:appliance_model=WM2010C* t:rebate_option_number="Rebate Option 1" t:appliance_make=LG t:rebate_option_description="ENERGY STAR Clothes Washer" t:existing_appliance_removed_and_recycled_y_n=N t:appliance_type="ENERGY STAR Clothes Washer" t:rebate_applicant_zip_code=11427 t:program_name="New York?s Great Appliance Swap Out Program" t:rebate_applicant_electric_utility=_Other m:rebate_amount=75

series e:cg7p-tdy5 d:2010-02-12T00:00:00.000Z t:rebate_application_id=177534 t:rebate_applicant_county=Oswego t:appliance_model=FFH17F7HW t:rebate_option_number="Rebate Option 1" t:appliance_make=Frigidaire t:rebate_option_description="ENERGY STAR Freezer" t:existing_appliance_removed_and_recycled_y_n=N t:appliance_type="ENERGY STAR Freezer" t:rebate_applicant_zip_code=13069 t:program_name="New York?s Great Appliance Swap Out Program" t:rebate_applicant_electric_utility="National Grid" m:rebate_amount=50
```

## Meta Commands

```ls
metric m:rebate_amount p:integer l:"Rebate Amount ($)" d:"Appliance rebate amount in US dollars (USD)" t:dataTypeName=number

metric m:estimated_age_of_recycled_appliance p:integer l:"Estimated Age of Recycled Appliance" d:"Estimated age of recycled the appliance being recycled" t:dataTypeName=number

entity e:cg7p-tdy5 l:"New York's Great Appliance Swap Out" t:attribution="New York State Energy Research and Development Authority" t:url=https://data.ny.gov/api/views/cg7p-tdy5

property e:cg7p-tdy5 t:meta.view v:id=cg7p-tdy5 v:category="Energy & Environment" v:averageRating=0 v:name="New York's Great Appliance Swap Out" v:attribution="New York State Energy Research and Development Authority"

property e:cg7p-tdy5 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:cg7p-tdy5 t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:cg7p-tdy5 t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| program_name                                | program_launch_date | program_close_date  | rebate_application_id | rebate_applicant_zip_code | rebate_applicant_county | rebate_application_date | rebate_applicant_electric_utility | rebate_option_number | rebate_option_description  | appliance_type             | appliance_make | appliance_model | rebate_amount | existing_appliance_removed_and_recycled_y_n | recycled_appliance_make | recycled_appliance_model | estimated_age_of_recycled_appliance | date_appliance_was_picked_up_for_recycling | 
| =========================================== | =================== | =================== | ===================== | ========================= | ======================= | ======================= | ================================= | ==================== | ========================== | ========================== | ============== | =============== | ============= | =========================================== | ======================= | ======================== | =================================== | ========================================== | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 168881                | 13501                     | Oneida                  | 2011-02-21T00:00:00     | National Grid                     | Rebate Option 1      | ENERGY STAR Freezer        | ENERGY STAR Freezer        | Kenmore        | 28712           | 50            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 119133                | 11427                     | Queens                  | 2010-04-13T00:00:00     | _Other                            | Rebate Option 1      | ENERGY STAR Clothes Washer | ENERGY STAR Clothes Washer | LG             | WM2010C*        | 75            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 177534                | 13069                     | Oswego                  | 2010-10-01T00:00:00     | National Grid                     | Rebate Option 1      | ENERGY STAR Freezer        | ENERGY STAR Freezer        | Frigidaire     | FFH17F7HW       | 50            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 228471                | 12883                     | Essex                   | 2010-02-16T00:00:00     | National Grid                     | Rebate Option 1      | ENERGY STAR Freezer        | ENERGY STAR Freezer        | Frigidaire     | FFH21F7HW*      | 50            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 110193                | 11756                     | Nassau                  | 2010-03-15T00:00:00     | _Other                            | Rebate Option 1      | ENERGY STAR Clothes Washer | ENERGY STAR Clothes Washer | Samsung        | WF219***        | 75            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 212632                | 14103                     | Orleans                 | 2011-03-01T00:00:00     | National Grid                     | Rebate Option 1      | ENERGY STAR Refrigerator   | ENERGY STAR Refrigerator   | Kenmore        | 5107#           | 75            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 260250                | 10992                     | Orange                  | 2010-10-11T00:00:00     | _Other                            | Rebate Option 1      | ENERGY STAR Clothes Washer | ENERGY STAR Clothes Washer | LG             | WM2301H*        | 75            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 229850                | 10475                     | Bronx                   | 2010-05-19T00:00:00     | _Other                            | Rebate Option 1      | ENERGY STAR Refrigerator   | ENERGY STAR Refrigerator   | Kenmore        | 5942*80*        | 75            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 242632                | 13069                     | Oswego                  | 2010-03-22T00:00:00     | National Grid                     | Rebate Option 1      | ENERGY STAR Refrigerator   | ENERGY STAR Refrigerator   | Samsung        | RF263AE**       | 75            | N                                           |                         |                          |                                     |                                            | 
| New York?s Great Appliance Swap Out Program | 2010-02-12T00:00:00 | 2011-03-04T00:00:00 | 129673                | 12211                     | Albany                  | 2010-11-18T00:00:00     | National Grid                     | Rebate Option 1      | ENERGY STAR Refrigerator   | ENERGY STAR Refrigerator   | Maytag         | MBF2258XE*      | 75            | N                                           |                         |                          |                                     |                                            | 
```