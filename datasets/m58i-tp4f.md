# Office of Finance and Development Bond with 4% Low-Income Housing Tax Credits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-of-finance-and-development-bond-with-4-low-income-housing-tax-credits) |
| Metadata | [Link](https://data.ny.gov/api/views/m58i-tp4f) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/m58i-tp4f/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/m58i-tp4f/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | m58i-tp4f |
| Name | Office of Finance and Development Bond with 4% Low-Income Housing Tax Credits |
| Attribution | NYS Homes & Community Renewal |
| Category | Economic Development |
| Tags | awards, housing, construction, tax credit, lihtc |
| Created | 2015-12-01T23:28:43Z |
| Publication Date | 2016-01-27T21:14:21Z |

## Description

Listing of bond with tax credits awarded by NYS Homes & Community Renewal?s Office of Finance and Development. Details include amount, developer name, project location, and accomplishments for completed projects based on project types.

## Columns

```ls
| Included | Schema Type    | Field Name         | Name               | Data Type | Render Type |
| ======== | ============== | ================== | ================== | ========= | =========== |
| Yes      | series tag     | project_number     | Project Number     | text      | number      |
| Yes      | series tag     | hcr_project_type   | HCR Project Type   | text      | text        |
| Yes      | series tag     | project_name       | Project Name       | text      | text        |
| Yes      | series tag     | developer_name     | Developer Name     | text      | text        |
| Yes      | series tag     | county             | County             | text      | text        |
| Yes      | series tag     | municipality       | Municipality       | text      | text        |
| Yes      | numeric metric | total_project_cost | Total Project Cost | money     | money       |
| Yes      | numeric metric | total_units        | Total Units        | number    | number      |
| Yes      | numeric metric | affordable_units   | Affordable Units   | number    | number      |
| Yes      | time           | calendar_year      | Calendar Year      | number    | number      |
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Data Commands

```ls
series e:m58i-tp4f d:2011-01-01T00:00:00.000Z t:hcr_project_type="HFA Bond" t:project_name="NEIGHBORHOOD OF THE ARTS SPECIAL NEEDS APTS (HFA)" t:county=MONROE t:developer_name="DEPAUL PROPERTIES INC." t:municipality=ROCHESTER t:project_number=20116012.00 m:affordable_units=46 m:total_project_cost=10983500 m:total_units=46

series e:m58i-tp4f d:2013-01-01T00:00:00.000Z t:hcr_project_type="HFA Bond" t:project_name="SCHOOLHOUSE TERRACE AT CROTON HEIGHTS - PS 6 (HFA)" t:county=WESTCHESTER t:developer_name="THE COMMUNITY BUILDERS, INC." t:municipality=YONKERS t:project_number=20116234.00 m:affordable_units=120 m:total_project_cost=63047201 m:total_units=121

series e:m58i-tp4f d:2012-01-01T00:00:00.000Z t:hcr_project_type="HFA Bond" t:project_name="MARINER TOWERS (HFA)" t:county=ERIE t:developer_name="LIBERTY AFFORDABLE HOUSING, IN" t:municipality=BUFFALO t:project_number=20116252.00 m:affordable_units=292 m:total_project_cost=45751796 m:total_units=292
```

## Meta Commands

```ls
metric m:total_project_cost p:integer l:"Total Project Cost" d:"The total soft (design and fees) and hard costs (actual construction) for the project." t:dataTypeName=money

metric m:total_units p:integer l:"Total Units" d:"Total number of units." t:dataTypeName=number

metric m:affordable_units p:integer l:"Affordable Units" d:"Number of affordable units." t:dataTypeName=number

entity e:m58i-tp4f l:"Office of Finance and Development Bond with 4% Low-Income Housing Tax Credits" t:attribution="NYS Homes & Community Renewal" t:url=https://data.ny.gov/api/views/m58i-tp4f

property e:m58i-tp4f t:meta.view v:id=m58i-tp4f v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/Programs/LIHC/ v:averageRating=0 v:name="Office of Finance and Development Bond with 4% Low-Income Housing Tax Credits" v:attribution="NYS Homes & Community Renewal"

property e:m58i-tp4f t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:m58i-tp4f t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| project_number | hcr_project_type | project_name                                       | developer_name                                            | county      | municipality  | total_project_cost | total_units | affordable_units | calendar_year | 
| ============== | ================ | ================================================== | ========================================================= | =========== | ============= | ================== | =========== | ================ | ============= | 
| 20116012.00    | HFA Bond         | NEIGHBORHOOD OF THE ARTS SPECIAL NEEDS APTS (HFA)  | DEPAUL PROPERTIES INC.                                    | MONROE      | ROCHESTER     | 10983500           | 46          | 46               | 2011          | 
| 20116234.00    | HFA Bond         | SCHOOLHOUSE TERRACE AT CROTON HEIGHTS - PS 6 (HFA) | THE COMMUNITY BUILDERS, INC.                              | WESTCHESTER | YONKERS       | 63047201           | 121         | 120              | 2013          | 
| 20116252.00    | HFA Bond         | MARINER TOWERS (HFA)                               | LIBERTY AFFORDABLE HOUSING, IN                            | ERIE        | BUFFALO       | 45751796           | 292         | 292              | 2012          | 
| 20116263.00    | HFA Bond         | CALKINS CORNERS                                    | BISHOP SHEEN ECUMENICAL HOUSIN                            | MONROE      | HENRIETTA     | 11510560           | 60          | 60               | 2012          | 
| 20120100.00    | HFA Bond         | CAMBA GARDENS PHASE 1                              | CAMBA HOUSING VENTURES INC.                               | KINGS       | NEW YORK CITY | 66882475           | 209         | 207              | 2011          | 
| 20120101.00    | HFA Bond         | GOTHAM WEST                                        | GOTHAM ORGANIZATION INC.                                  | NEW YORK    | NEW YORK CITY | 530515987          | 1238        | 682              | 2011          | 
| 20120102.00    | HFA Bond         | PINE TOWN HOMES                                    | FIRST ATLANTIC CAPITAL LTD                                | NASSAU      | LONG BEACH    | 33538769           | 130         | 129              | 2011          | 
| 20120103.00    | HFA Bond         | ALLEN BY THE BAY SENIOR HOUSING                    | ALLEN AME NEIGHBORHOOD PRESERVATION AND DEVELOPMENT CORP. | QUEENS      | NEW YORK CITY | 18436783           | 66          | 65               | 2011          | 
| 20120104.00    | HFA Bond         | FREDERICK DOUGLASS APARTMENTS                      | HOME LEASING, LLC                                         | MONROE      | ROCHESTER     | 7608719            | 28          | 28               | 2011          | 
| 20120106.00    | HFA Bond         | WOODSTOCK MANOR APARTMENTS                         | NEW YORK INSTITUTE FOR HUMAN D                            | WESTCHESTER | YONKERS       | 13600822           | 61          | 60               | 2011          | 
```