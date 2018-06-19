# Homes and Community Renewal Grant Awards: Beginning 1990

## Dataset

| Name | Value |
| :--- | :---- |
| Catalog | [Link](https://catalog.data.gov/dataset/homes-and-community-renewal-grant-awards-beginning-1990) |
| Metadata | [Link](https://data.ny.gov/api/views/4e8n-qriw) |
| Data: JSON | [100 Rows](https://data.ny.gov/api/views/4e8n-qriw/rows.json?max_rows=100) |
| Data: CSV | [100 Rows](https://data.ny.gov/api/views/4e8n-qriw/rows.csv?max_rows=100) |
| Host | data.ny.gov |
| Id | 4e8n-qriw |
| Name | Homes and Community Renewal Grant Awards: Beginning 1990 |
| Attribution | New York State Homes and Community Renewal (HCR) |
| Category | Economic Development |
| Tags | housing, community renewal |
| Created | 2015-07-29T18:42:50Z |
| Publication Date | 2017-03-16T15:21:29Z |

## Description

Listing of Local Programs Administrators (LPA) contracts awarded by New York State Homes & Community Renewal?s (HCR) Office of Community Renewal (OCR). Details include contract amount, organization name, project location, and accomplishments for completed projects based on project types, e.g. number of housing and commercial units renovated for completed contracts and units for Access to Home (ACSS), HOME, New York Main Street (NYMS), RESTORE, Rural Area Revitalization Projects (RARP) and Urban Initiatives (UI).

## Columns

```ls
| Included | Schema Type    | Field Name                 | Name                         | Data Type | Render Type |
| ======== | ============== | ========================== | ============================ | ========= | =========== |
| Yes      | series tag     | project_number             | Project Number               | text      | number      |
| Yes      | series tag     | program_name               | Program Name                 | text      | text        |
| Yes      | series tag     | project_type               | Project Type                 | text      | text        |
| Yes      | series tag     | activity                   | Activity                     | text      | text        |
| Yes      | numeric metric | contract_amount            | Contract Amount              | money     | money       |
| Yes      | series tag     | organization               | Organization                 | text      | text        |
| Yes      | series tag     | county                     | County                       | text      | text        |
| Yes      | series tag     | municipality               | Municipality                 | text      | text        |
| Yes      | series tag     | current_status             | Current Status               | text      | text        |
| Yes      | numeric metric | residential_units_existing | Residential Units - Existing | number    | number      |
| Yes      | numeric metric | residential_units_new      | Residential Units ? New      | number    | number      |
| Yes      | numeric metric | civic_units_existing       | Civic Units - Existing       | number    | number      |
| Yes      | numeric metric | civic_units_new            | Civic Units ? New            | number    | number      |
| Yes      | numeric metric | commercial_units_existing  | Commercial Units - Existing  | number    | number      |
| Yes      | numeric metric | commercial_units_new       | Commercial Units ? New       | number    | number      |
```

## Time Field

```ls
Value = 1990
Format & Zone = yyyy
```

## Data Commands

```ls
series e:4e8n-qriw d:1990-01-01T00:00:00.000Z t:organization="TOWN OF COLONIE" t:county=ALBANY t:program_name=REST t:municipality=COLONIE t:project_number=19900706 t:project_type=LPA t:current_status=CMPL t:activity=CNSTR/RHAB m:civic_units_existing=0 m:residential_units_existing=14 m:commercial_units_new=0 m:contract_amount=25000 m:civic_units_new=0 m:residential_units_new=0 m:commercial_units_existing=0

series e:4e8n-qriw d:1990-01-01T00:00:00.000Z t:organization="CITY OF NORWICH COMMUNITY DEVELOPMENT OFFICE" t:county=CHENANGO t:program_name=REST t:municipality=NORWICH t:project_number=19900707 t:project_type=LPA t:current_status=CMPL t:activity=CNSTR/RHAB m:civic_units_existing=0 m:residential_units_existing=18 m:commercial_units_new=0 m:contract_amount=25000 m:civic_units_new=0 m:residential_units_new=0 m:commercial_units_existing=0

series e:4e8n-qriw d:1990-01-01T00:00:00.000Z t:organization="CITY OF PLATTSBURGH COMMUNITY DEVELOPMENT OFFICE" t:county=CLINTON t:program_name=REST t:municipality=PLATTSBURGH t:project_number=19900708 t:project_type=LPA t:current_status=CMPL t:activity=CNSTR/RHAB m:civic_units_existing=0 m:residential_units_existing=10 m:commercial_units_new=0 m:contract_amount=25000 m:civic_units_new=0 m:residential_units_new=0 m:commercial_units_existing=0
```

## Meta Commands

```ls
metric m:contract_amount p:integer l:"Contract Amount" d:"Indicates amount of the contract awarded to the recipient organization (LPA)." t:dataTypeName=money

metric m:residential_units_existing p:integer l:"Residential Units - Existing" d:"Total residential (swelling) units proposed to be renovated as part of an open or completed contract, or renovated as part of completed contract." t:dataTypeName=number

metric m:residential_units_new p:integer l:"Residential Units ? New" d:"Total newly constructed residential (dwelling) units proposed as part of an open or completed contract, or total constructed as part of completed contract." t:dataTypeName=number

metric m:civic_units_existing p:integer l:"Civic Units - Existing" d:"Total civic/community units (units with a community purpose, such as a library) proposed to be renovated as part of an open or completed contract." t:dataTypeName=number

metric m:civic_units_new p:integer l:"Civic Units ? New" d:"Total newly constructed civic/community units (units with a community purpose, such as a library) proposed as part of an open or completed contract." t:dataTypeName=number

metric m:commercial_units_existing p:integer l:"Commercial Units - Existing" d:"Total commercial units (units used for business purposes) proposed to be renovated as part of open contract, or renovated as part of completed contract." t:dataTypeName=number

metric m:commercial_units_new p:integer l:"Commercial Units ? New" d:"Total newly constructed commercial units (units used for business purposes) proposed as part of an open or completed contract." t:dataTypeName=number

entity e:4e8n-qriw l:"Homes and Community Renewal Grant Awards:  Beginning 1990" t:attribution="New York State Homes and Community Renewal (HCR)" t:url=https://data.ny.gov/api/views/4e8n-qriw

property e:4e8n-qriw t:meta.view v:id=4e8n-qriw v:category="Economic Development" v:attributionLink=http://www.nyshcr.org/AboutUs/Offices/CommunityRenewal/ v:averageRating=0 v:name="Homes and Community Renewal Grant Awards:  Beginning 1990" v:attribution="New York State Homes and Community Renewal (HCR)"

property e:4e8n-qriw t:meta.view.owner v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:displayName="NY Open Data"

property e:4e8n-qriw t:meta.view.tableauthor v:id=xzik-pf59 v:profileImageUrlMedium=/api/users/xzik-pf59/profile_images/THUMB v:profileImageUrlLarge=/api/users/xzik-pf59/profile_images/LARGE v:screenName="NY Open Data" v:profileImageUrlSmall=/api/users/xzik-pf59/profile_images/TINY v:roleName=publisher v:displayName="NY Open Data"

property e:4e8n-qriw t:meta.view.metadata.custom_fields.common_core v:Publisher="State of New York" v:Contact_Email=opendata@its.ny.gov v:Contact_Name="Open Data NY"
```

## Top Records

```ls
| project_number | program_name | project_type | activity   | contract_amount | organization                                                        | county       | municipality | current_status | residential_units_existing | residential_units_new | civic_units_existing | civic_units_new | commercial_units_existing | commercial_units_new | 
| ============== | ============ | ============ | ========== | =============== | =================================================================== | ============ | ============ | ============== | ========================== | ===================== | ==================== | =============== | ========================= | ==================== | 
| 19900706       | REST         | LPA          | CNSTR/RHAB | 25000           | TOWN OF COLONIE                                                     | ALBANY       | COLONIE      | CMPL           | 14                         | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900707       | REST         | LPA          | CNSTR/RHAB | 25000           | CITY OF NORWICH COMMUNITY DEVELOPMENT OFFICE                        | CHENANGO     | NORWICH      | CMPL           | 18                         | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900708       | REST         | LPA          | CNSTR/RHAB | 25000           | CITY OF PLATTSBURGH COMMUNITY DEVELOPMENT OFFICE                    | CLINTON      | PLATTSBURGH  | CMPL           | 10                         | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900709       | REST         | LPA          | CNSTR/RHAB | 25000           | RUPCO, INC.                                                         | ULSTER       | MULTI-MUNI   | CMPL           | 9                          | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900710       | REST         | LPA          | CNSTR/RHAB | 25000           | CITY OF ALBANY COMMUNITY DEVELOPMENT AGENCY                         | ALBANY       | ALBANY       | CMPL           | 11                         | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900711       | REST         | LPA          | CNSTR/RHAB | 25000           | COMMUNITY SERVICES PROGRAMS INC.                                    | DUTCHESS     | MULTI-MUNI   | CMPL           | 7                          | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900712       | REST         | LPA          | CNSTR/RHAB | 25000           | CITY OF ELMIRA DEPT. OF COMMUNITY DEV./ ELMIRA URBAN RENEWAL AGENCY | CHEMUNG      | ELMIRA       | CMPL           | 13                         | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900713       | REST         | LPA          | CNSTR/RHAB | 25000           | TIOGA OPPORTUNITIES, INC.                                           | TIOGA        | MULTI-MUNI   | CMPL           | 7                          | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900714       | REST         | LPA          | CNSTR/RHAB | 25000           | COMMUNITY PROGRESS INC.                                             | MULTI-COUNTY |              | CMPL           | 12                         | 0                     | 0                    | 0               | 0                         | 0                    | 
| 19900715       | REST         | LPA          | CNSTR/RHAB | 25000           | ITHACA NEIGHBORHOOD HOUSING SERVICES, INC.                          | TOMPKINS     | MULTI-MUNI   | CMPL           | 10                         | 0                     | 0                    | 0               | 0                         | 0                    | 
```