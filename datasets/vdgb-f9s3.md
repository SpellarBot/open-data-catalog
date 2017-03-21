# Question Inventory on Tobacco (QIT)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/question-inventory-on-tobacco-qit-39432) |
| Metadata | [Link](https://data.cdc.gov/api/views/vdgb-f9s3) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/vdgb-f9s3/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/vdgb-f9s3/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | vdgb-f9s3 |
| Name | Question Inventory on Tobacco (QIT) |
| Category | Survey Questions (Tobacco Use) |
| Tags | tobacco, osh, office on smoking and health, qit, survey questions |
| Created | 2015-06-23T20:31:30Z |
| Publication Date | 2016-11-10T15:51:31Z |
| Rows Updated | 2016-11-09T17:50:21Z |

## Description

1965, 1966, 1970, 1974-2017. Centers for Disease Control and Prevention (CDC). Office on Smoking and Health (OSH). Tobacco-Related Survey Questions. The QIT is a compilation of more than 7,000 historical tobacco-related survey questions from various state, national and international surveys.

## Columns

```ls
| Included | Schema Type | Field Name       | Name             | Data Type | Render Type |
| ======== | =========== | ================ | ================ | ========= | =========== |
| Yes      | series tag  | topic1           | Topic1           | text      | text        |
| Yes      | series tag  | topic2           | Topic2           | text      | text        |
| Yes      | series tag  | topic3           | Topic3           | text      | text        |
| Yes      | series tag  | topic4           | Topic4           | text      | text        |
| Yes      | series tag  | e_cigarettes     | E-Cigarettes     | text      | text        |
| Yes      | series tag  | question         | Question         | text      | text        |
| Yes      | series tag  | responses        | Responses        | text      | text        |
| Yes      | time        | year             | Year             | number    | text        |
| Yes      | series tag  | surveynameabbrev | SurveyNameAbbrev | text      | text        |
| Yes      | series tag  | surveyname       | SurveyName       | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
```

## Meta Commands

```ls
entity e:vdgb-f9s3 l:"Question Inventory on Tobacco (QIT)" t:url=https://data.cdc.gov/api/views/vdgb-f9s3

property e:vdgb-f9s3 t:meta.view v:id=vdgb-f9s3 v:category="Survey Questions (Tobacco Use)" v:averageRating=0 v:name="Question Inventory on Tobacco (QIT)"

property e:vdgb-f9s3 t:meta.view.license v:name="Public Domain"

property e:vdgb-f9s3 t:meta.view.owner v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:displayName=OSHData

property e:vdgb-f9s3 t:meta.view.tableauthor v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:vdgb-f9s3 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```