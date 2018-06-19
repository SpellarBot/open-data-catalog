# Hudson River Valley Greenway National Heritage Area Heritage Sites List

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/hudson-river-valley-greenway-national-heritage-area-heritage-sites-list) |
| Metadata | [Link](https://data.ny.gov/api/views/me7a-kku4) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/me7a-kku4/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/me7a-kku4/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | me7a-kku4 |
| Name | Hudson River Valley Greenway National Heritage Area Heritage Sites List |
| Attribution | Hudson River Valley Greenway |
| Category | Recreation |
| Tags | national heritage area, greenway, ramble, hike, historic sites |
| Created | 2014-02-11T20:31:43Z |
| Publication Date | 2014-02-11T20:47:31Z |

## Description

A listing of all sites designated as part of the Hudson River Valley National Heritage Area.

## Columns

```ls
| Included | Schema Type | Field Name  | Name       | Data Type | Render Type |
| ======== | =========== | =========== | ========== | ========= | =========== |
| No       | time        | :updated_at | updated_at | meta_data | meta_data   |
| Yes      | series tag  | site_name   | Site Name  | text      | text        |
| Yes      | series tag  | city        | City       | text      | text        |
```

## Time Field

```ls
Value = updated_at
Format & Zone = seconds
```

## Data Commands

```ls
series e:me7a-kku4 d:2014-02-11T12:31:46.000Z t:site_name="Albany City Hall" t:city=Albany m:row_number.me7a-kku4=1

series e:me7a-kku4 d:2014-02-11T12:31:46.000Z t:site_name="Albany Institute of History & Art" t:city=Albany m:row_number.me7a-kku4=2

series e:me7a-kku4 d:2014-02-11T12:31:46.000Z t:site_name="Albany Shaker National Historic Site" t:city=Albany m:row_number.me7a-kku4=3
```

## Meta Commands

```ls
metric m:row_number.me7a-kku4 p:long l:"Row Number"

entity e:me7a-kku4 l:"Hudson River Valley Greenway National Heritage Area Heritage Sites List" t:attribution="Hudson River Valley Greenway" t:url=https://data.ny.gov/api/views/me7a-kku4

property e:me7a-kku4 t:meta.view v:id=me7a-kku4 v:category=Recreation v:attributionLink=http://www.hudsonrivervalley.com/Home.aspx v:averageRating=0 v:name="Hudson River Valley Greenway National Heritage Area Heritage Sites List" v:attribution="Hudson River Valley Greenway"

property e:me7a-kku4 t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:me7a-kku4 t:meta.view.tableauthor v:id=mwxm-zess v:profileImageUrlMedium=/api/users/mwxm-zess/profile_images/THUMB v:profileImageUrlLarge=/api/users/mwxm-zess/profile_images/LARGE v:screenName="Lindsey Krough" v:profileImageUrlSmall=/api/users/mwxm-zess/profile_images/TINY v:roleName=administrator v:displayName="Lindsey Krough"

property e:me7a-kku4 t:meta.view.metadata.custom_fields.common_core v:Contact_Email=opendata@its.ny.gov v:Publisher="State of New York" v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| :updated_at | site_name                            | city          | 
| =========== | ==================================== | ============= | 
| 1392121906  | Albany City Hall                     | Albany        | 
| 1392121906  | Albany Institute of History & Art    | Albany        | 
| 1392121906  | Albany Shaker National Historic Site | Albany        | 
| 1392121906  | Bear Mountain State Park             | Bear Mountain | 
| 1392121906  | Bennington Battlefield               | Walloomsac    | 
| 1392121906  | Boscobel House and Gardens           | Garrison      | 
| 1392121906  | Bronck Museum                        | Coxsackie     | 
| 1392121906  | Burden Iron Works Museum             | Troy          | 
| 1392121906  | Camp Shanks World War II Museum      | Orangeburg    | 
| 1392121906  | Cherry Hill                          | Albany        | 
```