# Office of Finance and Development State Low-Income Housing Tax Credits (SLIHTC) and Subsidy Only Projects

## Dataset

* [Dataset URL](https://data.ny.gov/api/views/f6sn-r72s/rows.json?max_rows=100)
* [Catalog URL](https://catalog.data.gov/dataset/office-of-finance-and-development-state-low-income-housing-tax-credits-slihtc-and-subsidy-)
* [Metadata URL](https://data.ny.gov/api/views/f6sn-r72s)
* Id = f6sn-r72s
* Name = Office of Finance and Development State Low-Income Housing Tax Credits (SLIHTC) and Subsidy Only Projects
* Attribution = NYS Homes and Community Renewal
* [Attribution Link](http://www.nyshcr.org/Programs/LIHC/)
* Category = Economic Development
* Tags = [awards, housing, construction, tax credit, lihtc]
* Created = 2015-12-01T23:37:55Z
* Publication Date = 2016-01-21T23:23:37Z
* Rows Updated = 2016-01-21T23:20:41Z

## Description

Listing of state tax credit and subsidies awarded by NYS Homes & Community Renewal?s Office of Finance and Development. Details include award amount, developer name, project location, and accomplishments for completed projects based on project types.

## Columns

```ls
| Name               | Field Name         | Data Type | Render Type | Schema Type    | Included | 
| ================== | ================== | ========= | =========== | ============== | ======== | 
| Project Number     | project_number     | number    | number      | numeric metric | Yes      | 
| HCR Project Type   | hcr_project_type   | text      | text        | series tag     | Yes      | 
| Project Name       | project_name       | text      | text        | series tag     | Yes      | 
| Developer Name     | developer_name     | text      | text        | series tag     | Yes      | 
| County             | county             | text      | text        | series tag     | Yes      | 
| Municipality       | municipality       | text      | text        | series tag     | Yes      | 
| Total Project Cost | total_project_cost | money     | money       | numeric metric | Yes      | 
| Total Units        | total_units        | number    | number      | numeric metric | Yes      | 
| Affordable Units   | affordable_units   | number    | number      | numeric metric | Yes      | 
| Calendar Year      | calendar_year      | number    | number      | time           | Yes      | 
```

## Time Field

```ls
Value = calendar_year
Format & Zone = yyyy
```

## Series Fields

```ls
Metric Prefix = 
Included Fields = *
Excluded Fields = 
Annotation Fields = 
```

## Data Commands

```ls
series e:f6sn-r72s d:2011-01-01T00:00:00.000Z t:hcr_project_type="SLIHC/Subsidy Stand Alone" t:project_name="AVENT HOUSE" t:county=ORANGE t:developer_name="REGIONAL ECONOMIC COMMUNITY ACTION PROGRAM, INC." t:municipality=MIDDLETOWN m:affordable_units=24 m:total_project_cost=447176 m:project_number=20106003 m:total_units=24

series e:f6sn-r72s d:2011-01-01T00:00:00.000Z t:hcr_project_type="SLIHC/Subsidy Stand Alone" t:project_name="AVSH RARP" t:county=CLINTON t:developer_name="APPLE VALLEY SENIOR HOUSING CORP." t:municipality=PERU m:affordable_units=30 m:total_project_cost=243990 m:project_number=20106004 m:total_units=30

series e:f6sn-r72s d:2011-01-01T00:00:00.000Z t:hcr_project_type="SLIHC/Subsidy Stand Alone" t:project_name="ART LEFEVRE SENIOR HOUSING REHABILITATION" t:county=CLINTON t:developer_name="FRIENDS OF THE NORTH COUNTRY, INC." t:municipality=PLATTSBURGH m:affordable_units=24 m:total_project_cost=124200 m:project_number=20106139 m:total_units=24
```

## Meta Commands

```ls
metric m:project_number l:"Project Number" d:"Project number used in NYS Homes and Community Renewal?s Statewide Housing Activity Reporting System (SHARS)." t:dataTypeName=number

metric m:total_units p:integer l:"Total Units" d:"Total number of units." t:dataTypeName=number

metric m:affordable_units p:integer l:"Affordable Units" d:"Number of affordable units." t:dataTypeName=number

entity e:f6sn-r72s l:"Office of Finance and Development State Low-Income Housing Tax Credits (SLIHTC) and Subsidy Only Projects" t:attribution="NYS Homes and Community Renewal" t:url=https://data.ny.gov/api/views/f6sn-r72s

property e:f6sn-r72s t:meta.view d:2017-03-08T02:36:39.288Z v:id=f6sn-r72s v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/Programs/LIHC/ v:averageRating=0 v:name="Office of Finance and Development State Low-Income Housing Tax Credits (SLIHTC) and Subsidy Only Projects" v:attribution="NYS Homes and Community Renewal"

property e:f6sn-r72s t:meta.view.owner d:2017-03-08T02:36:39.288Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:f6sn-r72s t:meta.view.tableauthor d:2017-03-08T02:36:39.288Z v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"
```