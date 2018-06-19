# On-street Parking Supply

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/on-street-parking-supply) |
| Metadata | [Link](https://data.sfgov.org/api/views/4gn7-eg5z) |
| Data: JSON | [100 Rows](https://data.sfgov.org/api/views/4gn7-eg5z/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.sfgov.org/api/views/4gn7-eg5z/rows.csv?max_rows=100) |
| Host | data.sfgov.org |
| Id | 4gn7-eg5z |
| Name | On-street Parking Supply |
| Category | Transportation |
| Tags | on-street parking |
| Created | 2016-04-14T23:35:56Z |
| Publication Date | 2016-04-20T22:19:13Z |

## Description

Provides on-street parking supply per street segment for various policy, planning and operations purposes. Counts collected via field surveys from 2008-2014 assuming 17 feet per undemarcated parking space, with a few exceptions. Geoprocessing methodology involved a series of spatial joins between side of street points and each street segment. Full parking census methodology can be found at http://sfpark.org/resources/parking-census-data-context-and-map-april-2014/ This dataset is updated infrequently on a schedule TBD. Other critical information: users should filter out segments with the value '5555' when aggregating parking census counts. This code is applied to some divided streets where the full parking census count for that street block was aggregated to one side of the divided street.

## Columns

```ls
| Included | Schema Type    | Field Name          | Name                | Data Type | Render Type |
| ======== | ============== | =================== | =================== | ========= | =========== |
| Yes      | series tag     | object_id           | Object ID           | text      | number      |
| Yes      | series tag     | cnn_id              | CNN ID              | text      | number      |
| Yes      | series tag     | street_name         | Street Name         | text      | text        |
| Yes      | series tag     | street_type         | Street Type         | text      | text        |
| Yes      | series tag     | supervisor_district | Supervisor District | text      | text        |
| Yes      | series tag     | layer_input         | Layer Input         | text      | text        |
| Yes      | series tag     | collection_method   | Collection Method   | text      | text        |
| Yes      | numeric metric | parking_supply      | Parking Supply      | number    | number      |
| No       |                | year                | Year                | number    | number      |
| Yes      | time           | last_edited_date    | Last Edited Date    | date      | date        |
| No       |                | geom                | Geom                | line      | line        |
```

## Time Field

```ls
Value = last_edited_date
Format & Zone = seconds
```

## Series Fields

```ls
Excluded Fields = geom,year
```

## Data Commands

```ls
series e:4gn7-eg5z d:2017-02-11T17:48:37.000Z t:layer_input=STREETS t:street_name=19TH t:object_id=1 t:cnn_id=924103 t:collection_method=FIELD t:supervisor_district=07 t:street_type=AVE m:parking_supply=34

series e:4gn7-eg5z d:2017-02-11T17:48:37.000Z t:layer_input=STREETS t:street_name=19TH t:object_id=2 t:cnn_id=924102 t:collection_method=FIELD t:supervisor_district=07 t:street_type=AVE m:parking_supply=5555

series e:4gn7-eg5z d:2017-02-11T17:48:37.000Z t:layer_input=STREETS t:street_name=CRANLEIGH t:object_id=3 t:cnn_id=4480000 t:collection_method=FIELD t:supervisor_district=07 t:street_type=DR m:parking_supply=39
```

## Meta Commands

```ls
metric m:parking_supply p:long l:"Parking Supply" t:dataTypeName=number

entity e:4gn7-eg5z l:"On-street Parking Supply" t:url=https://data.sfgov.org/api/views/4gn7-eg5z

property e:4gn7-eg5z t:meta.view v:id=4gn7-eg5z v:category=Transportation v:averageRating=0 v:name="On-street Parking Supply"

property e:4gn7-eg5z t:meta.view.license v:name="Open Data Commons Public Domain Dedication and License" v:termsLink=http://opendatacommons.org/licenses/pddl/1.0/

property e:4gn7-eg5z t:meta.view.owner v:id=dbag-6qd9 v:screenName=OpenData v:displayName=OpenData

property e:4gn7-eg5z t:meta.view.tableauthor v:id=dbag-6qd9 v:screenName=OpenData v:roleName=publisher v:displayName=OpenData
```

## Top Records

```ls
| object_id | cnn_id  | street_name | street_type | supervisor_district | layer_input | collection_method | parking_supply | year | last_edited_date | geom                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | 
| ========= | ======= | =========== | =========== | =================== | =========== | ================= | ============== | ==== | ================ | =========================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================================== | 
| 1         | 924103  | 19TH        | AVE         | 07                  | STREETS     | FIELD             | 34             | 2013 |                  | LINESTRING (-122.47513878780431 37.736017698865815, -122.47506084974584 37.734774506673745, -122.47511569008223 37.73463050912852)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 2         | 924102  | 19TH        | AVE         | 07                  | STREETS     | FIELD             | 5555           | 2010 |                  | LINESTRING (-122.47530177405834 37.73745967963975, -122.47522386091313 37.73737462862807, -122.47513878780431 37.736017698865815)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | 
| 3         | 4480000 | CRANLEIGH   | DR          | 07                  | STREETS     | FIELD             | 39             | 2012 |                  | LINESTRING (-122.47235489023741 37.734611108744666, -122.47232137598674 37.7340363101225, -122.47239519082177 37.73383825926831, -122.47263302380858 37.73375305374514, -122.47318674836835 37.73372728077432)                                                                                                                                                                                                                                                                                                                                                                                                                                              | 
| 4         | 629000  | 15TH        | AVE         | 07                  | STREETS     | FIELD             | 44             | 2012 |                  | LINESTRING (-122.47123915866375 37.741388044521145, -122.47110748941058 37.739520086703855)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | 
| 5         | 7553000 | JOHN MUIR   | DR          | 07                  | STREETS     | FIELD             | 376            | 2012 |                  | LINESTRING (-122.48573708286848 37.70809066287842, -122.48627463774604 37.70834042851208, -122.48736404998073 37.70892411606335, -122.487816910418 37.70942476560953, -122.48891707580081 37.71169076025599, -122.48930988774258 37.71206902307071, -122.49058185736034 37.71288485389834, -122.49126731876699 37.713393217009404, -122.4920918283094 37.71448748462141, -122.49297705293228 37.715245713627276, -122.49407553656751 37.71574071181722, -122.49741364557028 37.71673688772091, -122.49841408223958 37.717164397919156, -122.49933554399111 37.71800887785909, -122.49986292078295 37.71878354916231, -122.50023417483814 37.71896049246241) | 
| 6         | 4919000 | DORADO      | TER         | 07                  | STREETS     | FIELD             | 7              | 2012 |                  | LINESTRING (-122.46179927533264 37.726331273386016, -122.46181647557324 37.72682496101766)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 7         | 4915000 | DORADO      | TER         | 07                  | STREETS     | FIELD             | 7              | 2012 |                  | LINESTRING (-122.46073668532738 37.727027053034064, -122.46093235887754 37.7270517344133, -122.4613963554477 37.72683838127554, -122.46181647557324 37.72682496101766)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 
| 8         | 4914000 | DORADO      | TER         | 07                  | STREETS     | FIELD             | 8              | 2012 |                  | LINESTRING (-122.46037771288624 37.72698177300738, -122.46073668532738 37.727027053034064)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | 
| 9         | 6029000 | GATEVIEW    | CT          | 07                  | STREETS     | FIELD             | 3              | 2012 |                  | LINESTRING (-122.46679920080707 37.748382470904666, -122.46676925261453 37.74831780542766, -122.46675702674813 37.748133057942745)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | 
| 10        | 8974000 | MENDOSA     | AVE         | 07                  | STREETS     | FIELD             | 4              | 2012 |                  | LINESTRING (-122.46747401382905 37.74807796910848, -122.4675809647806 37.7482593325272, -122.46758306972141 37.748338776058034, -122.46752227656026 37.74843403643588)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | 
```