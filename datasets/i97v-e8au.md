# ENERGY STAR Certified Furnaces

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-furnaces) |
| Metadata | [Link](https://data.energystar.gov/api/views/i97v-e8au) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/i97v-e8au/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/i97v-e8au/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | i97v-e8au |
| Name | ENERGY STAR Certified Furnaces |
| Category | Active Specifications |
| Tags | furnaces |
| Created | 2014-08-08T12:06:09Z |
| Publication Date | 2016-12-29T15:39:44Z |
| Rows Updated | 2017-03-10T14:14:09Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 4.0 ENERGY STAR Program Requirements for Furnaces that are effective as of February 1, 2013. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=furnaces.pr_crit_furnaces

## Columns

```ls
| Included | Schema Type    | Field Name                          | Name                                           | Data Type     | Render Type   |
| ======== | ============== | =================================== | ============================================== | ============= | ============= |
| Yes      | series tag     | pd_id                               | ENERGY STAR Unique ID                          | text          | number        |
| Yes      | series tag     | energy_star_partner                 | ENERGY STAR Partner                            | text          | text          |
| Yes      | series tag     | brand_name                          | Brand Name                                     | text          | text          |
| Yes      | series tag     | model_name                          | Model Name                                     | text          | text          |
| Yes      | series tag     | model_number                        | Model Number                                   | text          | text          |
| Yes      | series tag     | additional_model_information        | Additional Model Information                   | text          | text          |
| Yes      | series tag     | fuel_type                           | Fuel Type                                      | text          | text          |
| Yes      | series tag     | furnace_is_energy_star_certified_in | Furnace is ENERGY STAR Certified in            | text          | text          |
| Yes      | numeric metric | efficiency_afue                     | Efficiency (AFUE)                              | number        | number        |
| Yes      | series tag     | capable_of_two_way_communication    | Capable of Two Way Communication?              | text          | text          |
| Yes      | time           | date_available_on_market            | Date Available On Market                       | calendar_date | calendar_date |
| No       |                | date_qualified                      | Date Qualified                                 | calendar_date | calendar_date |
| Yes      | series tag     | markets                             | Markets                                        | text          | text          |
| Yes      | series tag     | energy_star_model_identifier        | CB Model Identifier                            | text          | text          |
| Yes      | series tag     | can_integrate_hot_water_heating     | Can Integrate Hot Water Heating                | text          | text          |
| Yes      | series tag     | meets_most_efficient_criteria       | Meets ENERGY STAR Most Efficient 2017 Criteria | text          | text          |
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
series e:i97v-e8au d:2013-02-01T00:00:00.000Z t:energy_star_partner="Bryant Heating and Cooling Systems (Carrier Corporation)" t:capable_of_two_way_communication="Not Applicable" t:model_number=OVL098-BNX* t:fuel_type=Oil t:markets="United States, Canada" t:energy_star_model_identifier=ES_1019658_06112013094056_6313371 t:furnace_is_energy_star_certified_in=All t:meets_most_efficient_criteria=No t:can_integrate_hot_water_heating=No t:brand_name=Bryant t:model_name=OVL098-BNX t:pd_id=2182974 m:efficiency_afue=85.2

series e:i97v-e8au d:2013-02-01T00:00:00.000Z t:energy_star_partner="Bryant Heating and Cooling Systems (Carrier Corporation)" t:capable_of_two_way_communication="Not Applicable" t:model_number=OVL098-CAR* t:fuel_type=Oil t:markets="United States, Canada" t:energy_star_model_identifier=ES_1019658_06112013094056_6831293 t:furnace_is_energy_star_certified_in=All t:meets_most_efficient_criteria=No t:can_integrate_hot_water_heating=No t:brand_name=Bryant t:model_name=OVL098-CAR t:pd_id=2182975 m:efficiency_afue=85.2

series e:i97v-e8au d:2013-02-01T00:00:00.000Z t:energy_star_partner="Bryant Heating and Cooling Systems (Carrier Corporation)" t:capable_of_two_way_communication="Not Applicable" t:model_number=OVL098-RBF* t:fuel_type=Oil t:markets="United States, Canada" t:energy_star_model_identifier=ES_1019658_06112013094056_3260863 t:furnace_is_energy_star_certified_in=All t:meets_most_efficient_criteria=No t:can_integrate_hot_water_heating=No t:brand_name=Bryant t:model_name=OVL098-RBF t:pd_id=2182976 m:efficiency_afue=85
```

## Meta Commands

```ls
metric m:efficiency_afue l:"Efficiency (AFUE)" d:"The percentage of the heat in the incoming fuel which is converted to space heat instead of being lost." t:dataTypeName=number

entity e:i97v-e8au l:"ENERGY STAR Certified Furnaces" t:url=https://data.energystar.gov/api/views/i97v-e8au

property e:i97v-e8au t:meta.view d:2017-03-10T16:18:37.729Z v:id=i97v-e8au v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Furnaces"

property e:i97v-e8au t:meta.view.owner d:2017-03-10T16:18:37.729Z v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:displayName=ESddas

property e:i97v-e8au t:meta.view.tableauthor d:2017-03-10T16:18:37.729Z v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:displayName=ESddas

property e:i97v-e8au t:meta.view.metadata.custom_fields.common_core d:2017-03-10T16:18:37.729Z v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```