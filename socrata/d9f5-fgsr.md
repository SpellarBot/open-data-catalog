# Poverty Estimates for Washington Counties Age 0-17

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/poverty-estimates-for-washington-counties-age-0-17) |
| Metadata | [Link](https://data.wa.gov/api/views/d9f5-fgsr) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/d9f5-fgsr/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/d9f5-fgsr/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | d9f5-fgsr |
| Name | Poverty Estimates for Washington Counties Age 0-17 |
| Attribution | Office of Juvenile Justice |
| Category | Demographics |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, poverty, youth |
| Created | 2015-12-04T05:50:52Z |
| Publication Date | 2015-12-04T05:53:49Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type | Render Type |
| ======== | ============== | ======================= | ========================= | ========= | =========== |
| No       | time           | :updated_at             | updated_at                | meta_data | meta_data   |
| Yes      | series tag     | county                  | County                    | text      | text        |
| Yes      | numeric metric | 2012_poverty            | 2012 Poverty              | number    | number      |
| Yes      | numeric metric | 2012_of_0_17_population | 2012 % of 0-17 Population | number    | number      |
| Yes      | numeric metric | 2011_poverty            | 2011 Poverty              | number    | number      |
| Yes      | numeric metric | 2010_poverty            | 2010 Poverty              | number    | number      |
| Yes      | numeric metric | 2009_poverty            | 2009 Poverty              | number    | number      |
| Yes      | numeric metric | 2008_poverty            | 2008 Poverty              | number    | number      |
| Yes      | numeric metric | change_2011_2012        | % Change 2011-2012        | number    | number      |
| Yes      | numeric metric | of_change_2008_2012     | % of Change 2008-2012     | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:d9f5-fgsr d:2015-12-03T21:50:57.000Z t:county=Adams m:2009_poverty=1786 m:2008_poverty=1545 m:2012_poverty=1760 m:change_2011_2012=-6.7 m:2012_of_0_17_population=26.6 m:2010_poverty=1970 m:of_change_2008_2012=13.9 m:2011_poverty=1887

series e:d9f5-fgsr d:2015-12-03T21:50:57.000Z t:county=Asotin m:2009_poverty=1108 m:2008_poverty=1180 m:2012_poverty=1065 m:change_2011_2012=-11.3 m:2012_of_0_17_population=23.5 m:2010_poverty=1176 m:of_change_2008_2012=-9.7 m:2011_poverty=1200

series e:d9f5-fgsr d:2015-12-03T21:50:57.000Z t:county=Benton m:2009_poverty=8011 m:2008_poverty=7252 m:2012_poverty=10037 m:change_2011_2012=22.9 m:2012_of_0_17_population=21 m:2010_poverty=8693 m:of_change_2008_2012=38.4 m:2011_poverty=8165
```

## Meta Commands

```ls
metric m:2012_poverty p:integer l:"2012 Poverty" t:dataTypeName=number

metric m:2012_of_0_17_population p:float l:"2012 % of 0-17 Population" t:dataTypeName=number

metric m:2011_poverty p:integer l:"2011 Poverty" t:dataTypeName=number

metric m:2010_poverty p:integer l:"2010 Poverty" t:dataTypeName=number

metric m:2009_poverty p:integer l:"2009 Poverty" t:dataTypeName=number

metric m:2008_poverty p:integer l:"2008 Poverty" t:dataTypeName=number

metric m:change_2011_2012 p:float l:"% Change 2011-2012" t:dataTypeName=number

metric m:of_change_2008_2012 p:float l:"% of Change 2008-2012" t:dataTypeName=number

entity e:d9f5-fgsr l:"Poverty Estimates for Washington Counties Age 0-17" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/d9f5-fgsr

property e:d9f5-fgsr t:meta.view v:id=d9f5-fgsr v:category=Demographics v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Poverty Estimates for Washington Counties Age 0-17" v:attribution="Office of Juvenile Justice"

property e:d9f5-fgsr t:meta.view.license v:name="Public Domain"

property e:d9f5-fgsr t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:d9f5-fgsr t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| :updated_at | county   | 2012_poverty | 2012_of_0_17_population | 2011_poverty | 2010_poverty | 2009_poverty | 2008_poverty | change_2011_2012 | of_change_2008_2012 | 
| =========== | ======== | ============ | ======================= | ============ | ============ | ============ | ============ | ================ | =================== | 
| 1449179457  | Adams    | 1760         | 26.6                    | 1887         | 1970         | 1786         | 1545         | -6.7             | 13.9                | 
| 1449179457  | Asotin   | 1065         | 23.5                    | 1200         | 1176         | 1108         | 1180         | -11.3            | -9.7                | 
| 1449179457  | Benton   | 10037        | 21.0                    | 8165         | 8693         | 8011         | 7252         | 22.9             | 38.4                | 
| 1449179457  | Chelan   | 4085         | 22.8                    | 4314         | 3875         | 3432         | 3034         | -5.3             | 34.6                | 
| 1449179457  | Clallam  | 2778         | 22.6                    | 2508         | 2936         | 2859         | 2712         | 10.8             | 2.4                 | 
| 1449179457  | Clark    | 17814        | 16.1                    | 19973        | 19511        | 18151        | 14074        | -10.8            | 26.6                | 
| 1449179457  | Columbia | 164          | 22.8                    | 172          | 172          | 169          | 169          | -4.7             | -3.0                | 
| 1449179457  | Cowlitz  | 5497         | 23.6                    | 6514         | 6895         | 5640         | 4392         | -15.6            | 25.2                | 
| 1449179457  | Douglas  | 2460         | 23.9                    | 2796         | 2234         | 2172         | 1745         | -12.0            | 41.0                | 
| 1449179457  | Ferry    | 423          | 29.2                    | 424          | 409          | 504          | 488          | -0.2             | -13.3               | 
```