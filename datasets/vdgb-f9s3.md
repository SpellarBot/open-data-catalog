# Question Inventory on Tobacco (QIT)

## Dataset

* [Dataset URL](https://data.cdc.gov/api/views/vdgb-f9s3/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/question-inventory-on-tobacco-qit-39432)
* [Metadata URL](https://data.cdc.gov/api/views/vdgb-f9s3)
* Id = vdgb-f9s3
* Name = Question Inventory on Tobacco (QIT)
* Category = Survey Questions (Tobacco Use)
* Tags = [tobacco, osh, office on smoking and health, qit, survey questions]
* Created = 2015-06-23T20:31:30Z
* Publication Date = 2016-11-10T15:51:31Z
* Rows Updated = 2016-11-09T17:50:21Z

## Description

1965, 1966, 1970, 1974-2017. Centers for Disease Control and Prevention (CDC). Office on Smoking and Health (OSH). Tobacco-Related Survey Questions. The QIT is a compilation of more than 7,000 historical tobacco-related survey questions from various state, national and international surveys.

## Columns

```ls
| Name             | Field Name       | Data Type | Render Type | Schema Type | Included | 
| ================ | ================ | ========= | =========== | =========== | ======== | 
| Topic1           | topic1           | text      | text        | series tag  | Yes      | 
| Topic2           | topic2           | text      | text        | series tag  | Yes      | 
| Topic3           | topic3           | text      | text        | series tag  | Yes      | 
| Topic4           | topic4           | text      | text        | series tag  | Yes      | 
| E-Cigarettes     | e_cigarettes     | text      | text        | series tag  | Yes      | 
| Question         | question         | text      | text        | series tag  | Yes      | 
| Responses        | responses        | text      | text        | series tag  | Yes      | 
| Year             | year             | number    | text        | time        | Yes      | 
| SurveyNameAbbrev | surveynameabbrev | text      | text        | series tag  | Yes      | 
| SurveyName       | surveyname       | text      | text        | series tag  | Yes      | 
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls





```

## Meta Commands

```ls
entity e:vdgb-f9s3 l:"Question Inventory on Tobacco (QIT)" t:url=https://data.cdc.gov/api/views/vdgb-f9s3

property e:vdgb-f9s3 t:meta.view d:2017-03-08T01:09:01.650Z v:id=vdgb-f9s3 v:category="Survey Questions (Tobacco Use)" v:averageRating=0 v:name="Question Inventory on Tobacco (QIT)"

property e:vdgb-f9s3 t:meta.view.license d:2017-03-08T01:09:01.650Z v:name="Public Domain"

property e:vdgb-f9s3 t:meta.view.owner d:2017-03-08T01:09:01.650Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:vdgb-f9s3 t:meta.view.tableauthor d:2017-03-08T01:09:01.650Z v:id=p5wh-zttj v:profileImageUrlMedium=/api/users/p5wh-zttj/profile_images/THUMB v:profileImageUrlLarge=/api/users/p5wh-zttj/profile_images/LARGE v:screenName=OSHData v:profileImageUrlSmall=/api/users/p5wh-zttj/profile_images/TINY v:roleName=administrator v:displayName=OSHData

property e:vdgb-f9s3 t:meta.view.metadata.custom_fields.common_core d:2017-03-08T01:09:01.650Z v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:20 v:Program_Code=009:020
```