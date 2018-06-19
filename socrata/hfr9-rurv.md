# Healthy Aging Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/healthy-aging-data) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/hfr9-rurv) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/hfr9-rurv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/hfr9-rurv/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | hfr9-rurv |
| Name | Healthy Aging Data |
| Attribution | CDC Division of Population Health |
| Category | Healthy Aging |
| Tags | aging |
| Created | 2016-05-16T12:13:44Z |
| Publication Date | 2016-08-10T19:46:20Z |

## Description

2011-2014. This dataset contains data from BRFSS.

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                       | Data Type | Render Type |
| ======== | ============== | ========================== | ========================== | ========= | =========== |
| Yes      | time           | yearstart                  | YearStart                  | number    | number      |
| No       |                | yearend                    | YearEnd                    | number    | number      |
| Yes      | series tag     | locationabbr               | LocationAbbr               | text      | text        |
| Yes      | series tag     | locationdesc               | LocationDesc               | text      | text        |
| Yes      | series tag     | datasource                 | Datasource                 | text      | text        |
| Yes      | series tag     | class                      | Class                      | text      | text        |
| Yes      | series tag     | topic                      | Topic                      | text      | text        |
| Yes      | series tag     | question                   | Question                   | text      | text        |
| Yes      | series tag     | response                   | Response                   | text      | text        |
| No       |                | data_value_unit            | Data_Value_Unit            | text      | text        |
| Yes      | series tag     | datavaluetypeid            | DataValueTypeID            | text      | text        |
| No       |                | data_value_type            | Data_Value_Type            | text      | text        |
| Yes      | numeric metric | data_value                 | Data_Value                 | number    | text        |
| No       |                | data_value_alt             | Data_Value_Alt             | number    | number      |
| No       |                | data_value_footnote_symbol | Data_Value_Footnote_Symbol | text      | text        |
| No       |                | data_value_footnote        | Data_Value_Footnote        | text      | text        |
| Yes      | numeric metric | low_confidence_limit       | Low_Confidence_Limit       | number    | number      |
| Yes      | numeric metric | high_confidence_limit      | High_Confidence_Limit      | number    | number      |
| Yes      | numeric metric | sample_size                | Sample_Size                | number    | number      |
| Yes      | series tag     | stratificationcategory1    | StratificationCategory1    | text      | text        |
| Yes      | series tag     | stratification1            | Stratification1            | text      | text        |
| Yes      | series tag     | stratificationcategory2    | StratificationCategory2    | text      | text        |
| Yes      | series tag     | stratification2            | Stratification2            | text      | text        |
| Yes      | series tag     | stratificationcategory3    | StratificationCategory3    | text      | text        |
| Yes      | series tag     | stratification3            | Stratification3            | text      | text        |
| Yes      | series tag     | classid                    | ClassID                    | text      | text        |
| Yes      | series tag     | topicid                    | TopicID                    | text      | text        |
| Yes      | series tag     | questionid                 | QuestionID                 | text      | text        |
| Yes      | series tag     | responseid                 | ResponseID                 | text      | text        |
| Yes      | series tag     | locationid                 | LocationID                 | text      | text        |
| Yes      | series tag     | stratificationcategoryid1  | StratificationCategoryID1  | text      | text        |
| Yes      | series tag     | stratificationid1          | StratificationID1          | text      | text        |
| Yes      | series tag     | stratificationcategoryid2  | StratificationCategoryID2  | text      | text        |
| Yes      | series tag     | stratificationid2          | StratificationID2          | text      | text        |
| Yes      | series tag     | stratificationcategoryid3  | StratificationCategoryID3  | text      | text        |
| Yes      | series tag     | stratificationid3          | StratificationID3          | text      | text        |
| Yes      | series tag     | report                     | Report                     | text      | text        |
```

## Time Field

```ls
Value = yearstart
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = yearend,data_value_unit,data_value_type,data_value_alt,data_value_footnote_symbol,data_value_footnote
```

## Data Commands

```ls
series e:hfr9-rurv d:2014-01-01T00:00:00.000Z t:topic="Frequent mental distress" t:locationabbr=US t:locationdesc="United States, DC & Territories" t:topicid=TMC01 t:stratificationid2=FEMALE t:stratificationid1=5054 t:class="Mental Health" t:questionid=Q03 t:locationid=59 t:stratificationcategory2=Gender t:stratificationcategoryid2=GENDER t:stratificationcategoryid1=AGE t:stratificationcategory1="Age Group" t:stratification1="50-54 years" t:stratification2=Female t:question="Percentage of older adults who are experiencing frequent mental distress" t:datavaluetypeid=Prctg t:datasource=BRFSS t:classid=C05 m:high_confidence_limit=15.8 m:data_value=15 m:low_confidence_limit=14.2

