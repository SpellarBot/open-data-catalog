# 2012 Age 0-17 Youth Population by Race/Ethnicity by County

## Dataset

* [Dataset URL](https://data.wa.gov/api/views/j5r5-zefd/rows.json?accessType=DOWNLOAD)
* [Catalog URL](https://catalog.data.gov/dataset/2012-age-0-17-youth-population-by-race-ethnicity-by-county)
* Id = j5r5-zefd
* Name = 2012 Age 0-17 Youth Population by Race/Ethnicity by County
* Attribution = Office of Juvenile Justice
* Attribution Link = https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report
* Created = 2015-11-17T04:24:05Z
* Publication Date = 2015-11-17T04:26:44Z
* Rows Updated = 2015-11-17T04:24:21Z

## Description



## Columns

```ls
| Name                  | Field Name          | Data Type | Render Type | Schema Type    | Included | 
| ===================== | =================== | ========= | =========== | ============== | ======== | 
| updated_at            | :updated_at         | meta_data | meta_data   | time           | Yes      | 
| County                | county              | text      | text        | series tag     | Yes      | 
| White (Non-Hispanic)  | white_non_hispanic  | number    | number      | numeric metric | Yes      | 
| Black (Non-Hispanic)  | black_non_hispanic  | number    | number      | numeric metric | Yes      | 
| Indian (Non-Hispanic) | indian_non_hispanic | number    | number      | numeric metric | Yes      | 
| Asian (Non-Hispanic)  | asian_non_hispanic  | number    | number      | numeric metric | Yes      | 
| Hispanic              | hispanic            | number    | number      | numeric metric | Yes      | 
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:j5r5-zefd d:2015-11-16T20:24:12.000Z t:county=Adams m:asian_non_hispanic=37 m:indian_non_hispanic=31 m:black_non_hispanic=46 m:white_non_hispanic=1574 m:hispanic=4932

series e:j5r5-zefd d:2015-11-16T20:24:12.000Z t:county=Asotin m:asian_non_hispanic=52 m:indian_non_hispanic=112 m:black_non_hispanic=75 m:white_non_hispanic=4131 m:hispanic=293

series e:j5r5-zefd d:2015-11-16T20:24:12.000Z t:county=Benton m:asian_non_hispanic=1474 m:indian_non_hispanic=453 m:black_non_hispanic=1110 m:white_non_hispanic=30847 m:hispanic=14429
```

## Meta Commands

```ls
metric m:white_non_hispanic p:integer l:"White (Non-Hispanic)" t:dataTypeName=number

metric m:black_non_hispanic p:integer l:"Black (Non-Hispanic)" t:dataTypeName=number

metric m:indian_non_hispanic p:integer l:"Indian (Non-Hispanic)" t:dataTypeName=number

metric m:asian_non_hispanic p:integer l:"Asian (Non-Hispanic)" t:dataTypeName=number

metric m:hispanic p:integer l:Hispanic t:dataTypeName=number

entity e:j5r5-zefd l:"2012 Age 0-17 Youth Population by Race/Ethnicity by County" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/j5r5-zefd

property e:j5r5-zefd t:meta.view d:2017-03-03T13:50:04.581Z v:id=j5r5-zefd v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=100 v:name="2012 Age 0-17 Youth Population by Race/Ethnicity by County" v:attribution="Office of Juvenile Justice"

property e:j5r5-zefd t:meta.view.license d:2017-03-03T13:50:04.581Z v:name="Public Domain"

property e:j5r5-zefd t:meta.view.owner d:2017-03-03T13:50:04.581Z v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"

property e:j5r5-zefd t:meta.view.tableauthor d:2017-03-03T13:50:04.581Z v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```