# Top syndicated pages from CDC.gov by weekly page views

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/top-syndicated-pages-from-cdc-gov-by-weekly-page-views) |
| Metadata | [Link](https://data.cdc.gov/api/views/rppv-wbiv) |
| Data: JSON | [100 Rows](https://data.cdc.gov/api/views/rppv-wbiv/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cdc.gov/api/views/rppv-wbiv/rows.csv?max_rows=100) |
| Host | data.cdc.gov |
| Id | rppv-wbiv |
| Name | Top syndicated pages from CDC.gov by weekly page views |
| Attribution | Office of the Associate Director for Communication, Division of News and Electronic Media |
| Category | Web Metrics |
| Tags | syndication, cdc.gov, web pages, page views |
| Created | 2014-04-16T15:46:11Z |
| Publication Date | 2014-10-16T20:12:07Z |

## Description

The CDC Content Syndication site at https://tools.cdc.gov/syndication/ allows you to import content from CDC websites directly into your own website or application. These services are provided free of charge from CDC. The data shown in this table represent the weekly top page views from CDC.gov offered by syndication.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type     | Render Type   |
| ======== | ============== | =================== | =================== | ============= | ============= |
| Yes      | time           | date                | Week Beginning      | calendar_date | calendar_date |
| Yes      | series tag     | content_source_urls | Content Source URLs | text          | text          |
| Yes      | numeric metric | page_views          | Page Views          | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:rppv-wbiv d:2014-09-28T00:00:00.000Z t:content_source_urls=#121256 m:page_views=20

series e:rppv-wbiv d:2014-09-28T00:00:00.000Z t:content_source_urls=disease.html m:page_views=847

series e:rppv-wbiv d:2014-09-28T00:00:00.000Z t:content_source_urls="Ebola - Media Item#i-0" m:page_views=42
```

## Meta Commands

```ls
metric m:page_views p:integer l:"Page Views" t:dataTypeName=number

entity e:rppv-wbiv l:"Top syndicated pages from CDC.gov by weekly page views" t:attribution="Office of the Associate Director for Communication, Division of News and Electronic Media" t:url=https://data.cdc.gov/api/views/rppv-wbiv

property e:rppv-wbiv t:meta.view v:id=rppv-wbiv v:category="Web Metrics" v:attributionLink=https://tools.cdc.gov/syndication v:averageRating=0 v:name="Top syndicated pages from CDC.gov by weekly page views" v:attribution="Office of the Associate Director for Communication, Division of News and Electronic Media"

property e:rppv-wbiv t:meta.view.owner v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:displayName=CDC

property e:rppv-wbiv t:meta.view.tableauthor v:id=g3fc-zmqn v:profileImageUrlMedium=/api/users/g3fc-zmqn/profile_images/THUMB v:profileImageUrlLarge=/api/users/g3fc-zmqn/profile_images/LARGE v:screenName=CDC v:profileImageUrlSmall=/api/users/g3fc-zmqn/profile_images/TINY v:roleName=publisher v:displayName=CDC

property e:rppv-wbiv t:meta.view.metadata.custom_fields.common_core v:Contact_Email=cdcinfo@cdc.gov v:Contact_Name="CDC INFO" v:Bureau_Code=009:00 v:Program_Code=009:020
```

## Top Records

```ls
| date                | content_source_urls                                                                                  | page_views | 
| =================== | ==================================================================================================== | ========== | 
| 2014-09-28T00:00:00 | #121256                                                                                              | 20         | 
| 2014-09-28T00:00:00 | disease.html                                                                                         | 847        | 
| 2014-09-28T00:00:00 | Ebola - Media Item#i-0                                                                               | 42         | 
| 2014-09-28T00:00:00 | Ebola - Media Item#i-2                                                                               | 19         | 
| 2014-09-28T00:00:00 | Ebola - Media Item#i-3                                                                               | 24         | 
| 2014-09-28T00:00:00 | Ebola - Media Item#i-4                                                                               | 20         | 
| 2014-09-28T00:00:00 | file:///storage/emulated/0/Android/data/gov.cdc.general/files/dotw/common/quiz.html?loadview=2&disea | 35         | 
| 2014-09-28T00:00:00 | http://blogs.cdc.gov/publichealthmatters/2014/09/after-the-storm-pets-and-preparedness/              | 33         | 
| 2014-09-28T00:00:00 | http://blogs.cdc.gov/publichealthmatters/2014/09/a-prepared-caregiver/                               | 27         | 
| 2014-09-28T00:00:00 | http://blogs.cdc.gov/publichealthmatters/2014/09/businesses-ready-and-willing-to-help-communities-du | 63         | 
```