series e:hfr9-rurv d:2014-01-01T00:00:00.000Z t:topic="Frequent mental distress" t:locationabbr=US t:locationdesc="United States, DC & Territories" t:topicid=TMC01 t:stratificationid2=MALE t:stratificationid1=5054 t:class="Mental Health" t:questionid=Q03 t:locationid=59 t:stratificationcategory2=Gender t:stratificationcategoryid2=GENDER t:stratificationcategoryid1=AGE t:stratificationcategory1="Age Group" t:stratification1="50-54 years" t:stratification2=Male t:question="Percentage of older adults who are experiencing frequent mental distress" t:datavaluetypeid=Prctg t:datasource=BRFSS t:classid=C05 m:high_confidence_limit=11.8 m:data_value=11 m:low_confidence_limit=10.1

series e:hfr9-rurv d:2014-01-01T00:00:00.000Z t:topic="Frequent mental distress" t:locationabbr=US t:locationdesc="United States, DC & Territories" t:topicid=TMC01 t:stratificationid2=ASN t:stratificationid1=5054 t:class="Mental Health" t:questionid=Q03 t:locationid=59 t:stratificationcategory2=Race/Ethnicity t:stratificationcategoryid2=RACE t:stratificationcategoryid1=AGE t:stratificationcategory1="Age Group" t:stratification1="50-54 years" t:stratification2="Asian/Pacific Islander" t:question="Percentage of older adults who are experiencing frequent mental distress" t:datavaluetypeid=Prctg t:datasource=BRFSS t:classid=C05 m:high_confidence_limit=15.8 m:data_value=10.3 m:low_confidence_limit=6.6
```

## Meta Commands

```ls
metric m:data_value p:float l:Data_Value t:dataTypeName=number

metric m:low_confidence_limit p:float l:Low_Confidence_Limit t:dataTypeName=number

metric m:high_confidence_limit p:long l:High_Confidence_Limit t:dataTypeName=number

metric m:sample_size p:long l:Sample_Size t:dataTypeName=number

entity e:hfr9-rurv l:"Healthy Aging Data" t:attribution="CDC Division of Population Health" t:url=https://chronicdata.cdc.gov/api/views/hfr9-rurv

property e:hfr9-rurv t:meta.view v:id=hfr9-rurv v:category="Healthy Aging" v:averageRating=0 v:name="Healthy Aging Data" v:attribution="CDC Division of Population Health"

property e:hfr9-rurv t:meta.view.license v:name="Public Domain"

property e:hfr9-rurv t:meta.view.owner v:id=8mgn-axfp v:screenName="Christopher Taylor" v:displayName="Christopher Taylor"

property e:hfr9-rurv t:meta.view.tableauthor v:id=8mgn-axfp v:screenName="Christopher Taylor" v:roleName=publisher v:displayName="Christopher Taylor"

