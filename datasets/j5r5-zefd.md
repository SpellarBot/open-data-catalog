# 2012 Age 0-17 Youth Population by Race/Ethnicity by County

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/2012-age-0-17-youth-population-by-race-ethnicity-by-county) |
| Metadata | [Link](https://data.wa.gov/api/views/j5r5-zefd) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/j5r5-zefd/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/j5r5-zefd/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | j5r5-zefd |
| Name | 2012 Age 0-17 Youth Population by Race/Ethnicity by County |
| Attribution | Office of Juvenile Justice |
| Created | 2015-11-17T04:24:05Z |
| Publication Date | 2015-11-17T04:26:44Z |

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                  | Data Type | Render Type |
| ======== | ============== | =================== | ===================== | ========= | =========== |
| Yes      | series tag     | county              | County                | text      | text        |
| Yes      | numeric metric | white_non_hispanic  | White (Non-Hispanic)  | number    | number      |
| Yes      | numeric metric | black_non_hispanic  | Black (Non-Hispanic)  | number    | number      |
| Yes      | numeric metric | indian_non_hispanic | Indian (Non-Hispanic) | number    | number      |
| Yes      | numeric metric | asian_non_hispanic  | Asian (Non-Hispanic)  | number    | number      |
| Yes      | numeric metric | hispanic            | Hispanic              | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:j5r5-zefd d:2012-01-01T00:00:00.000Z t:county=Adams m:asian_non_hispanic=37 m:indian_non_hispanic=31 m:black_non_hispanic=46 m:white_non_hispanic=1574 m:hispanic=4932

series e:j5r5-zefd d:2012-01-01T00:00:00.000Z t:county=Asotin m:asian_non_hispanic=52 m:indian_non_hispanic=112 m:black_non_hispanic=75 m:white_non_hispanic=4131 m:hispanic=293

series e:j5r5-zefd d:2012-01-01T00:00:00.000Z t:county=Benton m:asian_non_hispanic=1474 m:indian_non_hispanic=453 m:black_non_hispanic=1110 m:white_non_hispanic=30847 m:hispanic=14429
```

## Meta Commands

```ls
metric m:white_non_hispanic p:integer l:"White (Non-Hispanic)" t:dataTypeName=number

metric m:black_non_hispanic p:integer l:"Black (Non-Hispanic)" t:dataTypeName=number

metric m:indian_non_hispanic p:integer l:"Indian (Non-Hispanic)" t:dataTypeName=number

metric m:asian_non_hispanic p:integer l:"Asian (Non-Hispanic)" t:dataTypeName=number

metric m:hispanic p:integer l:Hispanic t:dataTypeName=number

entity e:j5r5-zefd l:"2012 Age 0-17 Youth Population by Race/Ethnicity by County" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/j5r5-zefd

property e:j5r5-zefd t:meta.view v:id=j5r5-zefd v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=100 v:name="2012 Age 0-17 Youth Population by Race/Ethnicity by County" v:attribution="Office of Juvenile Justice"

property e:j5r5-zefd t:meta.view.license v:name="Public Domain"

property e:j5r5-zefd t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:j5r5-zefd t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```