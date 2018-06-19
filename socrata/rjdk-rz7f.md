# DOT- Traffic Signal Trouble Call Responses Within One Hour

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dot-traffic-signal-trouble-call-responses-within-one-hour-d0cb7) |
| Metadata | [Link](https://data.lacity.org/api/views/rjdk-rz7f) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/rjdk-rz7f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/rjdk-rz7f/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | rjdk-rz7f |
| Name | DOT- Traffic Signal Trouble Call Responses Within One Hour |
| Category | A Well Run City |
| Tags | traffic signal, ladot |
| Created | 2014-05-30T22:05:15Z |
| Publication Date | 2014-05-30T22:08:04Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                                    | Data Type     | Render Type   |
| ======== | ============== | =================== | ======================================= | ============= | ============= |
| No       |                | date_name           | Date Name                               | text          | text          |
| Yes      | time           | date_value          | Date Value                              | calendar_date | calendar_date |
| Yes      | numeric metric | percentage_of_calls | % of calls responded to within one hour | percent       | percent       |
```

## Time Field

```ls
Value = date_value
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = date_name
```

## Data Commands

```ls
series e:rjdk-rz7f d:2014-01-01T00:00:00.000Z m:percentage_of_calls=44

series e:rjdk-rz7f d:2014-02-01T00:00:00.000Z m:percentage_of_calls=41

series e:rjdk-rz7f d:2014-03-01T00:00:00.000Z m:percentage_of_calls=42
```

## Meta Commands

```ls
metric m:percentage_of_calls p:integer l:"% of calls responded to within one hour" t:dataTypeName=percent

entity e:rjdk-rz7f l:"DOT- Traffic Signal Trouble Call Responses Within One Hour" t:url=https://data.lacity.org/api/views/rjdk-rz7f

property e:rjdk-rz7f t:meta.view v:id=rjdk-rz7f v:category="A Well Run City" v:averageRating=0 v:name="DOT- Traffic Signal Trouble Call Responses Within One Hour"

property e:rjdk-rz7f t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:rjdk-rz7f t:meta.view.owner v:id=8b8n-vh2w v:profileImageUrlMedium=/api/users/8b8n-vh2w/profile_images/THUMB v:profileImageUrlLarge=/api/users/8b8n-vh2w/profile_images/LARGE v:screenName="LA DOT OpenData" v:profileImageUrlSmall=/api/users/8b8n-vh2w/profile_images/TINY v:displayName="LA DOT OpenData"

property e:rjdk-rz7f t:meta.view.tableauthor v:id=8b8n-vh2w v:profileImageUrlMedium=/api/users/8b8n-vh2w/profile_images/THUMB v:profileImageUrlLarge=/api/users/8b8n-vh2w/profile_images/LARGE v:screenName="LA DOT OpenData" v:profileImageUrlSmall=/api/users/8b8n-vh2w/profile_images/TINY v:roleName=publisher v:displayName="LA DOT OpenData"
```

## Top Records

```ls
| date_name | date_value          | percentage_of_calls | 
| ========= | =================== | =================== | 
| Jan-14    | 2014-01-01T00:00:00 | 44                  | 
| Feb-14    | 2014-02-01T00:00:00 | 41                  | 
| Mar-14    | 2014-03-01T00:00:00 | 42                  | 
| Apr-14    | 2014-04-01T00:00:00 | 38                  | 
| May-14    | 2014-05-01T00:00:00 | 52                  | 
```