# Recreation Centers (County in dark green, municipal in light green)

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/recreation-centers-county-in-dark-green-municipal-in-light-green) |
| Metadata | [Link](https://data.montgomerycountymd.gov/api/views/4cfy-a6bg) |
| Data: JSON | [100 Rows](https://data.montgomerycountymd.gov/api/views/4cfy-a6bg/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.montgomerycountymd.gov/api/views/4cfy-a6bg/rows.csv?max_rows=100) |
| Host | data.montgomerycountymd.gov |
| Id | 4cfy-a6bg |
| Name | Recreation Centers (County in dark green, municipal in light green) |
| Attribution | GIS |
| Category | Community/Recreation |
| Tags | recreation, centers |
| Created | 2016-03-15T19:38:32Z |
| Publication Date | 2016-03-15T19:38:57Z |

## Description

https://gis3.montgomerycountymd.gov/arcgis/rest/services/ploi/recreation_ctr/MapServer/0

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | objectid    | OBJECTID   | text      | number      |
| Yes      | series tag  | category    | CATEGORY   | text      | text        |
| Yes      | series tag  | name        | NAME       | text      | text        |
| No       |             | address     | ADDRESS    | text      | text        |
| Yes      | series tag  | city        | CITY       | text      | text        |
| Yes      | series tag  | zipcode     | ZIPCODE    | text      | text        |
| Yes      | series tag  | phone       | PHONE      | text      | text        |
| Yes      | series tag  | url         | URL        | text      | text        |
| Yes      | series tag  | data        | DATA       | text      | text        |
| No       |             | point_x     | POINT_X    | number    | number      |
| No       |             | point_y     | POINT_Y    | number    | number      |
| No       |             | latitude    | LATITUDE   | number    | number      |
| No       |             | longitude   | LONGITUDE  | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = address,point_x,point_y,latitude,longitude
```

## Data Commands

```ls
series e:4cfy-a6bg d:2016-03-15T19:38:32.000Z t:category="RECREATION CENTERS" t:phone=240-777-8077 t:name="Upper County Neighborhood Recreation Center" t:zipcode=20877 t:data=County t:objectid=1 t:url=http://www.montgomerycountymd.gov/rec/where/centers/index.html t:city=Gaithersburg m:row_number.4cfy-a6bg=1

series e:4cfy-a6bg d:2016-03-15T19:38:32.000Z t:category="RECREATION CENTERS" t:phone=240-777-6855 t:name="Jane E Lawton Center" t:zipcode=20815 t:data=County t:objectid=2 t:url=http://www.montgomerycountymd.gov/rec/where/centers/index.html t:city="Chevy Chase" m:row_number.4cfy-a6bg=2

series e:4cfy-a6bg d:2016-03-15T19:38:32.000Z t:category="RECREATION CENTERS" t:phone=240-777-4919 t:name="Plum Gar Neighborhood Recreation Center" t:zipcode=20874 t:data=County t:objectid=3 t:url=http://www.montgomerycountymd.gov/rec/where/centers/index.html t:city=Germantown m:row_number.4cfy-a6bg=3
```

## Meta Commands

```ls
metric m:row_number.4cfy-a6bg p:long l:"Row Number"

entity e:4cfy-a6bg l:"Recreation Centers (County in dark green, municipal in light green)" t:attribution=GIS t:url=https://data.montgomerycountymd.gov/api/views/4cfy-a6bg

property e:4cfy-a6bg t:meta.view v:id=4cfy-a6bg v:category=Community/Recreation v:averageRating=0 v:name="Recreation Centers (County in dark green, municipal in light green)" v:attribution=GIS

property e:4cfy-a6bg t:meta.view.owner v:id=hesx-43k8 v:screenName=Dan v:displayName=Dan

property e:4cfy-a6bg t:meta.view.tableauthor v:id=hesx-43k8 v:screenName=Dan v:roleName=publisher v:displayName=Dan
```

## Top Records

```ls
| :updated_at | objectid | category           | name                                           | address                | city          | zipcode | phone        | url                                                            | data   | point_x                                  | point_y                                   | latitude                                           | longitude                                          | 
| =========== | ======== | ================== | ============================================== | ====================== | ============= | ======= | ============ | ============================================================== | ====== | ======================================== | ========================================= | ================================================== | ================================================== | 
| 0           | 1        | RECREATION CENTERS | Upper County Neighborhood Recreation Center    | 8201 Emory Grove Rd    | Gaithersburg  | 20877   | 240-777-8077 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1264921.2499270099215209484100341796875  | 540234.6251134700141847133636474609375    | 39.1499332599999974036109051667153835296630859375  | -77.1671824799999939159533823840320110321044921875 | 
| 0           | 2        | RECREATION CENTERS | Jane E Lawton Center                           | 4301 Willow La         | Chevy Chase   | 20815   | 240-777-6855 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1287265.62498781993053853511810302734375 | 479218.4061766400118358433246612548828125 | 38.98248948999999896614099270664155483245849609375 | -77.0881849400000049854497774504125118255615234375 | 
| 0           | 3        | RECREATION CENTERS | Plum Gar Neighborhood Recreation Center        | 19561 Scenery Dr       | Germantown    | 20874   | 240-777-4919 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1246041.00005342997610569000244140625    | 549768.687458349973894655704498291015625  | 39.17599600999999864825440454296767711639404296875 | -77.233843070000006036934792064130306243896484375  | 
| 0           | 4        | RECREATION CENTERS | Clara Barton Recreation Center                 | 7425 Mac Arthur Blv    | Cabin John    | 20818   | 240-777-4910 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1268914.12493872991763055324554443359375 | 475880.7188775400281883776187896728515625 | 38.9732586800000007087874109856784343719482421875  | -77.1527233700000039107180782593786716461181640625 | 
| 0           | 5        | RECREATION CENTERS | Good Hope Neighborhood Rec Center (RENOVATION) | 14715 Good Hope Rd     | Silver Spring | 20905   | 240-777-8055 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1316495.4999590399675071239471435546875  | 520749.8437833199859596788883209228515625 | 39.09655369000000035839548218064010143280029296875 | -76.9853346000000016147168935276567935943603515625 | 
| 0           | 6        | RECREATION CENTERS | Gwendolyn E Coffield Recreation Center         | 2450 Lyttonsville Rd   | Silver Spring | 20910   | 240-777-4900 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1297852.25002168002538383007049560546875 | 485147.531302170013077557086944580078125  | 38.998791269999998121420503593981266021728515625   | -77.0509542300000020986772142350673675537109375    | 
| 0           | 7        | RECREATION CENTERS | Scotland Neighborhood Recreation Center        | 7700 Scotland Dr       | Potomac       | 20854   | 240-777-8075 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1267243.8749531800858676433563232421875  | 497027.906353230006061494350433349609375  | 39.03131456999999926438249531202018260955810546875 | -77.15872765000000299551174975931644439697265625   | 
| 0           | 8        | RECREATION CENTERS | Germantown Recreation Center                   | 18905 Kingsview Rd     | Germantown    | 20874   | 240-777-8095 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1231505.24989589001052081584930419921875 | 546009.875038850004784762859344482421875  | 39.16556246999999757463228888809680938720703125    | -77.285075530000000298969098366796970367431640625  | 
| 0           | 9        | RECREATION CENTERS | Marilyn J Praisner Community Recreation Center | 14906 Old Columbia Pik | Burtonsville  | 20866   | 240-777-4970 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1328902.5000346000306308269500732421875  | 522587.1562970299855805933475494384765625 | 39.10158464999999949895936879329383373260498046875 | -76.9416142900000039617225411348044872283935546875 | 
| 0           | 10       | RECREATION CENTERS | Bauer Drive Recreation Center                  | 14625 Bauer Dr         | Rockville     | 20853   | 240-777-6922 | http://www.montgomerycountymd.gov/rec/where/centers/index.html | County | 1281527.25007047993130981922149658203125 | 519924.06253454997204244136810302734375   | 39.09423702000000133693902171216905117034912109375 | -77.108542029999995293110259808599948883056640625  | 
```