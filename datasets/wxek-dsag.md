# High School Dropout Statistics by County 2012-2013 School Year 5-Year Cohort Dropout Rates

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/high-school-dropout-statistics-by-county-2012-2013-school-year-5-year-cohort-dropout-rates) |
| Metadata | [Link](https://data.wa.gov/api/views/wxek-dsag) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/wxek-dsag/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/wxek-dsag/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | wxek-dsag |
| Name | High School Dropout Statistics by County 2012-2013 School Year 5-Year Cohort Dropout Rates |
| Attribution | Office of Juvenile Justice |
| Category | Education |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, dropout, youth |
| Created | 2015-12-01T04:46:30Z |
| Publication Date | 2015-12-01T04:48:18Z |

## Columns

```ls
| Included | Schema Type    | Field Name               | Name                     | Data Type | Render Type |
| ======== | ============== | ======================== | ======================== | ========= | =========== |
| Yes      | series tag     | county                   | County                   | text      | text        |
| Yes      | numeric metric | 2012_2013_total_dropouts | 2012-2013 Total Dropouts | number    | number      |
| Yes      | series tag     | rank_by_number           | Rank by Number           | text      | number      |
| Yes      | numeric metric | cohort_dropout_rate      | Cohort Dropout Rate      | number    | number      |
| Yes      | numeric metric | rank_by_percent          | Rank by Percent          | number    | number      |
```

## Time Field

```ls
Value = 2012
Format & Zone = yyyy
```

## Data Commands

```ls
series e:wxek-dsag d:2012-01-01T00:00:00.000Z t:county=Adams t:rank_by_number=30 m:rank_by_percent=16 m:2012_2013_total_dropouts=55 m:cohort_dropout_rate=19.57

series e:wxek-dsag d:2012-01-01T00:00:00.000Z t:county=Asotin t:rank_by_number=28 m:rank_by_percent=9 m:2012_2013_total_dropouts=70 m:cohort_dropout_rate=23.65

series e:wxek-dsag d:2012-01-01T00:00:00.000Z t:county=Benton t:rank_by_number=10 m:rank_by_percent=27 m:2012_2013_total_dropouts=371 m:cohort_dropout_rate=14.61
```

## Meta Commands

```ls
metric m:2012_2013_total_dropouts p:integer l:"2012-2013 Total Dropouts" t:dataTypeName=number

metric m:cohort_dropout_rate p:float l:"Cohort Dropout Rate" t:dataTypeName=number

metric m:rank_by_percent p:integer l:"Rank by Percent" t:dataTypeName=number

entity e:wxek-dsag l:"High School Dropout Statistics by County 2012-2013 School Year 5-Year Cohort Dropout Rates" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/wxek-dsag

property e:wxek-dsag t:meta.view v:id=wxek-dsag v:category=Education v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="High School Dropout Statistics by County 2012-2013 School Year 5-Year Cohort Dropout Rates" v:attribution="Office of Juvenile Justice"

property e:wxek-dsag t:meta.view.license v:name="Public Domain"

property e:wxek-dsag t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:wxek-dsag t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| county   | 2012_2013_total_dropouts | rank_by_number | cohort_dropout_rate | rank_by_percent | 
| ======== | ======================== | ============== | =================== | =============== | 
| Adams    | 55                       | 30             | 19.57               | 16              | 
| Asotin   | 70                       | 28             | 23.65               | 9               | 
| Benton   | 371                      | 10             | 14.61               | 27              | 
| Chelan   | 231                      | 18             | 21.59               | 14              | 
| Clallam  | 971                      | 4              | 51.05               | 2               | 
| Clark    | 876                      | 6              | 15.09               | 25              | 
| Columbia | 6                        | 36             | 16.22               | 23              | 
| Cowlitz  | 239                      | 17             | 17.63               | 19              | 
| Douglas  | 66                       | 29             | 13.02               | 31              | 
| Ferry    | 6                        | 37             | 9.23                | 36              | 
```