# Clean Burning Wood Stove Grants

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/clean-burning-wood-stove-grants-77e03) |
| Metadata | [Link](https://data.maryland.gov/api/views/8aku-y93i) |
| Data: JSON | [100 Rows](https://data.maryland.gov/api/views/8aku-y93i/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.maryland.gov/api/views/8aku-y93i/rows.csv?max_rows=100) |
| Host | data.maryland.gov |
| Id | 8aku-y93i |
| Name | Clean Burning Wood Stove Grants |
| Attribution | Maryland Energy Administration |
| Category | Energy and Environment |
| Tags | wood burning stoves, grant, clean burning wood stove grants, wood stove, energy, energy grant, mea, maryland energy administration, clean energy grants, clean energy |
| Created | 2013-09-26T14:12:52Z |
| Publication Date | 2015-02-25T22:21:03Z |

## Description

To help Maryland homeowners invest in clean energy, the Maryland Energy Administration provides grants for clean burning wood stoves that displace electric, non-natural gas fossil fuel heating systems or old wood stoves.

More information is available on the program's website at: http://energy.maryland.gov/Residential/woodstoves/

## Columns

```ls
| Included | Schema Type    | Field Name         | Name                    | Data Type     | Render Type   |
| ======== | ============== | ================== | ======================= | ============= | ============= |
| Yes      | series tag     | program_name       | Program Name            | text          | text          |
| Yes      | series tag     | stove_type         | Stove Type              | text          | text          |
| Yes      | numeric metric | capacity_btus_hr   | Capacity (BTU/hr)       | number        | number        |
| Yes      | numeric metric | award_amount       | Award Amount            | money         | money         |
| Yes      | numeric metric | total_project_cost | Total Project Cost      | money         | money         |
| Yes      | time           | project_end_date   | Project Completion Date | calendar_date | calendar_date |
| No       |                | award_created_date | Award Date              | calendar_date | calendar_date |
| Yes      | series tag     | county             | County                  | text          | text          |
| Yes      | series tag     | city               | City                    | text          | text          |
| Yes      | series tag     | state              | State                   | text          | text          |
| Yes      | series tag     | zip_code_2         | Zip Code                | text          | text          |
```

## Time Field

```ls
Value = project_end_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Series Fields

```ls
Excluded Fields = award_created_date
```

## Data Commands

```ls
series e:8aku-y93i d:2014-10-02T00:00:00.000Z t:zip_code_2=21122 t:stove_type="Pellet Stove" t:county="Anne Arundel" t:program_name="Residential Renewable Grants" t:state=Maryland t:city=Pasadena m:award_amount=700 m:total_project_cost=5607 m:capacity_btus_hr=28200

series e:8aku-y93i d:2014-04-05T00:00:00.000Z t:zip_code_2=21158 t:stove_type="Wood Stove" t:county=Carroll t:program_name="Residential Renewable Grants" t:state=Maryland t:city=Westminster m:award_amount=500 m:total_project_cost=4334 m:capacity_btus_hr=66700

series e:8aku-y93i d:2014-11-21T00:00:00.000Z t:zip_code_2=21660 t:stove_type="Wood Stove" t:county=Caroline t:program_name="Residential Renewable Grants" t:state=Maryland t:city=Ridgely m:award_amount=500 m:total_project_cost=3251.97 m:capacity_btus_hr=65000
```

## Meta Commands

```ls
metric m:capacity_btus_hr p:integer l:"Capacity (BTU/hr)" t:dataTypeName=number

metric m:award_amount p:double l:"Award Amount" t:dataTypeName=money

metric m:total_project_cost p:double l:"Total Project Cost" t:dataTypeName=money

entity e:8aku-y93i l:"Clean Burning Wood Stove Grants" t:attribution="Maryland Energy Administration" t:url=https://data.maryland.gov/api/views/8aku-y93i

property e:8aku-y93i t:meta.view v:id=8aku-y93i v:category="Energy and Environment" v:averageRating=0 v:name="Clean Burning Wood Stove Grants" v:attribution="Maryland Energy Administration"

property e:8aku-y93i t:meta.view.owner v:id=5k99-dix4 v:screenName=Jenn v:displayName=Jenn

property e:8aku-y93i t:meta.view.tableauthor v:id=5k99-dix4 v:screenName=Jenn v:roleName=editor v:displayName=Jenn
```

## Top Records

```ls
| program_name                 | stove_type   | capacity_btus_hr | award_amount | total_project_cost | project_end_date    | award_created_date  | county       | city        | state    | zip_code_2 | 
| ============================ | ============ | ================ | ============ | ================== | =================== | =================== | ============ | =========== | ======== | ========== | 
| Residential Renewable Grants | Pellet Stove | 28200            | 700.00       | 5607.00            | 2014-10-02T00:00:00 | 2014-10-27T00:00:00 | Anne Arundel | Pasadena    | Maryland | 21122      | 
| Residential Renewable Grants | Wood Stove   | 66700            | 500.00       | 4334.00            | 2014-04-05T00:00:00 | 2014-06-18T00:00:00 | Carroll      | Westminster | Maryland | 21158      | 
| Residential Renewable Grants | Wood Stove   | 65000            | 500.00       | 3251.97            | 2014-11-21T00:00:00 | 2014-12-23T00:00:00 | Caroline     | Ridgely     | Maryland | 21660      | 
| Residential Renewable Grants | Pellet Stove | 43000            | 700.00       | 3454.78            | 2013-11-20T00:00:00 | 2013-12-19T00:00:00 | Baltimore    | White Marsh | Maryland | 21162      | 
| Residential Renewable Grants | Pellet Stove | 52460            | 700.00       | 6501.29            | 2014-11-13T00:00:00 | 2015-01-16T00:00:00 | Somerset     | Crisfield   | Maryland | 21817      | 
| Residential Renewable Grants | Pellet Stove | 34000            | 600.00       | 4706.93            | 2013-02-22T00:00:00 | 2014-02-11T00:00:00 | Harford      | Bel Air     | Maryland | 21014      | 
| Residential Renewable Grants | Pellet Stove | 52000            | 700.00       | 5469.98            | 2014-09-26T00:00:00 | 2014-10-03T00:00:00 | Baltimore    | Baltimore   | Maryland | 21237      | 
| Residential Renewable Grants | Wood Stove   | 43200            | 500.00       | 4748.00            | 2014-04-04T00:00:00 | 2014-04-22T00:00:00 | Carroll      | Westminster | Maryland | 21157      | 
| Residential Renewable Grants | Pellet Stove | 52460            | 700.00       | 5194.06            | 2014-09-24T00:00:00 | 2014-11-03T00:00:00 | Anne Arundel | Pasadena    | Maryland | 21122      | 
| Residential Renewable Grants | Wood Stove   | 70300            | 500.00       | 4000.00            | 2014-12-24T00:00:00 | 2015-02-18T00:00:00 | Washington   | Boonsboro   | Maryland | 21713      | 
```