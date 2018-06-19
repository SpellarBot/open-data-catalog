# Office of Finance and Development 9% Low-Income Housing Tax Credits

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-of-finance-and-development-9-low-income-housing-tax-credits) |
| Metadata | [Link](https://data.ny.gov/api/views/sfm6-zmzx) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/sfm6-zmzx/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/sfm6-zmzx/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | sfm6-zmzx |
| Name | Office of Finance and Development 9% Low-Income Housing Tax Credits |
| Attribution | NYS Homes and Community Renewal |
| Category | Economic Development |
| Tags | awards, housing, construction, tax credit, lihtc |
| Created | 2015-12-01T23:15:27Z |
| Publication Date | 2016-01-21T23:13:12Z |

## Description

Listing of tax credits awarded by NYS Homes & Community Renewal?s Office of Finance and Development. Details include project identifier, developer name, project location, and project types.

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
series e:sfm6-zmzx d:2011-01-01T00:00:00.000Z t:hcr_project_type="9% LIHTC" t:project_name="BELMONT GARDENS" t:county=KINGS t:developer_name="JACKSON DEVELOPMENT GROUP, LTD" t:municipality="NEW YORK CITY" t:project_number=20116002.00 m:affordable_units=64 m:total_project_cost=17073235 m:total_units=64

series e:sfm6-zmzx d:2011-01-01T00:00:00.000Z t:hcr_project_type="9% LIHTC" t:project_name="CREEKWOOD - PHASE I" t:county=JEFFERSON t:developer_name="NORSTAR DEVELOPMENT USA, LP" t:municipality=WATERTOWN t:project_number=20116003.00 m:affordable_units=72 m:total_project_cost=19856587 m:total_units=96

series e:sfm6-zmzx d:2011-01-01T00:00:00.000Z t:hcr_project_type="9% LIHTC" t:project_name="POETS LANDING APARTMENTS" t:county=TOMPKINS t:developer_name="CONIFER REALTY, LLC" t:municipality=DRYDEN t:project_number=20116004.00 m:affordable_units=72 m:total_project_cost=12880663 m:total_units=72
```

## Meta Commands

```ls
metric m:total_project_cost p:integer l:"Total Project Cost" d:"The total soft (design and fees) and hard costs (actual construction) for the project." t:dataTypeName=money

metric m:total_units p:integer l:"Total Units" d:"Total number of units." t:dataTypeName=number

metric m:affordable_units p:integer l:"Affordable Units" d:"Number of affordable units." t:dataTypeName=number

entity e:sfm6-zmzx l:"Office of Finance and Development 9% Low-Income Housing Tax Credits" t:attribution="NYS Homes and Community Renewal" t:url=https://data.ny.gov/api/views/sfm6-zmzx

property e:sfm6-zmzx t:meta.view v:id=sfm6-zmzx v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/Programs/LIHC/ v:averageRating=0 v:name="Office of Finance and Development 9% Low-Income Housing Tax Credits" v:attribution="NYS Homes and Community Renewal"

property e:sfm6-zmzx t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:sfm6-zmzx t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```

## Top Records

```ls
| project_number | hcr_project_type | project_name                          | developer_name                    | county     | municipality  | total_project_cost | total_units | affordable_units | calendar_year | 
| ============== | ================ | ===================================== | ================================= | ========== | ============= | ================== | =========== | ================ | ============= | 
| 20116002.00    | 9% LIHTC         | BELMONT GARDENS                       | JACKSON DEVELOPMENT GROUP, LTD    | KINGS      | NEW YORK CITY | 17073235           | 64          | 64               | 2011          | 
| 20116003.00    | 9% LIHTC         | CREEKWOOD - PHASE I                   | NORSTAR DEVELOPMENT USA, LP       | JEFFERSON  | WATERTOWN     | 19856587           | 96          | 72               | 2011          | 
| 20116004.00    | 9% LIHTC         | POETS LANDING APARTMENTS              | CONIFER REALTY, LLC               | TOMPKINS   | DRYDEN        | 12880663           | 72          | 72               | 2011          | 
| 20116007.00    | 9% LIHTC         | MONUMENT SQUARE APARTMENTS            | THE COMMUNITY BUILDERS, INC.      | RENSSELAER | TROY          | 18449508           | 89          | 89               | 2011          | 
| 20116008.00    | 9% LIHTC         | SISSON RESERVE                        | NRP HOLDINGS LLC.                 | SARATOGA   | MOREAU        | 17615443           | 80          | 80               | 2011          | 
| 20116009.00    | 9% LIHTC         | RIVERKNOLL AT RADISSON PHASE II       | BALDWIN REAL ESTATE DEV CORP.     | ONONDAGA   | LYSANDER      | 13877144           | 80          | 80               | 2011          | 
| 20116010.00    | 9% LIHTC         | FAIRPORT APARTMENTS                   | ROCHESTER'S CORNERSTONE GROUP     | MONROE     | PERINTON      | 15177562           | 104         | 104              | 2011          | 
| 20116011.00    | 9% LIHTC         | LOCKPORT CANAL HOMES                  | HOUSING VISIONS CONSULTANTS, INC. | NIAGARA    | LOCKPORT      | 8472783            | 30          | 30               | 2011          | 
| 20116017.00    | 9% LIHTC         | ROCKWOOD CENTER AT BRENTLAND WOODS    | ROCHESTER'S CORNERSTONE GROUP     | MONROE     | HENRIETTA     | 7404432            | 40          | 40               | 2011          | 
| 20116018.00    | 9% LIHTC         | HEMAN STREET SCHOOL SENIOR APARTMENTS | LAKEWOOD DEVELOPMENT, LLC         | ONONDAGA   | EAST SYRACUSE | 7340815            | 37          | 37               | 2011          | 
```