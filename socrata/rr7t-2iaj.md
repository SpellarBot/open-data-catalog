# Law enforcement call response times

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/law-enforcement-call-response-times-3bf2d) |
| Metadata | [Link](https://data.kingcounty.gov/api/views/rr7t-2iaj) |
| Data: JSON | [100 Rows](https://data.kingcounty.gov/api/views/rr7t-2iaj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.kingcounty.gov/api/views/rr7t-2iaj/rows.csv?max_rows=100) |
| Host | data.kingcounty.gov |
| Id | rr7t-2iaj |
| Name | Law enforcement call response times |
| Attribution | King County Sheriff |
| Category | Public Safety |
| Tags | 911, response times, sheriff |
| Created | 2013-02-13T20:29:12Z |
| Publication Date | 2013-02-13T20:31:43Z |

## Description

Priority X- critical dispatch: calls that pose an obvious threat to the safety of persons (such as shootings)
Priority 1- immediate dispatch: calls that require immediate police action (such as injury traffic accidents)
Priority 2- prompt dispatch: calls that could escalate to a more serious degree if not policed quickly (such as verbal disturbances)
Priority 3- routine dispatch: calls where response time is not a critical factor (such as audible alarms)

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| Yes      | series tag     | jurisdiction    | Jurisdiction    | text      | text        |
| Yes      | time           | year            | Year            | number    | number      |
| Yes      | series tag     | call_type       | Call type       | text      | text        |
| Yes      | numeric metric | number_of_calls | Number of calls | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:rr7t-2iaj d:2009-01-01T00:00:00.000Z t:call_type="Critical Dispatch Calls" t:jurisdiction="Contract Cities" m:number_of_calls=3.9

series e:rr7t-2iaj d:2009-01-01T00:00:00.000Z t:call_type="Critical Dispatch Calls" t:jurisdiction="Unincorporated Northeast" m:number_of_calls=5.1

series e:rr7t-2iaj d:2009-01-01T00:00:00.000Z t:call_type="Critical Dispatch Calls" t:jurisdiction="Unincorporated Southeast" m:number_of_calls=5.5
```

## Meta Commands

```ls
metric m:number_of_calls p:float l:"Number of calls" t:dataTypeName=number

entity e:rr7t-2iaj l:"Law enforcement call response times" t:attribution="King County Sheriff" t:url=https://data.kingcounty.gov/api/views/rr7t-2iaj

property e:rr7t-2iaj t:meta.view v:id=rr7t-2iaj v:category="Public Safety" v:averageRating=0 v:name="Law enforcement call response times" v:attribution="King County Sheriff"

property e:rr7t-2iaj t:meta.view.license v:name="Public Domain"

property e:rr7t-2iaj t:meta.view.owner v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"

property e:rr7t-2iaj t:meta.view.tableauthor v:id=7ja6-sv4x v:profileImageUrlMedium=/api/users/7ja6-sv4x/profile_images/THUMB v:profileImageUrlLarge=/api/users/7ja6-sv4x/profile_images/LARGE v:screenName="King County Open Data admin" v:profileImageUrlSmall=/api/users/7ja6-sv4x/profile_images/TINY v:roleName=administrator v:lastNotificationSeenAt=1492197205 v:displayName="King County Open Data admin"
```

## Top Records

```ls
| jurisdiction             | year | call_type               | number_of_calls | 
| ======================== | ==== | ======================= | =============== | 
| Contract Cities          | 2009 | Critical Dispatch Calls | 3.9             | 
| Unincorporated Northeast | 2009 | Critical Dispatch Calls | 5.1             | 
| Unincorporated Southeast | 2009 | Critical Dispatch Calls | 5.5             | 
| Unincorporated West      | 2009 | Critical Dispatch Calls | 4.3             | 
| Contract Cities          | 2010 | Critical Dispatch Calls | 4.1             | 
| Unincorporated Northeast | 2010 | Critical Dispatch Calls | 6.2             | 
| Unincorporated Southeast | 2010 | Critical Dispatch Calls | 6.6             | 
| Unincorporated West      | 2010 | Critical Dispatch Calls | 3.8             | 
| Contract Cities          | 2011 | Critical Dispatch Calls | 3.9             | 
| Unincorporated Northeast | 2011 | Critical Dispatch Calls | 8.2             | 
```