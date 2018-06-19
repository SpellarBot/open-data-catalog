# Admissions to Juvenile Detention Related to a Status Offense

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/admissions-to-juvenile-detention-related-to-a-status-offense) |
| Metadata | [Link](https://data.wa.gov/api/views/qsd2-yxis) |
| Data: JSON | [100 Rows](https://data.wa.gov/api/views/qsd2-yxis/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.wa.gov/api/views/qsd2-yxis/rows.csv?max_rows=100) |
| Host | data.wa.gov |
| Id | qsd2-yxis |
| Name | Admissions to Juvenile Detention Related to a Status Offense |
| Attribution | Office of Juvenile Justice |
| Category | Public Safety |
| Tags | juvenile justice, annual report, wa-pcjj report, office of juvenile justice, dshs, detention, status offense, youth |
| Created | 2015-12-27T06:10:09Z |
| Publication Date | 2016-01-12T20:04:27Z |

## Columns

```ls
| Included | Schema Type    | Field Name                                             | Name                                                   | Data Type | Render Type |
| ======== | ============== | ====================================================== | ====================================================== | ========= | =========== |
| No       | time           | :updated_at                                            | updated_at                                             | meta_data | meta_data   |
| Yes      | series tag     | facility                                               | Facility                                               | text      | text        |
| Yes      | numeric metric | any_status_offenders_total_2009                        | Any Status Offenders Total* 2009                       | number    | number      |
| Yes      | numeric metric | any_status_offenders_total_2010                        | Any Status Offenders Total* 2010                       | number    | number      |
| Yes      | numeric metric | any_status_offenders_total_2011                        | Any Status Offenders Total* 2011                       | number    | number      |
| Yes      | numeric metric | any_status_offenders_total_2012                        | Any Status Offenders Total* 2012                       | number    | number      |
| Yes      | numeric metric | any_status_offenders_total_2013                        | Any Status Offenders Total* 2013                       | number    | number      |
| Yes      | numeric metric | percent_of_total_holds_that_were_status_offenders_2009 | Percent of Total Holds That Were Status Offenders 2009 | number    | number      |
| Yes      | numeric metric | percent_of_total_holds_that_were_status_offenders_2010 | Percent of Total Holds That Were Status Offenders 2010 | number    | number      |
| Yes      | numeric metric | percent_of_total_holds_that_were_status_offenders_2011 | Percent of Total Holds That Were Status Offenders 2011 | number    | number      |
| Yes      | numeric metric | percent_of_total_holds_that_were_status_offenders_2012 | Percent of Total Holds That Were Status Offenders 2012 | number    | number      |
| Yes      | numeric metric | percent_of_total_holds_that_were_status_offenders_2013 | Percent of Total Holds That Were Status Offenders 2013 | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:qsd2-yxis d:2015-12-26T22:10:13.000Z t:facility=Benton/Franklin m:any_status_offenders_total_2013=154 m:any_status_offenders_total_2012=119 m:any_status_offenders_total_2011=129 m:percent_of_total_holds_that_were_status_offenders_2013=12.3 m:percent_of_total_holds_that_were_status_offenders_2009=2.9 m:percent_of_total_holds_that_were_status_offenders_2011=8.7 m:percent_of_total_holds_that_were_status_offenders_2012=8.7 m:any_status_offenders_total_2009=43 m:percent_of_total_holds_that_were_status_offenders_2010=7.7 m:any_status_offenders_total_2010=111

series e:qsd2-yxis d:2015-12-26T22:10:13.000Z t:facility=Chelan m:any_status_offenders_total_2013=58 m:any_status_offenders_total_2012=52 m:any_status_offenders_total_2011=40 m:percent_of_total_holds_that_were_status_offenders_2013=12.1 m:percent_of_total_holds_that_were_status_offenders_2009=6 m:percent_of_total_holds_that_were_status_offenders_2011=7.8 m:percent_of_total_holds_that_were_status_offenders_2012=7.8 m:any_status_offenders_total_2009=38 m:percent_of_total_holds_that_were_status_offenders_2010=11.4 m:any_status_offenders_total_2010=62

series e:qsd2-yxis d:2015-12-26T22:10:13.000Z t:facility=Clallam m:any_status_offenders_total_2013=132 m:any_status_offenders_total_2012=161 m:any_status_offenders_total_2011=144 m:percent_of_total_holds_that_were_status_offenders_2013=21 m:percent_of_total_holds_that_were_status_offenders_2009=18.9 m:percent_of_total_holds_that_were_status_offenders_2011=20.5 m:percent_of_total_holds_that_were_status_offenders_2012=20.5 m:any_status_offenders_total_2009=117 m:percent_of_total_holds_that_were_status_offenders_2010=26.4 m:any_status_offenders_total_2010=173
```

## Meta Commands

```ls
metric m:any_status_offenders_total_2009 p:integer l:"Any Status Offenders Total* 2009" t:dataTypeName=number

metric m:any_status_offenders_total_2010 p:integer l:"Any Status Offenders Total* 2010" t:dataTypeName=number

metric m:any_status_offenders_total_2011 p:integer l:"Any Status Offenders Total* 2011" t:dataTypeName=number

metric m:any_status_offenders_total_2012 p:integer l:"Any Status Offenders Total* 2012" t:dataTypeName=number

metric m:any_status_offenders_total_2013 p:integer l:"Any Status Offenders Total* 2013" t:dataTypeName=number

metric m:percent_of_total_holds_that_were_status_offenders_2009 p:float l:"Percent of Total Holds That Were Status Offenders 2009" t:dataTypeName=number

metric m:percent_of_total_holds_that_were_status_offenders_2010 p:float l:"Percent of Total Holds That Were Status Offenders 2010" t:dataTypeName=number

metric m:percent_of_total_holds_that_were_status_offenders_2011 p:float l:"Percent of Total Holds That Were Status Offenders 2011" t:dataTypeName=number

metric m:percent_of_total_holds_that_were_status_offenders_2012 p:float l:"Percent of Total Holds That Were Status Offenders 2012" t:dataTypeName=number

metric m:percent_of_total_holds_that_were_status_offenders_2013 p:float l:"Percent of Total Holds That Were Status Offenders 2013" t:dataTypeName=number

entity e:qsd2-yxis l:"Admissions to Juvenile Detention Related to a Status Offense" t:attribution="Office of Juvenile Justice" t:url=https://data.wa.gov/api/views/qsd2-yxis

property e:qsd2-yxis t:meta.view v:id=qsd2-yxis v:category="Public Safety" v:attributionLink=https://dshs.wa.gov/ra/office-juvenile-justice/washington-state-juvenile-justice-annual-report v:averageRating=0 v:name="Admissions to Juvenile Detention Related to a Status Offense" v:attribution="Office of Juvenile Justice"

property e:qsd2-yxis t:meta.view.owner v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:displayName="Alysa Kipersztok"

property e:qsd2-yxis t:meta.view.tableauthor v:id=6p7r-jviv v:profileImageUrlMedium=/api/users/6p7r-jviv/profile_images/THUMB v:profileImageUrlLarge=/api/users/6p7r-jviv/profile_images/LARGE v:screenName="Alysa Kipersztok" v:profileImageUrlSmall=/api/users/6p7r-jviv/profile_images/TINY v:roleName=viewer v:displayName="Alysa Kipersztok"
```

## Top Records

```ls
| :updated_at | facility        | any_status_offenders_total_2009 | any_status_offenders_total_2010 | any_status_offenders_total_2011 | any_status_offenders_total_2012 | any_status_offenders_total_2013 | percent_of_total_holds_that_were_status_offenders_2009 | percent_of_total_holds_that_were_status_offenders_2010 | percent_of_total_holds_that_were_status_offenders_2011 | percent_of_total_holds_that_were_status_offenders_2012 | percent_of_total_holds_that_were_status_offenders_2013 | 
| =========== | =============== | =============================== | =============================== | =============================== | =============================== | =============================== | ====================================================== | ====================================================== | ====================================================== | ====================================================== | ====================================================== | 
| 1451167813  | Benton/Franklin | 43                              | 111                             | 129                             | 119                             | 154                             | 2.9                                                    | 7.7                                                    | 8.7                                                    | 8.7                                                    | 12.3                                                   | 
| 1451167813  | Chelan          | 38                              | 62                              | 40                              | 52                              | 58                              | 6.0                                                    | 11.4                                                   | 7.8                                                    | 7.8                                                    | 12.1                                                   | 
| 1451167813  | Clallam         | 117                             | 173                             | 144                             | 161                             | 132                             | 18.9                                                   | 26.4                                                   | 20.5                                                   | 20.5                                                   | 21.0                                                   | 
| 1451167813  | Clark           | 6                               | 8                               | 9                               | 8                               | 3                               | 0.3                                                    | 0.4                                                    | 0.5                                                    | 0.5                                                    | 0.2                                                    | 
| 1451167813  | Cowlitz         | 45                              | 51                              | 104                             | 229                             | 246                             | 4.6                                                    | 5.5                                                    | 11.1                                                   | 11.1                                                   | 27.4                                                   | 
| 1451167813  | Grant           | 104                             | 132                             | 83                              | 57                              | 66                              | 17.5                                                   | 21.5                                                   | 15.0                                                   | 15.0                                                   | 16.4                                                   | 
| 1451167813  | Grays Harbor    | 461                             | 520                             | 501                             | 567                             | 559                             | 58.2                                                   | 67.9                                                   | 64.8                                                   | 64.8                                                   | 76.3                                                   | 
| 1451167813  | Island          | 37                              | 19                              | 27                              | 37                              | 37                              | 13.3                                                   | 6.5                                                    | 13.2                                                   | 13.2                                                   | 20.8                                                   | 
| 1451167813  | King            | 186                             | 221                             | 210                             | 179                             | 200                             | 5.7                                                    | 7.4                                                    | 8.8                                                    | 8.8                                                    | 9.4                                                    | 
| 1451167813  | Kitsap          | 64                              | 66                              | 44                              | 41                              | 30                              | 4.3                                                    | 4.8                                                    | 3.5                                                    | 3.5                                                    | 3.2                                                    | 
```