# ENERGY STAR Certified Water Coolers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-water-coolers) |
| Metadata | [Link](https://data.energystar.gov/api/views/x39k-wz7q) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/x39k-wz7q/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/x39k-wz7q/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | x39k-wz7q |
| Name | ENERGY STAR Certified Water Coolers |
| Category | Active Specifications |
| Tags | water coolers, coolers |
| Created | 2013-07-17T19:36:48Z |
| Publication Date | 2016-08-19T15:12:52Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 2.0 ENERGY STAR Program Requirements for Water Coolers that are effective as of February 1, 2014. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?fuseaction=find_a_product.showProductGroup&pgw_code=WA#specs

## Columns

```ls
| Included | Schema Type    | Field Name                                    | Name                                              | Data Type     | Render Type   |
| ======== | ============== | ============================================= | ================================================= | ============= | ============= |
| Yes      | series tag     | pd_id                                         | ENERGY STAR Unique ID                             | text          | number        |
| Yes      | series tag     | energy_star_partner                           | ENERGY STAR Partner                               | text          | text          |
| Yes      | series tag     | brand_name                                    | Brand Name                                        | text          | text          |
| Yes      | series tag     | model_name                                    | Model Name                                        | text          | text          |
| Yes      | series tag     | model_number                                  | Model Number                                      | text          | text          |
| Yes      | series tag     | additional_model_information                  | Additional Model Information                      | text          | text          |
| Yes      | series tag     | type                                          | Type                                              | text          | text          |
| Yes      | series tag     | water_source                                  | Water Source                                      | text          | text          |
| Yes      | series tag     | water_storage                                 | Water Storage                                     | text          | text          |
| Yes      | series tag     | refrigerated_compartment                      | Refrigerated Compartment                          | text          | text          |
| Yes      | numeric metric | energy_use_on_mode_with_no_water_draw_kwh_day | Energy Use (On Mode With No Water Draw) (kWh/day) | number        | number        |
| Yes      | time           | date_available_on_market                      | Date Available On Market                          | calendar_date | calendar_date |
| No       |                | date_qualified                                | Date Qualified                                    | calendar_date | calendar_date |
| Yes      | series tag     | markets                                       | Markets                                           | text          | text          |
| Yes      | series tag     | energy_star_model_identifier                  | CB Model Identifier                               | text          | text          |
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
series e:x39k-wz7q d:2014-04-14T00:00:00.000Z t:energy_star_partner="Crystal Mountain Products Limited" t:additional_model_information=MOS*2*T*1A%C,, t:model_number=GLS*2*T*1A%C t:markets="United States, Canada" t:energy_star_model_identifier=ES_1108611_GLS^2*T*1A%C_04142014100859_4253961 t:water_source="Bottled - Top Load" t:water_storage=Storage t:type="Cook and Cold" t:refrigerated_compartment=No t:brand_name="Crystal Mountain" t:model_name=GLS*2*T*1A%C t:pd_id=2209754 m:energy_use_on_mode_with_no_water_draw_kwh_day=0.13

series e:x39k-wz7q d:2014-01-14T00:00:00.000Z t:energy_star_partner="Crystal Mountain Products Limited" t:model_number=K2FM2*H*1CC t:markets="United States, Canada" t:energy_star_model_identifier=ES_1108611_K2FM2*H*1CC_01202014201453_3406793 t:water_source="Bottled - Top Load" t:water_storage=Storage t:type="Hot and Cold" t:refrigerated_compartment=No t:brand_name="Crystal Mountain" t:model_name=K2FM2*H*1CC t:pd_id=2202250 m:energy_use_on_mode_with_no_water_draw_kwh_day=0.79

series e:x39k-wz7q d:2016-05-01T00:00:00.000Z t:energy_star_partner="Crystal Mountain Products Limited" t:model_number=NOS-A2SHS1AC t:markets="United States" t:energy_star_model_identifier=ES_1108611_NOS-A2SHS1AC_05132016130948_5509302 t:water_source="Bottled - Top Load" t:water_storage=Storage t:type="Hot and Cold" t:refrigerated_compartment=No t:brand_name="Crystal Mountain" t:model_name=NOS-A2SHS1AC t:pd_id=2266786 m:energy_use_on_mode_with_no_water_draw_kwh_day=0.53
```

## Meta Commands

```ls
metric m:energy_use_on_mode_with_no_water_draw_kwh_day p:float l:"Energy Use (On Mode With No Water Draw) (kWh/day)" d:"The required energy to maintain cold and/or hot water at appropriate dispensing temperatures with no water being withdrawn." t:dataTypeName=number

entity e:x39k-wz7q l:"ENERGY STAR Certified Water Coolers" t:url=https://data.energystar.gov/api/views/x39k-wz7q

property e:x39k-wz7q t:meta.view v:id=x39k-wz7q v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Water Coolers"

property e:x39k-wz7q t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:x39k-wz7q t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:x39k-wz7q t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | energy_star_partner               | brand_name       | model_name     | model_number   | additional_model_information | type          | water_source          | water_storage | refrigerated_compartment | energy_use_on_mode_with_no_water_draw_kwh_day | date_available_on_market | date_qualified      | markets                                                                           | energy_star_model_identifier                      | 
| ======= | ================================= | ================ | ============== | ============== | ============================ | ============= | ===================== | ============= | ======================== | ============================================= | ======================== | =================== | ================================================================================= | ================================================= | 
| 2209754 | Crystal Mountain Products Limited | Crystal Mountain | GLS*2*T*1A%C   | GLS*2*T*1A%C   | MOS*2*T*1A%C,,               | Cook and Cold | Bottled - Top Load    | Storage       | No                       | 0.13                                          | 2014-04-14T00:00:00      | 2014-04-16T00:00:00 | United States, Canada                                                             | ES_1108611_GLS^2*T*1A%C_04142014100859_4253961    | 
| 2202250 | Crystal Mountain Products Limited | Crystal Mountain | K2FM2*H*1CC    | K2FM2*H*1CC    |                              | Hot and Cold  | Bottled - Top Load    | Storage       | No                       | 0.79                                          | 2014-01-14T00:00:00      | 2014-01-22T00:00:00 | United States, Canada                                                             | ES_1108611_K2FM2*H*1CC_01202014201453_3406793     | 
| 2266786 | Crystal Mountain Products Limited | Crystal Mountain | NOS-A2SHS1AC   | NOS-A2SHS1AC   |                              | Hot and Cold  | Bottled - Top Load    | Storage       | No                       | 0.53                                          | 2016-05-01T00:00:00      | 2016-05-16T00:00:00 | United States                                                                     | ES_1108611_NOS-A2SHS1AC_05132016130948_5509302    | 
| 2266791 | Crystal Mountain Products Limited | Crystal Mountain | NOS-A2STS1AC   | NOS-A2STS1AC   |                              | Cook and Cold | Bottled - Top Load    | Storage       | No                       | 0.12                                          | 2016-05-01T00:00:00      | 2016-05-16T00:00:00 | United States                                                                     | ES_1108611_NOS-A2STS1AC_05062016160621_355188     | 
| 2266787 | Crystal Mountain Products Limited | Crystal Mountain | NOS-P2SHS1AC   | NOS-P2SHS1AC   |                              | Hot and Cold  | Tap Water Source      | Storage       | No                       | 0.61                                          | 2016-05-01T00:00:00      | 2016-05-16T00:00:00 | United States                                                                     | ES_1108611_NOS-P2SHS1AC_05132016132446_5001336    | 
| 2202249 | Crystal Mountain Products Limited | Crystal Mountain | STFM2*H*1C     | STFM2*H*1C     |                              | Hot and Cold  | Bottled - Bottom Load | Storage       | No                       | 0.62                                          | 2014-01-14T00:00:00      | 2014-01-22T00:00:00 | United States, Canada                                                             | ES_1108611_STFM2*H*1C_01202014201253_7674981      | 
| 2245847 | Electrotemp Technologies, Inc.    | CLASSIC          | Bottom Loading | 8LIECHK-SC-SSF |                              | Hot and Cold  | Bottled - Bottom Load |               | No                       | 0.69                                          | 2014-04-30T00:00:00      | 2015-07-29T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1001510_8LIECHK-SC-SSF_08172015024741_70040538 | 
| 2204826 | Electrotemp Technologies, Inc.    | Electrotemp      | Top Loading    | 75CHK-*        |                              | Hot and Cold  | Bottled - Top Load    |               | No                       | 0.81                                          | 2014-02-10T00:00:00      | 2014-02-19T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1001510_75CHK-*_01132014025108_2679695         | 
| 2204827 | Electrotemp Technologies, Inc.    | Electrotemp      | Top Loading    | 75CHK-SC-*     |                              | Hot and Cold  | Bottled - Top Load    |               | No                       | 0.81                                          | 2014-02-10T00:00:00      | 2014-02-19T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1001510_75CHK-SC-*_01132014025109_2679695      | 
| 2204824 | Electrotemp Technologies, Inc.    | Electrotemp      | Top Loading    | 75IECHK-*      |                              | Hot and Cold  | Bottled - Top Load    |               | No                       | 0.82                                          | 2014-02-10T00:00:00      | 2014-02-19T00:00:00 | United States, Australia, New Zealand, Switzerland, Europe, Taiwan, Japan, Canada | ES_1001510_75IECHK-*_01132014025106_2679695       | 
```