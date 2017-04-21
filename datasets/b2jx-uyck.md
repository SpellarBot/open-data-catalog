# U.S. Census Annual Estimates of the Resident Population for Selected Age Groups by Sex for the United States

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/u-s-census-annual-estimates-of-the-resident-population-for-selected-age-groups-by-sex-for-) |
| Metadata | [Link](https://chronicdata.cdc.gov/api/views/b2jx-uyck) |
| Data: JSON | [100 Rows](https://chronicdata.cdc.gov/api/views/b2jx-uyck/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://chronicdata.cdc.gov/api/views/b2jx-uyck/rows.csv?max_rows=100) |
| Host | chronicdata.cdc.gov |
| Id | b2jx-uyck |
| Name | U.S. Census Annual Estimates of the Resident Population for Selected Age Groups by Sex for the United States |
| Attribution | Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health |
| Category | Tobacco Use |
| Created | 2016-11-30T14:10:19Z |
| Publication Date | 2016-12-05T13:03:37Z |

## Description

2010-2015. U.S. Census Annual Estimates of the Resident Population for Selected Age Groups by Sex for the United States. The estimates are based on the 2010 Census and reflect changes to the April 1, 2010 population due to the Count Question Resolution program and geographic program revisions. Median age is calculated based on single year of age. For population estimates methodology statements, see http://www.census.gov/popest/methodology/index.html.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type     | Render Type   |
| ======== | ============== | ================= | ================= | ============= | ============= |
| Yes      | time           | year              | YEAR              | number        | number        |
| Yes      | series tag     | locationabbr      | LocationAbbr      | text          | text          |
| Yes      | series tag     | locationdesc      | LocationDesc      | text          | text          |
| Yes      | series tag     | topictype         | TopicType         | text          | text          |
| Yes      | series tag     | topicdesc         | TopicDesc         | text          | text          |
| Yes      | series tag     | datasource        | DataSource        | text          | text          |
| No       |                | data_value_type   | Data_Value_Type   | text          | text          |
| Yes      | numeric metric | data_value        | Data_Value        | number        | number        |
| Yes      | series tag     | gender            | Gender            | text          | text          |
| Yes      | series tag     | age               | Age               | text          | text          |
| Yes      | series tag     | source_file_uscb  | Source_File_USCB  | text          | text          |
| No       |                | data_pulled       | Data_Pulled       | calendar_date | calendar_date |
| Yes      | series tag     | locationid        | LocationID        | text          | text          |
| Yes      | series tag     | topictypeid       | TopicTypeId       | text          | text          |
| Yes      | series tag     | topicid           | TopicId           | text          | text          |
| Yes      | series tag     | measureid         | MeasureId         | text          | text          |
| Yes      | series tag     | stratificationid1 | StratificationID1 | text          | text          |
| Yes      | series tag     | stratificationid2 | StratificationID2 | text          | text          |
| Yes      | series tag     | submeasureid      | SubMeasureID      | text          | text          |
| No       |                | displayorder      | DisplayOrder      | number        | number        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Excluded Fields = data_value_type,data_pulled,displayorder
```

## Data Commands

```ls
series e:b2jx-uyck d:2015-01-01T00:00:00.000Z t:locationdesc=Alabama t:locationabbr=AL t:topicid=100CEN t:stratificationid2=8AGE t:stratificationid1=1GEN t:measureid=100POP t:topicdesc="Census - Population" t:source_file_uscb="PEP_2015_PEPAGESEX, Factfinder2.census.gov" t:locationid=01 t:age=Total t:gender=Total t:topictype=Census t:submeasureid=CEN01 t:datasource="United States Census Bureau" t:topictypeid=CEN m:data_value=4858979

series e:b2jx-uyck d:2015-01-01T00:00:00.000Z t:locationdesc=Alabama t:locationabbr=AL t:topicid=100CEN t:stratificationid2=10AGE t:stratificationid1=1GEN t:measureid=100POP t:topicdesc="Census - Population" t:source_file_uscb="PEP_2015_PEPAGESEX, Factfinder2.census.gov" t:locationid=01 t:age=18+ t:gender=Total t:topictype=Census t:submeasureid=CEN02 t:datasource="United States Census Bureau" t:topictypeid=CEN m:data_value=3755483

series e:b2jx-uyck d:2015-01-01T00:00:00.000Z t:locationdesc=Alabama t:locationabbr=AL t:topicid=100CEN t:stratificationid2=11AGE t:stratificationid1=1GEN t:measureid=100POP t:topicdesc="Census - Population" t:source_file_uscb="PEP_2015_PEPAGESEX, Factfinder2.census.gov" t:locationid=01 t:age=<18 t:gender=Total t:topictype=Census t:submeasureid=CEN03 t:datasource="United States Census Bureau" t:topictypeid=CEN m:data_value=1103496
```

## Meta Commands

```ls
metric m:data_value p:integer l:Data_Value d:"Value of data" t:dataTypeName=number

entity e:b2jx-uyck l:"U.S. Census Annual Estimates of the Resident Population for Selected Age Groups by Sex for the United States" t:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health" t:url=https://chronicdata.cdc.gov/api/views/b2jx-uyck

property e:b2jx-uyck t:meta.view v:id=b2jx-uyck v:category="Tobacco Use" v:averageRating=0 v:name="U.S. Census Annual Estimates of the Resident Population for Selected Age Groups by Sex for the United States" v:attribution="Centers for Disease Control and Prevention, National Center for Chronic Disease Prevention and Health Promotion, Office on Smoking and Health"

property e:b2jx-uyck t:meta.view.license v:name="Public Domain"

property e:b2jx-uyck t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:b2jx-uyck t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:b2jx-uyck t:meta.view.metadata.custom_fields.common_core v:Contact_Email=CDCinfo@cdc.gov v:Contact_Name="CDC Info" v:Bureau_Code=009:20 v:Program_Code=009:020
```

## Top Records

```ls
| year | locationabbr | locationdesc | topictype | topicdesc           | datasource                  | data_value_type | data_value | gender | age   | source_file_uscb                           | data_pulled | locationid | topictypeid | topicid | measureid | stratificationid1 | stratificationid2 | submeasureid | displayorder | 
| ==== | ============ | ============ | ========= | =================== | =========================== | =============== | ========== | ====== | ===== | ========================================== | =========== | ========== | =========== | ======= | ========= | ================= | ================= | ============ | ============ | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 4858979    | Total  | Total | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 1GEN              | 8AGE              | CEN01        | 1            | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 3755483    | Total  | 18+   | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 1GEN              | 10AGE             | CEN02        | 2            | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 1103496    | Total  | <18   | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 1GEN              | 11AGE             | CEN03        | 3            | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 2353184    | Male   | Total | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 2GEN              | 8AGE              | CEN04        | 4            | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 1791379    | Male   | 18+   | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 2GEN              | 10AGE             | CEN05        | 5            | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 561805     | Male   | <18   | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 2GEN              | 11AGE             | CEN06        | 6            | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 2505795    | Female | Total | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 3GEN              | 8AGE              | CEN07        | 7            | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 1964104    | Female | 18+   | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 3GEN              | 10AGE             | CEN08        | 8            | 
| 2015 | AL           | Alabama      | Census    | Census - Population | United States Census Bureau | Count           | 541691     | Female | <18   | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 01         | CEN         | 100CEN  | 100POP    | 3GEN              | 11AGE             | CEN09        | 9            | 
| 2015 | AK           | Alaska       | Census    | Census - Population | United States Census Bureau | Count           | 738432     | Total  | Total | PEP_2015_PEPAGESEX, Factfinder2.census.gov |             | 02         | CEN         | 100CEN  | 100POP    | 1GEN              | 8AGE              | CEN01        | 1            | 
```