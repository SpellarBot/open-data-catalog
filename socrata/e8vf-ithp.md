# Juvenile Rehabilitation Client Population (2004-2013)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/juvenile-rehabilitation-client-population-2004-2013) |
| Metadata | [Link](https://data.wa.gov/api/views/e8vf-ithp) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/e8vf-ithp/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/e8vf-ithp/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | e8vf-ithp |
| Name | Juvenile Rehabilitation Client Population (2004-2013) |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, rehabilitation, youth |
| Created | 2015-12-29T07:51:25Z |
| Publication Date | 2016-01-12T19:50:42Z |

## Columns

```ls
| Included | Schema Type    | Field Name                | Name                      | Data Type | Render Type |
| ======== | ============== | ========================= | ========================= | ========= | =========== |
| Yes      | time           | year                      | Year                      | text      | text        |
| Yes      | numeric metric | percent_non_white         | Percent Non-White         | number    | number      |
| Yes      | numeric metric | percent_female            | Percent Female            | number    | number      |
| Yes      | numeric metric | percent_violent_offenders | Percent Violent Offenders | number    | number      |
| Yes      | numeric metric | percent_sex_offenders     | Percent Sex Offenders     | number    | number      |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:e8vf-ithp d:2013-01-01T00:00:00.000Z m:percent_violent_offenders=54.3 m:percent_sex_offenders=18.5 m:percent_non_white=58.5 m:percent_female=9.5

series e:e8vf-ithp d:2012-01-01T00:00:00.000Z m:percent_violent_offenders=51.4 m:percent_sex_offenders=16.7 m:percent_non_white=57.6 m:percent_female=9.2

series e:e8vf-ithp d:2011-01-01T00:00:00.000Z m:percent_violent_offenders=58.6 m:percent_sex_offenders=18.8 m:percent_non_white=56.8 m:percent_female=8.6
```

## Meta Commands

```ls
metric m:percent_non_white p:float l:"Percent Non-White" t:dataTypeName=number

metric m:percent_female p:float l:"Percent Female" t:dataTypeName=number

metric m:percent_violent_offenders p:float l:"Percent Violent Offenders" t:dataTypeName=number

metric m:percent_sex_offenders p:float l:"Percent Sex Offenders" t:dataTypeName=number

entity e:e8vf-ithp l:"Juvenile Rehabilitation Client Population (2004-2013)" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/e8vf-ithp

property e:e8vf-ithp t:meta.view v:id=e8vf-ithp v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Juvenile Rehabilitation Client Population (2004-2013)" v:attribution="Office of Juvenile Justice"

property e:e8vf-ithp t:meta.view.license v:name="Public Domain"

property e:e8vf-ithp t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:e8vf-ithp t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| year   | percent_non_white | percent_female | percent_violent_offenders | percent_sex_offenders | 
| ====== | ================= | ============== | ========================= | ===================== | 
| 2013   | 58.5              | 9.5            | 54.3                      | 18.5                  | 
| 2012   | 57.6              | 9.2            | 51.4                      | 16.7                  | 
| 2011   | 56.8              | 8.6            | 58.6                      | 18.8                  | 
| 2010   | 54.7              | 7.9            | 58.1                      | 16.4                  | 
| 2009   | 50.8              | 7.2            | 53.1                      | 15.9                  | 
| 2008   | 49.0              | 9.0            | 51.6                      | 15.7                  | 
| 2007** | 49.1              | 10.3           | 47.9                      | 16.9                  | 
| 2006   | 47.1              | 10.3           | 44.9                      | 20.9                  | 
| 2005   | 45.7              | 9.7            | 51.7                      | 22.4                  | 
| 2004   | 44.5              | 7.9            | 48.3                      | 22.3                  | 
```