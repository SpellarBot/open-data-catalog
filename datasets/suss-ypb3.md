# IDPH Causes of Death, by Resident County, 2008

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/idph-causes-of-death-by-resident-county-2008-3fa44) |
| Metadata | [Link](https://data.illinois.gov/api/views/suss-ypb3) |
| Data: JSON | [100 Rows](https://data.illinois.gov/api/views/suss-ypb3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.illinois.gov/api/views/suss-ypb3/rows.csv?max_rows=100) |
| Host | data.illinois.gov |
| Id | suss-ypb3 |
| Name | IDPH Causes of Death, by Resident County, 2008 |
| Attribution | Illinois Center for Health Statistics |
| Category | Public Health |
| Tags | cause, causes, death |
| Created | 2012-01-17T21:51:42Z |
| Publication Date | 2012-01-23T21:46:47Z |

## Description

Note: The sum of counties may not equal the total for some causes due to unknown geography.

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                       | Data Type | Render Type |
| ======== | ============== | ========================================== | ========================================== | ========= | =========== |
| Yes      | series tag     | resident_county                            | Resident County                            | text      | text        |
| Yes      | numeric metric | total_deaths                               | Total Deaths                               | number    | number      |
| Yes      | numeric metric | diseases_of_heart                          | Diseases of heart                          | number    | number      |
| Yes      | numeric metric | malignant_neoplasms                        | Malignant neoplasms                        | number    | number      |
| Yes      | numeric metric | cerebro_vascular_diseases_stroke_          | Cerebro-vascular diseases (stroke)         | number    | number      |
| Yes      | numeric metric | chronic_lower_respiratory_diseases         | Chronic lower respiratory diseases         | number    | number      |
| Yes      | numeric metric | accidents                                  | Accidents                                  | number    | number      |
| Yes      | numeric metric | alzheimer_s_disease                        | Alzheimer's disease                        | number    | number      |
| Yes      | numeric metric | diabetes_mellitus                          | Diabetes mellitus                          | number    | number      |
| Yes      | numeric metric | influenza_and_pneumonia                    | Influenza and pneumonia                    | number    | number      |
| Yes      | numeric metric | nephritis_nephrotic_syndrome_and_nephrosis | Nephritis,nephrotic syndrome and nephrosis | number    | number      |
| Yes      | numeric metric | septicemia                                 | Septicemia                                 | number    | number      |
| Yes      | numeric metric | intentional_self_harm_suicide_             | Intentional self-harm (suicide)            | number    | number      |
| Yes      | numeric metric | chronic_liver_disease_and_cirrhosis        | Chronic liver disease and cirrhosis        | number    | number      |
| Yes      | numeric metric | allother_causes                            | Allother causes                            | number    | number      |
```

## Time Field

```ls
Value = 2008
Format & Zone = yyyy
```

## Data Commands

```ls
series e:suss-ypb3 d:2008-01-01T00:00:00.000Z t:resident_county=Adams m:chronic_lower_respiratory_diseases=68 m:intentional_self_harm_suicide_=14 m:malignant_neoplasms=157 m:septicemia=14 m:diseases_of_heart=199 m:influenza_and_pneumonia=38 m:accidents=27 m:allother_causes=196 m:cerebro_vascular_diseases_stroke_=49 m:alzheimer_s_disease=22 m:nephritis_nephrotic_syndrome_and_nephrosis=26 m:diabetes_mellitus=27 m:chronic_liver_disease_and_cirrhosis=6 m:total_deaths=843

series e:suss-ypb3 d:2008-01-01T00:00:00.000Z t:resident_county=Alexander m:chronic_lower_respiratory_diseases=2 m:intentional_self_harm_suicide_=1 m:malignant_neoplasms=26 m:septicemia=4 m:diseases_of_heart=27 m:influenza_and_pneumonia=3 m:accidents=3 m:allother_causes=20 m:cerebro_vascular_diseases_stroke_=12 m:alzheimer_s_disease=1 m:nephritis_nephrotic_syndrome_and_nephrosis=5 m:diabetes_mellitus=7 m:chronic_liver_disease_and_cirrhosis=0 m:total_deaths=111

series e:suss-ypb3 d:2008-01-01T00:00:00.000Z t:resident_county=Bond m:chronic_lower_respiratory_diseases=9 m:intentional_self_harm_suicide_=0 m:malignant_neoplasms=36 m:septicemia=1 m:diseases_of_heart=43 m:influenza_and_pneumonia=8 m:accidents=11 m:allother_causes=25 m:cerebro_vascular_diseases_stroke_=8 m:alzheimer_s_disease=9 m:nephritis_nephrotic_syndrome_and_nephrosis=3 m:diabetes_mellitus=2 m:chronic_liver_disease_and_cirrhosis=1 m:total_deaths=156
```

## Meta Commands

```ls
metric m:total_deaths p:integer l:"Total Deaths" t:dataTypeName=number

metric m:diseases_of_heart p:integer l:"Diseases of heart" t:dataTypeName=number

metric m:malignant_neoplasms p:integer l:"Malignant neoplasms" t:dataTypeName=number

metric m:cerebro_vascular_diseases_stroke_ p:integer l:"Cerebro-vascular diseases (stroke)" t:dataTypeName=number

metric m:chronic_lower_respiratory_diseases p:integer l:"Chronic lower respiratory diseases" t:dataTypeName=number

metric m:accidents p:integer l:Accidents t:dataTypeName=number

metric m:alzheimer_s_disease p:integer l:"Alzheimer's disease" t:dataTypeName=number

metric m:diabetes_mellitus p:integer l:"Diabetes mellitus" t:dataTypeName=number

metric m:influenza_and_pneumonia p:integer l:"Influenza and pneumonia" t:dataTypeName=number

metric m:nephritis_nephrotic_syndrome_and_nephrosis p:integer l:"Nephritis,nephrotic syndrome and nephrosis" t:dataTypeName=number

metric m:septicemia p:integer l:Septicemia t:dataTypeName=number

metric m:intentional_self_harm_suicide_ p:integer l:"Intentional self-harm (suicide)" t:dataTypeName=number

metric m:chronic_liver_disease_and_cirrhosis p:integer l:"Chronic liver disease and cirrhosis" t:dataTypeName=number

metric m:allother_causes p:integer l:"Allother causes" t:dataTypeName=number

entity e:suss-ypb3 l:"IDPH Causes of Death, by Resident County, 2008" t:attribution="Illinois Center for Health Statistics" t:url=https://data.illinois.gov/api/views/suss-ypb3

property e:suss-ypb3 t:meta.view v:id=suss-ypb3 v:category="Public Health" v:attributionLink=http://www.idph.state.il.us/health/statshome.htm v:averageRating=0 v:name="IDPH Causes of Death, by Resident County, 2008" v:attribution="Illinois Center for Health Statistics"

property e:suss-ypb3 t:meta.view.owner v:id=e75b-y6hv v:screenName=Jenny v:displayName=Jenny

property e:suss-ypb3 t:meta.view.tableauthor v:id=ws2v-m6rq v:screenName="jonathan nuttall" v:displayName="jonathan nuttall"
```

## Top Records

```ls
| resident_county | total_deaths | diseases_of_heart | malignant_neoplasms | cerebro_vascular_diseases_stroke_ | chronic_lower_respiratory_diseases | accidents | alzheimer_s_disease | diabetes_mellitus | influenza_and_pneumonia | nephritis_nephrotic_syndrome_and_nephrosis | septicemia | intentional_self_harm_suicide_ | chronic_liver_disease_and_cirrhosis | allother_causes | 
| =============== | ============ | ================= | =================== | ================================= | ================================== | ========= | =================== | ================= | ======================= | ========================================== | ========== | ============================== | =================================== | =============== | 
| Adams           | 843          | 199               | 157                 | 49                                | 68                                 | 27        | 22                  | 27                | 38                      | 26                                         | 14         | 14                             | 6                                   | 196             | 
| Alexander       | 111          | 27                | 26                  | 12                                | 2                                  | 3         | 1                   | 7                 | 3                       | 5                                          | 4          | 1                              | 0                                   | 20              | 
| Bond            | 156          | 43                | 36                  | 8                                 | 9                                  | 11        | 9                   | 2                 | 8                       | 3                                          | 1          | 0                              | 1                                   | 25              | 
| Boone           | 365          | 95                | 80                  | 24                                | 26                                 | 17        | 17                  | 13                | 7                       | 4                                          | 7          | 5                              | 5                                   | 65              | 
| Brown           | 56           | 18                | 8                   | 4                                 | 4                                  | 2         | 0                   | 1                 | 1                       | 0                                          | 2          | 0                              | 2                                   | 14              | 
| Bureau          | 397          | 102               | 95                  | 17                                | 22                                 | 21        | 18                  | 7                 | 10                      | 23                                         | 2          | 6                              | 5                                   | 69              | 
| Calhoun         | 71           | 20                | 17                  | 7                                 | 4                                  | 5         | 2                   | 2                 | 0                       | 1                                          | 2          | 0                              | 0                                   | 11              | 
| Carroll         | 195          | 49                | 48                  | 16                                | 14                                 | 10        | 1                   | 4                 | 6                       | 9                                          | 2          | 1                              | 3                                   | 32              | 
| Cass            | 166          | 47                | 37                  | 9                                 | 16                                 | 5         | 6                   | 1                 | 2                       | 6                                          | 2          | 2                              | 1                                   | 32              | 
| Champaign       | 1147         | 254               | 257                 | 58                                | 70                                 | 68        | 51                  | 29                | 27                      | 21                                         | 16         | 15                             | 7                                   | 274             | 
```