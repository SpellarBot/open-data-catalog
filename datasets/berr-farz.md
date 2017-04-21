# State of Hawaii Open Data growth

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/state-of-hawaii-open-data-growth-b6a6b) |
| Metadata | [Link](https://data.hawaii.gov/api/views/berr-farz) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/berr-farz/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/berr-farz/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | berr-farz |
| Name | State of Hawaii Open Data growth |
| Attribution | Office of Information Management and Technology |
| Category | Government-Wide Support |
| Tags | open data, maps, charts |
| Created | 2013-04-19T21:25:13Z |
| Publication Date | 2013-04-19T21:53:57Z |

## Description

Quarter by quarter updates of the number of maps, charts and datasets made available to the public

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type | Render Type |
| ======== | ============== | =============== | =============== | ========= | =========== |
| No       |                | quarter         | Quarter         | number    | text        |
| No       |                | year            | Year            | number    | text        |
| Yes      | numeric metric | charts          | Charts          | number    | number      |
| Yes      | numeric metric | maps            | Maps            | number    | number      |
| Yes      | numeric metric | data_sets       | Data Sets       | number    | number      |
| Yes      | series tag     | months          | Months          | text      | text        |
| Yes      | numeric metric | charts_added    | Charts added    | number    | number      |
| Yes      | numeric metric | maps_added      | Maps Added      | number    | number      |
| Yes      | numeric metric | data_sets_added | Data Sets Added | number    | number      |
```

## Time Field

```ls
Value = year-quarter
Format & Zone = yyyy-q
```

## Series Fields

```ls
Excluded Fields = year,quarter
```

## Data Commands

```ls
series e:berr-farz d:2012-04-01T00:00:00.000Z t:months=April-June m:charts=16 m:maps_added=17 m:maps=17 m:data_sets_added=239 m:charts_added=60 m:data_sets=239

series e:berr-farz d:2012-07-01T00:00:00.000Z t:months=July-September m:charts=145 m:maps_added=39 m:maps=56 m:data_sets_added=440 m:charts_added=85 m:data_sets=679

series e:berr-farz d:2012-10-01T00:00:00.000Z t:months=October-December m:charts=283 m:maps_added=115 m:maps=171 m:data_sets_added=158 m:charts_added=138 m:data_sets=837
```

## Meta Commands

```ls
metric m:charts p:integer l:Charts d:"Number of charts on data.hawaii.gov" t:dataTypeName=number

metric m:maps p:integer l:Maps d:"Number of Maps available at data.hawaii.gov" t:dataTypeName=number

metric m:data_sets p:integer l:"Data Sets" d:"Number pf datasets available at data.hawaii.gov" t:dataTypeName=number

metric m:charts_added p:integer l:"Charts added" d:"Number of charts added this period" t:dataTypeName=number

metric m:maps_added p:integer l:"Maps Added" d:"Maps added this period" t:dataTypeName=number

metric m:data_sets_added p:integer l:"Data Sets Added" d:"Number of data sets added this period" t:dataTypeName=number

entity e:berr-farz l:"State of Hawaii Open Data growth" t:attribution="Office of Information Management and Technology" t:url=https://data.hawaii.gov/api/views/berr-farz

property e:berr-farz t:meta.view v:id=berr-farz v:category="Government-Wide Support" v:attributionLink=http://hawaii.gov/oimt v:averageRating=0 v:name="State of Hawaii Open Data growth" v:attribution="Office of Information Management and Technology"

property e:berr-farz t:meta.view.license v:name="Creative Commons Attribution | Noncommercial | No Derivative Works 3.0 Unported" v:termsLink=http://creativecommons.org/licenses/by-nc-nd/3.0/legalcode v:logoUrl=images/licenses/cc30byncnd.png

property e:berr-farz t:meta.view.owner v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:displayName="OIMT Open Data Coordinator"

property e:berr-farz t:meta.view.tableauthor v:id=a5cm-ukuw v:profileImageUrlMedium=/api/users/a5cm-ukuw/profile_images/THUMB v:profileImageUrlLarge=/api/users/a5cm-ukuw/profile_images/LARGE v:screenName="OIMT Open Data Coordinator" v:profileImageUrlSmall=/api/users/a5cm-ukuw/profile_images/TINY v:roleName=publisher v:displayName="OIMT Open Data Coordinator"
```

## Top Records

```ls
| quarter | year | charts | maps | data_sets | months           | charts_added | maps_added | data_sets_added | 
| ======= | ==== | ====== | ==== | ========= | ================ | ============ | ========== | =============== | 
| 2       | 2012 | 16     | 17   | 239       | April-June       | 60           | 17         | 239             | 
| 3       | 2012 | 145    | 56   | 679       | July-September   | 85           | 39         | 440             | 
| 4       | 2012 | 283    | 171  | 837       | October-December | 138          | 115        | 158             | 
| 1       | 2013 | 302    | 189  | 905       | January-March    | 19           | 18         | 68              | 
```