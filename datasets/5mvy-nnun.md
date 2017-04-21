# Volunteer Fire Assistance Grants Awarded: Beginning 2009

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/volunteer-fire-assistance-grants-awarded-beginning-2009) |
| Metadata | [Link](https://data.ny.gov/api/views/5mvy-nnun) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/5mvy-nnun/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/5mvy-nnun/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 5mvy-nnun |
| Name | Volunteer Fire Assistance Grants Awarded: Beginning 2009 |
| Attribution | New York State Department of Environmental Conservation, Division of Forest Protection |
| Category | Public Safety |
| Tags | rural fire departments, volunteer fire assistance, us forest service grants, cooperative forestry assistance act of 1978 |
| Created | 2016-09-16T21:00:47Z |
| Publication Date | 2016-09-21T21:16:41Z |

## Description

List of grant awards made to New York State rural fire departments through the Department of Environmental Conservation to purchase wildland firefighting equipment. The grant is funded by the United States Department of Agriculture Forest Service.

## Columns

```ls
| Included | Schema Type    | Field Name           | Name                 | Data Type | Render Type |
| ======== | ============== | ==================== | ==================== | ========= | =========== |
| Yes      | time           | year                 | Year                 | number    | number      |
| Yes      | series tag     | county               | County               | text      | text        |
| Yes      | series tag     | fire_department_name | Fire Department Name | text      | text        |
| Yes      | series tag     | fire_department_id   | Fire Department ID # | text      | text        |
| Yes      | numeric metric | amount_requested     | Amount Requested     | money     | money       |
| Yes      | numeric metric | amount_spent         | Amount Spent         | money     | money       |
| Yes      | numeric metric | grant_amount         | Grant Amount         | money     | money       |
```

## Time Field

```ls
Value = year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:5mvy-nnun d:2010-01-01T00:00:00.000Z t:fire_department_name="GRAFTON VFD   *" t:county=RENSSELAER t:fire_department_id=42013 m:grant_amount=0.33 m:amount_spent=2191.25 m:amount_requested=3257.61

series e:5mvy-nnun d:2014-01-01T00:00:00.000Z t:fire_department_name="GREENPORT FIRE DISTRICT" t:county=COLUMBIA t:fire_department_id=11015 m:grant_amount=115.8 m:amount_spent=1933.5 m:amount_requested=966

series e:5mvy-nnun d:2014-01-01T00:00:00.000Z t:fire_department_name="SALAMANCA (CITY OF)" t:county=CATTARAUGUS t:fire_department_id=05028 m:grant_amount=251.5 m:amount_spent=503 m:amount_requested=246.5
```

## Meta Commands

```ls
metric m:amount_requested p:double l:"Amount Requested" d:"The total amount of US Dollars needed to purchase the equipment requested in the grant." t:dataTypeName=money

metric m:amount_spent p:double l:"Amount Spent" d:"Total cost of the equipment purchased by the fire department as requested in the grant." t:dataTypeName=money

metric m:grant_amount p:double l:"Grant Amount" d:"The amount of funds provided by the grant to the fire department that purchased the equipment requested in the grant application." t:dataTypeName=money

entity e:5mvy-nnun l:"Volunteer Fire Assistance Grants Awarded: Beginning 2009" t:attribution="New York State Department of Environmental Conservation, Division of Forest Protection" t:url=https://data.ny.gov/api/views/5mvy-nnun

property e:5mvy-nnun t:meta.view v:id=5mvy-nnun v:category="Public Safety" v:attributionLink=http://www.dec.ny.gov/regulations/2364.html v:averageRating=0 v:name="Volunteer Fire Assistance Grants Awarded: Beginning 2009" v:attribution="New York State Department of Environmental Conservation, Division of Forest Protection"

property e:5mvy-nnun t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:5mvy-nnun t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| year | county      | fire_department_name              | fire_department_id | amount_requested | amount_spent | grant_amount | 
| ==== | =========== | ================================= | ================== | ================ | ============ | ============ | 
| 2010 | RENSSELAER  | GRAFTON VFD *                     | 42013              | 3257.61          | 2191.25      | 0.33         | 
| 2014 | COLUMBIA    | GREENPORT FIRE DISTRICT           | 11015              | 966              | 1933.5       | 115.8        | 
| 2014 | CATTARAUGUS | SALAMANCA (CITY OF)               | 05028              | 246.5            | 503          | 251.5        | 
| 2014 | WESTCHESTER | NORTH CASTLE SOUTH FIRE DIST NO 1 | 60037              | 319.6            | 639.2        | 319.6        | 
| 2010 | DELAWARE    | GRAND GORGE HOSE FD               | 13015              | 627.75           | 656.99       | 328.5        | 
| 2012 | ONEIDA      | STANWIX HEIGHT VOL FIRE DEPT      | 33039              | 342.63           | 678.88       | 339.44       | 
| 2011 | GREENE      | EAST JEWETT FD                    | 20009              | 1787.5           | 713.44       | 356.72       | 
| 2011 | WARREN      | STONY CREEK VFC                   | 57021              | 1400             | 731.22       | 365.61       | 
| 2012 | TOMPKINS    | SPEEDSVILLE FIRE CO               | 55017              | 871              | 771.98       | 385.99       | 
| 2011 | OTSEGO      | SCHENEVUS FD / CH GRAHAM HOSE CO  | 39018              | 1588             | 795.99       | 398          | 
```