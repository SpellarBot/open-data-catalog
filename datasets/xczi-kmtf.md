# Performance Metrics - Family & Support Services - Youth Services Program Monthly Utilization

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/performance-metrics-family-support-services-youth-services-program-monthly-utilization-61918) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/xczi-kmtf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/xczi-kmtf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/xczi-kmtf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | xczi-kmtf |
| Name | Performance Metrics - Family & Support Services - Youth Services Program Monthly Utilization |
| Attribution | City of Chicago |
| Category | Administration & Finance |
| Tags | performance metrics, service delivery, human services |
| Created | 2011-08-01T15:45:14Z |
| Publication Date | 2014-07-10T17:13:57Z |

## Description

This metric tracks the number of young people enrolled in youth services per month. DFSS is committed to creating a premier out-of-school time system that provides young people the opportunity to participate in high-quality, safe, and structured programs. DFSS funds over 200 Out-of-School Time (OST) programs that serve youth between the ages of 6 to 18 years across the city of Chicago in five types of programs: Academic/Vocational Support and Enrichment; Science, Computer, and Technology; Arts and Culture; Sports, Fitness, Health, and Nutrition; and Innovative. Missing: This dataset does not include additional OST programs supported by other city agencies such as the Chicago Park District, Chicago Public Schools, the Chicago Housing Authority, etc.
?        Academic/Vocational Support and Enrichment - academic support, remedial education services, tutoring, literacy, and reconnecting youth with other educational opportunities
?        Science, Computer, and Technology - skills building focused on computer programming, software, and technology
?        Arts and Culture -  promoting excellence in the arts through access, awareness  and opportunities for creative expression, increased cultural awareness, and demonstrative skills  concluding with an event, play or exhibit
?        Sports, Fitness, Health, and Nutrition - opportunities for physical activities and education that supports healthy choices and a positive lifestyle
?        Innovative ? opportunities for youth ages 13 to 15 and 16 to 18 that provide customized projects supporting skills building in areas such as  civic engagement, entrepreneurship, workforce development, and post-secondary education to prepare youth for the job market and life-long learning

## Columns

```ls
| Included | Schema Type    | Field Name                                 | Name                                         | Data Type | Render Type |
| ======== | ============== | ========================================== | ============================================ | ========= | =========== |
| Yes      | series tag     | month                                      | Month                                        | text      | text        |
| Yes      | time           | year                                       | Year                                         | number    | text        |
| Yes      | numeric metric | academic_vocational_support_and_enrichment | Academic / Vocational Support and Enrichment | number    | number      |
| Yes      | numeric metric | arts_and_culture                           | Arts and Culture                             | number    | number      |
| Yes      | numeric metric | health_and_nutrition                       | Health and Nutrition                         | number    | number      |
| Yes      | numeric metric | innovative                                 | Innovative                                   | number    | number      |
| Yes      | numeric metric | science_computer_and_technology            | Science, Computer and Technology             | number    | number      |
| Yes      | numeric metric | sports_recreation_and_fitness              | Sports Recreation and Fitness                | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xczi-kmtf d:2011-01-01T00:00:00.000Z t:month=11-Jan m:health_and_nutrition=413 m:arts_and_culture=1026 m:academic_vocational_support_and_enrichment=3199 m:sports_recreation_and_fitness=1123 m:innovative=52 m:science_computer_and_technology=255

series e:xczi-kmtf d:2011-01-01T00:00:00.000Z t:month=11-Feb m:health_and_nutrition=310 m:arts_and_culture=1006 m:academic_vocational_support_and_enrichment=3282 m:sports_recreation_and_fitness=1102 m:innovative=152 m:science_computer_and_technology=307

series e:xczi-kmtf d:2011-01-01T00:00:00.000Z t:month=11-Mar m:health_and_nutrition=328 m:arts_and_culture=1117 m:academic_vocational_support_and_enrichment=3432 m:sports_recreation_and_fitness=1175 m:innovative=122 m:science_computer_and_technology=322
```

## Meta Commands

```ls
metric m:academic_vocational_support_and_enrichment p:integer l:"Academic / Vocational Support and Enrichment" t:dataTypeName=number

metric m:arts_and_culture p:integer l:"Arts and Culture" t:dataTypeName=number

metric m:health_and_nutrition p:integer l:"Health and Nutrition" t:dataTypeName=number

metric m:innovative p:integer l:Innovative t:dataTypeName=number

metric m:science_computer_and_technology p:integer l:"Science, Computer and Technology" t:dataTypeName=number

metric m:sports_recreation_and_fitness p:integer l:"Sports Recreation and Fitness" t:dataTypeName=number

entity e:xczi-kmtf l:"Performance Metrics - Family & Support Services - Youth Services Program Monthly Utilization" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/xczi-kmtf

property e:xczi-kmtf t:meta.view v:id=xczi-kmtf v:category="Administration & Finance" v:attributionLink=http://www.cityofchicago.org/performance v:averageRating=0 v:name="Performance Metrics - Family & Support Services - Youth Services Program Monthly Utilization" v:attribution="City of Chicago"

property e:xczi-kmtf t:meta.view.owner v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve

property e:xczi-kmtf t:meta.view.tableauthor v:id=7jj6-h75i v:screenName=Eve v:displayName=Eve
```

## Top Records

```ls
| month  | year | academic_vocational_support_and_enrichment | arts_and_culture | health_and_nutrition | innovative | science_computer_and_technology | sports_recreation_and_fitness | 
| ====== | ==== | ========================================== | ================ | ==================== | ========== | =============================== | ============================= | 
| 11-Jan | 2011 | 3199                                       | 1026             | 413                  | 52         | 255                             | 1123                          | 
| 11-Feb | 2011 | 3282                                       | 1006             | 310                  | 152        | 307                             | 1102                          | 
| 11-Mar | 2011 | 3432                                       | 1117             | 328                  | 122        | 322                             | 1175                          | 
| 11-Apr | 2011 | 3245                                       | 1015             | 388                  | 163        | 319                             | 1129                          | 
| 11-May | 2011 | 3076                                       | 975              | 266                  | 105        | 224                             | 1062                          | 
| 11-Jun | 2011 | 3485                                       | 946              | 361                  | 193        | 206                             | 1409                          | 
| 11-Jul | 2011 | 1524                                       | 443              | 156                  | 148        | 30                              | 973                           | 
| 11-Aug | 2011 | 1880                                       | 537              | 234                  | 153        | 89                              | 1306                          | 
| 11-Sep | 2011 | 2715                                       | 638              | 230                  | 107        | 225                             | 1004                          | 
| 11-Oct | 2011 | 2963                                       | 814              | 237                  | 192        | 332                             | 1247                          | 
```