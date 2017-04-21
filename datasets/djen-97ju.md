# MDS Quality Measures

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/quality-measures) |
| Metadata | [Link](https://data.medicare.gov/api/views/djen-97ju) |
| Data: JSON | [100 Rows](https://data.medicare.gov/api/views/djen-97ju/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.medicare.gov/api/views/djen-97ju/rows.csv?max_rows=100) |
| Host | data.medicare.gov |
| Id | djen-97ju |
| Name | MDS Quality Measures |
| Category | Nursing Home Compare |
| Tags | nhc, nursing home, quality, measures, ratings, quality measures |
| Created | 2013-07-11T15:41:19Z |
| Publication Date | 2017-03-22T02:04:42Z |

## Description

A list of the quality measures displayed on Nursing Home Compare, excluding Measures of Rehospitalization, Emergency Room Visit, and Community Discharge.  Each row contains a specific quality measure for a specific nursing home and includes the three-quarter score average and the score for each individual quarter

## Columns

```ls
| Included | Schema Type    | Field Name                               | Name                                     | Data Type     | Render Type   |
| ======== | ============== | ======================================== | ======================================== | ============= | ============= |
| Yes      | series tag     | federal_provider_number                  | Federal Provider Number                  | text          | text          |
| Yes      | series tag     | provider_name                            | Provider Name                            | text          | text          |
| No       |                | provider_address                         | Provider Address                         | text          | text          |
| Yes      | series tag     | provider_city                            | Provider City                            | text          | text          |
| Yes      | series tag     | provider_state                           | Provider State                           | text          | text          |
| Yes      | series tag     | provider_zip_code                        | Provider Zip Code                        | text          | text          |
| Yes      | series tag     | measure_code                             | Measure Code                             | text          | text          |
| Yes      | series tag     | measure_description                      | Measure Description                      | text          | text          |
| Yes      | series tag     | resident_type                            | Resident type                            | text          | text          |
| Yes      | numeric metric | q1_measure_score                         | Q1 Measure Score                         | percent       | percent       |
| No       |                | footnote_for_q1_measure_score            | Footnote for Q1 Measure Score            | text          | text          |
| Yes      | numeric metric | q2_measure_score                         | Q2 Measure Score                         | percent       | percent       |
| No       |                | footnote_for_q2_measure_score            | Footnote for Q2 Measure Score            | text          | text          |
| Yes      | numeric metric | q3_measure_score                         | Q3 Measure Score                         | percent       | percent       |
| No       |                | footnote_for_q3_measure_score            | Footnote for Q3 Measure Score            | text          | text          |
| Yes      | numeric metric | q4_measure_score                         | Q4 Measure Score                         | percent       | percent       |
| No       |                | footnote_for_q4_measure_score            | Footnote for Q4 Measure Score            | text          | text          |
| Yes      | numeric metric | three_quarter_average                    | Four Quarter Average Score               | percent       | percent       |
| No       |                | footnote_for_three_quarter_average       | Footnote for Four Quarter Average        | text          | text          |
| Yes      | series tag     | used_in_quality_measure_five_star_rating | Used in Quality Measure Five Star Rating | checkbox      | checkbox      |
| No       |                | q1_quarter                               | Q1 quarter                               | text          | text          |
| No       |                | q2_quarter                               | Q2 quarter                               | text          | text          |
| No       |                | q3_quarter                               | Q3 quarter                               | text          | text          |
| No       |                | q4_quarter                               | Q4 quarter                               | text          | text          |
| Yes      | time           | processing_date                          | Processing Date                          | calendar_date | calendar_date |
```

## Time Field

```ls
Value = processing_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = provider_address,footnote_for_q1_measure_score,footnote_for_q2_measure_score,footnote_for_q3_measure_score,footnote_for_q4_measure_score,footnote_for_three_quarter_average,q2_quarter,q3_quarter,q4_quarter,q1_quarter
```

## Data Commands

```ls
series e:djen-97ju d:2017-03-01T00:00:00.000Z t:resident_type="Long Stay" t:used_in_quality_measure_five_star_rating=true t:federal_provider_number=225236 t:measure_code=403 t:measure_description="Percentage of high risk long-stay residents with pressure ulcers" t:provider_zip_code=01040 t:provider_state=MA t:provider_name="CARE ONE AT HOLYOKE" t:provider_city=HOLYOKE m:three_quarter_average=3.164555 m:q3_measure_score=5 m:q4_measure_score=2.7027 m:q1_measure_score=2.5641 m:q2_measure_score=2.38095

series e:djen-97ju d:2017-03-01T00:00:00.000Z t:resident_type="Long Stay" t:used_in_quality_measure_five_star_rating=true t:federal_provider_number=225227 t:measure_code=419 t:measure_description="Percentage of long-stay residents who received an antipsychotic medication" t:provider_zip_code=01420 t:provider_state=MA t:provider_name="FITCHBURG GARDENS FOR NURSING AND REHABILITATION" t:provider_city=FITCHBURG m:three_quarter_average=19.047618 m:q3_measure_score=18.42105 m:q4_measure_score=21.42857 m:q1_measure_score=17.77778 m:q2_measure_score=18.60465

series e:djen-97ju d:2017-03-01T00:00:00.000Z t:resident_type="Short Stay" t:used_in_quality_measure_five_star_rating=false t:federal_provider_number=225262 t:measure_code=426 t:measure_description="Percentage of short-stay residents who were assessed and appropriately given the seasonal influenza vaccine" t:provider_zip_code=01089 t:provider_state=MA t:provider_name="WINGATE AT WEST SPRINGFIELD REHAB & SKILL NUR RES" t:provider_city="WEST SPRINGFIELD" m:three_quarter_average=88.888889 m:q3_measure_score=89.622642 m:q4_measure_score=89.622642 m:q1_measure_score=86.757991 m:q2_measure_score=89.62264
```

## Meta Commands

```ls
metric m:q1_measure_score p:float l:"Q1 Measure Score" t:dataTypeName=percent

metric m:q2_measure_score p:float l:"Q2 Measure Score" t:dataTypeName=percent

metric m:q3_measure_score p:float l:"Q3 Measure Score" t:dataTypeName=percent

metric m:q4_measure_score p:float l:"Q4 Measure Score" t:dataTypeName=percent

metric m:three_quarter_average p:float l:"Four Quarter Average Score" t:dataTypeName=percent

entity e:djen-97ju l:"MDS Quality Measures" t:url=https://data.medicare.gov/api/views/djen-97ju

property e:djen-97ju t:meta.view v:id=djen-97ju v:category="Nursing Home Compare" v:averageRating=0 v:name="MDS Quality Measures"

property e:djen-97ju t:meta.view.owner v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:displayName=cms

property e:djen-97ju t:meta.view.tableauthor v:id=drs7-75yr v:profileImageUrlMedium=/api/users/drs7-75yr/profile_images/THUMB v:profileImageUrlLarge=/api/users/drs7-75yr/profile_images/LARGE v:screenName=cms v:profileImageUrlSmall=/api/users/drs7-75yr/profile_images/TINY v:roleName=administrator v:displayName=cms

property e:djen-97ju t:meta.view.metadata.custom_fields.common_core v:Publisher="Centers for Medicare & Medicaid Services (CMS)" v:Contact_Email=Edward.Mortimore@cms.hhs.gov v:Contact_Name=CMS v:Bureau_Code=009:38 v:Program_Code=009:078
```

## Top Records

```ls
| federal_provider_number | provider_name                                     | provider_address      | provider_city    | provider_state | provider_zip_code | measure_code | measure_description                                                                                         | resident_type | q1_measure_score | footnote_for_q1_measure_score | q2_measure_score | footnote_for_q2_measure_score | q3_measure_score | footnote_for_q3_measure_score | q4_measure_score | footnote_for_q4_measure_score                                                                      | three_quarter_average | footnote_for_three_quarter_average | used_in_quality_measure_five_star_rating | q1_quarter | q2_quarter | q3_quarter | q4_quarter | processing_date     | 
| ======================= | ================================================= | ===================== | ================ | ============== | ================= | ============ | =========================================================================================================== | ============= | ================ | ============================= | ================ | ============================= | ================ | ============================= | ================ | ================================================================================================== | ===================== | ================================== | ======================================== | ========== | ========== | ========== | ========== | =================== | 
| 225236                  | CARE ONE AT HOLYOKE                               | 260 EASTHAMPTON ROAD  | HOLYOKE          | MA             | 01040             | 403          | Percentage of high risk long-stay residents with pressure ulcers                                            | Long Stay     | 2.564100         |                               | 2.380950         |                               | 5.000000         |                               | 2.702700         |                                                                                                    | 3.164555              |                                    | true                                     | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225227                  | FITCHBURG GARDENS FOR NURSING AND REHABILITATION  | 94 SUMMER STREET      | FITCHBURG        | MA             | 01420             | 419          | Percentage of long-stay residents who received an antipsychotic medication                                  | Long Stay     | 17.777780        |                               | 18.604650        |                               | 18.421050        |                               | 21.428570        |                                                                                                    | 19.047618             |                                    | true                                     | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225262                  | WINGATE AT WEST SPRINGFIELD REHAB & SKILL NUR RES | 42 PROSPECT AVENUE    | WEST SPRINGFIELD | MA             | 01089             | 426          | Percentage of short-stay residents who were assessed and appropriately given the seasonal influenza vaccine | Short Stay    | 86.757991        |                               | 89.622640        |                               | 89.622642        |                               | 89.622642        |                                                                                                    | 88.888889             |                                    | false                                    | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225272                  | BEAR HILL NURSING CENTER AT WAKEFIELD             | ENTER 11 NORTH STREET | STONEHAM         | MA             | 02180             | 406          | Percentage of long-stay residents with a catheter inserted and left in their bladder                        | Long Stay     | 1.844479         |                               | 2.563846         |                               | 0.719709         |                               | 1.444355         |                                                                                                    | 1.649336              |                                    | true                                     | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225270                  | CARE ONE AT ESSEX PARK                            | 265 ESSEX STREET      | BEVERLY          | MA             | 01915             | 424          | Percentage of short-stay residents who self-report moderate to severe pain                                  | Short Stay    | 12.030080        |                               | 9.923660         |                               | 6.060610         |                               | 3.418800         |                                                                                                    | 7.992203              |                                    | true                                     | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225279                  | BAYPATH AT DUXBURY NURSING & REHABILITATION CTR   | 308 KINGSTOWN WAY     | DUXBURY          | MA             | 02332             | 419          | Percentage of long-stay residents who received an antipsychotic medication                                  | Long Stay     | 18.750000        |                               | 20.000000        |                               | 15.116280        |                               | 14.444440        |                                                                                                    | 17.127071             |                                    | true                                     | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225279                  | BAYPATH AT DUXBURY NURSING & REHABILITATION CTR   | 308 KINGSTOWN WAY     | DUXBURY          | MA             | 02332             | 434          | Percentage of short-stay residents who newly received an antipsychotic medication                           | Short Stay    | 0.970870         |                               | 1.626020         |                               | 0.699300         |                               | 0.819670         |                                                                                                    | 1.018329              |                                    | true                                     | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225274                  | BRUSH HILL CARE CENTER                            | 1200 BRUSH HILL ROAD  | MILTON           | MA             | 02186             | 471          | Percentage of short-stay residents who made improvements in function                                        | Short Stay    | 66.643035        |                               | 59.960049        |                               | 56.836110        |                               |                  | The number of residents is too small to report. Call the facility to discuss this quality measure. | 62.103932             |                                    | true                                     | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225263                  | QUINCY HEALTH AND REHABILITATION CENTER LLC       | 11 MCGRATH HIGHWAY    | QUINCY           | MA             | 02169             | 408          | Percentage of long-stay residents who have depressive symptoms                                              | Long Stay     | 1.136360         |                               | 4.878050         |                               | 2.222220         |                               | 1.111110         |                                                                                                    | 2.285713              |                                    | false                                    | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
| 225284                  | GOLDEN LIVING CENTER-PLYMOUTH                     | 19 OBERY STREET       | PLYMOUTH         | MA             | 02360             | 425          | Percentage of short-stay residents with pressure ulcers that are new or worsened                            | Short Stay    | 0.571491         |                               | 0.684512         |                               | 0.729044         |                               | 0.000000         |                                                                                                    | 0.490102              |                                    | true                                     | 2015Q4     | 2016Q1     | 2016Q2     | 2016Q3     | 2017-03-01T00:00:00 | 
```