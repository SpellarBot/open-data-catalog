# Office of Finance and Development State Low-Income Housing Tax Credits (SLIHTC) and Subsidy Only Projects

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/office-of-finance-and-development-state-low-income-housing-tax-credits-slihtc-and-subsidy-) |
| Metadata | [Link](https://data.ny.gov/api/views/f6sn-r72s) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/f6sn-r72s/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/f6sn-r72s/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | f6sn-r72s |
| Name | Office of Finance and Development State Low-Income Housing Tax Credits (SLIHTC) and Subsidy Only Projects |
| Attribution | NYS Homes and Community Renewal |
| Category | Economic Development |
| Tags | awards, housing, construction, tax credit, lihtc |
| Created | 2015-12-01T23:37:55Z |
| Publication Date | 2016-01-21T23:23:37Z |

## Description

Listing of state tax credit and subsidies awarded by NYS Homes & Community Renewal’s Office of Finance and Development. Details include award amount, developer name, project location, and accomplishments for completed projects based on project types.

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
series e:f6sn-r72s d:2011-01-01T00:00:00.000Z t:project_number=20106003.00 t:hcr_project_type="SLIHC/Subsidy Stand Alone" t:developer_name="REGIONAL ECONOMIC COMMUNITY ACTION PROGRAM, INC." t:county=ORANGE t:municipality=MIDDLETOWN t:project_name="AVENT HOUSE" m:affordable_units=24 m:total_project_cost=447176 m:total_units=24

series e:f6sn-r72s d:2011-01-01T00:00:00.000Z t:project_number=20106004.00 t:hcr_project_type="SLIHC/Subsidy Stand Alone" t:developer_name="APPLE VALLEY SENIOR HOUSING CORP." t:county=CLINTON t:municipality=PERU t:project_name="AVSH RARP" m:affordable_units=30 m:total_project_cost=243990 m:total_units=30

series e:f6sn-r72s d:2011-01-01T00:00:00.000Z t:project_number=20106139.00 t:hcr_project_type="SLIHC/Subsidy Stand Alone" t:developer_name="FRIENDS OF THE NORTH COUNTRY, INC." t:county=CLINTON t:municipality=PLATTSBURGH t:project_name="ART LEFEVRE SENIOR HOUSING REHABILITATION" m:affordable_units=24 m:total_project_cost=124200 m:total_units=24
```

## Meta Commands

```ls
metric m:total_project_cost p:integer l:"Total Project Cost" d:"The total soft (design and fees) and hard costs (actual construction) for the project." t:dataTypeName=money

metric m:total_units p:integer l:"Total Units" d:"Total number of units." t:dataTypeName=number

metric m:affordable_units p:integer l:"Affordable Units" d:"Number of affordable units." t:dataTypeName=number

entity e:f6sn-r72s l:"Office of Finance and Development State Low-Income Housing Tax Credits (SLIHTC) and Subsidy Only Projects" t:attribution="NYS Homes and Community Renewal" t:url=https://data.ny.gov/api/views/f6sn-r72s

property e:f6sn-r72s t:meta.view d:2017-09-25T07:23:19.457Z v:averageRating=0 v:name="Office of Finance and Development State Low-Income Housing Tax Credits (SLIHTC) and Subsidy Only Projects" v:attribution="NYS Homes and Community Renewal" v:attributionLink=http://www.nyshcr.org/Programs/LIHC/ v:id=f6sn-r72s v:category="Economic Development"

property e:f6sn-r72s t:meta.view.owner d:2017-09-25T07:23:19.457Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB

property e:f6sn-r72s t:meta.view.tableauthor d:2017-09-25T07:23:19.457Z v:displayName="NY Open Data" v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:roleName=publisher v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:id=xzik-pf59 v:screenName="NY Open Data" v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB
```

## Top Records

```ls
| project_number | hcr_project_type          | project_name                              | developer_name                                   | county   | municipality  | total_project_cost | total_units | affordable_units | calendar_year | 
| ============== | ========================= | ========================================= | ================================================ | ======== | ============= | ================== | =========== | ================ | ============= | 
| 20106003.00    | SLIHC/Subsidy Stand Alone | AVENT HOUSE                               | REGIONAL ECONOMIC COMMUNITY ACTION PROGRAM, INC. | ORANGE   | MIDDLETOWN    | 447176             | 24          | 24               | 2011          | 
| 20106004.00    | SLIHC/Subsidy Stand Alone | AVSH RARP                                 | APPLE VALLEY SENIOR HOUSING CORP.                | CLINTON  | PERU          | 243990             | 30          | 30               | 2011          | 
| 20106139.00    | SLIHC/Subsidy Stand Alone | ART LEFEVRE SENIOR HOUSING REHABILITATION | FRIENDS OF THE NORTH COUNTRY, INC.               | CLINTON  | PLATTSBURGH   | 124200             | 24          | 24               | 2011          | 
| 20106151.00    | SLIHC/Subsidy Stand Alone | 1818 MAIN REVITALIZATION                  | CENTER CITY NEIGHBORHOOD DEVELOPMENT CORPORATION | NIAGARA  | NIAGARA FALLS | 220610             | 4           | 4                | 2011          | 
| 20110253.00    | SLIHC/Subsidy Stand Alone | OIL-FILLED BOILER REPLACEMENT PROJECT     | SENIOR CITZENS COUNCIL OF CLINTON COUNTY, INC.   | CLINTON  | PLATTSBURGH   | 96669              | 0           | 0                | 2011          | 
| 20116014.00    | SLIHC/Subsidy Stand Alone | HARLEM RIVER POINT                        | L&M DEVELOPMENT PARTNERS                         | NEW YORK | NEW YORK CITY | 58225354           | 173         | 173              | 2011          | 
| 20116030.00    | SLIHC/Subsidy Stand Alone | SON-HOUSE APARTMENTS                      | PROVIDENCE HOUSING DEVELOPMENT                   | MONROE   | ROCHESTER     | 4552751            | 21          | 21               | 2011          | 
| 20116032.00    | SLIHC/Subsidy Stand Alone | HIGHBRIDGE OVERLOOK                       | DUNN DEVELOPMENT CORP.                           | BRONX    | NEW YORK CITY | 45225062           | 155         | 154              | 2011          | 
| 20116084.00    | SLIHC/Subsidy Stand Alone | DEAN STREET                               | HABITAT FOR HUMANITY - NEW YOR                   | KINGS    | NEW YORK CITY | 5799878            | 15          | 15               | 2011          | 
| 20116086.00    | SLIHC/Subsidy Stand Alone | VULCAN SPECIAL NEEDS APARTMENTS           | SOUTHERN TIER ENVIRONMENTS FOR                   | ERIE     | BUFFALO       | 3403131            | 13          | 13               | 2011          | 
```