property e:hfr9-rurv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| yearstart | yearend | locationabbr | locationdesc                    | datasource | class         | topic                    | question                                                                 | response | data_value_unit | datavaluetypeid | data_value_type | data_value | data_value_alt | data_value_footnote_symbol | data_value_footnote | low_confidence_limit | high_confidence_limit | sample_size | stratificationcategory1 | stratification1 | stratificationcategory2 | stratification2          | stratificationcategory3 | stratification3 | classid | topicid | questionid | responseid | locationid | stratificationcategoryid1 | stratificationid1 | stratificationcategoryid2 | stratificationid2 | stratificationcategoryid3 | stratificationid3 | report | 
| ========= | ======= | ============ | =============================== | ========== | ============= | ======================== | ======================================================================== | ======== | =============== | =============== | =============== | ========== | ============== | ========================== | =================== | ==================== | ===================== | =========== | ======================= | =============== | ======================= | ======================== | ======================= | =============== | ======= | ======= | ========== | ========== | ========== | ========================= | ================= | ========================= | ================= | ========================= | ================= | ====== | 
| 2014      | 2014    | US           | United States, DC & Territories | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 15         | 15             |                            |                     | 14.2                 | 15.8                  |             | Age Group               | 50-54 years     | Gender                  | Female                   |                         |                 | C05     | TMC01   | Q03        |            | 59         | AGE                       | 5054              | GENDER                    | FEMALE            |                           |                   |        | 
| 2014      | 2014    | US           | United States, DC & Territories | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 11         | 11             |                            |                     | 10.1                 | 11.8                  |             | Age Group               | 50-54 years     | Gender                  | Male                     |                         |                 | C05     | TMC01   | Q03        |            | 59         | AGE                       | 5054              | GENDER                    | MALE              |                           |                   |        | 
| 2014      | 2014    | US           | United States, DC & Territories | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 10.3       | 10.3           |                            |                     | 6.6                  | 15.8                  |             | Age Group               | 50-54 years     | Race/Ethnicity          | Asian/Pacific Islander   |                         |                 | C05     | TMC01   | Q03        |            | 59         | AGE                       | 5054              | RACE                      | ASN               |                           |                   |        | 
| 2014      | 2014    | US           | United States, DC & Territories | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 13.2       | 13.2           |                            |                     | 11.5                 | 15.2                  |             | Age Group               | 50-54 years     | Race/Ethnicity          | Black, non-Hispanic      |                         |                 | C05     | TMC01   | Q03        |            | 59         | AGE                       | 5054              | RACE                      | BLK               |                           |                   |        | 
| 2014      | 2014    | US           | United States, DC & Territories | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 12.2       | 12.2           |                            |                     | 10.5                 | 14.2                  |             | Age Group               | 50-54 years     | Race/Ethnicity          | Hispanic                 |                         |                 | C05     | TMC01   | Q03        |            | 59         | AGE                       | 5054              | RACE                      | HIS               |                           |                   |        | 
| 2014      | 2014    | US           | United States, DC & Territories | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 23.9       | 23.9           |                            |                     | 17.8                 | 31.3                  |             | Age Group               | 50-54 years     | Race/Ethnicity          | Native Am/Alaskan Native |                         |                 | C05     | TMC01   | Q03        |            | 59         | AGE                       | 5054              | RACE                      | NAA               |                           |                   |        | 
| 2014      | 2014    | US           | United States, DC & Territories | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 13         | 13             |                            |                     | 12.3                 | 13.7                  |             | Age Group               | 50-54 years     | Race/Ethnicity          | White, non-Hispanic      |                         |                 | C05     | TMC01   | Q03        |            | 59         | AGE                       | 5054              | RACE                      | WHT               |                           |                   |        | 
| 2014      | 2014    | AL           | Alabama                         | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 18.8       | 18.8           |                            |                     | 15.7                 | 22.3                  |             | Age Group               | 50-54 years     |                         |                          |                         |                 | C05     | TMC01   | Q03        |            | 1          | AGE                       | 5054              |                           |                   |                           |                   |        | 
| 2014      | 2014    | AK           | Alaska                          | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 9.5        | 9.5            |                            |                     | 6.5                  | 13.6                  |             | Age Group               | 50-54 years     |                         |                          |                         |                 | C05     | TMC01   | Q03        |            | 2          | AGE                       | 5054              |                           |                   |                           |                   |        | 
| 2014      | 2014    | AZ           | Arizona                         | BRFSS      | Mental Health | Frequent mental distress | Percentage of older adults who are experiencing frequent mental distress |          | %               | Prctg           | Percentage      | 14.2       | 14.2           |                            |                     | 11.3                 | 17.8                  |             | Age Group               | 50-54 years     |                         |                          |                         |                 | C05     | TMC01   | Q03        |            | 4          | AGE                       | 5054              |                           |                   |                           |                   |        | 
```