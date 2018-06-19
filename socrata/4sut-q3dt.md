# Real Property Assessment Equity Statistics By Municipality: Beginning 2004

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/real-property-assessment-equity-statistics-by-municipality-beginning-2004) |
| Metadata | [Link](https://data.ny.gov/api/views/4sut-q3dt) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4sut-q3dt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4sut-q3dt/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4sut-q3dt |
| Name | Real Property Assessment Equity Statistics By Municipality: Beginning 2004 |
| Attribution | New York State Department of Taxation and Finance |
| Category | Government & Finance |
| Tags | equity, coefficient of dispersion, price-related differential, reassessment |
| Created | 2013-03-05T17:24:26Z |
| Publication Date | 2017-03-06T23:04:49Z |

## Description

The Department of Taxation and Finance annually produces a report documenting the results of the Market Value Survey pertaining to property assessment.  The report contains the staff findings regarding assessment equity by municipality in New York State, that is, the degree to which assessments are at a uniform percentage of their market value.  Equity is measured primarily by two statistics ? the coefficient of dispersion (COD) and the price-related differential (PRD).  For more information please go to:  http://www.tax.ny.gov/research/property/default.htm

## Columns

```ls
| Included | Schema Type    | Field Name                                              | Name                                                    | Data Type     | Render Type   |
| ======== | ============== | ======================================================= | ======================================================= | ============= | ============= |
| No       |                | survey_year                                             | Survey Year                                             | number        | number        |
| Yes      | series tag     | swis_code                                               | Swis Code                                               | text          | text          |
| Yes      | series tag     | municipality                                            | Municipality                                            | text          | text          |
| Yes      | series tag     | county                                                  | County                                                  | text          | text          |
| Yes      | numeric metric | population_per_square_mile                              | Population Per Square Mile                              | number        | number        |
| Yes      | series tag     | population_group                                        | Population Group                                        | text          | text          |
| Yes      | series tag     | method_of_evaluating_equity_for_residential_property    | Method of Evaluating Equity for Residential Property    | text          | text          |
| Yes      | numeric metric | residential_coefficient_of_dispersion                   | Residential Coefficient of Dispersion                   | number        | number        |
| Yes      | numeric metric | residential_price_related_differential                  | Residential Price Related Differential                  | number        | number        |
| Yes      | numeric metric | residential_market_value_ratio                          | Residential Market Value Ratio                          | number        | number        |
| Yes      | series tag     | method_of_evaluating_equity_for_all_property            | Method of Evaluating Equity for All Property            | text          | text          |
| Yes      | numeric metric | all_property_coefficient_of_dispersion                  | All Property Coefficient of Dispersion                  | number        | number        |
| Yes      | numeric metric | all_property_price_related_differential                 | All Property Price Related Differential                 | number        | number        |
| Yes      | numeric metric | subsequent_year_of_reassessment                         | Subsequent Year of Reassessment                         | number        | number        |
| Yes      | series tag     | does_municipality_have_a_plan_for_cyclical_reassessment | Does Municipality have a plan for Cyclical Reassessment | text          | text          |
| Yes      | time           | report_or_data_preparation_date                         | Report or Data Preparation Date                         | calendar_date | calendar_date |
| Yes      | numeric metric | equalization_rate                                       | Equalization Rate                                       | number        | number        |
| Yes      | numeric metric | municipality_stated_uniform_percentage                  | Municipality Stated Uniform Percentage                  | number        | number        |
```

## Time Field

```ls
Value = report_or_data_preparation_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = survey_year
```

## Data Commands

```ls
series e:4sut-q3dt d:2013-12-04T00:00:00.000Z t:county=Albany t:method_of_evaluating_equity_for_residential_property=CAMA t:method_of_evaluating_equity_for_all_property=CAMA/Appraisals t:municipality=Albany t:swis_code=010100 t:population_group=C m:residential_market_value_ratio=111.71 m:all_property_coefficient_of_dispersion=13.65 m:population_per_square_mile=4575 m:all_property_price_related_differential=1 m:residential_price_related_differential=1 m:residential_coefficient_of_dispersion=14.21 m:municipality_stated_uniform_percentage=111.71 m:equalization_rate=111.71

series e:4sut-q3dt d:2013-12-04T00:00:00.000Z t:county=Albany t:method_of_evaluating_equity_for_residential_property="Sales Ratio" t:method_of_evaluating_equity_for_all_property=Sales/Appraisals t:municipality=Cohoes t:swis_code=010300 t:population_group=C m:residential_market_value_ratio=56 m:all_property_coefficient_of_dispersion=20.08 m:population_per_square_mile=4285 m:all_property_price_related_differential=1.08 m:residential_price_related_differential=1.07 m:residential_coefficient_of_dispersion=19.89 m:municipality_stated_uniform_percentage=56 m:equalization_rate=56

series e:4sut-q3dt d:2013-12-04T00:00:00.000Z t:county=Albany t:method_of_evaluating_equity_for_residential_property="Review of Reassessment" t:method_of_evaluating_equity_for_all_property="Review of Reassessment" t:municipality=Watervliet t:swis_code=011800 t:population_group=C t:does_municipality_have_a_plan_for_cyclical_reassessment=Yes m:residential_market_value_ratio=100 m:population_per_square_mile=7621 m:municipality_stated_uniform_percentage=100 m:subsequent_year_of_reassessment=2015 m:equalization_rate=100
```

## Meta Commands

```ls
metric m:population_per_square_mile p:integer l:"Population Per Square Mile" d:"Population per square mile for municipality based on 2010 census" t:dataTypeName=number

metric m:residential_coefficient_of_dispersion p:float l:"Residential Coefficient of Dispersion" d:"Review of Reassessment municipalities are deemed equitable due to their recent reassessment. Desired Maximum All-Property Coefficient of Dispersion by Population: A - 20.00, B - 17.00, C - 15.00." t:dataTypeName=number

metric m:residential_price_related_differential p:float l:"Residential Price Related Differential" d:"Price Related Differential statistics not calculated for Review of Reassessment municipalities." t:dataTypeName=number

metric m:residential_market_value_ratio p:float l:"Residential Market Value Ratio" d:"The ratio on residential property calculated by Tax and Finance for the survey year" t:dataTypeName=number

metric m:all_property_coefficient_of_dispersion p:float l:"All Property Coefficient of Dispersion" d:"Review of Reassessment municipalities are deemed equitable due to their recent reassessment. Desired Maximum All-Property Coefficient of Dispersion by Population: A - 20.00, B - 17.00, C - 15.00." t:dataTypeName=number

metric m:all_property_price_related_differential p:float l:"All Property Price Related Differential" d:"Price Related Differential statistics not calculated for Review of Reassessment municipalities." t:dataTypeName=number

metric m:subsequent_year_of_reassessment p:integer l:"Subsequent Year of Reassessment" d:"As of the report preparation time, the planned roll year for the next reassessment" t:dataTypeName=number

metric m:equalization_rate p:float l:"Equalization Rate" d:"Municipal equalization rate for the survey year" t:dataTypeName=number

metric m:municipality_stated_uniform_percentage p:float l:"Municipality Stated Uniform Percentage" d:"The uniform percentage at which properties are assessed, as stated by the municipality" t:dataTypeName=number

entity e:4sut-q3dt l:"Real Property Assessment Equity Statistics By Municipality: Beginning 2004" t:attribution="New York State Department of Taxation and Finance" t:url=https://data.ny.gov/api/views/4sut-q3dt

property e:4sut-q3dt t:meta.view v:id=4sut-q3dt v:category="Government & Finance" v:attributionLink=http://www.tax.ny.gov/pubs_and_bulls/orpts/publications/reports_annual.htm v:averageRating=0 v:name="Real Property Assessment Equity Statistics By Municipality: Beginning 2004" v:attribution="New York State Department of Taxation and Finance"

property e:4sut-q3dt t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4sut-q3dt t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4sut-q3dt t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| survey_year | swis_code | municipality | county | population_per_square_mile | population_group | method_of_evaluating_equity_for_residential_property | residential_coefficient_of_dispersion | residential_price_related_differential | residential_market_value_ratio | method_of_evaluating_equity_for_all_property | all_property_coefficient_of_dispersion | all_property_price_related_differential | subsequent_year_of_reassessment | does_municipality_have_a_plan_for_cyclical_reassessment | report_or_data_preparation_date | equalization_rate | municipality_stated_uniform_percentage | 
| =========== | ========= | ============ | ====== | ========================== | ================ | ==================================================== | ===================================== | ====================================== | ============================== | ============================================ | ====================================== | ======================================= | =============================== | ======================================================= | =============================== | ================= | ====================================== | 
| 2013        | 010100    | Albany       | Albany | 4575                       | C                | CAMA                                                 | 14.21                                 | 1                                      | 111.71                         | CAMA/Appraisals                              | 13.65                                  | 1                                       |                                 |                                                         | 2013-12-04T00:00:00             | 111.71            | 111.71                                 | 
| 2013        | 010300    | Cohoes       | Albany | 4285                       | C                | Sales Ratio                                          | 19.89                                 | 1.07                                   | 56                             | Sales/Appraisals                             | 20.08                                  | 1.08                                    |                                 |                                                         | 2013-12-04T00:00:00             | 56                | 56                                     | 
| 2013        | 011800    | Watervliet   | Albany | 7621                       | C                | Review of Reassessment                               |                                       |                                        | 100                            | Review of Reassessment                       |                                        |                                         | 2015                            | Yes                                                     | 2013-12-04T00:00:00             | 100               | 100                                    | 
| 2013        | 012000    | Berne        | Albany | 44                         | A                | Sales/Appraisals                                     | 26.5                                  | 1.1                                    | 66                             | Sales/Appraisals                             | 27.4                                   | 0.95                                    |                                 |                                                         | 2013-12-04T00:00:00             | 67                | 67                                     | 
| 2013        | 012200    | Bethlehem    | Albany | 686                        | C                | Sales Ratio                                          | 6.88                                  | 1                                      | 100                            | Sales/Appraisals                             | 6.9                                    | 1                                       | 2014                            | Yes                                                     | 2013-12-04T00:00:00             | 100               | 100                                    | 
| 2013        | 012400    | Coeymans     | Albany | 148                        | B                | CAMA                                                 | 8.94                                  | 1                                      | 106.69                         | CAMA/Appraisals                              | 8.64                                   | 1                                       |                                 |                                                         | 2013-12-04T00:00:00             | 100               | 100                                    | 
| 2013        | 012600    | Colonie      | Albany | 1458                       | C                | Sales Ratio                                          | 11.56                                 | 1                                      | 59.82                          | Sales/Appraisals                             | 13.2                                   | 0.92                                    |                                 |                                                         | 2013-12-04T00:00:00             | 70.25             | 70.25                                  | 
| 2013        | 012800    | Green Island | Albany | 3507                       | C                | Sales Ratio                                          | 19.59                                 | 1.05                                   | 4.6                            | Sales/Appraisals                             | 23.11                                  | 0.79                                    | 2014                            |                                                         | 2013-12-04T00:00:00             | 5.84              | 5.84                                   | 
| 2013        | 013000    | Guilderland  | Albany | 610                        | C                | Sales Ratio                                          | 12.45                                 | 1                                      | 92                             | Sales/Appraisals                             | 12.49                                  | 1.03                                    |                                 |                                                         | 2013-12-04T00:00:00             | 92                | 92                                     | 
| 2013        | 013200    | Knox         | Albany | 64                         | A                | Sales/Appraisals                                     | 18.1                                  | 1.06                                   | 61.2                           | Sales/Appraisals                             | 22.26                                  | 0.97                                    |                                 |                                                         | 2013-12-04T00:00:00             | 62                | 62                                     | 
```