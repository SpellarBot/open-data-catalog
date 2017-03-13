# Zoning Density Assumptions For Zoned Development Capacity Model

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/zoning-density-assumptions-for-zoned-development-capacity-model) |
| Metadata | [Link](https://data.seattle.gov/api/views/i6qv-ar46) |
| Data: JSON | [100 Rows](https://data.seattle.gov/api/views/i6qv-ar46/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.seattle.gov/api/views/i6qv-ar46/rows.csv?max_rows=100) |
| Host | data.seattle.gov |
| Id | i6qv-ar46 |
| Name | Zoning Density Assumptions For Zoned Development Capacity Model |
| Category | Land Base |
| Created | 2015-06-09T22:38:52Z |
| Publication Date | 2015-06-09T22:41:08Z |
| Rows Updated | 2015-06-09T22:39:24Z |

## Columns

```ls
| Included | Schema Type    | Field Name                      | Name                            | Data Type | Render Type |
| ======== | ============== | =============================== | =============================== | ========= | =========== |
| No       | time           | :updated_at                     | updated_at                      | meta_data | meta_data   |
| Yes      | series tag     | zoning                          | ZONING                          | text      | text        |
| Yes      | series tag     | mio_base_zone                   | MIO_BASE_ZONE                   | text      | text        |
| Yes      | series tag     | geo                             | GEO                             | text      | text        |
| Yes      | series tag     | category                        | CATEGORY                        | text      | text        |
| Yes      | series tag     | category_description            | CATEGORY_DESCRIPTION            | text      | text        |
| Yes      | series tag     | class                           | CLASS                           | text      | text        |
| Yes      | series tag     | class_description               | CLASS_DESCRIPTION               | text      | text        |
| Yes      | series tag     | future_land_use_map_designation | FUTURE_LAND_USE_MAP_DESIGNATION | text      | text        |
| Yes      | numeric metric | empl_per_sqft                   | EMPL_PER_SQFT                   | number    | number      |
| Yes      | numeric metric | splitres                        | SPLITRES                        | number    | number      |
| Yes      | numeric metric | splitcom                        | SPLITCOM                        | number    | number      |
| Yes      | numeric metric | maxrdens                        | MAXRDENS                        | number    | number      |
| Yes      | numeric metric | du_gross_sqft                   | DU_GROSS_SQFT                   | number    | number      |
| Yes      | numeric metric | res_obs_far                     | RES_OBS_FAR                     | number    | number      |
| Yes      | numeric metric | res_max_far                     | RES_MAX_FAR                     | number    | number      |
| Yes      | numeric metric | comm_obs_far                    | COMM_OBS_FAR                    | number    | number      |
| Yes      | numeric metric | comm_max_far                    | COMM_MAX_FAR                    | number    | number      |
| Yes      | numeric metric | max_height                      | MAX_HEIGHT                      | number    | number      |
| Yes      | numeric metric | du_acre                         | DU_ACRE                         | number    | number      |
| Yes      | series tag     | stat_type                       | STAT_TYPE                       | text      | text        |
| Yes      | numeric metric | ratio                           | RATIO                           | number    | number      |
| Yes      | series tag     | comments                        | COMMENTS                        | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:i6qv-ar46 d:2015-06-09T15:39:03.000Z t:category=C1 t:stat_type=DR:SQFT t:geo=NONE t:class_description=Commercial t:class=C t:category_description="Commercial 1" t:future_land_use_map_designation="Commercial / Mixed Use Areas" t:zoning=C1-125 m:comm_obs_far=3.5 m:splitcom=0.5 m:splitres=0.5 m:ratio=0.4 m:max_height=125 m:comm_max_far=5 m:du_gross_sqft=1000 m:res_obs_far=5 m:res_max_far=5 m:maxrdens=250 m:empl_per_sqft=300 m:du_acre=174

series e:i6qv-ar46 d:2015-06-09T15:39:03.000Z t:category=C1 t:stat_type=DR:SQFT t:geo=SAO t:class_description=Commercial t:class=C t:category_description="Commercial 1" t:future_land_use_map_designation="Commercial / Mixed Use Areas" t:zoning=C1-125 m:comm_obs_far=3.5 m:splitcom=0.5 m:splitres=0.5 m:ratio=0.4 m:max_height=125 m:comm_max_far=6 m:du_gross_sqft=1000 m:res_obs_far=6 m:res_max_far=6 m:maxrdens=250 m:empl_per_sqft=300 m:du_acre=174

series e:i6qv-ar46 d:2015-06-09T15:39:03.000Z t:category=C1 t:stat_type=DR:SQFT t:geo=NONE t:class_description=Commercial t:class=C t:category_description="Commercial 1" t:future_land_use_map_designation="Commercial / Mixed Use Areas" t:zoning=C1-160 m:comm_obs_far=3.5 m:splitcom=0.5 m:splitres=0.5 m:ratio=0.4 m:max_height=160 m:comm_max_far=5 m:du_gross_sqft=1000 m:res_obs_far=5 m:res_max_far=5 m:maxrdens=200 m:empl_per_sqft=300 m:du_acre=217
```

## Meta Commands

```ls
metric m:empl_per_sqft p:integer l:EMPL_PER_SQFT t:dataTypeName=number

metric m:splitres p:double l:SPLITRES t:dataTypeName=number

metric m:splitcom p:double l:SPLITCOM t:dataTypeName=number

metric m:maxrdens p:integer l:MAXRDENS t:dataTypeName=number

metric m:du_gross_sqft p:integer l:DU_GROSS_SQFT t:dataTypeName=number

metric m:res_obs_far p:float l:RES_OBS_FAR t:dataTypeName=number

metric m:res_max_far p:float l:RES_MAX_FAR t:dataTypeName=number

metric m:comm_obs_far p:double l:COMM_OBS_FAR t:dataTypeName=number

metric m:comm_max_far p:double l:COMM_MAX_FAR t:dataTypeName=number

metric m:max_height p:integer l:MAX_HEIGHT t:dataTypeName=number

metric m:du_acre p:integer l:DU_ACRE t:dataTypeName=number

metric m:ratio p:double l:RATIO t:dataTypeName=number

entity e:i6qv-ar46 l:"Zoning Density Assumptions For Zoned Development Capacity Model" t:url=https://data.seattle.gov/api/views/i6qv-ar46

property e:i6qv-ar46 t:meta.view v:id=i6qv-ar46 v:category="Land Base" v:averageRating=0 v:name="Zoning Density Assumptions For Zoned Development Capacity Model"

property e:i6qv-ar46 t:meta.view.license v:name="Public Domain"

property e:i6qv-ar46 t:meta.view.owner v:id=5wys-t5s3 v:screenName="Seattle DPD" v:roleName=publisher v:displayName="Seattle DPD"

property e:i6qv-ar46 t:meta.view.tableauthor v:id=5wys-t5s3 v:screenName="Seattle DPD" v:roleName=publisher v:displayName="Seattle DPD"
```