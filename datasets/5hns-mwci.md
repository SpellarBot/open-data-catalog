# Global Tobacco Surveillance System (GTSS) - Global School Personnel Survey (GSPS)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/global-tobacco-surveillance-system-gtss-global-school-personnel-survey-gsps) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/5hns-mwci) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/5hns-mwci/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/5hns-mwci/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | 5hns-mwci |
| Name | Global Tobacco Surveillance System (GTSS) - Global School Personnel Survey (GSPS) |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Global Survey Data |
| Tags | tobacco, osh, gtss, gsps, school personnel |
| Created | 2015-03-16T14:54:29Z |
| Publication Date | 2016-12-14T14:02:27Z |

## Description

2001-2011. The GSPS was initiated in 2000 to collect information on tobacco use, knowledge and attitudes of school personnel toward tobacco, existence and effectiveness of tobacco control policies in schools, and training and materials available for implementing tobacco prevention and control interventions.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | year                       | Year                       | number    | number      |
| Yes      | series tag     | who_region                 | WHO_Region                 | text      | text        |
| Yes      | series tag     | datasource                 | Datasource                 | text      | text        |
| Yes      | series tag     | country                    | Country                    | text      | text        |
| Yes      | series tag     | surveysite                 | SurveySite                 | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | mpower                     | Mpower                     | text      | text        |
| Yes      | series tag     | indicator                  | Indicator                  | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | profession                 | Profession                 | text      | text        |
| Yes      | series tag     | regionabbr                 | RegionAbbr                 | text      | text        |
| Yes      | series tag     | countryabbr                | CountryAbbr                | text      | text        |
| Yes      | series tag     | surveysiteabbr             | SurveySiteAbbr             | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | mpowerid                   | MpowerID                   | text      | text        |
| Yes      | series tag     | indicatorid                | IndicatorID                | text      | text        |
| Yes      | series tag     | stratificationid           | StratificationID           | text      | text        |
| Yes      | series tag     | datavaluetypeid            | DataValueTypeID            | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_unit,data_value_type,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:5hns-mwci d:2011-01-01T00:00:00.000Z t:topic="School Policies" t:indicator="Percentage of school personnel who agree that schools should have a policy prohibiting tobacco use among school personnel" t:surveysite="Czech Republic - National" t:mpowerid=M03 t:topicid=T11 t:regionabbr=EUR t:countryabbr=ez t:profession=Total t:country="Czech Republic" t:surveysiteabbr=ez100 t:stratificationid=P9901 t:locationid=364 t:indicatorid=Q51 t:who_region="European Region" t:datavaluetypeid=Prctg t:datasource=GSPS t:mpower=Protect m:sample_size=469 m:data_value=59.5

series e:5hns-mwci d:2011-01-01T00:00:00.000Z t:topic="School Policies" t:indicator="Percentage of school personnel who reported that their school has a policy prohibiting tobacco use among students" t:surveysite="Czech Republic - National" t:mpowerid=M03 t:topicid=T11 t:regionabbr=EUR t:countryabbr=ez t:profession=Total t:country="Czech Republic" t:surveysiteabbr=ez100 t:stratificationid=P9901 t:locationid=364 t:indicatorid=Q56 t:who_region="European Region" t:datavaluetypeid=Prctg t:datasource=GSPS t:mpower=Protect m:sample_size=476 m:data_value=84

series e:5hns-mwci d:2011-01-01T00:00:00.000Z t:topic="School Policies" t:indicator="Percentage of school personnel who agree that schools should have a policy prohibiting tobacco use among students" t:surveysite="Czech Republic - National" t:mpowerid=M03 t:topicid=T11 t:regionabbr=EUR t:countryabbr=ez t:profession=Total t:country="Czech Republic" t:surveysiteabbr=ez100 t:stratificationid=P9901 t:locationid=364 t:indicatorid=Q52 t:who_region="European Region" t:datavaluetypeid=Prctg t:datasource=GSPS t:mpower=Protect m:sample_size=473 m:data_value=86.9
```

## Meta Commands

```ls
metric m:data_value p:double l:Data_Value d:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit d:"Low Confidence Limit" t:dataTypeName=number

metric m:high_confidence_limit p:double l:High_Confidence_Limit d:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:integer l:Sample_Size d:Sample_Size t:dataTypeName=number

entity e:5hns-mwci l:"Global Tobacco Surveillance System (GTSS) - Global School Personnel Survey (GSPS)" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/5hns-mwci

