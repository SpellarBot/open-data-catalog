# Title and Salary Listing

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/title-and-salary-listing) |
| Metadata | [Link](https://data.ny.gov/api/views/t3vp-5tka) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/t3vp-5tka/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/t3vp-5tka/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | t3vp-5tka |
| Name | Title and Salary Listing |
| Attribution | New York State Department of Civil Service |
| Category | Government & Finance |
| Tags | workforce, personnel, classification, compensation, title |
| Created | 2014-09-08T17:28:43Z |
| Publication Date | 2017-04-03T22:18:33Z |

## Description

The Title and Salary Listing is a compilation of job titles under the jurisdiction of the Department of Civil Service.

## Columns

```ls
| Included | Schema Type    | Field Name                                | Name                                      | Data Type     | Render Type   |
| ======== | ============== | ========================================= | ========================================= | ============= | ============= |
| Yes      | series tag     | title_code                                | Title Code                                | text          | text          |
| Yes      | series tag     | title_name                                | Title Name                                | text          | text          |
| Yes      | series tag     | grade                                     | Grade                                     | text          | text          |
| Yes      | numeric metric | jurisdictional_classification             | Jurisdictional Classification             | number        | number        |
| Yes      | series tag     | jurisdictional_classification_description | Jurisdictional Classification Description | text          | text          |
| Yes      | series tag     | negotiating_unit                          | Negotiating Unit                          | text          | text          |
| Yes      | series tag     | negotiating_unit_description              | Negotiating Unit Description              | text          | text          |
| Yes      | series tag     | federal_occupational_code                 | Federal Occupational Code                 | text          | number        |
| Yes      | series tag     | federal_occupational_code_description     | Federal Occupational Code Description     | text          | text          |
| Yes      | series tag     | level                                     | Job Level                                 | text          | text          |
| Yes      | series tag     | level_description                         | Job Level Description                     | text          | text          |
| Yes      | series tag     | standard_number                           | Standard Number                           | text          | text          |
| Yes      | series tag     | agency_code                               | Agency Code                               | text          | text          |
| Yes      | series tag     | agency_description                        | Agency Description                        | text          | text          |
| Yes      | numeric metric | filled_positions                          | Filled Positions                          | number        | number        |
| Yes      | time           | effective_date                            | Effective Date                            | calendar_date | calendar_date |
```

## Time Field

```ls
Value = effective_date
Format & Zone = yyyy-MM-dd'T'HH:mm:ss
```

## Data Commands

```ls
series e:t3vp-5tka d:1998-07-01T00:00:00.000Z t:level=E t:jurisdictional_classification_description=Unclassified t:federal_occupational_code=1 t:agency_description="Executive Chamber" t:title_code=0000100 t:negotiating_unit_description="MANAGERIAL/CONFIDENTIAL  GROUP" t:grade=OS t:level_description="Elected Official" t:federal_occupational_code_description="Officials and Administrators" t:negotiating_unit=06 t:agency_code=01000 t:title_name=Governor m:filled_positions=1 m:jurisdictional_classification=4

series e:t3vp-5tka d:2009-07-10T00:00:00.000Z t:level=J t:jurisdictional_classification_description=Unclassified t:federal_occupational_code=1 t:agency_description="Executive Chamber" t:title_code=0000110 t:negotiating_unit_description="MANAGERIAL/CONFIDENTIAL  GROUP" t:grade=OS t:level_description="Journey Level, Approved" t:federal_occupational_code_description="Officials and Administrators" t:negotiating_unit=06 t:agency_code=01000 t:title_name="Lieutenant Governor" m:filled_positions=0 m:jurisdictional_classification=4

series e:t3vp-5tka d:1998-07-01T00:00:00.000Z t:level=A t:jurisdictional_classification_description=Unclassified t:federal_occupational_code=1 t:agency_description="Budget, Division of the" t:title_code=0000200 t:negotiating_unit_description="MANAGERIAL/CONFIDENTIAL  GROUP" t:grade=NS t:level_description="Appointed Official" t:federal_occupational_code_description="Officials and Administrators" t:negotiating_unit=06 t:agency_code=01010 t:title_name="Dir Of The Budget" m:filled_positions=1 m:jurisdictional_classification=4
```

## Meta Commands

```ls
metric m:jurisdictional_classification p:integer l:"Jurisdictional Classification" d:"The title's jurisdictional classification code." t:dataTypeName=number

metric m:filled_positions p:integer l:"Filled Positions" d:"Number of positions filled when report was run" t:dataTypeName=number

entity e:t3vp-5tka l:"Title and Salary Listing" t:attribution="New York State Department of Civil Service" t:url=https://data.ny.gov/api/views/t3vp-5tka

property e:t3vp-5tka t:meta.view v:id=t3vp-5tka v:category="Government & Finance" v:attributionLink=http://www.cs.ny.gov/tsplan/tsp.html v:averageRating=0 v:name="Title and Salary Listing" v:attribution="New York State Department of Civil Service"

property e:t3vp-5tka t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:t3vp-5tka t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:t3vp-5tka t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| title_code | title_name                          | grade | jurisdictional_classification | jurisdictional_classification_description | negotiating_unit | negotiating_unit_description  | federal_occupational_code | federal_occupational_code_description | level | level_description       | standard_number | agency_code | agency_description      | filled_positions | effective_date      | 
| ========== | =================================== | ===== | ============================= | ========================================= | ================ | ============================= | ========================= | ===================================== | ===== | ======================= | =============== | =========== | ======================= | ================ | =================== | 
| 0000100    | Governor                            | OS    | 4                             | Unclassified                              | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | E     | Elected Official        |                 | 01000       | Executive Chamber       | 1                | 1998-07-01T00:00:00 | 
| 0000110    | Lieutenant Governor                 | OS    | 4                             | Unclassified                              | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | J     | Journey Level, Approved |                 | 01000       | Executive Chamber       | 0                | 2009-07-10T00:00:00 | 
| 0000200    | Dir Of The Budget                   | NS    | 4                             | Unclassified                              | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | A     | Appointed Official      |                 | 01010       | Budget, Division of the | 1                | 1998-07-01T00:00:00 | 
| 0000300    | Comptroller                         | OS    | 4                             | Unclassified                              | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | E     | Elected Official        |                 | 02000       | Comptroller, Office of  | 1                | 1998-07-01T00:00:00 | 
| 0000500    | Chief Of Staff                      | NS    | 2                             | Exempt                                    | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | J     | Journey Level, Approved |                 | 02000       | Comptroller, Office of  | 1                | 2003-08-19T00:00:00 | 
| 0000510    | First Deputy Comptroller            | NS    | 2                             | Exempt                                    | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | J     | Journey Level, Approved |                 | 02000       | Comptroller, Office of  | 1                | 1998-07-01T00:00:00 | 
| 0000520    | Executive Deputy Comptroller        | NS    | 2                             | Exempt                                    | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | J     | Journey Level, Approved |                 | 02000       | Comptroller, Office of  | 1                | 2003-08-19T00:00:00 | 
| 0000620    | Deputy Comptroller City Of New York | NS    | 2                             | Exempt                                    | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | J     | Journey Level, Approved |                 | 02000       | Comptroller, Office of  | 1                | 1988-01-07T00:00:00 | 
| 0000800    | Deputy Comptroller                  | NS    | 2                             | Exempt                                    | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | J     | Journey Level, Approved |                 | 02000       | Comptroller, Office of  | 7                | 1998-07-01T00:00:00 | 
| 0003900    | Commr Of Labor                      | OS    | 4                             | Unclassified                              | 06               | MANAGERIAL/CONFIDENTIAL GROUP | 1                         | Officials and Administrators          | A     | Appointed Official      |                 | 14020       | Labor, Department of    | 1                | 1998-07-01T00:00:00 | 
```