# DOT - Total Miles Of Bicycle Lanes And Paths Chart

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/dot-total-miles-of-bicycle-lanes-and-paths-chart-deb3c) |
| Metadata | [Link](https://data.lacity.org/api/views/pnat-cnpj) |
| Data: JSON | [100 Rows](https://data.lacity.org/api/views/pnat-cnpj/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.lacity.org/api/views/pnat-cnpj/rows.csv?max_rows=100) |
| Host | data.lacity.org |
| Id | pnat-cnpj |
| Name | DOT - Total Miles Of Bicycle Lanes And Paths Chart |
| Category | A Livable and Sustainable City |
| Created | 2014-05-30T22:06:25Z |
| Publication Date | 2014-05-30T22:06:47Z |

## Columns

```ls
| Included | Schema Type    | Field Name                             | Name                                   | Data Type     | Render Type   |
| ======== | ============== | ====================================== | ====================================== | ============= | ============= |
| No       |                | date_name                              | Date Name                              | text          | text          |
| Yes      | time           | date_value                             | Date Value                             | calendar_date | calendar_date |
| Yes      | numeric metric | total_miles_of_bicycle_lanes_and_paths | Total Miles of Bicycle Lanes and Paths | number        | number        |
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
series e:pnat-cnpj d:2009-07-01T00:00:00.000Z m:total_miles_of_bicycle_lanes_and_paths=203.46

series e:pnat-cnpj d:2010-07-01T00:00:00.000Z m:total_miles_of_bicycle_lanes_and_paths=205.2

series e:pnat-cnpj d:2011-07-01T00:00:00.000Z m:total_miles_of_bicycle_lanes_and_paths=228.61
```

## Meta Commands

```ls
metric m:total_miles_of_bicycle_lanes_and_paths p:float l:"Total Miles of Bicycle Lanes and Paths" t:dataTypeName=number

entity e:pnat-cnpj l:"DOT - Total Miles Of Bicycle Lanes And Paths Chart" t:url=https://data.lacity.org/api/views/pnat-cnpj

property e:pnat-cnpj t:meta.view v:id=pnat-cnpj v:category="A Livable and Sustainable City" v:averageRating=0 v:name="DOT - Total Miles Of Bicycle Lanes And Paths Chart"

property e:pnat-cnpj t:meta.view.license v:name="Creative Commons 1.0 Universal (Public Domain Dedication)" v:termsLink=http://creativecommons.org/publicdomain/zero/1.0/legalcode v:logoUrl=images/licenses/ccZero.png

property e:pnat-cnpj t:meta.view.owner v:id=8b8n-vh2w v:profileImageUrlMedium=/api/users/8b8n-vh2w/profile_images/THUMB v:profileImageUrlLarge=/api/users/8b8n-vh2w/profile_images/LARGE v:screenName="LA DOT OpenData" v:profileImageUrlSmall=/api/users/8b8n-vh2w/profile_images/TINY v:displayName="LA DOT OpenData"

property e:pnat-cnpj t:meta.view.tableauthor v:id=8b8n-vh2w v:profileImageUrlMedium=/api/users/8b8n-vh2w/profile_images/THUMB v:profileImageUrlLarge=/api/users/8b8n-vh2w/profile_images/LARGE v:screenName="LA DOT OpenData" v:profileImageUrlSmall=/api/users/8b8n-vh2w/profile_images/TINY v:roleName=publisher v:displayName="LA DOT OpenData"
```

## Top Records

```ls
| date_name | date_value          | total_miles_of_bicycle_lanes_and_paths | 
| ========= | =================== | ====================================== | 
| FY2009    | 2009-07-01T00:00:00 | 203.46                                 | 
| FY2010    | 2010-07-01T00:00:00 | 205.2                                  | 
| FY2011    | 2011-07-01T00:00:00 | 228.61                                 | 
| FY2012    | 2012-07-01T00:00:00 | 283.15                                 | 
| FY2013    | 2013-07-01T00:00:00 | 385.65                                 | 
```