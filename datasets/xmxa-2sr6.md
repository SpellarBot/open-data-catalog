# Foster Care Placements - Children Served (For Fiscal Years 2006-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/foster-care-placements-children-served-for-fiscal-years-2006-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/xmxa-2sr6) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/xmxa-2sr6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/xmxa-2sr6/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | xmxa-2sr6 |
| Name | Foster Care Placements - Children Served (For Fiscal Years 2006-2013) |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, foster care, youth |
| Created | 2015-12-14T14:59:37Z |
| Publication Date | 2016-01-20T04:44:44Z |

## Columns

```ls
| Included | Schema Type    | Field Name              | Name                      | Data Type | Render Type |
| ======== | ============== | ======================= | ========================= | ========= | =========== |
| Yes      | series tag     | year                    | Year                      | text      | text        |
| Yes      | numeric metric | youth_served_age_0_17   | Youth Served Age 0-17 *   | number    | number      |
| Yes      | numeric metric | white_non_hispanic_only | White (Non-Hispanic) Only | percent   | percent     |
| Yes      | numeric metric | any_minority_total      | Any Minority Total        | percent   | percent     |
```

## Time Field

```ls
Value = 2006
Format & Zone = yyyy
```

## Data Commands

```ls
series e:xmxa-2sr6 d:2006-01-01T00:00:00.000Z t:year="SFY 2012" m:youth_served_age_0_17=8948 m:any_minority_total=55.5 m:white_non_hispanic_only=44.1

series e:xmxa-2sr6 d:2006-01-01T00:00:00.000Z t:year="SFY 2011" m:youth_served_age_0_17=9398 m:any_minority_total=55.6 m:white_non_hispanic_only=43.9

series e:xmxa-2sr6 d:2006-01-01T00:00:00.000Z t:year="SFY 2010" m:youth_served_age_0_17=9795 m:any_minority_total=55.2 m:white_non_hispanic_only=44.3
```

## Meta Commands

```ls
metric m:youth_served_age_0_17 p:integer l:"Youth Served Age 0-17 *" t:dataTypeName=number

metric m:white_non_hispanic_only p:float l:"White (Non-Hispanic) Only" t:dataTypeName=percent

metric m:any_minority_total p:float l:"Any Minority Total" t:dataTypeName=percent

entity e:xmxa-2sr6 l:"Foster Care Placements - Children Served (For Fiscal Years 2006-2013)" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/xmxa-2sr6

property e:xmxa-2sr6 t:meta.view v:id=xmxa-2sr6 v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Foster Care Placements - Children Served (For Fiscal Years 2006-2013)" v:attribution="Office of Juvenile Justice"

property e:xmxa-2sr6 t:meta.view.license v:name="Public Domain"

property e:xmxa-2sr6 t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:xmxa-2sr6 t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| year     | youth_served_age_0_17 | white_non_hispanic_only | any_minority_total | 
| ======== | ===================== | ======================= | ================== | 
| SFY 2012 | 8948                  | 44.1                    | 55.5               | 
| SFY 2011 | 9398                  | 43.9                    | 55.6               | 
| SFY 2010 | 9795                  | 44.3                    | 55.2               | 
| SFY 2009 | 10130                 | 45.3                    | 54.1               | 
| SFY 2008 | 10568                 | 46.5                    | 53.2               | 
| SFY 2007 | 10975                 | 47.9                    | 52.0               | 
| SFY 2006 | 10955                 | 49.0                    | 50.8               | 
```