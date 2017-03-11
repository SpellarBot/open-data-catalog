# Missouri Deaf and Hard of Hearing Demographics Statistics

## Dataset

* [Dataset URL](https://data.mo.gov/api/views/3vxz-wrn6/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/missouri-deaf-and-hard-of-hearing-demographics-statistics)
* [Metadata URL](https://data.mo.gov/api/views/3vxz-wrn6)
* Id = 3vxz-wrn6
* Name = Missouri Deaf and Hard of Hearing Demographics Statistics
* Category = Education
* Created = 2015-08-06T14:26:54Z
* Publication Date = 2015-09-04T20:13:31Z
* Rows Updated = 2015-09-04T20:11:41Z

## Description



## Columns

```ls
| Name                    | Field Name            | Data Type | Render Type | Schema Type    | Included | 
| ======================= | ===================== | ========= | =========== | ============== | ======== | 
| updated_at              | :updated_at           | meta_data | meta_data   | time           | No       | 
| County                  | county                | text      | text        | series tag     | Yes      | 
| Total Population (2010) | total_population_2010 | number    | number      | numeric metric | Yes      | 
| Est Deaf (1%)           | est_deaf_1            | number    | number      | numeric metric | Yes      | 
| Est HoH (9%)            | est_hoh_9             | number    | number      | numeric metric | Yes      | 
| Est Deaf + HoH (10%)    | est_deaf_hoh_10       | number    | number      | numeric metric | Yes      | 
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
series e:3vxz-wrn6 d:2015-08-06T12:15:52.000Z t:county=Missouri m:est_deaf_hoh_10=598893 m:est_deaf_1=59889 m:total_population_2010=5988927 m:est_hoh_9=539003

series e:3vxz-wrn6 d:2015-08-06T12:15:52.000Z t:county=Adair m:est_deaf_hoh_10=2561 m:est_deaf_1=256 m:total_population_2010=25607 m:est_hoh_9=2305

series e:3vxz-wrn6 d:2015-08-06T12:15:52.000Z t:county=Andrew m:est_deaf_hoh_10=1729 m:est_deaf_1=173 m:total_population_2010=17291 m:est_hoh_9=1556
```

## Meta Commands

```ls
metric m:total_population_2010 p:integer l:"Total Population (2010)" t:dataTypeName=number

metric m:est_deaf_1 p:integer l:"Est Deaf (1%)" t:dataTypeName=number

metric m:est_hoh_9 p:integer l:"Est HoH (9%)" t:dataTypeName=number

metric m:est_deaf_hoh_10 p:integer l:"Est Deaf + HoH (10%)" t:dataTypeName=number

entity e:3vxz-wrn6 l:"Missouri Deaf and Hard of Hearing Demographics Statistics" t:url=https://data.mo.gov/api/views/3vxz-wrn6

property e:3vxz-wrn6 t:meta.view d:2017-03-07T16:38:31.382Z v:id=3vxz-wrn6 v:category=Education v:averageRating=0 v:name="Missouri Deaf and Hard of Hearing Demographics Statistics"

property e:3vxz-wrn6 t:meta.view.owner d:2017-03-07T16:38:31.382Z v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:displayName=Breanna

property e:3vxz-wrn6 t:meta.view.tableauthor d:2017-03-07T16:38:31.382Z v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:displayName=Breanna
```