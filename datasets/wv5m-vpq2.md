# Historic Secured Property Tax Rolls

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/historic-secured-property-tax-rolls) |
| Metadata | [Link](https://data.sfgov.org/api/views/wv5m-vpq2) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/wv5m-vpq2/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/wv5m-vpq2/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | wv5m-vpq2 |
| Name | Historic Secured Property Tax Rolls |
| Category | Housing and Buildings |
| Tags | valuation, property, property tax, property value |
| Created | 2016-03-21T20:12:21Z |
| Publication Date | 2017-03-31T17:13:18Z |

## Description

This data set includes the Office of the Assessor-Recorder?s secured property tax roll spanning from 2007 to 2016. It includes all legally disclosable information, including location of property, value of property, the unique property identifier, and specific property characteristics. The data is used to accurately and fairly appraise all taxable property in the City and County of San Francisco. The Office of the Assessor-Recorder makes no representation or warranty that the information provided is accurate and/or has no errors or omissions. Please see the attached documentation under About for more.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| No       |                | closed_roll_fiscal_year                    | Closed Roll Fiscal Year                    | number    | text        |
| Yes      | series tag     | property_location                          | Property Location                          | text      | text        |
| Yes      | series tag     | neighborhood_code                          | Neighborhood Code                          | text      | text        |
| Yes      | series tag     | neighborhood_code_definition               | Neighborhood Code Definition               | text      | text        |
| Yes      | series tag     | block_and_lot_number                       | Block and Lot Number                       | text      | text        |
| Yes      | series tag     | volume_number                              | Volume Number                              | text      | number      |
| Yes      | series tag     | property_class_code                        | Property Class Code                        | text      | text        |
| Yes      | series tag     | property_class_code_definition             | Property Class Code Definition             | text      | text        |
| Yes      | numeric metric | year_property_built                        | Year Property Built                        | number    | text        |
| Yes      | numeric metric | number_of_bathrooms                        | Number of Bathrooms                        | number    | number      |
| Yes      | numeric metric | number_of_bedrooms                         | Number of Bedrooms                         | number    | number      |
| Yes      | numeric metric | number_of_rooms                            | Number of Rooms                            | number    | number      |
| Yes      | numeric metric | number_of_stories                          | Number of Stories                          | number    | number      |
| Yes      | numeric metric | number_of_units                            | Number of Units                            | number    | number      |
| No       |                | characteristics_change_date                | Characteristics Change Date                | date      | date        |
| Yes      | series tag     | zoning_code                                | Zoning Code                                | text      | text        |
| Yes      | series tag     | construction_type                          | Construction Type                          | text      | text        |
| Yes      | numeric metric | lot_depth                                  | Lot Depth                                  | number    | number      |
| Yes      | numeric metric | lot_frontage                               | Lot Frontage                               | number    | number      |
| Yes      | numeric metric | property_area_in_square_feet               | Property Area in Square Feet               | number    | number      |
| Yes      | numeric metric | basement_area                              | Basement Area                              | number    | number      |
| Yes      | numeric metric | lot_area                                   | Lot Area                                   | number    | number      |
| Yes      | series tag     | lot_code                                   | Lot Code                                   | text      | text        |
| No       |                | prior_sales_date                           | Prior Sales Date                           | date      | date        |
| Yes      | time           | recordation_date                           | Recordation Date                           | date      | date        |
| Yes      | series tag     | document_number                            | Document Number                            | text      | text        |
| Yes      | numeric metric | document_number_2                          | Document Number 2                          | number    | text        |
| Yes      | series tag     | tax_rate_area_code                         | Tax Rate Area Code                         | text      | text        |
| Yes      | numeric metric | percent_of_ownership                       | Percent of Ownership                       | number    | number      |
| Yes      | series tag     | closed_roll_exemption_type_code            | Closed Roll Exemption Type Code            | text      | text        |
| Yes      | series tag     | closed_roll_exemption_type_code_definition | Closed Roll Exemption Type Code Definition | text      | text        |
| Yes      | series tag     | closed_roll_status_code                    | Closed Roll Status Code                    | text      | text        |
| Yes      | numeric metric | closed_roll_misc_exemption_value           | Closed Roll Misc Exemption Value           | number    | number      |
| Yes      | numeric metric | closed_roll_homeowner_exemption_value      | Closed Roll Homeowner Exemption Value      | number    | number      |
| No       |                | current_sales_date                         | Current Sales Date                         | date      | date        |
| Yes      | numeric metric | closed_roll_assessed_fixtures_value        | Closed Roll Assessed Fixtures Value        | number    | number      |
| Yes      | numeric metric | closed_roll_assessed_improvement_value     | Closed Roll Assessed Improvement Value     | number    | number      |
| Yes      | numeric metric | closed_roll_assessed_land_value            | Closed Roll Assessed Land Value            | number    | number      |
| Yes      | numeric metric | closed_roll_assessed_personal_prop_value   | Closed Roll Assessed Personal Prop Value   | number    | number      |
| Yes      | series tag     | supervisor_district                        | Supervisor District                        | text      | text        |
| Yes      | series tag     | neighborhood_district                      | Neighborhoods - Analysis Boundaries        | text      | text        |
```

## Time Field

```ls
Value = recordation_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = characteristics_change_date,prior_sales_date,current_sales_date,closed_roll_fiscal_year
```

## Data Commands

```ls
series e:wv5m-vpq2 d:1990-07-31T00:00:00.000Z t:volume_number=25 t:block_and_lot_number=3722273 t:document_number=I809 t:property_location="0000 0188 MINNA               ST0024C" t:property_class_code_definition=Z t:neighborhood_district="Financial District/South Beach" t:tax_rate_area_code=1005 t:supervisor_district=6 t:neighborhood_code=09B t:property_class_code=Z m:number_of_bathrooms=2 m:year_property_built=2005 m:lot_frontage=0 m:percent_of_ownership=1 m:closed_roll_misc_exemption_value=0 m:closed_roll_assessed_personal_prop_value=0 m:document_number_2=119 m:property_area_in_square_feet=1670 m:lot_area=0 m:closed_roll_homeowner_exemption_value=0 m:closed_roll_assessed_land_value=1140725 m:number_of_units=0 m:closed_roll_assessed_fixtures_value=0 m:number_of_bedrooms=2 m:lot_depth=0 m:closed_roll_assessed_improvement_value=760483 m:basement_area=0 m:number_of_rooms=5 m:number_of_stories=0

series e:wv5m-vpq2 d:2011-04-15T00:00:00.000Z t:volume_number=9 t:block_and_lot_number=1278032 t:document_number=J163 t:property_location="0000 1006 COLE                ST0000" t:property_class_code_definition=Z t:construction_type=D t:neighborhood_district="Haight Ashbury" t:tax_rate_area_code=1000 t:zoning_code=RH3 t:neighborhood_code_definition="Parnassus/Ashbury Heights" t:supervisor_district=5 t:neighborhood_code=05E t:property_class_code=Z m:number_of_bathrooms=3 m:year_property_built=1907 m:lot_frontage=0 m:percent_of_ownership=1 m:closed_roll_misc_exemption_value=0 m:closed_roll_assessed_personal_prop_value=0 m:document_number_2=78 m:property_area_in_square_feet=1450 m:lot_area=0 m:closed_roll_homeowner_exemption_value=0 m:closed_roll_assessed_land_value=519843 m:number_of_units=1 m:closed_roll_assessed_fixtures_value=0 m:number_of_bedrooms=3 m:lot_depth=0 m:closed_roll_assessed_improvement_value=346562 m:basement_area=0 m:number_of_rooms=6 m:number_of_stories=1

series e:wv5m-vpq2 d:1974-11-19T00:00:00.000Z t:volume_number=5 t:block_and_lot_number=0685050 t:property_location="0000 0000VWEBSTER             ST0000" t:property_class_code_definition=V t:construction_type=D t:neighborhood_district=Japantown t:tax_rate_area_code=1007 t:zoning_code=NC2 t:neighborhood_code_definition="Lower Pacific Heights" t:supervisor_district=5 t:neighborhood_code=06C t:property_class_code=V m:number_of_bathrooms=0 m:year_property_built=1900 m:lot_frontage=0 m:percent_of_ownership=1 m:closed_roll_misc_exemption_value=0 m:closed_roll_assessed_personal_prop_value=0 m:document_number_2=0 m:property_area_in_square_feet=0 m:lot_area=0 m:closed_roll_homeowner_exemption_value=0 m:closed_roll_assessed_land_value=182948 m:number_of_units=0 m:closed_roll_assessed_fixtures_value=0 m:number_of_bedrooms=0 m:lot_depth=0 m:closed_roll_assessed_improvement_value=17572 m:basement_area=0 m:number_of_rooms=0 m:number_of_stories=0
```

## Meta Commands

```ls
metric m:year_property_built p:integer l:"Year Property Built" d:"Year improvement was built (can be blend of original and newer construction)" t:dataTypeName=number

metric m:number_of_bathrooms p:integer l:"Number of Bathrooms" d:"Number of bathrooms (BA with no shower or tub is 1/2 bathroom)" t:dataTypeName=number

metric m:number_of_bedrooms p:integer l:"Number of Bedrooms" d:"Number of bedrooms (bedrooms have a closet)" t:dataTypeName=number

metric m:number_of_rooms p:integer l:"Number of Rooms" d:"Number of rooms, excluding bathrooms, halls, closets, etc." t:dataTypeName=number

metric m:number_of_stories p:integer l:"Number of Stories" d:"Number of stories" t:dataTypeName=number

metric m:number_of_units p:integer l:"Number of Units" d:"Number of units" t:dataTypeName=number

metric m:lot_depth p:float l:"Lot Depth" d:"Depth of lot in linear feet" t:dataTypeName=number

metric m:lot_frontage p:float l:"Lot Frontage" d:"Linear footage of front facing side of lot (front foot)" t:dataTypeName=number

metric m:property_area_in_square_feet p:integer l:"Property Area in Square Feet" d:"Square footage of lot" t:dataTypeName=number

metric m:basement_area p:integer l:"Basement Area" d:"Square footage of basement" t:dataTypeName=number

metric m:lot_area p:integer l:"Lot Area" d:"Square footage of lot" t:dataTypeName=number

metric m:document_number_2 p:integer l:"Document Number 2" t:dataTypeName=number

metric m:percent_of_ownership p:double l:"Percent of Ownership" d:"Percent of ownership" t:dataTypeName=number

metric m:closed_roll_misc_exemption_value p:integer l:"Closed Roll Misc Exemption Value" d:"Exemption value for misc. exemptions such as Welfare" t:dataTypeName=number

metric m:closed_roll_homeowner_exemption_value p:integer l:"Closed Roll Homeowner Exemption Value" d:"Homeowner's exemption value" t:dataTypeName=number

metric m:closed_roll_assessed_fixtures_value p:integer l:"Closed Roll Assessed Fixtures Value" d:"Assessed value of fixtures" t:dataTypeName=number

metric m:closed_roll_assessed_improvement_value p:integer l:"Closed Roll Assessed Improvement Value" d:"Assessed value of improvements" t:dataTypeName=number

metric m:closed_roll_assessed_land_value p:integer l:"Closed Roll Assessed Land Value" d:"Assessed value of land" t:dataTypeName=number

metric m:closed_roll_assessed_personal_prop_value p:integer l:"Closed Roll Assessed Personal Prop Value" d:"Assessed value of personal property" t:dataTypeName=number

entity e:wv5m-vpq2 l:"Historic Secured Property Tax Rolls" t:url=https://data.sfgov.org/api/views/wv5m-vpq2

property e:wv5m-vpq2 t:meta.view v:id=wv5m-vpq2 v:category="Housing and Buildings" v:averageRating=0 v:name="Historic Secured Property Tax Rolls"

property e:wv5m-vpq2 t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wv5m-vpq2 t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:wv5m-vpq2 t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| closed_roll_fiscal_year | property_location                 | neighborhood_code | neighborhood_code_definition | block_and_lot_number | volume_number | property_class_code | property_class_code_definition | year_property_built | number_of_bathrooms | number_of_bedrooms | number_of_rooms | number_of_stories | number_of_units | characteristics_change_date | zoning_code | construction_type | lot_depth | lot_frontage | property_area_in_square_feet | basement_area | lot_area | lot_code | prior_sales_date | recordation_date | document_number | document_number_2 | tax_rate_area_code | percent_of_ownership | closed_roll_exemption_type_code | closed_roll_exemption_type_code_definition | closed_roll_status_code | closed_roll_misc_exemption_value | closed_roll_homeowner_exemption_value | current_sales_date | closed_roll_assessed_fixtures_value | closed_roll_assessed_improvement_value | closed_roll_assessed_land_value | closed_roll_assessed_personal_prop_value | supervisor_district | neighborhood_district          | 
| ======================= | ================================= | ================= | ============================ | ==================== | ============= | =================== | ============================== | =================== | =================== | ================== | =============== | ================= | =============== | =========================== | =========== | ================= | ========= | ============ | ============================ | ============= | ======== | ======== | ================ | ================ | =============== | ================= | ================== | ==================== | =============================== | ========================================== | ======================= | ================================ | ===================================== | ================== | =================================== | ====================================== | =============================== | ======================================== | =================== | ============================== | 
| 2012                    | 0000 0188 MINNA ST0024C           | 09B               |                              | 3722273              | 25            | Z                   | Z                              | 2005                | 2                   | 2                  | 5               | 0                 | 0               |                             |             |                   | 0         | 0            | 1670                         | 0             | 0        |          |                  | 649382400        | I809            | 119               | 1005               | 1                    |                                 |                                            |                         | 0                                | 0                                     | 649382400          | 0                                   | 760483                                 | 1140725                         | 0                                        | 6                   | Financial District/South Beach | 
| 2014                    | 0000 1006 COLE ST0000             | 05E               | Parnassus/Ashbury Heights    | 1278032              | 9             | Z                   | Z                              | 1907                | 3                   | 3                  | 6               | 1                 | 1               |                             | RH3         | D                 | 0         | 0            | 1450                         | 0             | 0        |          |                  | 1302825600       | J163            | 78                | 1000               | 1                    |                                 |                                            |                         | 0                                | 0                                     | 1302825600         | 0                                   | 346562                                 | 519843                          | 0                                        | 5                   | Haight Ashbury                 | 
| 2007                    | 0000 0000VWEBSTER ST0000          | 06C               | Lower Pacific Heights        | 0685050              | 5             | V                   | V                              | 1900                | 0                   | 0                  | 0               | 0                 | 0               |                             | NC2         | D                 | 0         | 0            | 0                            | 0             | 0        |          |                  | 154051200        |                 | 0                 | 1007               | 1                    |                                 |                                            |                         | 0                                | 0                                     |                    | 0                                   | 17572                                  | 182948                          | 0                                        | 5                   | Japantown                      | 
| 2014                    | 0000 0601 VAN NESS AV0044         | 08F               | Van Ness/ Civic Center       | 0762044              | 6             | Z                   | Z                              | 1982                | 3                   | 3                  | 5               | 2                 | 1               |                             | RC4         | C                 | 0         | 0            | 1037                         | 0             | 0        |          |                  | 1392681600       | G897            | 177               | 1007               | 1                    | 11                              | Home Owners                                |                         | 0                                | 7000                                  | 1264896000         | 0                                   | 295002                                 | 295002                          | 0                                        | 5                   | Western Addition               | 
| 2008                    | 0000 1221 HARRISON ST0014         | 09F               | South of Market              | 3757127              | 25            | LZ                  | LZ                             | 2004                | 0                   | 0                  | 0               | 0                 | 0               |                             |             |                   | 0         | 0            | 1185                         | 0             | 0        |          |                  | -626140800       | H911            | 265               | 1000               | 1                    |                                 |                                            |                         | 0                                | 0                                     | -933984000         | 0                                   | 249383                                 | 424483                          | 0                                        | 6                   | South of Market                | 
| 2012                    | 0000 0517 11TH AV0000             | 01B               | Inner Richmond               | 1554002              | 11            | D                   | D                              | 1913                | 0                   | 0                  | 6               | 2                 | 1               |                             | RH2         | D                 | 0         | 0            | 1950                         | 0             | 2495     | O        |                  | 885772800        |                 | 0                 | 1000               | 0.66666              |                                 |                                            |                         | 0                                | 0                                     |                    | 0                                   | 42819                                  | 35093                           | 0                                        | 1                   | Inner Richmond                 | 
| 2008                    | 0000 3124 PACHECO ST0000          | 02D               | Parkside                     | 2099002J             | 16            | D                   | D                              | 1949                | 2                   | 2                  | 5               | 1                 | 1               |                             | RH1         | D                 | 0         | 0            | 1080                         | 0             | 2500     | R        |                  | 1280016000       |                 | 0                 | 1000               | 1                    | 11                              | Home Owners                                |                         | 0                                | 7000                                  | 692496000          | 0                                   | 141354                                 | 215399                          | 0                                        | 4                   | Sunset/Parkside                | 
| 2015                    | 0000 9350 BUENA VISTA WEST AV0000 | 05F               | Buena Vista Park             | 1242002              | 9             | F                   | F                              | 1904                | 2                   | 2                  | 10              | 3                 | 1               |                             | RH3         | D                 | 50        | 0            | 2920                         | 0             | 1412.5   | R        |                  | -299548800       |                 | 0                 | 1000               | 1                    |                                 |                                            |                         | 0                                | 0                                     |                    | 0                                   | 178507                                 | 142799                          | 0                                        | 5                   | Haight Ashbury                 | 
| 2014                    | 0000 0235 BERRY ST0403            | 09D               | Mission Bay                  | 8708148              | 44            | Z                   | Z                              | 2007                | 2                   | 2                  | 0               | 0                 | 0               |                             |             |                   | 0         | 0            | 1070                         | 0             | 0        |          |                  | 1380758400       | I331            | 226               | 1013               | 0.7                  | 11                              | Home Owners                                |                         | 0                                | 7000                                  | 2764800            | 0                                   | 421593                                 | 421593                          | 0                                        | 6                   | Mission Bay                    | 
| 2008                    | 0000 2582 GREAT HW0000            | 02B               | Outer Parkside               | 2448002F             | 18            | D                   | D                              | 1941                | 4                   | 4                  | 9               | 2                 | 1               |                             | RH1         | D                 | 0         | 0            | 2361                         | 475           | 2957     |          |                  |                  | I491            | 509               | 1000               | 1                    | 11                              | Home Owners                                |                         | 0                                | 7000                                  |                    | 0                                   | 465000                                 | 1085000                         | 0                                        | 4                   | Sunset/Parkside                | 
```