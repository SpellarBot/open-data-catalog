# Medicaid Coverage Of Cessation Treatments And Barriers To Treatments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/medicaid-coverage-of-cessation-treatments-and-barriers-to-treatments-a9fe0) |
| Metadata | [Link](https://data.cdc.gov/api/views/ntaa-dtex) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/ntaa-dtex/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/ntaa-dtex/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | ntaa-dtex |
| Name | Medicaid Coverage Of Cessation Treatments And Barriers To Treatments |
| Attribution | Centers for Disease Control and Prevention National Center for Disease Prevention and Health Promotion Office on Smoking and Health |
| Category | Cessation Coverage |
| Tags | american lung association, osh, office on smoking and health, cessation coverage, medicaid coverage of cessation treatment, comprehensive medicaid coverage |
| Created | 2014-04-22T11:56:58Z |
| Publication Date | 2017-04-13T14:10:30Z |

## Description

2008-2017. American Lung Association. Cessation Coverage.  Medicaid data compiled by the Centers for Disease Control and Prevention?s Office on Smoking and Health were obtained from the State Tobacco Cessation Coverage Database, developed and administered by the American Lung Association.  Data from 2008-2012 are reported on an annual basis; beginning in 2013 data are reported on a quarterly basis.  Data include state-level information on Medicaid coverage of approved medications by the Food and Drug Administration (FDA) for tobacco cessation treatment; types of counseling recommended by the Public Health Service (PHS) and barriers to accessing cessation treatment. Note: Section 2502 of the Patient Protection and Affordable Care Act requires all state Medicaid programs to cover all FDA-approved tobacco cessation medications as of January 1, 2014. However, states are currently in the process of modifying their coverage to come into compliance with this requirement. Data in the STATE System on Medicaid coverage of tobacco cessation medications reflect evidence of coverage that is found in documentable sources, and may not yet reflect medications covered under this requirement.

## Columns

```ls
| Included | Schema Type    | Field Name                     | Name                           | Data Type | Render Type |
| ======== | ============== | ============================== | ============================== | ========= | =========== |
| No       |                | year                           | Year                           | number    | number      |
| No       |                | quarter                        | Quarter                        | number    | number      |
| Yes      | series tag     | locationabbrv                  | LocationAbbrv                  | text      | text        |
| Yes      | series tag     | locationdesc                   | LocationDesc                   | text      | text        |
| Yes      | series tag     | topictype                      | TopicType                      | text      | text        |
| Yes      | series tag     | topic                          | Topic                          | text      | text        |
| Yes      | series tag     | measure                        | Measure                        | text      | text        |
| Yes      | series tag     | submeasure                     | SubMeasure                     | text      | text        |
| Yes      | series tag     | fee_for_service_plans          | Fee-For-Service Plans          | text      | text        |
| Yes      | numeric metric | fee_for_service_plans_altvalue | Fee-For-Service_Plans_AltValue | number    | number      |
| Yes      | series tag     | managed_care_plans             | Managed Care Plans             | text      | text        |
| Yes      | numeric metric | managed_care_plans_altvalue    | Managed Care Plans_AltValue    | number    | number      |
| Yes      | series tag     | summary                        | Summary                        | text      | text        |
| Yes      | numeric metric | summary_altvalue               | Summary_AltValue               | number    | number      |
| No       |                | data_value_footnote_symbol     | Data_Value_Footnote_Symbol     | text      | text        |
| No       |                | data_value_footnote            | Data_Value_Footnote            | text      | text        |
| Yes      | series tag     | datasource                     | DataSource                     | text      | text        |
| Yes      | series tag     | topictypeid                    | TopicTypeId                    | text      | text        |
| Yes      | series tag     | topicid                        | TopicId                        | text      | text        |
| Yes      | series tag     | measureid                      | MeasureId                      | text      | text        |
| Yes      | series tag     | submeasureid                   | SubMeasureID                   | text      | text        |
| No       |                | displayorder                   | DisplayOrder                   | number    | text        |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = data_value_footnote_symbol,data_value_footnote,displayorder,year,quarter
```

## Data Commands

```ls
series e:ntaa-dtex d:2016-10-01T00:00:00.000Z t:topic="Medicaid Coverage of Cessation Treatments and Barriers to Treatments" t:summary=Yes t:locationdesc=Alaska t:topicid=910MED t:measure="Barriers to Treatments" t:managed_care_plans="Not Applicable" t:measureid=1000BT t:fee_for_service_plans=Yes t:locationabbrv=AK t:submeasure="Barriers to Treatments" t:topictype="Cessation Coverage" t:submeasureid=MCB011 t:datasource="American Lung Association" t:topictypeid=MED m:fee_for_service_plans_altvalue=2 m:summary_altvalue=2 m:managed_care_plans_altvalue=5

series e:ntaa-dtex d:2016-10-01T00:00:00.000Z t:topic="Medicaid Coverage of Cessation Treatments and Barriers to Treatments" t:summary=Yes t:locationdesc=Alaska t:topicid=910MED t:measure="Barriers to Treatments" t:managed_care_plans="Not Applicable" t:measureid=1000BT t:fee_for_service_plans=Yes t:locationabbrv=AK t:submeasure="Co-Payments Required" t:topictype="Cessation Coverage" t:submeasureid=MCB012 t:datasource="American Lung Association" t:topictypeid=MED m:fee_for_service_plans_altvalue=2 m:summary_altvalue=2 m:managed_care_plans_altvalue=5

series e:ntaa-dtex d:2016-10-01T00:00:00.000Z t:topic="Medicaid Coverage of Cessation Treatments and Barriers to Treatments" t:summary=Yes t:locationdesc=Alaska t:topicid=910MED t:measure="Barriers to Treatments" t:managed_care_plans="Not Applicable" t:measureid=1000BT t:fee_for_service_plans=Yes t:locationabbrv=AK t:submeasure="Prior Authorization Required" t:topictype="Cessation Coverage" t:submeasureid=MCB013 t:datasource="American Lung Association" t:topictypeid=MED m:fee_for_service_plans_altvalue=2 m:summary_altvalue=2 m:managed_care_plans_altvalue=5
```

## Meta Commands

```ls
metric m:fee_for_service_plans_altvalue p:integer l:Fee-For-Service_Plans_AltValue d:"Plan availability - Fee-For-Service - numeric value for mapping" t:dataTypeName=number

metric m:managed_care_plans_altvalue p:integer l:"Managed Care Plans_AltValue" d:"Plan availability - Managed Care Plans - numeric value for mapping" t:dataTypeName=number

metric m:summary_altvalue p:integer l:Summary_AltValue d:"Summary Value - numeric value for mapping" t:dataTypeName=number

entity e:ntaa-dtex l:"Medicaid Coverage Of Cessation Treatments And Barriers To Treatments" t:attribution="Centers for Disease Control and Prevention National Center for Disease Prevention and Health Promotion Office on Smoking and Health" t:url=https://data.cdc.gov/api/views/ntaa-dtex

property e:ntaa-dtex t:meta.view v:id=ntaa-dtex v:category="Cessation Coverage" v:attributionLink=http://www.lung.org/stop-smoking/tobacco-control-advocacy/states-communities/cessation-coverage.html v:averageRating=0 v:name="Medicaid Coverage Of Cessation Treatments And Barriers To Treatments" v:attribution="Centers for Disease Control and Prevention National Center for Disease Prevention and Health Promotion Office on Smoking and Health"

property e:ntaa-dtex t:meta.view.license v:name="Public Domain"

property e:ntaa-dtex t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:ntaa-dtex t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:ntaa-dtex t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | quarter | locationabbrv | locationdesc | topictype          | topic                                                                | measure                                   | submeasure                                    | fee_for_service_plans | fee_for_service_plans_altvalue | managed_care_plans | managed_care_plans_altvalue | summary | summary_altvalue | data_value_footnote_symbol | data_value_footnote | datasource                | topictypeid | topicid | measureid | submeasureid | displayorder | 
| ==== | ======= | ============= | ============ | ================== | ==================================================================== | ========================================= | ============================================= | ===================== | ============================== | ================== | =========================== | ======= | ================ | ========================== | =================== | ========================= | =========== | ======= | ========= | ============ | ============ | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Barriers to Treatments                        | Yes                   | 2                              | Not Applicable     | 5                           | Yes     | 2                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB011       | 11           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Co-Payments Required                          | Yes                   | 2                              | Not Applicable     | 5                           | Yes     | 2                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB012       | 12           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Prior Authorization Required                  | Yes                   | 2                              | Not Applicable     | 5                           | Yes     | 2                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB013       | 13           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Counseling Required for Medications           | No                    | 1                              | Not Applicable     | 5                           | No      | 1                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB014       | 14           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Stepped Care Therapy Required                 | No                    | 1                              | Not Applicable     | 5                           | No      | 1                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB015       | 15           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Limits on Duration                            | Yes                   | 2                              | Not Applicable     | 5                           | Yes     | 2                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB016       | 16           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Annual Limits                                 | Yes                   | 2                              | Not Applicable     | 5                           | Yes     | 2                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB017       | 17           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Lifetime Limits                               | No                    | 1                              | Not Applicable     | 5                           | No      | 1                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB018       | 18           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Barriers to Treatments                    | Other                                         | No                    | 1                              | Not Applicable     | 5                           | No      | 1                |                            |                     | American Lung Association | MED         | 910MED  | 1000BT    | MCB019       | 19           | 
| 2016 | 4       | AK            | Alaska       | Cessation Coverage | Medicaid Coverage of Cessation Treatments and Barriers to Treatments | Medicaid Coverage of Cessation Treatments | Comprehensive Medicaid Coverage of Treatments | No                    | 1                              | Not Applicable     | 5                           | No      | 1                |                            |                     | American Lung Association | MED         | 910MED  | 1000MCT   | MCB001       | 1            | 
```