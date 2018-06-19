# Seattle Parks and Recreation Community Center People Counter Data

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/seattle-parks-and-recreation-community-center-people-counter-data) |
| Metadata | [Link](https://data.seattle.gov/api/views/k7wr-k9jj) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/k7wr-k9jj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/k7wr-k9jj/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | k7wr-k9jj |
| Name | Seattle Parks and Recreation Community Center People Counter Data |
| Attribution | Seattle Parks and Recreation |
| Category | Parks and Recreation |
| Tags | seattle, parks, recreation, community center, people, counter, data |
| Created | 2016-03-09T22:33:56Z |
| Publication Date | 2016-03-17T23:46:04Z |

## Description

People Counter is a tool used to count the number of people entering Seattle Parks and Recreation Community Centers. Seattle Parks and Recreation has twenty-six Community Centers that offer a vast variety of classes and programming.

## Columns

```ls
| Included | Schema Type    | Field Name             | Name                   | Data Type     | Render Type   |
| ======== | ============== | ====================== | ====================== | ============= | ============= |
| Yes      | series tag     | facility_name          | Facility Name          | text          | text          |
| Yes      | time           | date                   | Date                   | calendar_date | calendar_date |
| Yes      | numeric metric | full_service           | Full Service           | number        | number        |
| Yes      | numeric metric | add_l_community_access | Add'l Community Access | number        | number        |
| Yes      | numeric metric | late_night_teens       | Late Night Teens       | number        | number        |
| Yes      | numeric metric | total                  | Total                  | number        | number        |
```

## Time Field

```ls
Value = date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:k7wr-k9jj d:2015-01-01T00:00:00.000Z t:facility_name="Alki CC" m:total=6078 m:add_l_community_access=2525 m:full_service=3553 m:late_night_teens=0

series e:k7wr-k9jj d:2015-02-01T00:00:00.000Z t:facility_name="Alki CC" m:total=5968 m:add_l_community_access=2456 m:full_service=3512 m:late_night_teens=0

series e:k7wr-k9jj d:2015-03-01T00:00:00.000Z t:facility_name="Alki CC" m:total=6967 m:add_l_community_access=2881 m:full_service=4086 m:late_night_teens=0
```

## Meta Commands

```ls
metric m:full_service p:integer l:"Full Service" t:dataTypeName=number

metric m:add_l_community_access p:integer l:"Add'l Community Access" t:dataTypeName=number

metric m:late_night_teens p:integer l:"Late Night Teens" t:dataTypeName=number

metric m:total p:integer l:Total t:dataTypeName=number

entity e:k7wr-k9jj l:"Seattle Parks and Recreation Community Center People Counter Data" t:attribution="Seattle Parks and Recreation" t:url=https://data.seattle.gov/api/views/k7wr-k9jj

property e:k7wr-k9jj t:meta.view v:id=k7wr-k9jj v:category="Parks and Recreation" v:attributionLink=http://www.seattle.gov/parks v:averageRating=0 v:name="Seattle Parks and Recreation Community Center People Counter Data" v:attribution="Seattle Parks and Recreation"

property e:k7wr-k9jj t:meta.view.license v:name="Public Domain"

property e:k7wr-k9jj t:meta.view.owner v:id=3asm-yice v:profileImageUrlMedium=/api/users/3asm-yice/profile_images/THUMB v:profileImageUrlLarge=/api/users/3asm-yice/profile_images/LARGE v:screenName="Smith, Christopher" v:profileImageUrlSmall=/api/users/3asm-yice/profile_images/TINY v:displayName="Smith, Christopher"

property e:k7wr-k9jj t:meta.view.tableauthor v:id=3asm-yice v:profileImageUrlMedium=/api/users/3asm-yice/profile_images/THUMB v:profileImageUrlLarge=/api/users/3asm-yice/profile_images/LARGE v:screenName="Smith, Christopher" v:profileImageUrlSmall=/api/users/3asm-yice/profile_images/TINY v:roleName=publisher v:displayName="Smith, Christopher"
```

## Top Records

```ls
| facility_name | date                | full_service | add_l_community_access | late_night_teens | total | 
| ============= | =================== | ============ | ====================== | ================ | ===== | 
| Alki CC       | 2015-01-01T00:00:00 | 3553         | 2525                   | 0                | 6078  | 
| Alki CC       | 2015-02-01T00:00:00 | 3512         | 2456                   | 0                | 5968  | 
| Alki CC       | 2015-03-01T00:00:00 | 4086         | 2881                   | 0                | 6967  | 
| Alki CC       | 2015-04-01T00:00:00 | 3473         | 3489                   | 0                | 6962  | 
| Alki CC       | 2015-05-01T00:00:00 | 3749         | 3093                   | 0                | 6842  | 
| Alki CC       | 2015-06-01T00:00:00 | 3525         | 3693                   | 0                | 7218  | 
| Alki CC       | 2015-07-01T00:00:00 | 3291         | 5472                   | 0                | 8763  | 
| Alki CC       | 2015-08-01T00:00:00 | 2980         | 4608                   | 0                | 7588  | 
| Alki CC       | 2015-09-01T00:00:00 | 3633         | 3883                   | 0                | 7516  | 
| Alki CC       | 2015-10-01T00:00:00 | 4062         | 3416                   | 0                | 7478  | 
```