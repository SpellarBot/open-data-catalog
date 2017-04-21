# Slideshow Content

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/slideshow-content-1e54a) |
| Metadata | [Link](https://data.hawaii.gov/api/views/7dae-bjqc) |
| Data: JSON | [100 Rows](https://data.hawaii.gov/api/views/7dae-bjqc/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.hawaii.gov/api/views/7dae-bjqc/rows.csv?max_rows=100) |
| Host | data.hawaii.gov |
| Id | 7dae-bjqc |
| Name | Slideshow Content |
| Created | 2012-10-04T20:40:33Z |
| Publication Date | 2012-10-04T20:45:02Z |

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | title       | Title      | text      | text        |
| Yes      | series tag  | text        | Text       | text      | text        |
| Yes      | series tag  | image       | Image      | photo     | photo       |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:7dae-bjqc d:2012-10-04T13:44:06.000Z t:title="Welcome to data.hawaii.gov" t:image=iAkEqFOT5R3ItgBb8TdzpWDHBWIZWbVz5GsZunjosuo m:row_number.7dae-bjqc=1

series e:7dae-bjqc d:2012-10-04T13:44:28.000Z t:text="Leading public sector innovators are leveraging cloud, platform and social technologies to deliver better citizen access to information, modernize online service delivery and improve internal efficiencies. We call the transformation of your data assets into productive information resources that people can easily access, share and reuse, Open Data. By sharing our data via data.hawaii.gov in an open and transparent means we empower our citizens, ourselves and our customers to access information anywhere, anytime. Data.hawaii.gov provides a platform to promote our data to a common statewide location that is accessible to everyone." t:title="Data for Hawaii" t:image=2xcP_pVgdVAdWEjTHsIBWpiLLBEwf0rdIAWY3qYoHng m:row_number.7dae-bjqc=2

series e:7dae-bjqc d:2012-10-04T13:44:46.000Z t:title="Data sharing" t:image=PkJu3kSh-Sgr8XGiS9_B1ZnldAyePzJqrlXh5AaB5jg m:row_number.7dae-bjqc=3
```

## Meta Commands

```ls
metric m:row_number.7dae-bjqc p:long l:"Row Number"

entity e:7dae-bjqc l:"Slideshow Content" t:url=https://data.hawaii.gov/api/views/7dae-bjqc

property e:7dae-bjqc t:meta.view v:id=7dae-bjqc v:averageRating=0 v:name="Slideshow Content"

property e:7dae-bjqc t:meta.view.owner v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"

property e:7dae-bjqc t:meta.view.tableauthor v:id=zs8p-j3v5 v:profileImageUrlMedium=/api/users/zs8p-j3v5/profile_images/THUMB v:profileImageUrlLarge=/api/users/zs8p-j3v5/profile_images/LARGE v:screenName="Darrell Cabales" v:profileImageUrlSmall=/api/users/zs8p-j3v5/profile_images/TINY v:displayName="Darrell Cabales"
```

## Top Records

```ls
| :updated_at | title                      | text                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | image                                       | 
| =========== | ========================== | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | =========================================== | 
| 1349358246  | Welcome to data.hawaii.gov |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | iAkEqFOT5R3ItgBb8TdzpWDHBWIZWbVz5GsZunjosuo | 
| 1349358268  | Data for Hawaii            | Leading public sector innovators are leveraging cloud, platform and social technologies to deliver better citizen access to information, modernize online service delivery and improve internal efficiencies. We call the transformation of your data assets into productive information resources that people can easily access, share and reuse, Open Data. By sharing our data via data.hawaii.gov in an open and transparent means we empower our citizens, ourselves and our customers to access information anywhere, anytime. Data.hawaii.gov provides a platform to promote our data to a common statewide location that is accessible to everyone. | 2xcP_pVgdVAdWEjTHsIBWpiLLBEwf0rdIAWY3qYoHng | 
| 1349358286  | Data sharing               |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | PkJu3kSh-Sgr8XGiS9_B1ZnldAyePzJqrlXh5AaB5jg | 
```