# City and County of San Francisco - LIVES standard feed info

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/city-and-county-of-san-francisco-lives-standard-feed-info) |
| Metadata | [Link](https://data.sfgov.org/api/views/77fi-8jag) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/77fi-8jag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/77fi-8jag/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 77fi-8jag |
| Name | City and County of San Francisco - LIVES standard feed info |
| Category | Health and Social Services |
| Created | 2015-12-17T17:26:22Z |
| Publication Date | 2015-12-17T17:28:20Z |

## Description

This is the feed information for the LIVES standard dataset available here: https://data.sfgov.org/d/7bjp-f3sp. It contains basic metadata about the feed for use by developers using the data.

## Columns

```ls
| Included | Schema Type    | Field Name        | Name              | Data Type | Render Type |
| ======== | ============== | ================= | ================= | ========= | =========== |
| No       | time           | :updated_at       | updated_at        | meta_data | meta_data   |
| Yes      | numeric metric | feed_version      | feed_version      | number    | text        |
| Yes      | series tag     | municipality_name | municipality_name | text      | text        |
| Yes      | series tag     | municipality_url  | municipality_url  | text      | text        |
| Yes      | series tag     | contact_email     | contact_email     | text      | text        |
| Yes      | series tag     | scoring_method    | scoring_method    | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:77fi-8jag d:2015-12-17T09:26:35.000Z t:municipality_name="City and County of San Francisco" t:municipality_url=http://www.sfgov.org t:contact_email=EnvHealth.DPH@sfdph.org t:scoring_method=graded m:feed_version=2
```

## Meta Commands

```ls
metric m:feed_version p:float l:feed_version t:dataTypeName=number

entity e:77fi-8jag l:"City and County of San Francisco - LIVES standard feed info" t:url=https://data.sfgov.org/api/views/77fi-8jag

property e:77fi-8jag t:meta.view v:id=77fi-8jag v:category="Health and Social Services" v:averageRating=0 v:name="City and County of San Francisco - LIVES standard feed info"

property e:77fi-8jag t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:77fi-8jag t:meta.view.owner v:id=grh2-fx3e v:screenName="FME Internal" v:displayName="FME Internal"

property e:77fi-8jag t:meta.view.tableauthor v:id=grh2-fx3e v:screenName="FME Internal" v:displayName="FME Internal"
```

## Top Records

```ls
| :updated_at | feed_version | municipality_name                | municipality_url     | contact_email           | scoring_method | 
| =========== | ============ | ================================ | ==================== | ======================= | ============== | 
| 1450344395  | 2.0          | City and County of San Francisco | http://www.sfgov.org | EnvHealth.DPH@sfdph.org | graded         | 
```