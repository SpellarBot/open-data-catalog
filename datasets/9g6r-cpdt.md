# ENERGY STAR Certified Commercial Clothes Washers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/energy-star-certified-commercial-clothes-washers) |
| Metadata | [Link](https://data.energystar.gov/api/views/9g6r-cpdt) |
| Data: JSON | [100 Rows](https://data.energystar.gov/api/views/9g6r-cpdt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.energystar.gov/api/views/9g6r-cpdt/rows.csv?max_rows=100) |
| Host | data.energystar.gov |
| Id | 9g6r-cpdt |
| Name | ENERGY STAR Certified Commercial Clothes Washers |
| Category | Active Specifications |
| Tags | commercial clothes washers |
| Created | 2013-07-16T15:26:42Z |
| Publication Date | 2016-08-19T15:45:57Z |

## Description

Certified models meet all ENERGY STAR requirements as listed in the Version 7.0 ENERGY STAR Program Requirements for Clothes Washers that are effective as of March 7, 2015. A detailed listing of key efficiency criteria are available at http://www.energystar.gov/index.cfm?c=clotheswash.pr_crit_clothes_washers

## Columns

```ls
| Included | Schema Type    | Field Name                   | Name                         | Data Type     | Render Type   |
| ======== | ============== | ============================ | ============================ | ============= | ============= |
| Yes      | series tag     | pd_id                        | ENERGY STAR Unique ID        | text          | number        |
| Yes      | series tag     | brand_name                   | Brand Name                   | text          | text          |
| Yes      | series tag     | model_number                 | Model Number                 | text          | text          |
| Yes      | series tag     | additional_model_information | Additional Model Information | text          | text          |
| Yes      | series tag     | upc                          | UPC                          | text          | text          |
| Yes      | series tag     | load_configuration           | Load Configuration           | text          | text          |
| Yes      | series tag     | intended_market              | Intended Market              | text          | text          |
| Yes      | numeric metric | volume_cubic_feet            | Volume (cu. ft.)             | number        | number        |
| Yes      | numeric metric | modified_energy_factor_mef   | Modified Energy Factor (MEF) | number        | number        |
| Yes      | numeric metric | us_federal_standard_mef      | US Federal Standard (MEF)    | number        | text          |
| Yes      | numeric metric | annual_energy_use_kwh_year   | Annual Energy Use (kWh/yr)   | number        | number        |
| Yes      | numeric metric | water_factor_wf              | Water Factor (WF)            | number        | number        |
| Yes      | numeric metric | us_federal_standard_wf       | US Federal Standard (WF)     | number        | number        |
| Yes      | time           | date_available_on_market     | Date Available On Market     | calendar_date | calendar_date |
| No       |                | date_qualified               | Date Certified               | calendar_date | calendar_date |
| Yes      | series tag     | markets                      | Markets                      | text          | text          |
| Yes      | series tag     | energy_star_model_identifier | CB Model Identifier          | text          | text          |
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
series e:9g6r-cpdt d:2012-05-30T00:00:00.000Z t:model_number=EHWF09810M t:intended_market=Commercial t:markets="United States, Canada" t:energy_star_model_identifier=ES_0031566_EHWF09810M_05042015024816_70031392 t:load_configuration="Front Load" t:upc=1 t:brand_name=Laundrylux t:pd_id=2238726 m:us_federal_standard_wf=5.5 m:water_factor_wf=3.7 m:us_federal_standard_mef=2 m:modified_energy_factor_mef=2.47 m:annual_energy_use_kwh_year=113 m:volume_cubic_feet=3.5

series e:9g6r-cpdt d:2012-05-30T00:00:00.000Z t:model_number=EHWF09810NM t:intended_market=Commercial t:markets="United States, Canada" t:energy_star_model_identifier=ES_0031566_EHWF09810NM_05042015024815_70031392 t:load_configuration="Front Load" t:upc=1 t:brand_name=Laundrylux t:pd_id=2238727 m:us_federal_standard_wf=5.5 m:water_factor_wf=3.7 m:us_federal_standard_mef=2 m:modified_energy_factor_mef=2.47 m:annual_energy_use_kwh_year=113 m:volume_cubic_feet=3.5

series e:9g6r-cpdt d:2016-12-01T00:00:00.000Z t:model_number=WHLFP715M t:intended_market=Commercial t:markets="United States, Canada" t:energy_star_model_identifier="ES_0031566_WHLFP715M _11012016113615_7010486" t:load_configuration="Front Load" t:upc=856013006016 t:brand_name=Laundrylux t:pd_id=2285547 m:us_federal_standard_wf=5.5 m:water_factor_wf=3.7 m:us_federal_standard_mef=2 m:modified_energy_factor_mef=2.47 m:annual_energy_use_kwh_year=113 m:volume_cubic_feet=3.5
```

## Meta Commands

```ls
metric m:volume_cubic_feet p:float l:"Volume (cu. ft.)" d:"This is the tub capacity of the clothes washer in cubic feet, as measured by the U.S. Department of Energy (DOE) test procedure, Code of Federal Regulations, Title 10, Section 430, Appendix J1." t:dataTypeName=number

metric m:modified_energy_factor_mef p:double l:"Modified Energy Factor (MEF)" d:"MEF is the energy performance metric for ENERGY STAR qualified clothes washers. The higher the MEF, the more efficient the clothes washer. The metric has units: ft3/kWh/cycle, and is calculated as the quotient of the capacity of the clothes container divided by the total clothes washer energy consumption per cycle. The total clothes washer energy consumption per cycle is the sum of the machine electrical energy consumption, the hot water energy consumption, and the energy required for removal of the remaining moisture in the wash load." t:dataTypeName=number

metric m:us_federal_standard_mef p:integer l:"US Federal Standard (MEF)" d:"The mandatory energy efficiency standards for clothes washers, established by DOE rulemaking activities and federal laws." t:dataTypeName=number

metric m:annual_energy_use_kwh_year p:integer l:"Annual Energy Use (kWh/yr)" d:"This is the estimated annual energy use of the clothes washer under typical conditions, including the energy used by the washer and the energy needed to heat the water used by the clothes washer with an electric water heater. Unlike MEF, the estimated annual energy use does not address how effective the washer is at removing moisture from the wash load and thus reducing the energy needed to fully dry a load in the clothes dryer. It is based on an annual usage of 392 loads per year, or around 8 loads per week, as referenced by the U.S. Department of Energy (DOE) test procedure, Code of Federal Regulations, Title 10, Section 430, Appendix J1. Actual energy consumption will vary depending on various factors such as the amount of laundry done, the size of the loads, and the settings chosen." t:dataTypeName=number

metric m:water_factor_wf p:float l:"Water Factor (WF)" d:"WF is the water performance metric for ENERGY STAR qualified clothes washers. The lower the WF, the more efficient the clothes washer. The metric has units: gallons/cycle/ft3, and is calculated as the quotient of total weighted per-cycle water consumption divided by the capacity of the clothes washer. For example, if a clothes washer has a total weighted per-cycle water consumption of 20 gallons and a tub volume of 4.0 cubic feet, then the water factor is 5.0." t:dataTypeName=number

metric m:us_federal_standard_wf p:float l:"US Federal Standard (WF)" d:"The mandatory water efficiency standards for clothes washers, established by DOE rulemaking activities and federal laws." t:dataTypeName=number

entity e:9g6r-cpdt l:"ENERGY STAR Certified Commercial Clothes Washers" t:url=https://data.energystar.gov/api/views/9g6r-cpdt

property e:9g6r-cpdt t:meta.view v:id=9g6r-cpdt v:category="Active Specifications" v:averageRating=0 v:name="ENERGY STAR Certified Commercial Clothes Washers"

property e:9g6r-cpdt t:meta.view.owner v:id=guxy-scz5 v:screenName=ESddas v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:9g6r-cpdt t:meta.view.tableauthor v:id=guxy-scz5 v:screenName=ESddas v:roleName=publisher v:lastNotificationSeenAt=1491492552 v:displayName=ESddas

property e:9g6r-cpdt t:meta.view.metadata.custom_fields.common_core v:Publisher="U.S. Environmental Protection Agency" v:License=https://edg.epa.gov/EPA_Data_License.html v:Contact_Name="Kathleen Vokes" v:Bureau_Code=020:00 v:Program_Code=020:033
```

## Top Records

```ls
| pd_id   | brand_name | model_number | additional_model_information | upc          | load_configuration | intended_market | volume_cubic_feet | modified_energy_factor_mef | us_federal_standard_mef | annual_energy_use_kwh_year | water_factor_wf | us_federal_standard_wf | date_available_on_market | date_qualified      | markets               | energy_star_model_identifier                   | 
| ======= | ========== | ============ | ============================ | ============ | ================== | =============== | ================= | ========================== | ======================= | ========================== | =============== | ====================== | ======================== | =================== | ===================== | ============================================== | 
| 2238726 | Laundrylux | EHWF09810M   |                              | 1            | Front Load         | Commercial      | 3.5               | 2.47                       | 2                       | 113                        | 3.7             | 5.5                    | 2012-05-30T00:00:00      | 2012-03-27T00:00:00 | United States, Canada | ES_0031566_EHWF09810M_05042015024816_70031392  | 
| 2238727 | Laundrylux | EHWF09810NM  |                              | 1            | Front Load         | Commercial      | 3.5               | 2.47                       | 2                       | 113                        | 3.7             | 5.5                    | 2012-05-30T00:00:00      | 2012-03-27T00:00:00 | United States, Canada | ES_0031566_EHWF09810NM_05042015024815_70031392 | 
| 2285547 | Laundrylux | WHLFP715M    |                              | 856013006016 | Front Load         | Commercial      | 3.5               | 2.47                       | 2                       | 113                        | 3.7             | 5.5                    | 2016-12-01T00:00:00      | 2016-11-04T00:00:00 | United States, Canada | ES_0031566_WHLFP715M _11012016113615_7010486   | 
| 2238724 | Laundrylux | WHWF09810M   |                              | 1            | Front Load         | Commercial      | 3.5               | 2.47                       | 2                       | 113                        | 3.7             | 5.5                    | 2012-05-30T00:00:00      | 2012-03-27T00:00:00 | United States, Canada | ES_0031566_WHWF09810M_05042015024818_70031392  | 
| 2238725 | Laundrylux | WHWF09810NM  |                              | 1            | Front Load         | Commercial      | 3.5               | 2.47                       | 2                       | 113                        | 3.7             | 5.5                    | 2012-05-30T00:00:00      | 2012-03-27T00:00:00 | United States, Canada | ES_0031566_WHWF09810NM_05042015024817_70031392 | 
| 2282585 | LG         | GCWF1069**#  |                              | 1            | Front Load         | Commercial      | 3.7               | 3                          | 2                       | 130                        | 3.7             | 5.5                    | 2016-10-01T00:00:00      | 2016-10-25T00:00:00 | United States, Canada | ES_1118034_GCWF1069**#_10272016041759_70099627 | 
| 2235869 | LG         | GCWP1069***  |                              | 1            | Front Load         | Commercial      | 3.6               | 2.6                        | 2                       | 145                        | 3.7             | 5.5                    | 2014-12-31T00:00:00      | 2015-03-31T00:00:00 | United States, Canada | ES_1118034_GCWP1069***_04062015061649_2685304  | 
| 2235868 | LG         | TCW2013***   |                              | 1            | Front Load         | Commercial      | 5.2               | 2.4                        | 2                       | 195                        | 4               | 5.5                    | 2014-04-30T00:00:00      | 2015-03-31T00:00:00 | United States, Canada | ES_1118034_TCW2013***_04062015061649_2691999   | 
| 2236110 | Maytag     | MHN30PDCW*+  |                              | 883049343280 | Front Load         | Commercial      | 3.1               | 2.5                        | 2                       | 120                        | 3.9             | 5.5                    | 2014-05-01T00:00:00      | 2014-05-05T00:00:00 | United States, Canada | ES_0022856_MHN30PDCW*+_04092015012959_8888884  | 
| 2265258 | Maytag     | MHN30PDCW*+  |                              | 8            | Front Load         | Commercial      | 3.1               | 2.5                        | 2                       | 120                        | 3.9             | 5.5                    | 2016-06-01T00:00:00      | 2016-04-25T00:00:00 | United States, Canada | ES_22856_MHN30PDCW*+_04252016204919_7359751    | 
```