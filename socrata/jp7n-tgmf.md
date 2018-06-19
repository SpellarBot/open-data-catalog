# Small Business Improvement Fund (SBIF) Grant Agreements

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/small-business-improvement-fund-sbif-grant-agreements-38502) |
| Metadata | [Link](https://data.cityofchicago.org/api/views/jp7n-tgmf) |
| Data: JSON | [100 Rows](https://data.cityofchicago.org/api/views/jp7n-tgmf/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.cityofchicago.org/api/views/jp7n-tgmf/rows.csv?max_rows=100) |
| Host | data.cityofchicago.org |
| Id | jp7n-tgmf |
| Name | Small Business Improvement Fund (SBIF) Grant Agreements |
| Attribution | City of Chicago |
| Category | Community & Economic Development |
| Tags | tif, sbif, sustainability |
| Created | 2011-08-30T23:09:06Z |
| Publication Date | 2017-03-27T19:43:11Z |

## Description

Small Business Improvement Fund (SBIF) program grants made since 2001. SBIF uses Tax Increment Financing (TIF) revenues to help owners of commercial and industrial properties within specific TIF districts to repair or remodel their facilities for their own business or on behalf of tenants. For more info, go to http://bit.ly/p91J7T.

## Columns

```ls
| Included | Schema Type    | Field Name      | Name            | Data Type     | Render Type   |
| ======== | ============== | =============== | =============== | ============= | ============= |
| Yes      | series tag     | company         | Company         | text          | text          |
| No       |                | address         | Address         | text          | text          |
| Yes      | series tag     | tif_district    | TIF District    | text          | text          |
| Yes      | time           | completion_date | Completion Date | calendar_date | calendar_date |
| Yes      | numeric metric | actual_costs    | Actual Costs    | money         | money         |
| Yes      | numeric metric | actual_grant    | Actual Grant    | money         | money         |
| Yes      | series tag     | work_items      | Work Items      | text          | text          |
```

## Time Field

```ls
Value = completion_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = address
```

## Data Commands

```ls
series e:jp7n-tgmf d:2001-02-01T00:00:00.000Z t:tif_district="Kinzie Industrial Corridor Industrial Corridor" t:company="Damen Lake Property LLC (Standard Equipment Co)" t:work_items="Truck dock, Skylights, Roof" m:actual_grant=41506.5 m:actual_costs=83013

series e:jp7n-tgmf d:2001-02-08T00:00:00.000Z t:tif_district="Kinzie Industrial Corridor Industrial Corridor" t:company="Northern Greenhouses Inc" t:work_items="New Roof" m:actual_grant=50000 m:actual_costs=125000

series e:jp7n-tgmf d:2001-10-02T00:00:00.000Z t:tif_district="Kinzie Industrial Corridor Industrial Corridor" t:company="Roger Berman Co" t:work_items="HVAC / Elevator renovate / tuckpointing." m:actual_grant=49168.35 m:actual_costs=98336.7
```

## Meta Commands

```ls
metric m:actual_costs p:double l:"Actual Costs" t:dataTypeName=money

metric m:actual_grant p:double l:"Actual Grant" t:dataTypeName=money

entity e:jp7n-tgmf l:"Small Business Improvement Fund (SBIF) Grant Agreements" t:attribution="City of Chicago" t:url=https://data.cityofchicago.org/api/views/jp7n-tgmf

property e:jp7n-tgmf t:meta.view v:id=jp7n-tgmf v:category="Community & Economic Development" v:attributionLink=http://www.cityofchicago.org/city/en/depts/dcd/provdrs/tif.html v:averageRating=0 v:name="Small Business Improvement Fund (SBIF) Grant Agreements" v:attribution="City of Chicago"

property e:jp7n-tgmf t:meta.view.owner v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:displayName=cocadmin v:privilegesDisabled=false

property e:jp7n-tgmf t:meta.view.tableauthor v:id=scy9-9wg4 v:profileImageUrlMedium=/api/users/scy9-9wg4/profile_images/THUMB v:profileImageUrlLarge=/api/users/scy9-9wg4/profile_images/LARGE v:screenName=cocadmin v:profileImageUrlSmall=/api/users/scy9-9wg4/profile_images/TINY v:roleName=administrator v:displayName=cocadmin v:privilegesDisabled=false
```

## Top Records

```ls
| company                                         | address             | tif_district                                   | completion_date     | actual_costs | actual_grant | work_items                                                                        | 
| =============================================== | =================== | ============================================== | =================== | ============ | ============ | ================================================================================= | 
| Damen Lake Property LLC (Standard Equipment Co) | 2033 W Walnut       | Kinzie Industrial Corridor Industrial Corridor | 2001-02-01T00:00:00 | 83013.00     | 41506.50     | Truck dock, Skylights, Roof                                                       | 
| Northern Greenhouses Inc                        | 1756 W Lake         | Kinzie Industrial Corridor Industrial Corridor | 2001-02-08T00:00:00 | 125000.00    | 50000.00     | New Roof                                                                          | 
| Roger Berman Co                                 | 832 W Fulton Market | Kinzie Industrial Corridor Industrial Corridor | 2001-10-02T00:00:00 | 98336.70     | 49168.35     | HVAC / Elevator renovate / tuckpointing.                                          | 
| Moylan Insurance Agency                         | 3301-05 W 111th     | 111th/Kedzie                                   | 2001-10-18T00:00:00 | 21718.75     | 10859.38     | Roof / Sign removal / Awnings                                                     | 
| Mt Greenwood Local Redevelopment Corp           | 3255-3257 W 111th   | 111th/Kedzie                                   | 2001-11-08T00:00:00 | 33149.75     | 16574.87     | Window-Door Replace / masonry / sign removal / awnings / exterior lighting / HVAC | 
| Consolidated Chemical Works                     | 400 N Ashland       | Kinzie Industrial Corridor Industrial Corridor | 2001-11-15T00:00:00 | 27528.00     | 13764.00     | Tuckpointing and roof repair / replacement.                                       | 
| Marco Lighting Components Inc                   | 457 N Leavitt       | Kinzie Industrial Corridor Industrial Corridor | 2002-01-04T00:00:00 | 104552.00    | 50000.00     | Gutter-flashing. Roof / Tuckpointing / Electrical / Emergency lighting            | 
| Value Transmission Inc                          | 5434 W Higgins      | Jefferson Park                                 | 2002-01-04T00:00:00 | 96771.00     | 48385.50     | Tuckpointing, Facade, Window replacement, Front door, Roof, Sign                  | 
| American Soda Fountain Inc                      | 455 N Oakley Blvd   | Kinzie Industrial Corridor Industrial Corridor | 2002-02-25T00:00:00 | 46118.00     | 19061.00     | Roof repair/ tuckpointing/ sign                                                   | 
| Building Blocks Inc                             | 1621 W Carroll      | Kinzie Industrial Corridor Industrial Corridor | 2002-02-25T00:00:00 | 38633.40     | 19316.70     | Tuckpointing/ Renovation of washroom                                              | 
```