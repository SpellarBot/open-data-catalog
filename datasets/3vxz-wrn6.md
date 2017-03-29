# Missouri Deaf and Hard of Hearing Demographics Statistics

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/missouri-deaf-and-hard-of-hearing-demographics-statistics) |
| Metadata | [Link](https://data.mo.gov/api/views/3vxz-wrn6) |
| Data: JSON | [100 Rows](https://data.mo.gov/api/views/3vxz-wrn6/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.mo.gov/api/views/3vxz-wrn6/rows.csv?max_rows=100) |
| Host | data.mo.gov |
| Id | 3vxz-wrn6 |
| Name | Missouri Deaf and Hard of Hearing Demographics Statistics |
| Category | Education |
| Created | 2015-08-06T14:26:54Z |
| Publication Date | 2015-09-04T20:13:31Z |

## Columns

```ls
| Included | Schema Type    | Field Name            | Name                    | Data Type | Render Type |
| ======== | ============== | ===================== | ======================= | ========= | =========== |
| No       | time           | :updated_at           | updated_at              | meta_data | meta_data   |
| Yes      | series tag     | county                | County                  | text      | text        |
| Yes      | numeric metric | total_population_2010 | Total Population (2010) | number    | number      |
| Yes      | numeric metric | est_deaf_1            | Est Deaf (1%)           | number    | number      |
| Yes      | numeric metric | est_hoh_9             | Est HoH (9%)            | number    | number      |
| Yes      | numeric metric | est_deaf_hoh_10       | Est Deaf + HoH (10%)    | number    | number      |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
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

property e:3vxz-wrn6 t:meta.view v:id=3vxz-wrn6 v:category=Education v:averageRating=0 v:name="Missouri Deaf and Hard of Hearing Demographics Statistics"

property e:3vxz-wrn6 t:meta.view.owner v:id=jzbz-iqr6 v:screenName=Breanna v:displayName=Breanna

property e:3vxz-wrn6 t:meta.view.tableauthor v:id=jzbz-iqr6 v:screenName=Breanna v:roleName=administrator v:displayName=Breanna
```

## Top Records

```ls
| :updated_at | county    | total_population_2010 | est_deaf_1 | est_hoh_9 | est_deaf_hoh_10 | 
| =========== | ========= | ===================== | ========== | ========= | =============== | 
| 1438863352  | Missouri  | 5988927               | 59889      | 539003    | 598893          | 
| 1438863352  | Adair     | 25607                 | 256        | 2305      | 2561            | 
| 1438863352  | Andrew    | 17291                 | 173        | 1556      | 1729            | 
| 1438863352  | Atchison  | 5685                  | 57         | 512       | 569             | 
| 1438863352  | Audrain   | 25529                 | 255        | 2298      | 2553            | 
| 1438863352  | Barry     | 35597                 | 356        | 3204      | 3560            | 
| 1438863352  | Barton    | 12402                 | 124        | 1116      | 1240            | 
| 1438863352  | Bates     | 17049                 | 170        | 1534      | 1705            | 
| 1438863352  | Benton    | 19056                 | 191        | 1715      | 1906            | 
| 1438863352  | Bollinger | 12363                 | 124        | 1113      | 1236            | 
```