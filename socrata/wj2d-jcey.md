# Spirit of East Austin Comments

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/spirit-of-east-austin-comments) |
| Metadata | [Link](https://data.austintexas.gov/api/views/wj2d-jcey) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/wj2d-jcey/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/wj2d-jcey/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | wj2d-jcey |
| Name | Spirit of East Austin Comments |
| Category | Neighborhood |
| Tags | spirit of east austin, east austin |
| Created | 2016-04-12T14:23:39Z |
| Publication Date | 2016-04-12T17:03:03Z |

## Description

During the Sept. 12, 2015 Spirit of East Austin launch event, participants were asked: What community resources do we have? What community resources are we missing? What?s one thing you could have to improve the quality of life? What?s one thing I can do to make a difference? These are their captured responses.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | theme       | Theme      | text      | text        |
| Yes      | series tag  | category    | Category   | text      | text        |
| Yes      | series tag  | comment     | Comment    | text      | text        |
| Yes      | series tag  | zip_code    | ZIP Code   | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:wj2d-jcey d:2016-04-12T07:23:44.000Z t:category=Wisdom t:theme=Education t:comment="That a lot of people are about education" m:row_number.wj2d-jcey=1

series e:wj2d-jcey d:2016-04-12T07:23:44.000Z t:category=Wisdom t:zip_code=78752 t:theme=Education t:comment="College funding was cut by the state this year. This pertains to voting. Make change through your vote!" m:row_number.wj2d-jcey=2

series e:wj2d-jcey d:2016-04-12T07:23:44.000Z t:category=Wisdom t:theme=Education t:comment="Cuts by state. Disparity in education funding. Public schools. Community colleges." m:row_number.wj2d-jcey=3
```

## Meta Commands

```ls
metric m:row_number.wj2d-jcey p:long l:"Row Number"

entity e:wj2d-jcey l:"Spirit of East Austin Comments" t:url=https://data.austintexas.gov/api/views/wj2d-jcey

property e:wj2d-jcey t:meta.view v:id=wj2d-jcey v:category=Neighborhood v:averageRating=0 v:name="Spirit of East Austin Comments"

property e:wj2d-jcey t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:wj2d-jcey t:meta.view.owner v:id=n7eq-gk2e v:screenName="Marbenn Cayetano" v:lastNotificationSeenAt=1491926094 v:displayName="Marbenn Cayetano"

property e:wj2d-jcey t:meta.view.tableauthor v:id=n7eq-gk2e v:screenName="Marbenn Cayetano" v:roleName=administrator v:lastNotificationSeenAt=1491926094 v:displayName="Marbenn Cayetano"
```

## Top Records

```ls
| :updated_at | theme     | category | comment                                                                                                 | zip_code | 
| =========== | ========= | ======== | ======================================================================================================= | ======== | 
| 1460445824  | Education | Wisdom   | That a lot of people are about education                                                                |          | 
| 1460445824  | Education | Wisdom   | College funding was cut by the state this year. This pertains to voting. Make change through your vote! | 78752    | 
| 1460445824  | Education | Wisdom   | Cuts by state. Disparity in education funding. Public schools. Community colleges.                      |          | 
| 1460445824  | Education | Wisdom   | Knowledge leads to voting, which leads to change!                                                       | 78752    | 
| 1460445824  | Education | Wisdom   | The public needs to know more about what's happening in schools                                         |          | 
| 1460445824  | Education | Wisdom   | Everyone needs a seat at the table.                                                                     |          | 
| 1460445824  | Education | Wisdom   | Knowledge is power!                                                                                     |          | 
| 1460445824  | Education | Wisdom   | Knowledge is dynamic, not static! This forum creates knowledge!                                         | 78723    | 
| 1460445824  | Education | Wisdom   | People are hungry for change in education outcomes.                                                     |          | 
| 1460445824  | Education | Wisdom   | Learned we have common hopes and dreams for our community.                                              | 78723    | 
```