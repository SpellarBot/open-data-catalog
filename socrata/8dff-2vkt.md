# Recreation Centers

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recreation-centers-1257a) |
| Metadata | [Link](https://data.austintexas.gov/api/views/8dff-2vkt) |
| Data: JSON | [100 Rows](https://data.austintexas.gov/api/views/8dff-2vkt/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.austintexas.gov/api/views/8dff-2vkt/rows.csv?max_rows=100) |
| Host | data.austintexas.gov |
| Id | 8dff-2vkt |
| Name | Recreation Centers |
| Attribution | City of Austin |
| Category | Government |
| Tags | recreation center |
| Created | 2016-05-11T15:48:55Z |
| Publication Date | 2016-05-11T15:50:49Z |

## Columns

```ls
| Included | Schema Type | Field Name         | Name               | Data Type | Render Type |
| ======== | =========== | ================== | ================== | ========= | =========== |
| No       | time        | :updated_at        | updated_at         | meta_data | meta_data   |
| Yes      | series tag  | recreation_centers | Recreation Centers | text      | text        |
| Yes      | series tag  | zip_code           | Zip Code           | text      | text        |
| Yes      | series tag  | phone_number       | Phone Number       | text      | text        |
| Yes      | series tag  | website            | Website            | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:8dff-2vkt d:2016-05-11T08:49:09.000Z t:phone_number="(512) 453-7765" t:zip_code=78751 t:website=http://www.austintexas.gov/department/hancock-recreation-center t:recreation_centers="Hancock Recreation Center" m:row_number.8dff-2vkt=1

series e:8dff-2vkt d:2016-05-11T08:49:09.000Z t:phone_number="(512) 974-6972" t:zip_code=78757 t:website=http://www.austintexas.gov/department/northwest-recreation-center t:recreation_centers="Northwest Recreation Center" m:row_number.8dff-2vkt=2

series e:8dff-2vkt d:2016-05-11T08:49:09.000Z t:phone_number="(512) 926-3491" t:zip_code=78723 t:website=http://www.austintexas.gov/department/dottie-jordan-recreation-center t:recreation_centers="Dottie Jordan Recreation Center" m:row_number.8dff-2vkt=3
```

## Meta Commands

```ls
metric m:row_number.8dff-2vkt p:long l:"Row Number"

entity e:8dff-2vkt l:"Recreation Centers" t:attribution="City of Austin" t:url=https://data.austintexas.gov/api/views/8dff-2vkt

property e:8dff-2vkt t:meta.view v:id=8dff-2vkt v:category=Government v:attributionLink=http://www.austintexas.gov/recreation v:averageRating=0 v:name="Recreation Centers" v:attribution="City of Austin"

property e:8dff-2vkt t:meta.view.license v:name="Public Domain"

property e:8dff-2vkt t:meta.view.owner v:id=wpqw-45f6 v:screenName=Betty v:displayName=Betty

property e:8dff-2vkt t:meta.view.tableauthor v:id=wpqw-45f6 v:screenName=Betty v:roleName=editor v:displayName=Betty
```

## Top Records

```ls
| :updated_at | recreation_centers                | zip_code | phone_number   | website                                                                 | 
| =========== | ================================= | ======== | ============== | ======================================================================= | 
| 1462956549  | Hancock Recreation Center         | 78751    | (512) 453-7765 | http://www.austintexas.gov/department/hancock-recreation-center         | 
| 1462956549  | Northwest Recreation Center       | 78757    | (512) 974-6972 | http://www.austintexas.gov/department/northwest-recreation-center       | 
| 1462956549  | Dottie Jordan Recreation Center   | 78723    | (512) 926-3491 | http://www.austintexas.gov/department/dottie-jordan-recreation-center   | 
| 1462956549  | Metz Recreation Center            | 78702    | (512) 478-8716 | http://www.austintexas.gov/department/metz-recreation-center            | 
| 1462956549  | Delores Duffie Recreation Center  | 78702    | (512) 472-6838 | http://www.austintexas.gov/department/rosewood-recreation-center        | 
| 1462956549  | Dittmar Recreation Center         | 78745    | (512) 974-6090 | http://www.austintexas.gov/Dittmar                                      | 
| 1462956549  | Pickfair Community Center         | 78750    | (512) 401-8119 | http://www.austintexas.gov/department/pickfair-community-center         | 
| 1462956549  | Alamo Recreation                  | 78722    | (512) 974-5680 | http://www.austintexas.gov/department/alamo-recreation-center           | 
| 1462956549  | Austin Recreation Center          | 78701    | (512) 476-5662 | http://www.austintexas.gov/AustinRec                                    | 
| 1462956549  | Parque Zaragoza Recreation Center | 78702    | (512) 472-7142 | http://www.austintexas.gov/department/parque-zaragoza-recreation-center | 
```