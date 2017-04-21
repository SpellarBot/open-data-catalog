# Labor Market Regions

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/labor-market-regions) |
| Metadata | [Link](https://data.ny.gov/api/views/imem-myat) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/imem-myat/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/imem-myat/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | imem-myat |
| Name | Labor Market Regions |
| Attribution | New York State Department of Labor |
| Category | Economic Development |
| Tags | labor market region |
| Created | 2013-12-13T19:22:32Z |
| Publication Date | 2013-12-23T17:20:45Z |

## Description

The New York State Department of Labor has ten labor market regions across the state. This dataset lists the counties and their corresponding labor market region.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | region      | Region     | text      | text        |
| Yes      | series tag  | county      | County     | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:imem-myat d:2013-12-13T11:22:40.000Z t:region="Capital Region" t:county=Albany m:row_number.imem-myat=1

series e:imem-myat d:2013-12-13T11:22:40.000Z t:region="Capital Region" t:county=Columbia m:row_number.imem-myat=2

series e:imem-myat d:2013-12-13T11:22:40.000Z t:region="Capital Region" t:county=Greene m:row_number.imem-myat=3
```

## Meta Commands

```ls
metric m:row_number.imem-myat p:long l:"Row Number"

entity e:imem-myat l:"Labor Market Regions" t:attribution="New York State Department of Labor" t:url=https://data.ny.gov/api/views/imem-myat

property e:imem-myat t:meta.view v:id=imem-myat v:category="Economic Development" v:attributionLink=http://labor.ny.gov/stats/regmap.shtm v:averageRating=0 v:name="Labor Market Regions" v:attribution="New York State Department of Labor"

property e:imem-myat t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:imem-myat t:meta.view.tableauthor v:id=28jg-4c4u v:screenName="Diane L. Boyd" v:roleName=administrator v:displayName="Diane L. Boyd"

property e:imem-myat t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | region           | county      | 
| =========== | ================ | =========== | 
| 1386933760  | Capital Region   | Albany      | 
| 1386933760  | Capital Region   | Columbia    | 
| 1386933760  | Capital Region   | Greene      | 
| 1386933760  | Capital Region   | Rensselaer  | 
| 1386933760  | Capital Region   | Saratoga    | 
| 1386933760  | Capital Region   | Schenectady | 
| 1386933760  | Capital Region   | Warren      | 
| 1386933760  | Capital Region   | Washington  | 
| 1386933760  | Central New York | Cayuga      | 
| 1386933760  | Central New York | Cortland    | 
```