property e:5hns-mwci t:meta.view v:id=5hns-mwci v:category="Global Survey Data" v:attributionLink=http://nccd.cdc.gov/GTSSData/default/default.aspx v:averageRating=0 v:name="Global Tobacco Surveillance System (GTSS) - Global School Personnel Survey (GSPS)" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:5hns-mwci t:meta.view.license v:name="Open Database License" v:termsLink=http://opendatacommons.org/licenses/odbl/1.0/

property e:5hns-mwci t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:5hns-mwci t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:5hns-mwci t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | who_region      | datasource | country        | surveysite                | topic                            | mpower  | indicator                                                                                                                                                                        | data_value_unit | data_value_type | data_value | data_value_footnote_symbol | data_value_footnote                                      | low_confidence_limit | high_confidence_limit | sample_size | profession | regionabbr | countryabbr | surveysiteabbr | locationid | topicid | mpowerid | indicatorid | stratificationid | datavaluetypeid | 
| ==== | =============== | ========== | ============== | ========================= | ================================ | ======= | ================================================================================================================================================================================ | =============== | =============== | ========== | ========================== | ======================================================== | ==================== | ===================== | =========== | ========== | ========== | =========== | ============== | ========== | ======= | ======== | =========== | ================ | =============== | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | School Policies                  | Protect | Percentage of school personnel who agree that schools should have a policy prohibiting tobacco use among school personnel                                                        | %               | Percentage      | 59.5       |                            |                                                          |                      |                       | 469         | Total      | EUR        | ez          | ez100          | 364        | T11     | M03      | Q51         | P9901            | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | School Policies                  | Protect | Percentage of school personnel who reported that their school has a policy prohibiting tobacco use among students                                                                | %               | Percentage      | 84         |                            |                                                          |                      |                       | 476         | Total      | EUR        | ez          | ez100          | 364        | T11     | M03      | Q56         | P9901            | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | School Policies                  | Protect | Percentage of school personnel who agree that schools should have a policy prohibiting tobacco use among students                                                                | %               | Percentage      | 86.9       |                            |                                                          |                      |                       | 473         | Total      | EUR        | ez          | ez100          | 364        | T11     | M03      | Q52         | P9901            | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | School Policies                  | Protect | Percentage of school personnel who reported that their school has a policy prohibiting tobacco use among school personnel                                                        | %               | Percentage      | 47.4       |                            |                                                          |                      |                       | 473         | Total      | EUR        | ez          | ez100          | 364        | T11     | M03      | Q55         | P9901            | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | School Policies                  | Protect | Percentage of school personnel who reported that their school's policy prohibiting tobacco use among students and school personnel is enforced                                   | %               | Percentage      | 60.4       |                            |                                                          |                      |                       | 477         | Total      | EUR        | ez          | ez100          | 364        | T11     | M03      | Q57         | P9901            | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | Access to Materials and Training |         | Percentage of school personnel who reported that tobacco use prevention is included in their school's curriculum                                                                 | %               | Percentage      |            | ?                          | No Data Available. Indicator was not included in survey. |                      |                       |             | Total      | EUR        | ez          | ez100          | 364        | T12     | M99      | Q58         | P9901            | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | Access to Materials and Training |         | Percentage of school personnel who think teachers need specific training to be able to teach students how to avoid or stop using tobacco                                         | %               | Percentage      | 52.6       |                            |                                                          |                      |                       | 475         | Total      | EUR        | ez          | ez100          | 364        | T12     | M99      | Q64         | P9901            | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | Access to Materials and Training |         | Percentage of school personnel who reported having access to teaching and learning materials about tobacco use and how to prevent its use among youth                            | %               | Percentage      | 57.2       |                            |                                                          |                      |                       | 404         | Teachers   | EUR        | ez          | ez100          | 364        | T12     | M99      | Q70         | P03              | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | Access to Materials and Training |         | Percentage of school personnel who reported ever receiving training to prevent tobacco use among youth                                                                           | %               | Percentage      | 21.2       |                            |                                                          |                      |                       | 406         | Teachers   | EUR        | ez          | ez100          | 364        | T12     | M99      | Q69         | P03              | Prctg           | 
| 2011 | European Region | GSPS       | Czech Republic | Czech Republic - National | Access to Materials and Training |         | Percentage of school personnel who reported that non-classroom programs or activities (such as an assembly) are used to teach tobacco use prevention to students in their school | %               | Percentage      | 44.9       |                            |                                                          |                      |                       | 336         | Total      | EUR        | ez          | ez100          | 364        | T12     | M99      | Q54         | P9901            | Prctg           | 
```