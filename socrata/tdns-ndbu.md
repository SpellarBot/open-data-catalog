# Roll-up By Location

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/roll-up-by-location-842fe) |
| Metadata | [Link](https://data.hawaii.gov/api/views/tdns-ndbu) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/tdns-ndbu/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/tdns-ndbu/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | tdns-ndbu |
| Name | Roll-up By Location |
| Created | 2013-11-21T00:56:15Z |
| Publication Date | 2013-11-21T01:03:40Z |

## Description

Source data: https://data.hawaii.gov/Public-Safety/Roll-up-by-Location/v3gj-97wt

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                 | Data Type     | Render Type   |
| ======== | ============== | ================== | ==================== | ============= | ============= |
| Yes      | time           | date               | Date                 | calendar_date | calendar_date |
| Yes      | series tag     | location           | Location             | text          | text          |
| Yes      | series tag     | count              | Count                | text          | text          |
| Yes      | numeric metric | total_count        | Total Count          | number        | number        |
| Yes      | numeric metric | total_count_male   | Total Count (Male)   | number        | number        |
| Yes      | numeric metric | total_count_female | Total Count (Female) | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:tdns-ndbu d:2012-07-02T00:00:00.000Z t:count=Weekly t:location=Hawaii m:total_count_male=3449 m:total_count_female=632 m:total_count=4081

series e:tdns-ndbu d:2012-07-02T00:00:00.000Z t:count=Weekly t:location=Mainland m:total_count_male=1677 m:total_count_female=0 m:total_count=1677

series e:tdns-ndbu d:2012-07-09T00:00:00.000Z t:count=Weekly t:location=Hawaii m:total_count_male=3415 m:total_count_female=641 m:total_count=4056
```

## Meta Commands

```ls
metric m:total_count p:integer l:"Total Count" t:dataTypeName=number

metric m:total_count_male p:integer l:"Total Count (Male)" t:dataTypeName=number

metric m:total_count_female p:integer l:"Total Count (Female)" t:dataTypeName=number

entity e:tdns-ndbu l:"Roll-up By Location" t:url=https://data.hawaii.gov/api/views/tdns-ndbu

property e:tdns-ndbu t:meta.view v:id=tdns-ndbu v:attributionLink=https://data.hawaii.gov/Public-Safety/Roll-up-by-Location/v3gj-97wt v:averageRating=0 v:name="Roll-up By Location"

property e:tdns-ndbu t:meta.view.owner v:id=wktp-67q4 v:screenName=karen v:displayName=karen

property e:tdns-ndbu t:meta.view.tableauthor v:id=trij-xrnq v:profileImageUrlMedium=/api/users/trij-xrnq/profile_images/THUMB v:profileImageUrlLarge=/api/users/trij-xrnq/profile_images/LARGE v:screenName="Meredith Slota" v:profileImageUrlSmall=/api/users/trij-xrnq/profile_images/TINY v:lastNotificationSeenAt=1492637852 v:displayName="Meredith Slota"
```

## Top Records

```ls
| date                | location | count  | total_count | total_count_male | total_count_female | 
| =================== | ======== | ====== | =========== | ================ | ================== | 
| 2012-07-02T00:00:00 | Hawaii   | Weekly | 4081        | 3449             | 632                | 
| 2012-07-02T00:00:00 | Mainland | Weekly | 1677        | 1677             | 0                  | 
| 2012-07-09T00:00:00 | Hawaii   | Weekly | 4056        | 3415             | 641                | 
| 2012-07-09T00:00:00 | Mainland | Weekly | 1488        | 1488             | 0                  | 
| 2012-07-16T00:00:00 | Mainland | Weekly | 1677        | 1677             | 0                  | 
| 2012-07-16T00:00:00 | Hawaii   | Weekly | 4060        | 3424             | 636                | 
| 2012-07-23T00:00:00 | Hawaii   | Weekly | 4099        | 3448             | 651                | 
| 2012-07-23T00:00:00 | Mainland | Weekly | 1676        | 1676             | 0                  | 
| 2012-07-30T00:00:00 | Hawaii   | Weekly | 4118        | 3415             | 703                | 
| 2012-07-30T00:00:00 | Mainland | Weekly | 1677        | 1677             | 0                  | 
```