# Meals Served by the Office for the Aging: Beginning 1974

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/meals-served-by-the-office-for-the-aging-beginning-1974) |
| Metadata | [Link](https://data.ny.gov/api/views/uhw9-gyvi) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/uhw9-gyvi/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/uhw9-gyvi/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | uhw9-gyvi |
| Name | Meals Served by the Office for the Aging: Beginning 1974 |
| Attribution | New York State Office for the Aging |
| Category | Human Services |
| Tags | aging resources, aging offices, congregate meals, home delivered meals |
| Created | 2014-02-21T15:16:36Z |
| Publication Date | 2016-11-08T23:02:15Z |

## Description

This dataset is a listing of congregate and home delivered meals served 1974 to the present by the network of Area Agencies on Aging (AAAs).  AAAs - local offices for the Aging - provide services at senior center locations either directly or through subcontracts. Services may include but are not limited to congregate meals, health promotion, educational programs, recreation, etc.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | nysofa_county_code | NYSOFA County Code | text      | text        |
| Yes      | series tag     | county_name        | County Name        | text      | text        |
| Yes      | time           | year               | Year               | number    | number      |
| Yes      | numeric metric | meal_units_served  | Meal Units Served  | number    | number      |
| Yes      | series tag     | meal_type          | Meal Type          | text      | text        |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:uhw9-gyvi d:1974-01-01T00:00:00.000Z t:meal_type="Congregate Meals" t:nysofa_county_code=1 t:county_name=Albany m:meal_units_served=54161

series e:uhw9-gyvi d:1974-01-01T00:00:00.000Z t:meal_type="Home Delivered Meals" t:nysofa_county_code=1 t:county_name=Albany m:meal_units_served=7558

series e:uhw9-gyvi d:1974-01-01T00:00:00.000Z t:meal_type="Congregate Meals" t:nysofa_county_code=2 t:county_name=Allegany m:meal_units_served=13244
```

## Meta Commands

```ls
metric m:meal_units_served p:integer l:"Meal Units Served" d:"Shows the number of meals served." t:dataTypeName=number

entity e:uhw9-gyvi l:"Meals Served by the Office for the Aging:  Beginning 1974" t:attribution="New York State Office for the Aging" t:url=https://data.ny.gov/api/views/uhw9-gyvi

property e:uhw9-gyvi t:meta.view v:id=uhw9-gyvi v:category="Human Services" v:attributionLink=http://aging.ny.gov v:averageRating=0 v:name="Meals Served by the Office for the Aging:  Beginning 1974" v:attribution="New York State Office for the Aging"

property e:uhw9-gyvi t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:uhw9-gyvi t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:uhw9-gyvi t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| nysofa_county_code | county_name | year | meal_units_served | meal_type            | 
| ================== | =========== | ==== | ================= | ==================== | 
| 1                  | Albany      | 1974 | 54161             | Congregate Meals     | 
| 1                  | Albany      | 1974 | 7558              | Home Delivered Meals | 
| 2                  | Allegany    | 1974 | 13244             | Congregate Meals     | 
| 2                  | Allegany    | 1974 | 4984              | Home Delivered Meals | 
| 3                  | Broome      | 1974 | 74614             | Congregate Meals     | 
| 3                  | Broome      | 1974 | 11679             | Home Delivered Meals | 
| 4                  | Cattaraugus | 1974 | 10583             | Congregate Meals     | 
| 4                  | Cattaraugus | 1974 | 376               | Home Delivered Meals | 
| 5                  | Cayuga      | 1974 | 12710             | Congregate Meals     | 
| 5                  | Cayuga      | 1974 | 1959              | Home Delivered Meals | 
```